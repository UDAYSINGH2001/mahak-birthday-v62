# Mahak Birthday Website — V6.1 Memory Collage Edition

This keeps the original V6 multi-page scrapbook design and expands it with all uploaded memories.

- Birthday: 18 November
- First meeting and engagement: 28 January 2026
- 32 Mahak portrait / memory photos plus 6 engagement photographs
- 5 video memories, including the three videos uploaded on 12 November 2026
- Responsive collage homepage, masonry memory wall, filters and tap-to-expand photos
- One looping background song shared by all pages; browser may require the first tap to start playback

## Add your song
Copy your MP3 into this folder as `music/home.mp3`. On Ubuntu, if your old V6 song is still at the path below, run from your Downloads folder:

```bash
cp ~/Downloads/my/mahak-birthday-v6/music/home.mp3 ~/Downloads/mahak-birthday-v61/music/home.mp3
```

## Run locally
Open Terminal in this folder and run:

```bash
python3 -m http.server 8080
```

Open http://localhost:8080.

If your extracted folder has a different name or location, adjust the `cd` / copy destination accordingly.
