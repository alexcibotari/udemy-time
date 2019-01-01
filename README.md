# ZooDemy

[![Build Status](https://travis-ci.org/alexcibotari/zoodemy.svg?branch=master)](https://travis-ci.org/alexcibotari/zoodemy)

A minimalistic Udemy offline courses downloader and player. Built on Electron, Angular and Material for frontend.

![Video](zoodemy.gif)

## Features

- Display subscribed course
  - Video
  - Article
  - Quiz
- Download subscribed course
  - Progress bar
  - Retry to download lecture on network issues (10 retries)
  - Retry to download course after network issues (manually)
  - Assets:
    - Video
    - Additional Assets
    - Articles
    - E-Book
- Settings
  - Change app home folder

## Future Features

- Download subscribed course
  - Assets:
    - Quiz
    - Subtitles
- Settings
  - Choose preferred video resolution
  - Additional Assets
  - Subtitles
- Multi language (Only English at the moment)
  
Please let me know about your preferable features.

## Developers

- Run locally ``npm run electron``.
- Debug locally. Open two consoles in first run ``npm run build:watch`` and wait until build ends, in second console run ``npm run electron:dev``.

## For personal use only
Do not share courses downloaded with the application, it is for personal use only.
Please read Udemy Terms of Use
