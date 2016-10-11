#FFmpeg prebuilt for NW.js

FFMpeg prebuilt binaries with proprietary codecs and build instructions for window, linux and osx.

##### Usage:

build_ffmpeg.py [-h] [-c] [-nw NW_VERSION] [-tp TARGET_PLATFORM]
                       [-ta TARGET_ARCH] [-pc]
###### Arguments explanied:
-  *-h, --help* : Show the help message and exit
-  *-c, --clean* : Clean the workspace, removes downloaded source code
-  *-nw NW_VERSION, --nw_version NW_VERSION* : Build ffmpeg for the specified Nw.js version
-  *-tp TARGET_PLATFORM, --target_platform TARGET_PLATFORM* : Target platform, win, linux, mac...
-  *-ta TARGET_ARCH, --target_arch TARGET_ARCH* : Target architecture, ia32, x64, arm64, arm...
-  *-pc, --proprietary_codecs* : Build ffmpeg with proprietary codecs applied from  [build_ffmpeg.py patch](https://github.com/vzamanillo/nwjs-ffmpeg-prebuilt/blob/master/patch/build_ffmpeg_proprietary_codecs.patch#L17)

###### Specific guides:  

- [Windows guide](guides/build_windows.md)
- [Linux guide](guides/build_linux.md)
- [Mac guide](guides/build_mac.md)


Downloads [prebuilt binaries](https://github.com/vzamanillo/nwjs-ffmpeg-prebuilt/releases).

You can get the FFmpeg source code from [here](https://chromium.googlesource.com/chromium/third_party/ffmpeg).

>###License and Patent Fee
> Using MP3 and H.264 codecs requires you to pay attention to the patent royalties and the license of the source code. Consult a lawyer if you do not understand the licensing constraints and using patented media formats in your application. For more information about the license of the source code, check [here](https://chromium.googlesource.com/chromium/third_party/ffmpeg.git/+/master/CREDITS.chromium).
