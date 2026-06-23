---
# yaml-language-server: $schema=schemas/page.schema.json
Object type:
    - Page
Creation date: "2026-03-29T14:47:54Z"
Created by:
    - Alan Moreira
id: bafyreiconxivgm47wd3as4toftebrbffpvuuy4mydsxer2luzpphqmhesa
---
# yt-dlp   


https://music.youtube.com/playlist?list=OLAK5uy\_kgmfCHiGMsONdw1e-iPFTzADjt25-mdAM 
   
   
```
yt-dlp -x --audio-format best --no-keep-video "URL"


```
   
```
yt-dlp -x --audio-format mp3 --audio-quality 0 \  --embed-thumbnail --add-metadata \  -o "%(playlist_index)03d - %(title)s.%(ext)s" \  "<PLAYLIST_URL>"


```
   
```
yt-dlp -x --audio-format best \  --embed-thumbnail --add-metadata \  -o "%(playlist_index)03d - %(title)s.%(ext)s" \  https://music.youtube.com/playlist?list=OLAK5uy_llgdbXOt5XuLE3nT06yi0HxtQp-vu-_zQ

```
