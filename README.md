# gregcohen.com (archival recreation)

The original Yahoo SiteBuilder site ("Retro TV - Multiple color" template), rebuilt from its own markup and files as saved by the Wayback Machine.

- Homepage: capture 2018-07-15 (20180715195814)
- Photo Albums, Videos, Mascots, About Us: capture 2023-03-29 (20230329221541)
- Images, audio and video: nearest Wayback captures (2018–2023)

Changes from the original:

- **Hit counter (index.html):** the dead SiteBuilder counter image is replaced with a look-alike `<span>` (yellow `#FFFF00` on blue `#0000FF`, bold Courier New). A small inline script calls the free [Abacus](https://abacus.jasoncameron.dev) counting API (`/hit/chacoh.github.io/gregcohen-com-visits`, CORS-enabled, no signup). Each visit adds one and shows the new total. The counter was created starting at the original preset value, 3096. If the request fails, the span keeps showing 3096.
- **Media (mascots.html, about_us.html):** the Windows Media Player `<object>`/`<embed>` tags are replaced with HTML5 `<video controls>` / `<audio controls>` in the same positioned boxes and at the same sizes. The clips were converted with ffmpeg so they play in modern browsers: `Videos/Eli.mp4`, `Videos/Macy.mp4`, `Videos/OzzieChewing.mp4` (H.264/AAC, yuv420p, faststart, original frame sizes) and `AudioFiles/GregBody.mp3`, `AudioFiles/RebeccaSong.mp3`. The original `.mpeg`/`.avi`/`.wav` files are kept beside them.
- An injected third-party script is removed.

External album links (ofoto, Snapfish) are kept as they were and no longer work.
