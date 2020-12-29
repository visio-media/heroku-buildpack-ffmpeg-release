# heroku-buildpack-ffmpeg-release

A Heroku buildpack based on [jonathanong/heroku-buildpack-ffmpeg-latest](https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest). The only difference is this fork is pinned to a specific release (currently [ffmpeg version 4.3.1](http://johnvansickle.com/ffmpeg/) instead of the latest git master. This resolves issues we were observing with the unreleased development build.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/visio-media/heroku-buildpack-ffmpeg-release.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/visio-media/heroku-buildpack-ffmpeg-release.git
```
