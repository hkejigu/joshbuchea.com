---
layout: post
title: Convert PSD to PNG with ImageMagick
---

Make sure [ImageMagick](https://www.imagemagick.org) is installed on your system and open up a terminal:

- Convert entire PSD to one PNG file: `convert 'image.psd[0]' image.png` (keep the `[0]` there)
- Output all layers (cropped) to individual PNG files: `convert image.psd image-%d.png`
