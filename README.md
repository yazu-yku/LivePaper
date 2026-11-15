## LivePaper

LivePaper is a small Python script desktop app that play GIFs and MP4 videos as an animated wallpaper.
This app is currently for Linux (especially Debian 13 Trixie) with xfce desktop environment only (maybe idk if its work on KDE or other).

![Preview](https://livepaper.nekoweb.org/preview/prev-1_old.png)
![Preview](https://livepaper.nekoweb.org/preview/prev-2.png)

## Run
Python 3.10 or newer is recommended. And please read the "requirements.txt" when you extract the zip.

Choose a `.gif` or `.mp4`, then select **Set as wallpaper**. MP4 audio is not played. Closing the main window hides LivePaper to the system tray and keeps the wallpaper running. Reopen it from the tray icon, or choose **Quit LivePaper** in the tray menu to exit and stop the wallpaper.

LivePaper remembers the last selected media file and restores it when **Launch at startup** enabled. This option uses the current user's standard startup mechanism on Linux.

It uses Qt's bottom-of-desktop window hint; how this behaves behind desktop icons depends on the desktop environment and window manager. MP4 playback depends on the media codecs available to Qt Multimedia on the system.

## Skins
This lets you customize your LivePaper appearance with CSS code. (because css is easy right?)
You can choose it inside of the app by make/put your CSS code into "/skins" folder then you should restart the app so it can detect your skin.
