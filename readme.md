# fast-cli [![Build Status](https://travis-ci.org/sindresorhus/fast-cli.svg?branch=master)](https://travis-ci.org/sindresorhus/fast-cli)

> Test your download and upload speed using [fast.com](https://fast.com)

![](screenshot.gif)


## Install

Ensure you have [Node.js](https://nodejs.org) version 8+ installed. Then run the following:

```
$ npm install --global fast-cli
```

<a href="https://www.patreon.com/sindresorhus">
	<img src="https://c5.patreon.com/external/logo/become_a_patron_button@2x.png" width="160">
</a>


## Usage

```
$ fast --help

  Usage
    $ fast
    $ fast > file

  Options
    --upload, -u  Measure upload speed in addition to download speed

  Examples
    $ fast --upload > file && cat file
    17 Mbps
    4.4 Mbps
```


##### Upload speed

<img src="screenshot-upload.gif" width="500" height="260">


## Related

- [speed-test](https://github.com/sindresorhus/speed-test) - Test your internet connection speed and ping using speedtest.net


## License

MIT © [Sindre Sorhus](https://sindresorhus.com)
