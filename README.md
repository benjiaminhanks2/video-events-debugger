# video-events-debugger

HTML5 Video element and Hls.js events debugging tools.

## Supports

- `<video>` element
- [hls.js](https://github.com/video-dev/hls.js "hls.js")

## Install

Install with [npm](https://www.npmjs.com/):

    npm install video-events-debugger

## Usage


Video Element:

```js
import {injectDevTools, injectConsole} from "video-events-debugger"
// to Redux DevTools
injectDevTools(video: HTMLVideoElement);
// to Browser's console
injectConsole(video: HTMLVideoElement);
```

Hls.js:(experimental)

```js
import {injectHlsJsDebugger} from "video-events-debugger"
injectHlsJsDebugger(hls: Hls);
```

Steps:

1. Install [Redux-DevTool extension](https://github.com/zalmoxisus/redux-devtools-extension) to your browser
2. Open DevTools
3. Open "Redux" tab

### Bookmarklet

- [ ] Welcome to PR

1. Run bookmarklet
2. Input target video selector
3. See developer tools console

### remote-redux-devtools

- [ ] Integrate with [remote-redux-devtools](https://github.com/zalmoxisus/remote-redux-devtools "remote-redux-devtools")

## Changelog

See [Releases page](https://github.com/azu/video-events-debugger/releases).

## Running tests

Install devDependencies and Run `npm test`:

    npm i -d && npm test

## Contributing

Pull requests and stars are always welcome.

For bugs and feature requests, [please create an issue](https://github.com/azu/video-events-debugger/issues).

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Author

- [github/azu](https://github.com/azu)
- [twitter/azu_re](https://twitter.com/azu_re)

## License

MIT © azu
