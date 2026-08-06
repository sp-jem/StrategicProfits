# YouTube Transcript Downloader v2

Downloads transcripts from YouTube channels. It tries **youtube-transcript-api** first, and uses **Whisper** as a fallback for videos without captions.

## Usage

```bash
python3 download_transcripts_v2.py --channel CHANNEL_NAME
python3 download_transcripts_v2.py --channel CHANNEL_NAME --whisper  # Use Whisper as fallback
```

## What this script does

- Fetches a channel’s video list using `scrapetube`.
- For each video:
  - Attempts to fetch captions using `youtube-transcript-api` (fastest).
  - If not available and `--whisper` is enabled, downloads audio with `yt-dlp` and transcribes using Whisper.
- Saves results to:
  - A human-readable **Markdown** file (`.md`)
  - A structured **JSON** file (`.json`)

## Key features

- Parallel processing with a thread pool.
- Language preference order for captions: `pt`, `pt-BR`, `en`, `en-US`, `es`, then “any available”.
- Optional Whisper fallback (CPU/GPU intensive); automatically reduces thread count when enabled.

## Requirements

### Python

- Python 3.x

### Dependencies

```bash
pip3 install --user youtube-transcript-api scrapetube yt-dlp openai-whisper
```

> Whisper also requires `ffmpeg` installed and available.

## Arguments (translated)

- `--channel`, `-c` (**required**)  
  YouTube channel name (without `@`)

- `--output`, `-o`  
  Output directory (default: `~/Documents/youtube_transcripts`)

- `--threads`, `-t`  
  Number of parallel threads (default: `10`)

- `--limit`, `-l`  
  Limit the number of videos

- `--name`, `-n`  
  Output file name (without extension)

- `--whisper`, `-w`  
  Use Whisper as fallback for videos without captions

- `--whisper-model`  
  Whisper model to use (default: `base`)  
  Choices: `tiny`, `base`, `small`, `medium`, `large`

## Translated user-facing messages (reference)

The original script prints Portuguese messages like:

- “AVISO: youtube-transcript-api não instalado…” → “WARNING: youtube-transcript-api not installed…”
- “Buscando vídeos do canal…” → “Fetching videos from channel…”
- “Baixando transcripts…” → “Downloading transcripts…”
- “Salvando arquivos…” → “Saving files…”
- “CONCLUÍDO!” → “DONE!”
- “Arquivos gerados:” → “Generated files:”
- “Transcript não disponível” → “Transcript not available”

If you want, I can also produce a **fully translated `.py` file** where these strings (and the module docstring/comments) are translated inline while keeping code logic identical.

## Output format (Markdown)

Each video section includes:

- Title (with `[YouTube]` or `[Whisper]` source badge when available)
- URL
- Published date (when available)
- Transcript text
