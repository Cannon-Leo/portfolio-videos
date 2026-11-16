# Web versions (branch `web`, tag `v2`)
Compressed copies of every video on `main` for the portfolio site: 1280px max width, 24fps, H.264, no audio (cards play muted), fast start.
Why: jsDelivr does not serve GitHub repos larger than 50 MB; `main` is ~216 MB, so newer videos failed to load. This branch is ~25 MB.
Originals stay untouched on `main`.
Use: https://cdn.jsdelivr.net/gh/Cannon-Leo/portfolio-videos@v2/<file name>
To add a video: compress it the same way, commit it to `web`, then create a new tag (v3, v4...) and use that tag in the URL.
