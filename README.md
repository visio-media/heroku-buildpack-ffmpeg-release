# heroku-buildpack-ffmpeg-release

A Heroku buildpack based on [jonathanong/heroku-buildpack-ffmpeg-latest](https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest). The only difference is this fork downloads the latest [release static build](http://johnvansickle.com/ffmpeg/) instead of the latest git master. This should make for a more stable ffmpeg build.

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/visio-media/heroku-buildpack-ffmpeg-release.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/visio-media/heroku-buildpack-ffmpeg-release.git
```
