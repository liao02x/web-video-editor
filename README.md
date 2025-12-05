# Web Video Editor

Fork of https://github.com/shadowmoose/Web-Video-Editor

Try it out here: https://liao02x.github.io/Web-Video-Editor/web/

Load a video, adjust the time, and click+drag on the screen to crop into a rectangle.

The web page (optionally) supports loading a Javascript-compiled version of FFmpeg, 
which can encode small jobs within the browser.

Applied the fix from https://github.com/orgs/community/discussions/13309#discussioncomment-3844940 to fix the issue of SharedArrayBuffer not being available in GitHub Pages. Tested working on Chrome.
