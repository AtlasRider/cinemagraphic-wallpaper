Cinemagraphic Wallpaper
=======================

Intro
-----

Loads a few favorite cinemagraphic of mine and stretches it full screen. If you combine this with a utility to display a webpage as wallpaper, then you have animated wallpaper. This uses MP4s from Imgur, and you can supply your own Ids of your favorites in the code.

Example
-------

Point your browser here for an example:

https://atlasrider.github.io/cinemagraphic-wallpaper/

Have it reload every 60 seconds like so:

https://atlasrider.github.io/cinemagraphic-wallpaper/?t=60

Mac OS X Usage
--------------

![Example](https://raw.githubusercontent.com/AtlasRider/cinemagraphic-wallpaper/master/example.gif)

1. Install this screensaver: https://github.com/liquidx/webviewscreensaver
2. Configure screen saver with this URL: https://atlasrider.github.io/cinemagraphic-wallpaper/
3. Run this command to run screensaver service as your background (also in start-osx.sh):

```
/System/Library/Frameworks/ScreenSaver.framework/Resources/ScreenSaverEngine.app/Contents/MacOS/ScreenSaverEngine -background
```

Note
- - -
Run local webserver for testing

`python -m SimpleHTTPServer 8000`