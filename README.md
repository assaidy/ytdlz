# ytdlz

A simple bash script to download YouTube videos or audio with interactive quality selection.

### Dependencies
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - YouTube downloader
- [mutagen](https://mutagen.readthedocs.io/) - For metadata handling
- [fzf](https://github.com/junegunn/fzf) - Fuzzy finder for interactive selection

### Usage
```bash
./ytdlz <YouTube-URL>
```

The script will then:

1. Ask whether to download video or audio-only
2. For video: let you select the resolution
3. Download the content with optimal settings

### Output

- Audio downloads as best quality audio file with metadata
- Video downloads as MP4 with selected resolution
- Files are saved in current directory with original titles
