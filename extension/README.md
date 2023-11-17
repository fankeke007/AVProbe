# AVProbe (VSCode Extension)
Display the information of Audio/Video files using the built-in ffmpeg/ffprobe.

## Screenshots

![](https://images.xueshi.io/screenshots/screenshots_01.png)
![](https://images.xueshi.io/screenshots/screenshots_02.png)

## Features
* [x] Support mp4/mkv/mov and others
* [x] Displays basic information such as streams, formats, etc
* [x] Presents packets information in a table format
* [x] Enhanced User Interface (implemented using Vue3 + AntDesign for Vue)
* [x] Responsive Webview
* [ ] Preview specified frame
* [ ] Dark theme for Dark mode

## How to use?

### 0. Prerequisite
Install the ffprobe / ffmpeg command-line tool. AVProbe inspects media information through ffprobe, so you need to install ffprobe first.

### 1. Config `ffprobe` path

![Alt text](https://images.xueshi.io/screenshots/set_custom_ffprobe_path.png)

### 2. Open media files with 'AVProbe'
> Simply right-click on the media file, then select ‘Audio/Video Probe’ to open it
![Alt text](https://images.xueshi.io/screenshots/open_with_avprobe.png)