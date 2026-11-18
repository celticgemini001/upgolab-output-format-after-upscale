# Output Format After Upscaling: What JPEG, WebP and AVIF Do to the Detail You Just Bought

At a matched 400 KB, AVIF scored 46.44 dB against JPEG's 43.15 on the same upscaled frame. Every encoder added high-frequency energy rather than removing it, and JPEG reached a byte-identical fixed point after 29 re-encodes while AVIF never did.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-output-format-after-upscale/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
