Echode is a small library to play local audio files in NodeJS using FFmpeg

## Installation

`$ npm i install echode`

or

`$ yarn add echode`

### Important
Make certain FFmpeg, specifically FFplay is available on your system. Otherwise this library will **not** work!


## Usage

```typescript

import {playAudio} from "echode";

await playAudio("sound.mp3")

```

That's it!




