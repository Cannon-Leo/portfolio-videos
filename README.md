# Web versions (branch `web`, pinned by commit)
Compressed copies of every video on `main` for the portfolio site: 1280px max width, 24fps, H.264, no audio (cards play muted), fast start.
Why: jsDelivr does not serve GitHub repos larger than 50 MB; `main` is ~216 MB, so newer videos failed to load. This branch is ~25 MB.
Originals stay untouched on `main`.
Use: https://cdn.jsdelivr.net/gh/Cannon-Leo/portfolio-videos@<commit sha>/<file name>  (the site uses the sha of the commit that added each file)
To add a video: compress it the same way, commit it to `web`, then use the new commit sha in the URL. Pinning a sha keeps the files cached permanently.
