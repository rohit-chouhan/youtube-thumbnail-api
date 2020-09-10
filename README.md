# Youtube Thumbnail API
Open Source Javascript Framework to Get all size and quality thumbnail of Youtube Video from URL

## Installation

#### CDN
`api.min.js`
```sh
https://cdn.jsdelivr.net/npm/youtube-thumbnail-api/api.min.js
```

`api.js`
```sh
https://cdn.jsdelivr.net/npm/youtube-thumbnail-api/api.js
```
`with NPM`
```sh
$ npm install @youtube-thumbnail-api
```
### Documentation

Method | Size
--------------------------------------|----------------------------------------
ytubethumb.set("video-url") | Pass Youtube Video Inside of function to set Youtube Video
ytubethumb.default() | 120x90
ytubethumb.mq() | 320x180
ytubethumb.hq() | 480x460
ytubethumb.sd() | 640x480
ytubethumb.max() | 1280x720 & 1920x1080

### Sample Code
```js
//set youtube video 
ytubethumb.set("https://www.youtube.com/watch?v=olm8XOFPSHQ");

console.log(ytubethumb.default());
//return 120x90 size thubnail image

console.log(ytubethumb.mq());
//return 320x180 size thubnail image

console.log(ytubethumb.hq());
//return 480x460 size thubnail image

console.log(ytubethumb.sd());
//return 640x480 size thubnail image

console.log(ytubethumb.max());
//return 1280x720 & 1920x1080 size thubnail image
```

### Developers
![Rohit](http://graph.facebook.com/100004453384015/picture?type=square)\
Developed by [Rohit Chouhan](https://rohitchouhan.com),  MIT License

[![GithHub](https://img.shields.io/badge/Developed%20By-%40github%2Frohit--chouhan-green)](https://github.com/rohit-chouhan)
[![Facebook](https://img.shields.io/badge/Facebook-%40itsrohitofficialprofile-blue)](https://facebook.com/itsrohitofficialprofile)
[![Twitter](https://img.shields.io/badge/Twitter-%40itsrealrohit-blue)](https://twitter.com/itsrealrohit)
[![Instagram](https://img.shields.io/badge/Instagram-%40rohitchauhanofficial-orange)](https://instagram.com/rohitchauhanofficial)
[![Website](https://img.shields.io/badge/Website-rohitchouhan.com-yellow)](https://rohitchouhan.com)
