# Alex Hormozi Wiki

Source material for the Ask Hormozi plugin. Structured knowledge extraction from Alex Hormozi's public content.

## Sources

- **YouTube transcripts**: 1,988 auto-generated captions via [ScribeSalad](https://github.com/wa3dbk/ScribeSalad) (credit: wa3dbk)
- **Course content**: Referenced from [Risedial/Alex-Hormozi-Full-Course-Content](https://github.com/Risedial/Alex-Hormozi-Full-Course-Content)
- **Podcast RSS**: The Game with Alex Hormozi (https://feeds.captivate.fm/the-game-alex-hormozi/)

## Pipeline Status

- [x] Raw transcript IDs collected (1,988 placeholder VTT files)
- [~] VTT → clean markdown (50/1,988 downloaded and converted via yt-dlp)
- [x] Initial skill scan (10 deep-read transcripts, 16 framework candidates identified)
- [ ] Full corpus download (remaining 1,938 transcripts)
- [ ] Signal survey (grep across full corpus)
- [ ] Semantic chunking
- [ ] Entity extraction
- [ ] Skill building (6 Decision Skills, 4 Coaching Skills estimated)
- [ ] Plugin assembly

## Scripts

- `scripts/vtt-to-markdown.sh [batch_size]` - Downloads captions via yt-dlp and converts to clean markdown. Default batch: 50.

## Key Files

- `skills/initial-skill-scan.md` - Framework inventory from first 50 transcripts (16 candidates, 6 Decision Skills ready to build)

## Domain: alexhormozi.wiki
