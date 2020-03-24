
```powershell

Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Try the new cross-platform PowerShell https://aka.ms/pscore6

PS C:\Users\ZHJ> cd E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> ls


    Directory: E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         3/23/2020   4:01 PM                workspace
d-----         3/23/2020   3:56 PM                _internal
-a----         3/23/2020   3:56 PM            418 1) clear workspace.bat
-a----         3/23/2020   3:56 PM            201 2) extract PNG from video data_src.bat
-a----         3/23/2020   3:56 PM            147 3.1) cut video (drop video on me).bat
-a----         3/23/2020   3:56 PM            216 3.2) extract PNG from video data_dst FULL FPS.bat
-a----         3/23/2020   3:56 PM            164 3.other) denoise extracted data_dst.bat
-a----         3/23/2020   3:56 PM            249 4) data_src extract faces DLIB all GPU debug.bat
-a----         3/23/2020   3:56 PM            234 4) data_src extract faces DLIB all GPU.bat
-a----         3/23/2020   3:56 PM            215 4) data_src extract faces DLIB best GPU.bat
-a----         3/23/2020   3:56 PM            251 4) data_src extract faces MANUAL.bat
-a----         3/23/2020   3:56 PM            247 4) data_src extract faces MT all GPU debug.bat
-a----         3/23/2020   3:56 PM            232 4) data_src extract faces MT all GPU.bat
-a----         3/23/2020   3:56 PM            213 4) data_src extract faces MT best GPU.bat
-a----         3/23/2020   3:56 PM            249 4) data_src extract faces S3FD all GPU debug.bat
-a----         3/23/2020   3:56 PM            234 4) data_src extract faces S3FD all GPU.bat
-a----         3/23/2020   3:56 PM            215 4) data_src extract faces S3FD best GPU.bat
-a----         3/23/2020   3:56 PM            136 4.1) data_src check result.bat
-a----         3/23/2020   3:56 PM            163 4.2.1) data_src sort by blur.bat
-a----         3/23/2020   3:56 PM            163 4.2.2) data_src sort by similar histogram.bat
-a----         3/23/2020   3:56 PM            170 4.2.4) data_src sort by dissimilar face.bat
-a----         3/23/2020   3:56 PM            170 4.2.4) data_src sort by dissimilar histogram.bat
-a----         3/23/2020   3:56 PM            169 4.2.5) data_src sort by face pitch.bat
-a----         3/23/2020   3:56 PM            167 4.2.5) data_src sort by face yaw.bat
-a----         3/23/2020   3:56 PM            164 4.2.6) data_src sort by final.bat
-a----         3/23/2020   3:56 PM            164 4.2.other) data_src sort by black.bat
-a----         3/23/2020   3:56 PM            169 4.2.other) data_src sort by brightness.bat
-a----         3/23/2020   3:56 PM            162 4.2.other) data_src sort by hue.bat
-a----         3/23/2020   3:56 PM            166 4.2.other) data_src sort by one face in image.bat
-a----         3/23/2020   3:56 PM            167 4.2.other) data_src sort by original filename.bat
-a----         3/23/2020   3:56 PM            182 4.2.other) data_src util add landmarks debug images.bat
-a----         3/23/2020   3:56 PM            189 4.2.other) data_src util recover original filename.bat
-a----         3/23/2020   3:56 PM            269 5) data_dst extract faces DLIB all GPU +manual fix.bat
-a----         3/23/2020   3:56 PM            249 5) data_dst extract faces DLIB all GPU .bat
-a----         3/23/2020   3:56 PM            230 5) data_dst extract faces DLIB best GPU.bat
-a----         3/23/2020   3:56 PM            284 5) data_dst extract faces MANUAL RE-EXTRACT DELETED RESULTS DEBUG.bat
-a----         3/23/2020   3:56 PM            251 5) data_dst extract faces MANUAL.bat
-a----         3/23/2020   3:56 PM            267 5) data_dst extract faces MT all GPU + manual fix.bat
-a----         3/23/2020   3:56 PM            247 5) data_dst extract faces MT all GPU .bat
-a----         3/23/2020   3:56 PM            228 5) data_dst extract faces MT best GPU.bat
-a----         3/23/2020   3:56 PM            269 5) data_dst extract faces S3FD all GPU + manual fix.bat
-a----         3/23/2020   3:56 PM            249 5) data_dst extract faces S3FD all GPU.bat
-a----         3/23/2020   3:56 PM            230 5) data_dst extract faces S3FD best GPU.bat
-a----         3/23/2020   3:56 PM            142 5.1) data_dst check results debug.bat
-a----         3/23/2020   3:56 PM            136 5.1) data_dst check results.bat
-a----         3/23/2020   3:56 PM            163 5.2) data_dst sort by similar histogram.bat
-a----         3/23/2020   3:56 PM            163 5.3) data_dst sort by blur.bat
-a----         3/23/2020   3:56 PM            170 5.3) data_dst sort by dissimilar histogram.bat
-a----         3/23/2020   3:56 PM            169 5.3) data_dst sort by face pitch.bat
-a----         3/23/2020   3:56 PM            167 5.3) data_dst sort by face yaw.bat
-a----         3/23/2020   3:56 PM            167 5.3.other) data_dst sort by original filename.bat
-a----         3/23/2020   3:56 PM            189 5.3.other) data_dst util recover original filename.bat
-a----         3/23/2020   3:56 PM            278 6) train DF.bat
-a----         3/23/2020   3:56 PM            280 6) train H128.bat
-a----         3/23/2020   3:56 PM            280 6) train H64.bat
-a----         3/23/2020   3:56 PM            284 6) train LIAEF128.bat
-a----         3/23/2020   3:56 PM            279 6) train SAE.bat
-a----         3/23/2020   3:56 PM            319 7) convert DF debug.bat
-a----         3/23/2020   3:56 PM            304 7) convert DF.bat
-a----         3/23/2020   3:56 PM            321 7) convert H128 debug.bat
-a----         3/23/2020   3:56 PM            306 7) convert H128.bat
-a----         3/23/2020   3:56 PM            320 7) convert H64 debug.bat
-a----         3/23/2020   3:56 PM            307 7) convert H64.bat
-a----         3/23/2020   3:56 PM            325 7) convert LIAEF128 debug.bat
-a----         3/23/2020   3:56 PM            310 7) convert LIAEF128.bat
-a----         3/23/2020   3:56 PM            320 7) convert SAE debug.bat
-a----         3/23/2020   3:56 PM            305 7) convert SAE.bat
-a----         3/23/2020   3:56 PM            263 8) converted to avi.bat
-a----         3/23/2020   3:56 PM            281 8) converted to mov(lossless+alpha).bat
-a----         3/23/2020   3:56 PM            263 8) converted to mp4.bat
-a----         3/23/2020   3:56 PM            160 9) util convert aligned PNG to JPG (drop folder on me).bat
-a----         3/23/2020   3:56 PM           1614 changelog_en.txt
-a----         3/23/2020   3:56 PM           2098 changelog_ru.txt
-a----         3/23/2020   3:56 PM           1068 manual_en.txt
-a----         3/23/2020   3:56 PM        2961665 manual_ru.pdf


PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> & '.\4) data_src extract faces DLIB all GPU debug.bat'
Performing 1st pass...
Running on GeForce GTX 950M #0.
100%|################################################################################| 275/275 [01:44<00:00,  2.62it/s]
Performing 2nd pass...
Running on GeForce GTX 950M.
Using TensorFlow backend.
100%|################################################################################| 275/275 [00:58<00:00,  4.73it/s]
Performing 3rd pass...
Running on CPU2.
Running on CPU3.
Running on CPU1.
Running on CPU0.
100%|################################################################################| 275/275 [00:09<00:00, 30.21it/s]
-------------------------
Images found:        275
Faces detected:      274
-------------------------
Done.
Press any key to continue . . .
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> & '.\3.2) extract PNG from video data_dst FULL FPS.bat'
ffmpeg version N-89980-ge752da5464 Copyright (c) 2000-2018 the FFmpeg developers
  built with gcc 7.2.0 (GCC)
  configuration: --enable-gpl --enable-version3 --enable-sdl2 --enable-bzlib --enable-fontconfig --enable-gnutls --enable-iconv --enable-libass --enable-libbluray --enable-libfreetype --enable-libmp3lame --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopenjpeg --enable-libopus --enable-libshine --enable-libsnappy --enable-libsoxr --enable-libtheora --enable-libtwolame --enable-libvpx --enable-libwavpack --enable-libwebp --enable-libx264 --enable-libx265 --enable-libxml2 --enable-libzimg --enable-lzma --enable-zlib --enable-gmp --enable-libvidstab --enable-libvorbis --enable-libvo-amrwbenc --enable-libmysofa --enable-libspeex --enable-libxvid --enable-libmfx --enable-amf --enable-cuda --enable-cuvid --enable-d3d11va --enable-nvenc --enable-dxva2 --enable-avisynth
  libavutil      56.  7.100 / 56.  7.100
  libavcodec     58. 10.100 / 58. 10.100
  libavformat    58.  9.100 / 58.  9.100
  libavdevice    58.  1.100 / 58.  1.100
  libavfilter     7. 11.101 /  7. 11.101
  libswscale      5.  0.101 /  5.  0.101
  libswresample   3.  0.101 /  3.  0.101
  libpostproc    55.  0.100 / 55.  0.100
Input #0, mov,mp4,m4a,3gp,3g2,mj2, from 'E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\workspace\data_dst.mp4':
  Metadata:
    major_brand     : isom
    compatible_brands: isomiso2avc1mp41
    Stream #0:0(und): Video: h264 (High) (avc1 / 0x31637661), yuv420p(tv, bt709), 1920x1080 [SAR 1:1 DAR 16:9], 545 kb/s, 23.99 fps, 23.98 tbr, 90k tbn, 47.95 tbc (default)
    Metadata:
      handler_name    : VideoHandler
    Stream #0:1(und): Audio: aac (LC) (mp4a / 0x6134706D), 44100 Hz, stereo, fltp, 125 kb/s (default)
    Metadata:
      handler_name    : SoundHandler
Stream mapping:
Press [q] to stop, [?] for help
  Metadata:
    major_brand     : isom
    minor_version   : 512
    compatible_brands: isomiso2avc1mp41
    encoder         : Lavf58.9.100
    Stream #0:0(und): Video: png, rgb24, 1920x1080 [SAR 1:1 DAR 16:9], q=2-31, 200 kb/s, 23.98 fps, 23.98 tbn, 23.98 tbc (default)
    Metadata:
      handler_name    : VideoHandler
      encoder         : Lavc58.10.100 png
frame= 1538 fps= 13 q=-0.0 Lsize=N/A time=00:01:04.14 bitrate=N/A speed=0.523x
video:540583kB audio:0kB subtitle:0kB other streams:0kB global headers:0kB muxing overhead: unknown
Done.
Press any key to continue . . .
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> '.\5) data_dst extract faces DLIB all GPU .bat'
.\5) data_dst extract faces DLIB all GPU .bat
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> & '.\5.1) data_dst check results debug.bat'
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> ./ '.\5) data_dst extract faces DLIB all GPU .bat'
./ : The term './' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ ./ '.\5) data_dst extract faces DLIB all GPU .bat'
+ ~~
    + CategoryInfo          : ObjectNotFound: (./:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> '.\5) data_dst extract faces DLIB all GPU .bat'
.\5) data_dst extract faces DLIB all GPU .bat
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> ls


    Directory: E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         3/23/2020   6:15 PM                workspace
d-----         3/23/2020   3:56 PM                _internal
-a----         3/23/2020   3:56 PM            418 1) clear workspace.bat
-a----         3/23/2020   3:56 PM            201 2) extract PNG from video data_src.bat
-a----         3/23/2020   3:56 PM            147 3.1) cut video (drop video on me).bat
-a----         3/23/2020   3:56 PM            216 3.2) extract PNG from video data_dst FULL FPS.bat
-a----         3/23/2020   3:56 PM            164 3.other) denoise extracted data_dst.bat
-a----         3/23/2020   3:56 PM            249 4) data_src extract faces DLIB all GPU debug.bat
-a----         3/23/2020   3:56 PM            234 4) data_src extract faces DLIB all GPU.bat
-a----         3/23/2020   3:56 PM            215 4) data_src extract faces DLIB best GPU.bat
-a----         3/23/2020   3:56 PM            251 4) data_src extract faces MANUAL.bat
-a----         3/23/2020   3:56 PM            247 4) data_src extract faces MT all GPU debug.bat
-a----         3/23/2020   3:56 PM            232 4) data_src extract faces MT all GPU.bat
-a----         3/23/2020   3:56 PM            213 4) data_src extract faces MT best GPU.bat
-a----         3/23/2020   3:56 PM            249 4) data_src extract faces S3FD all GPU debug.bat
-a----         3/23/2020   3:56 PM            234 4) data_src extract faces S3FD all GPU.bat
-a----         3/23/2020   3:56 PM            215 4) data_src extract faces S3FD best GPU.bat
-a----         3/23/2020   3:56 PM            136 4.1) data_src check result.bat
-a----         3/23/2020   3:56 PM            163 4.2.1) data_src sort by blur.bat
-a----         3/23/2020   3:56 PM            163 4.2.2) data_src sort by similar histogram.bat
-a----         3/23/2020   3:56 PM            170 4.2.4) data_src sort by dissimilar face.bat
-a----         3/23/2020   3:56 PM            170 4.2.4) data_src sort by dissimilar histogram.bat
-a----         3/23/2020   3:56 PM            169 4.2.5) data_src sort by face pitch.bat
-a----         3/23/2020   3:56 PM            167 4.2.5) data_src sort by face yaw.bat
-a----         3/23/2020   3:56 PM            164 4.2.6) data_src sort by final.bat
-a----         3/23/2020   3:56 PM            164 4.2.other) data_src sort by black.bat
-a----         3/23/2020   3:56 PM            169 4.2.other) data_src sort by brightness.bat
-a----         3/23/2020   3:56 PM            162 4.2.other) data_src sort by hue.bat
-a----         3/23/2020   3:56 PM            166 4.2.other) data_src sort by one face in image.bat
-a----         3/23/2020   3:56 PM            167 4.2.other) data_src sort by original filename.bat
-a----         3/23/2020   3:56 PM            182 4.2.other) data_src util add landmarks debug images.bat
-a----         3/23/2020   3:56 PM            189 4.2.other) data_src util recover original filename.bat
-a----         3/23/2020   3:56 PM            269 5) data_dst extract faces DLIB all GPU +manual fix.bat
-a----         3/23/2020   3:56 PM            249 5) data_dst extract faces DLIB all GPU .bat
-a----         3/23/2020   3:56 PM            230 5) data_dst extract faces DLIB best GPU.bat
-a----         3/23/2020   3:56 PM            284 5) data_dst extract faces MANUAL RE-EXTRACT DELETED RESULTS DEBUG.bat
-a----         3/23/2020   3:56 PM            251 5) data_dst extract faces MANUAL.bat
-a----         3/23/2020   3:56 PM            267 5) data_dst extract faces MT all GPU + manual fix.bat
-a----         3/23/2020   3:56 PM            247 5) data_dst extract faces MT all GPU .bat
-a----         3/23/2020   3:56 PM            228 5) data_dst extract faces MT best GPU.bat
-a----         3/23/2020   3:56 PM            269 5) data_dst extract faces S3FD all GPU + manual fix.bat
-a----         3/23/2020   3:56 PM            249 5) data_dst extract faces S3FD all GPU.bat
-a----         3/23/2020   3:56 PM            230 5) data_dst extract faces S3FD best GPU.bat
-a----         3/23/2020   3:56 PM            142 5.1) data_dst check results debug.bat
-a----         3/23/2020   3:56 PM            136 5.1) data_dst check results.bat
-a----         3/23/2020   3:56 PM            163 5.2) data_dst sort by similar histogram.bat
-a----         3/23/2020   3:56 PM            163 5.3) data_dst sort by blur.bat
-a----         3/23/2020   3:56 PM            170 5.3) data_dst sort by dissimilar histogram.bat
-a----         3/23/2020   3:56 PM            169 5.3) data_dst sort by face pitch.bat
-a----         3/23/2020   3:56 PM            167 5.3) data_dst sort by face yaw.bat
-a----         3/23/2020   3:56 PM            167 5.3.other) data_dst sort by original filename.bat
-a----         3/23/2020   3:56 PM            189 5.3.other) data_dst util recover original filename.bat
-a----         3/23/2020   3:56 PM            278 6) train DF.bat
-a----         3/23/2020   3:56 PM            280 6) train H128.bat
-a----         3/23/2020   3:56 PM            280 6) train H64.bat
-a----         3/23/2020   3:56 PM            284 6) train LIAEF128.bat
-a----         3/23/2020   3:56 PM            279 6) train SAE.bat
-a----         3/23/2020   3:56 PM            304 7) convert DF.bat
-a----         3/23/2020   3:56 PM            321 7) convert H128 debug.bat
-a----         3/23/2020   3:56 PM            306 7) convert H128.bat
-a----         3/23/2020   3:56 PM            320 7) convert H64 debug.bat
-a----         3/23/2020   3:56 PM            307 7) convert H64.bat
-a----         3/23/2020   3:56 PM            325 7) convert LIAEF128 debug.bat
-a----         3/23/2020   3:56 PM            310 7) convert LIAEF128.bat
-a----         3/23/2020   3:56 PM            320 7) convert SAE debug.bat
-a----         3/23/2020   3:56 PM            305 7) convert SAE.bat
-a----         3/23/2020   3:56 PM            263 8) converted to avi.bat
-a----         3/23/2020   3:56 PM            281 8) converted to mov(lossless+alpha).bat
-a----         3/23/2020   3:56 PM            281 8) converted to mp4(lossless+alpha).bat
-a----         3/23/2020   3:56 PM            263 8) converted to mp4.bat
-a----         3/23/2020   3:56 PM            160 9) util convert aligned PNG to JPG (drop folder on me).bat
-a----         3/23/2020   3:56 PM           1614 changelog_en.txt
-a----         3/23/2020   3:56 PM           2098 changelog_ru.txt
-a----         3/23/2020   3:56 PM           1068 manual_en.txt
-a----         3/23/2020   3:56 PM        2961665 manual_ru.pdf


PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> ./5) data_dst extract faces DLIB all GPU .bat
At line:1 char:4
+ ./5) data_dst extract faces DLIB all GPU .bat
+    ~
Unexpected token ')' in expression or statement.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : UnexpectedToken

PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> & '.\6) train H64.bat'
Running trainer.

Loading model...

Model first run. Enter model options as default for each run.
Write preview history? (y/n ?:help skip:n) :
n
Target iteration (skip:unlimited/default) :
0
Batch_size (?:help skip:0/default) :
0
Feed faces to network sorted by yaw? (y/n ?:help skip:n) :
n
Flip faces randomly? (y/n ?:help skip:y) :
y
0
Use lightweight autoencoder? (y/n, ?:help skip:n) :
n
Use pixel loss? (y/n, ?:help skip: n/default ) :
n
Using TensorFlow backend.
Loading: 0it [00:00, ?it/s]
Loading: 100%|####################################################################| 1506/1506 [00:03<00:00, 408.78it/s]
Error: integer division or modulo by zero
Traceback (most recent call last):
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\mainscripts\Trainer.py", line 41, in trainerThread
    device_args=device_args)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\models\ModelBase.py", line 163, in __init__
    self.sample_for_preview = self.generate_next_sample()
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\models\ModelBase.py", line 353, in generate_next_sample
    return [next(generator) for generator in self.generator_list]
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\models\ModelBase.py", line 353, in <listcomp>
    return [next(generator) for generator in self.generator_list]
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\samples\SampleGeneratorFace.py", line 57, in __next__
    generator = self.generators[self.generator_counter % len(self.generators) ]
ZeroDivisionError: integer division or modulo by zero
Done.
Press any key to continue . . .
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> & '.\6) train H64.bat'
Running trainer.

Loading model...

Model first run. Enter model options as default for each run.
Write preview history? (y/n ?:help skip:n) :
n
Target iteration (skip:unlimited/default) :
0
Batch_size (?:help skip:0/default) :
0
Feed faces to network sorted by yaw? (y/n ?:help skip:n) :
n
Flip faces randomly? (y/n ?:help skip:y) :
Src face scale modifier % ( -30...30, ?:help skip:0) :
0
Use lightweight autoencoder? (y/n, ?:help skip:n) : y
Use pixel loss? (y/n, ?:help skip: n/default ) :
n
Using TensorFlow backend.
Loading: 0it [00:00, ?it/s]
Loading: 100%|####################################################################| 1506/1506 [00:03<00:00, 429.71it/s]
Error: integer division or modulo by zero
Traceback (most recent call last):
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\mainscripts\Trainer.py", line 41, in trainerThread
    device_args=device_args)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\models\ModelBase.py", line 163, in __init__
    self.sample_for_preview = self.generate_next_sample()
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\models\ModelBase.py", line 353, in generate_next_sample
    return [next(generator) for generator in self.generator_list]
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\models\ModelBase.py", line 353, in <listcomp>
    return [next(generator) for generator in self.generator_list]
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\samples\SampleGeneratorFace.py", line 57, in __next__
    generator = self.generators[self.generator_counter % len(self.generators) ]
ZeroDivisionError: integer division or modulo by zero
Done.
Press any key to continue . . .
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> & '.\2) extract PNG from video data_src.bat'
Enter FPS ( ?:help skip:fullfps ) :
0
ffmpeg version N-89980-ge752da5464 Copyright (c) 2000-2018 the FFmpeg developers
  built with gcc 7.2.0 (GCC)
  configuration: --enable-gpl --enable-version3 --enable-sdl2 --enable-bzlib --enable-fontconfig --enable-gnutls --enable-iconv --enable-libass --enable-libbluray --enable-libfreetype --enable-libmp3lame --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopenjpeg --enable-libopus --enable-libshine --enable-libsnappy --enable-libsoxr --enable-libtheora --enable-libtwolame --enable-libvpx --enable-libwavpack --enable-libwebp --enable-libx264 --enable-libx265 --enable-libxml2 --enable-libzimg --enable-lzma --enable-zlib --enable-gmp --enable-libvidstab --enable-libvorbis --enable-libvo-amrwbenc --enable-libmysofa --enable-libspeex --enable-libxvid --enable-libmfx --enable-amf --enable-cuda --enable-cuvid --enable-d3d11va --enable-nvenc --enable-dxva2 --enable-avisynth
  libavutil      56.  7.100 / 56.  7.100
  libavcodec     58. 10.100 / 58. 10.100
  libavformat    58.  9.100 / 58.  9.100
  libavdevice    58.  1.100 / 58.  1.100
  libavfilter     7. 11.101 /  7. 11.101
  libswscale      5.  0.101 /  5.  0.101
  libswresample   3.  0.101 /  3.  0.101
  libpostproc    55.  0.100 / 55.  0.100
Input #0, mov,mp4,m4a,3gp,3g2,mj2, from 'E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\workspace\data_src.mp4':
  Metadata:
    major_brand     : mp42
    compatible_brands: mp42isom
    creation_time   : 2018-04-19T07:29:40.000000Z
  Duration: 00:00:27.36, start: 0.041708, bitrate: 4027 kb/s
    Stream #0:0(eng): Video: h264 (High) (avc1 / 0x31637661), yuv420p(tv, bt709), 1920x1080 [SAR 1:1 DAR 16:9], 4025 kb/s, 23.98 fps, 23.98 tbr, 24k tbn, 47.95 tbc (default)
    Metadata:
      creation_time   : 2018-04-19T07:29:40.000000Z
      handler_name    : Video Media Handler
      encoder         : AVC Coding
Stream mapping:
  Stream #0:0 -> #0:0 (h264 (native) -> png (native))
Press [q] to stop, [?] for help
Output #0, image2, to 'E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\workspace\data_src\%5d.png':
  Metadata:
    major_brand     : mp42
    minor_version   : 19529854
    compatible_brands: mp42isom
    encoder         : Lavf58.9.100
    Stream #0:0(eng): Video: png, rgb24, 1920x1080 [SAR 1:1 DAR 16:9], q=2-31, 200 kb/s, 23.98 fps, 23.98 tbn, 23.98 tbc (default)
    Metadata:
      creation_time   : 2018-04-19T07:29:40.000000Z
      handler_name    : Video Media Handler
      encoder         : Lavc58.10.100 png
frame=  655 fps=6.9 q=-0.0 Lsize=N/A time=00:00:27.31 bitrate=N/A speed=0.287x
video:501791kB audio:0kB subtitle:0kB other streams:0kB global headers:0kB muxing overhead: unknown
Done.
Press any key to continue . . .
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> ls


    Directory: E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         3/23/2020   6:15 PM                workspace
d-----         3/23/2020   3:56 PM                _internal
-a----         3/23/2020   3:56 PM            418 1) clear workspace.bat
-a----         3/23/2020   3:56 PM            201 2) extract PNG from video data_src.bat
-a----         3/23/2020   3:56 PM            147 3.1) cut video (drop video on me).bat
-a----         3/23/2020   3:56 PM            216 3.2) extract PNG from video data_dst FULL FPS.bat
-a----         3/23/2020   3:56 PM            164 3.other) denoise extracted data_dst.bat
-a----         3/23/2020   3:56 PM            249 4) data_src extract faces DLIB all GPU debug.bat
-a----         3/23/2020   3:56 PM            234 4) data_src extract faces DLIB all GPU.bat
-a----         3/23/2020   3:56 PM            215 4) data_src extract faces DLIB best GPU.bat
-a----         3/23/2020   3:56 PM            251 4) data_src extract faces MANUAL.bat
-a----         3/23/2020   3:56 PM            247 4) data_src extract faces MT all GPU debug.bat
-a----         3/23/2020   3:56 PM            232 4) data_src extract faces MT all GPU.bat
-a----         3/23/2020   3:56 PM            213 4) data_src extract faces MT best GPU.bat
-a----         3/23/2020   3:56 PM            249 4) data_src extract faces S3FD all GPU debug.bat
-a----         3/23/2020   3:56 PM            234 4) data_src extract faces S3FD all GPU.bat
-a----         3/23/2020   3:56 PM            215 4) data_src extract faces S3FD best GPU.bat
-a----         3/23/2020   3:56 PM            136 4.1) data_src check result.bat
-a----         3/23/2020   3:56 PM            163 4.2.1) data_src sort by blur.bat
-a----         3/23/2020   3:56 PM            163 4.2.2) data_src sort by similar histogram.bat
-a----         3/23/2020   3:56 PM            170 4.2.4) data_src sort by dissimilar face.bat
-a----         3/23/2020   3:56 PM            170 4.2.4) data_src sort by dissimilar histogram.bat
-a----         3/23/2020   3:56 PM            169 4.2.5) data_src sort by face pitch.bat
-a----         3/23/2020   3:56 PM            167 4.2.5) data_src sort by face yaw.bat
-a----         3/23/2020   3:56 PM            164 4.2.6) data_src sort by final.bat
-a----         3/23/2020   3:56 PM            164 4.2.other) data_src sort by black.bat
-a----         3/23/2020   3:56 PM            169 4.2.other) data_src sort by brightness.bat
-a----         3/23/2020   3:56 PM            162 4.2.other) data_src sort by hue.bat
-a----         3/23/2020   3:56 PM            166 4.2.other) data_src sort by one face in image.bat
-a----         3/23/2020   3:56 PM            167 4.2.other) data_src sort by original filename.bat
-a----         3/23/2020   3:56 PM            182 4.2.other) data_src util add landmarks debug images.bat
-a----         3/23/2020   3:56 PM            189 4.2.other) data_src util recover original filename.bat
-a----         3/23/2020   3:56 PM            269 5) data_dst extract faces DLIB all GPU +manual fix.bat
-a----         3/23/2020   3:56 PM            249 5) data_dst extract faces DLIB all GPU .bat
-a----         3/23/2020   3:56 PM            230 5) data_dst extract faces DLIB best GPU.bat
-a----         3/23/2020   3:56 PM            284 5) data_dst extract faces MANUAL RE-EXTRACT DELETED RESULTS DEBUG.bat
-a----         3/23/2020   3:56 PM            251 5) data_dst extract faces MANUAL.bat
-a----         3/23/2020   3:56 PM            267 5) data_dst extract faces MT all GPU + manual fix.bat
-a----         3/23/2020   3:56 PM            247 5) data_dst extract faces MT all GPU .bat
-a----         3/23/2020   3:56 PM            228 5) data_dst extract faces MT best GPU.bat
-a----         3/23/2020   3:56 PM            269 5) data_dst extract faces S3FD all GPU + manual fix.bat
-a----         3/23/2020   3:56 PM            249 5) data_dst extract faces S3FD all GPU.bat
-a----         3/23/2020   3:56 PM            230 5) data_dst extract faces S3FD best GPU.bat
-a----         3/23/2020   3:56 PM            142 5.1) data_dst check results debug.bat
-a----         3/23/2020   3:56 PM            136 5.1) data_dst check results.bat
-a----         3/23/2020   3:56 PM            163 5.2) data_dst sort by similar histogram.bat
-a----         3/23/2020   3:56 PM            163 5.3) data_dst sort by blur.bat
-a----         3/23/2020   3:56 PM            170 5.3) data_dst sort by dissimilar histogram.bat
-a----         3/23/2020   3:56 PM            169 5.3) data_dst sort by face pitch.bat
-a----         3/23/2020   3:56 PM            167 5.3) data_dst sort by face yaw.bat
-a----         3/23/2020   3:56 PM            167 5.3.other) data_dst sort by original filename.bat
-a----         3/23/2020   3:56 PM            189 5.3.other) data_dst util recover original filename.bat
-a----         3/23/2020   3:56 PM            278 6) train DF.bat
-a----         3/23/2020   3:56 PM            280 6) train H128.bat
-a----         3/23/2020   3:56 PM            280 6) train H64.bat
-a----         3/23/2020   3:56 PM            284 6) train LIAEF128.bat
-a----         3/23/2020   3:56 PM            279 6) train SAE.bat
-a----         3/23/2020   3:56 PM            319 7) convert DF debug.bat
-a----         3/23/2020   3:56 PM            304 7) convert DF.bat
-a----         3/23/2020   3:56 PM            321 7) convert H128 debug.bat
-a----         3/23/2020   3:56 PM            306 7) convert H128.bat
-a----         3/23/2020   3:56 PM            320 7) convert H64 debug.bat
-a----         3/23/2020   3:56 PM            307 7) convert H64.bat
-a----         3/23/2020   3:56 PM            325 7) convert LIAEF128 debug.bat
-a----         3/23/2020   3:56 PM            310 7) convert LIAEF128.bat
-a----         3/23/2020   3:56 PM            320 7) convert SAE debug.bat
-a----         3/23/2020   3:56 PM            305 7) convert SAE.bat
-a----         3/23/2020   3:56 PM            263 8) converted to avi.bat
-a----         3/23/2020   3:56 PM            281 8) converted to mov(lossless+alpha).bat
-a----         3/23/2020   3:56 PM            263 8) converted to mp4.bat
-a----         3/23/2020   3:56 PM            160 9) util convert aligned PNG to JPG (drop folder on me).bat
-a----         3/23/2020   3:56 PM           1614 changelog_en.txt
-a----         3/23/2020   3:56 PM           2098 changelog_ru.txt
-a----         3/23/2020   3:56 PM           1068 manual_en.txt
-a----         3/23/2020   3:56 PM        2961665 manual_ru.pdf


PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> & '.\4) data_src extract faces DLIB best GPU.bat'
Performing 1st pass...
Running on GeForce GTX 950M #0.
100%|################################################################################| 655/655 [04:11<00:00,  2.60it/s]
Performing 2nd pass...
Running on GeForce GTX 950M.
Using TensorFlow backend.
100%|################################################################################| 655/655 [02:08<00:00,  5.11it/s]
Performing 3rd pass...
Running on CPU2.
Running on CPU3.
Running on CPU0.
Running on CPU1.
100%|################################################################################| 655/655 [00:10<00:00, 64.31it/s]
-------------------------
Images found:        655
Faces detected:      654
-------------------------
Done.
Press any key to continue . . .
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> & '.\6) train H64.bat'
Running trainer.

Loading model...

Model first run. Enter model options as default for each run.
Write preview history? (y/n ?:help skip:n) :
n
Target iteration (skip:unlimited/default) :
0
Batch_size (?:help skip:0/default) :
0
Feed faces to network sorted by yaw? (y/n ?:help skip:n) :
n
Flip faces randomly? (y/n ?:help skip:y) :
y
Src face scale modifier % ( -30...30, ?:help skip:0) :
0
Use lightweight autoencoder? (y/n, ?:help skip:n) :
n
Use pixel loss? (y/n, ?:help skip: n/default ) :
n
Using TensorFlow backend.
Loading: 100%|######################################################################| 654/654 [00:01<00:00, 365.11it/s]
Loading: 100%|####################################################################| 1506/1506 [00:03<00:00, 434.66it/s]
===== Model summary =====
== Model name: H64
==
== Current iteration: 0
==
== Model options:
== |== batch_size : 4
== |== sort_by_yaw : False
== |== random_flip : True
== |== lighter_ae : False
== |== pixel_loss : False
== Running on:
== |== [0 : GeForce GTX 950M]
==
== WARNING: You are using 2GB GPU. Result quality may be significantly decreased.
== If training does not start, close all programs and try again.
== Also you can disable Windows Aero Desktop to get extra free VRAM.
==
=========================
Saving....
Starting. Press "Enter" to stop training and save model.
Error: OOM when allocating tensor with shape[16384,1024] and type float on /job:localhost/replica:0/task:0/device:GPU:0
by allocator GPU_0_bfc
         [[node training/Adam/Variable_8/Assign (defined at E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\backend\tensorflow_backend.py:402)  = Assign[T=DT_FLOAT, _grappler_relax_allocator_constraints=true, use_locking=true, validate_shape=true, _device="/job:localhost/replica:0/task:0/device:GPU:0"](training/Adam/Variable_8, training/Adam/zeros_54)]]
Hint: If you want to see a list of allocated tensors when OOM happens, add report_tensor_allocations_upon_oom to RunOptions for current allocation info.


Caused by op 'training/Adam/Variable_8/Assign', defined at:
  File "threading.py", line 884, in _bootstrap
  File "threading.py", line 916, in _bootstrap_inner
  File "threading.py", line 864, in run
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\mainscripts\Trainer.py", line 78, in trainerThread
    loss_string = model.train_one_iter()
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\models\ModelBase.py", line 358, in train_one_iter
    losses = self.onTrainOneIter(sample, self.generator_list)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\models\Model_H64\Model.py", line 85, in
onTrainOneIter
    total, loss_src_bgr, loss_src_mask, loss_dst_bgr, loss_dst_mask = self.ae.train_on_batch( [warped_src, target_src_full_mask, warped_dst, target_dst_full_mask], [target_src, target_src_full_mask, target_dst, target_dst_full_mask] )
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\engine\training.py", line 1216, in train_on_batch
    self._make_train_function()
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\engine\training.py", line 509, in _make_train_function
    loss=self.total_loss)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\legacy\interfaces.py", line 91, in wrapper
    return func(*args, **kwargs)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\optimizers.py", line 487, in get_updates
    ms = [K.zeros(K.int_shape(p), dtype=K.dtype(p)) for p in params]
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\optimizers.py", line 487, in <listcomp>
    ms = [K.zeros(K.int_shape(p), dtype=K.dtype(p)) for p in params]
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\backend\tensorflow_backend.py", line 704, in zeros
    return variable(v, dtype=dtype, name=name)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\backend\tensorflow_backend.py", line 402, in variable
    v = tf.Variable(value, dtype=tf.as_dtype(dtype), name=name)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variables.py", line 183, in __call__
    return cls._variable_v1_call(*args, **kwargs)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variables.py", line 146, in _variable_v1_call
    aggregation=aggregation)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variables.py", line 125, in <lambda>
    previous_getter = lambda **kwargs: default_variable_creator(None, **kwargs)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variable_scope.py", line 2444, in default_variable_creator
    expected_shape=expected_shape, import_scope=import_scope)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variables.py", line 187, in __call__
    return super(VariableMetaclass, cls).__call__(*args, **kwargs)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variables.py", line 1329, in __init__
    constraint=constraint)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variables.py", line 1481, in _init_from_args
    validate_shape=validate_shape).op
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\state_ops.py", line 221, in assign
    validate_shape=validate_shape)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\gen_state_ops.py", line 61, in assign
    use_locking=use_locking, name=name)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\framework\op_def_library.py", line 787, in _apply_op_helper
    op_def=op_def)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\util\deprecation.py", line 488, in new_func
    return func(*args, **kwargs)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\framework\ops.py", line 3274, in create_op
    op_def=op_def)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\framework\ops.py", line 1770, in __init__
    self._traceback = tf_stack.extract_stack()

ResourceExhaustedError (see above for traceback): OOM when allocating tensor with shape[16384,1024] and type float on /job:localhost/replica:0/task:0/device:GPU:0 by allocator GPU_0_bfc
         [[node training/Adam/Variable_8/Assign (defined at E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\backend\tensorflow_backend.py:402)  = Assign[T=DT_FLOAT, _grappler_relax_allocator_constraints=true, use_locking=true, validate_shape=true, _device="/job:localhost/replica:0/task:0/device:GPU:0"](training/Adam/Variable_8, training/Adam/zeros_54)]]
Hint: If you want to see a list of allocated tensors when OOM happens, add report_tensor_allocations_upon_oom to RunOptions for current allocation info.


Traceback (most recent call last):
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\client\session.py", line 1334, in _do_call
    return fn(*args)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\client\session.py", line 1319, in _run_fn
    options, feed_dict, fetch_list, target_list, run_metadata)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\client\session.py", line 1407, in _call_tf_sessionrun
    run_metadata)
tensorflow.python.framework.errors_impl.ResourceExhaustedError: OOM when allocating tensor with shape[16384,1024] and type float on /job:localhost/replica:0/task:0/device:GPU:0 by allocator GPU_0_bfc
         [[{{node training/Adam/Variable_8/Assign}} = Assign[T=DT_FLOAT, _grappler_relax_allocator_constraints=true, use_locking=true, validate_shape=true, _device="/job:localhost/replica:0/task:0/device:GPU:0"](training/Adam/Variable_8, training/Adam/zeros_54)]]
Hint: If you want to see a list of allocated tensors when OOM happens, add report_tensor_allocations_upon_oom to RunOptions for current allocation info.


During handling of the above exception, another exception occurred:

Traceback (most recent call last):
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\mainscripts\Trainer.py", line 78, in trainerThread
    loss_string = model.train_one_iter()
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\models\ModelBase.py", line 358, in train_one_iter
    losses = self.onTrainOneIter(sample, self.generator_list)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\models\Model_H64\Model.py", line 85, in
onTrainOneIter
    total, loss_src_bgr, loss_src_mask, loss_dst_bgr, loss_dst_mask = self.ae.train_on_batch( [warped_src, target_src_full_mask, warped_dst, target_dst_full_mask], [target_src, target_src_full_mask, target_dst, target_dst_full_mask] )
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\engine\training.py", line 1217, in train_on_batch
    outputs = self.train_function(ins)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\backend\tensorflow_backend.py", line 2697, in __call__
    if hasattr(get_session(), '_make_callable_from_options'):
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\backend\tensorflow_backend.py", line 206, in get_session
    session.run(tf.variables_initializer(uninitialized_vars))
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\client\session.py", line 929, in run
    run_metadata_ptr)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\client\session.py", line 1152, in _run
    feed_dict_tensor, options, run_metadata)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\client\session.py", line 1328, in _do_run
    run_metadata)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\client\session.py", line 1348, in _do_call
    raise type(e)(node_def, op, message)
tensorflow.python.framework.errors_impl.ResourceExhaustedError: OOM when allocating tensor with shape[16384,1024] and type float on /job:localhost/replica:0/task:0/device:GPU:0 by allocator GPU_0_bfc
         [[node training/Adam/Variable_8/Assign (defined at E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\backend\tensorflow_backend.py:402)  = Assign[T=DT_FLOAT, _grappler_relax_allocator_constraints=true, use_locking=true, validate_shape=true, _device="/job:localhost/replica:0/task:0/device:GPU:0"](training/Adam/Variable_8, training/Adam/zeros_54)]]
Hint: If you want to see a list of allocated tensors when OOM happens, add report_tensor_allocations_upon_oom to RunOptions for current allocation info.


Caused by op 'training/Adam/Variable_8/Assign', defined at:
  File "threading.py", line 884, in _bootstrap
  File "threading.py", line 916, in _bootstrap_inner
  File "threading.py", line 864, in run
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\mainscripts\Trainer.py", line 78, in trainerThread
    loss_string = model.train_one_iter()
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\models\ModelBase.py", line 358, in train_one_iter
    losses = self.onTrainOneIter(sample, self.generator_list)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\DeepFaceLab\models\Model_H64\Model.py", line 85, in
onTrainOneIter
    total, loss_src_bgr, loss_src_mask, loss_dst_bgr, loss_dst_mask = self.ae.train_on_batch( [warped_src, target_src_full_mask, warped_dst, target_dst_full_mask], [target_src, target_src_full_mask, target_dst, target_dst_full_mask] )
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\engine\training.py", line 1216, in train_on_batch
    self._make_train_function()
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\engine\training.py", line 509, in _make_train_function
    loss=self.total_loss)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\legacy\interfaces.py", line 91, in wrapper
    return func(*args, **kwargs)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\optimizers.py", line 487, in get_updates
    ms = [K.zeros(K.int_shape(p), dtype=K.dtype(p)) for p in params]
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\optimizers.py", line 487, in <listcomp>
    ms = [K.zeros(K.int_shape(p), dtype=K.dtype(p)) for p in params]
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\backend\tensorflow_backend.py", line 704, in zeros
    return variable(v, dtype=dtype, name=name)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\backend\tensorflow_backend.py", line 402, in variable
    v = tf.Variable(value, dtype=tf.as_dtype(dtype), name=name)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variables.py", line 183, in __call__
    return cls._variable_v1_call(*args, **kwargs)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variables.py", line 146, in _variable_v1_call
    aggregation=aggregation)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variables.py", line 125, in <lambda>
    previous_getter = lambda **kwargs: default_variable_creator(None, **kwargs)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variable_scope.py", line 2444, in default_variable_creator
    expected_shape=expected_shape, import_scope=import_scope)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variables.py", line 187, in __call__
    return super(VariableMetaclass, cls).__call__(*args, **kwargs)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variables.py", line 1329, in __init__
    constraint=constraint)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\variables.py", line 1481, in _init_from_args
    validate_shape=validate_shape).op
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops\state_ops.py", line 221, in assign
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\ops    use_locking=use_locking, name=name)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\framework\op_def_library.py", line 787, in _apply_op_helper
    op_def=op_def)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\util\deprecation.py", line 488, in new_func
    return func(*args, **kwargs)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\fra    op_def=op_def)
  File "E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\tensorflow\python\framework\ops.py", line 1770, in __init__
ResourceExhaustedError (see above for traceback): OOM when allocating tensor with shape[16384,1024] and type float on /job:localhost/replica:0/task:0/device:GPU:0 by allocator GPU_0_bfc
         [[node training/Adam/Variable_8/Assign (defined at E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\_internal\python-3.6.8\lib\site-packages\keras\backend\tensorflow_backend.py:402)  = Assign[T=DT_FLOAT, _grappler_relax_allocator_constraints=true, use_locking=true, validate_shape=true, _device="/job:localhost/replica:0/task:0/device:GPU:0"](training/Adam/Variable_8, training/Adam/zeros_54)]]
Hint: If you want to see a list of allocated tensors when OOM happens, add report_tensor_allocations_upon_oom to RunOptions for current allocation info.


Done.
Press any key to continue . . .
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> python -V
Python 3.7.4
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> python
Python 3.7.4 (default, Aug  9 2019, 18:34:13) [MSC v.1915 64 bit (AMD64)] :: Anaconda, Inc. on win32

Warning:
This Python interpreter is in a conda environment, but the environment has
not been activated.  Libraries may fail to load.  To activate this environment
please see https://conda.io/activation

Type "help", "copyright", "credits" or "license" for more information.
>>> import tensorflow
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ModuleNotFoundError: No module named 'tensorflow'
>>> quit()
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> & '.\6) train H64.bat'
Running trainer.

Loading model...

Model first run. Enter model options as default for each run.
Write preview history? (y/n ?:help skip:n) :
n
Target iteration (skip:unlimited/default) :
0
Batch_size (?:help skip:0/default) :
0
Feed faces to network sorted by yaw? (y/n ?:help skip:n) :
n
Flip faces randomly? (y/n ?:help skip:y) :
y
Src face scale modifier % ( -30...30, ?:help skip:0) :
0
Use lightweight autoencoder? (y/n, ?:help skip:n) : y
Use pixel loss? (y/n, ?:help skip: n/default ) :
n
Using TensorFlow backend.
Loading: 100%|######################################################################| 654/654 [00:01<00:00, 364.71it/s]
Loading: 100%|####################################################################| 1506/1506 [00:03<00:00, 433.41it/s]
===== Model summary =====
== Model name: H64
==
== Current iteration: 0
==
== Model options:
== |== batch_size : 4
== |== sort_by_yaw : False
== |== random_flip : True
== |== lighter_ae : True
== |== pixel_loss : False
== Running on:
== |== [0 : GeForce GTX 950M]
==
== WARNING: You are using 2GB GPU. Result quality may be significantly decreased.
== If training does not start, close all programs and try again.
== Also you can disable Windows Aero Desktop to get extra free VRAM.
==
=========================
Saving....
Starting. Press "Enter" to stop training and save model.
[20:52:48][#001763][0498ms] loss_src:1.796 loss_dst:1.040
[21:07:48][#003571][0497ms] loss_src:1.562 loss_dst:0.987
[21:22:48][#005364][0492ms] loss_src:1.343 loss_dst:0.854
[21:37:48][#007130][0494ms] loss_src:1.899 loss_dst:1.023
[21:52:48][#008907][0494ms] loss_src:1.538 loss_dst:0.910
[22:07:49][#010724][0489ms] loss_src:1.893 loss_dst:0.743
[22:22:49][#012540][0492ms] loss_src:1.615 loss_dst:0.825
[22:37:49][#014358][0492ms] loss_src:1.076 loss_dst:0.603
[22:52:49][#016176][0497ms] loss_src:1.621 loss_dst:1.054
[23:07:49][#017995][0494ms] loss_src:1.929 loss_dst:0.600
[23:22:50][#019812][0493ms] loss_src:1.255 loss_dst:0.665
[23:37:50][#021628][0492ms] loss_src:1.699 loss_dst:0.499
[23:52:50][#023447][0495ms] loss_src:1.061 loss_dst:1.083
[00:07:50][#025265][0493ms] loss_src:1.142 loss_dst:0.588
[00:22:51][#027084][0492ms] loss_src:1.124 loss_dst:1.028
[00:37:51][#028902][0491ms] loss_src:1.125 loss_dst:0.936
[00:52:51][#030720][0491ms] loss_src:1.584 loss_dst:0.652
[01:07:51][#032539][0492ms] loss_src:0.969 loss_dst:1.027
[01:22:52][#034357][0494ms] loss_src:1.194 loss_dst:0.800
[01:37:52][#036175][0491ms] loss_src:0.857 loss_dst:0.844
[01:52:52][#037993][0494ms] loss_src:1.141 loss_dst:0.570
[02:07:52][#039811][0494ms] loss_src:0.945 loss_dst:0.551
[02:22:52][#041630][0494ms] loss_src:0.812 loss_dst:0.634
[02:37:53][#043448][0493ms] loss_src:0.749 loss_dst:0.910
[02:52:53][#045267][0488ms] loss_src:0.850 loss_dst:0.518
[03:07:53][#047085][0491ms] loss_src:1.188 loss_dst:0.554
[03:22:53][#048900][0494ms] loss_src:0.986 loss_dst:0.883
[03:37:53][#050718][0492ms] loss_src:0.836 loss_dst:0.564
[03:52:53][#052536][0492ms] loss_src:0.963 loss_dst:0.394
[04:07:53][#054354][0491ms] loss_src:1.400 loss_dst:0.730
[04:22:54][#056173][0491ms] loss_src:0.869 loss_dst:0.443
[04:37:54][#057992][0493ms] loss_src:1.376 loss_dst:0.682
[04:52:55][#059811][0493ms] loss_src:0.847 loss_dst:0.536
[05:07:55][#061630][0492ms] loss_src:1.435 loss_dst:0.499
[05:22:55][#063448][0490ms] loss_src:1.047 loss_dst:0.724
[05:37:56][#065266][0492ms] loss_src:1.178 loss_dst:0.352
[05:52:56][#067085][0491ms] loss_src:0.927 loss_dst:0.533
[06:07:56][#068904][0494ms] loss_src:1.000 loss_dst:0.712
[06:22:57][#070720][2223ms] loss_src:0.753 loss_dst:0.941
[06:37:58][#072505][0493ms] loss_src:1.007 loss_dst:0.620
[06:52:58][#074322][0493ms] loss_src:1.581 loss_dst:0.456
[07:07:58][#076140][0492ms] loss_src:0.686 loss_dst:0.436
[07:22:59][#077957][0492ms] loss_src:0.720 loss_dst:0.571
[07:37:59][#079776][0495ms] loss_src:1.466 loss_dst:0.656
[07:52:59][#081593][0495ms] loss_src:0.512 loss_dst:0.465
[08:07:59][#083374][0507ms] loss_src:1.075 loss_dst:0.630
[08:22:59][#085152][0496ms] loss_src:0.942 loss_dst:0.427
[08:38:00][#086944][0492ms] loss_src:1.011 loss_dst:0.463
[08:53:00][#088733][0516ms] loss_src:0.833 loss_dst:0.483
[09:08:00][#090533][0492ms] loss_src:0.957 loss_dst:0.548
[09:23:00][#092330][0493ms] loss_src:0.570 loss_dst:0.506
[09:38:01][#094132][0506ms] loss_src:1.028 loss_dst:0.348
[09:53:01][#095894][0495ms] loss_src:0.740 loss_dst:1.000
[10:08:01][#097668][0497ms] loss_src:1.254 loss_dst:0.334
[10:23:01][#099456][0493ms] loss_src:0.597 loss_dst:0.598
[10:38:02][#101184][0497ms] loss_src:0.749 loss_dst:0.503
[10:53:02][#102942][0497ms] loss_src:0.693 loss_dst:0.927
[11:08:02][#104655][0806ms] loss_src:1.217 loss_dst:0.406
[11:23:03][#106365][0537ms] loss_src:0.740 loss_dst:0.623
[11:38:03][#108017][0503ms] loss_src:0.699 loss_dst:0.515
[11:53:03][#109749][0499ms] loss_src:0.744 loss_dst:0.642
[12:08:03][#111519][0491ms] loss_src:0.715 loss_dst:0.476
[12:23:03][#113326][0492ms] loss_src:0.666 loss_dst:0.683
[12:38:04][#115131][0508ms] loss_src:0.949 loss_dst:0.321
[12:53:04][#116933][0498ms] loss_src:0.678 loss_dst:0.404
[13:08:04][#118724][0493ms] loss_src:0.745 loss_dst:0.330
[13:23:04][#120518][0494ms] loss_src:0.791 loss_dst:0.374
[13:38:05][#122323][0491ms] loss_src:0.718 loss_dst:0.990
[13:53:05][#124140][0492ms] loss_src:0.801 loss_dst:0.437
[14:08:05][#125955][0494ms] loss_src:1.049 loss_dst:0.403
[14:23:06][#127771][0493ms] loss_src:0.594 loss_dst:0.581
[14:38:06][#129586][0495ms] loss_src:0.743 loss_dst:0.498
[14:53:06][#131402][0493ms] loss_src:0.676 loss_dst:0.687
[15:23:07][#135032][0490ms] loss_src:0.834 loss_dst:0.629
[15:38:07][#136848][0494ms] loss_src:1.147 loss_dst:0.465
[15:53:07][#138664][0492ms] loss_src:0.605 loss_dst:0.358
[16:08:07][#140479][0494ms] loss_src:1.187 loss_dst:0.482
[16:23:08][#142291][0489ms] loss_src:0.705 loss_dst:0.385
[16:38:08][#144106][0490ms] loss_src:0.727 loss_dst:0.364
[16:53:08][#145921][0515ms] loss_src:1.643 loss_dst:0.665
[17:08:08][#147736][0492ms] loss_src:0.859 loss_dst:0.471
[17:23:08][#149551][0493ms] loss_src:0.681 loss_dst:0.352
[17:38:08][#151366][0493ms] loss_src:0.558 loss_dst:0.452
[17:53:08][#153180][0492ms] loss_src:0.880 loss_dst:0.532
[18:08:09][#154995][0493ms] loss_src:0.687 loss_dst:0.457
[18:23:09][#156810][0497ms] loss_src:0.610 loss_dst:0.570
[18:38:09][#158623][0493ms] loss_src:0.688 loss_dst:0.488
[18:53:10][#160438][0494ms] loss_src:0.841 loss_dst:0.440
[19:08:10][#162256][0490ms] loss_src:0.441 loss_dst:0.336
[19:23:10][#164078][0491ms] loss_src:0.622 loss_dst:0.403
[19:38:10][#165899][0495ms] loss_src:0.529 loss_dst:0.389
[19:53:10][#167718][0491ms] loss_src:0.732 loss_dst:0.524
[20:08:10][#169536][0491ms] loss_src:0.651 loss_dst:0.564
[20:23:10][#171337][0500ms] loss_src:0.823 loss_dst:0.435
[20:38:10][#173125][0491ms] loss_src:0.783 loss_dst:0.469
[20:53:10][#174877][0494ms] loss_src:0.510 loss_dst:0.494
[20:53:29][#174912][0493ms] loss_src:0.650 loss_dst:0.474
[20:53:34][#174921][0493ms] loss_src:0.833 loss_dst:0.913
Done.
Press any key to continue . . .
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> & '.\7) convert H64.bat'
Running converter.

Loading model...
Using TensorFlow backend.
===== Model summary =====
== Model name: H64
==
== Current iteration: 174921
==
== Model options:
== |== batch_size : 4
== |== sort_by_yaw : False
== |== random_flip : True
== |== lighter_ae : True
== |== pixel_loss : False
== Running on:
== |== [0 : GeForce GTX 950M]
==
== WARNING: You are using 2GB GPU. Result quality may be significantly decreased.
== If training does not start, close all programs and try again.
== Also you can disable Windows Aero Desktop to get extra free VRAM.
==
=========================
Choose mode: (1) overlay, (2) hist match, (3) hist match bw, (4) seamless, (5) raw. Default - 4 :
4
Suppress seamless jitter? [ y/n ] (?:help skip:n ) :
n
Seamless hist match? (y/n skip:n) :
n
Use predicted mask? (y/n skip:y) :
y
Choose erode mask modifier [-200..200] (skip:0) :
0
Choose blur mask modifier [-200..200] (skip:0) :
0
Choose seamless erode mask modifier [-100..100] (skip:0) :
0
Choose output face scale modifier [-50..50] (skip:0) :
0
Apply color transfer to predicted face? Choose mode ( rct/lct skip:None ) :
None
Degrade color power of final image [0..100] (skip:0) :
0
Export png with alpha channel? (y/n skip:n) :
n

Collecting alignments: 100%|########################################################| 1506/1506 [00:02<00:00, 603.52it/s]
Running on CPU0.
Running on CPU1.
Running on CPU2.
Running on CPU3.
Converting:   0%|                                                                               | 0/1538 [00:00<?, ?it/s]no faces found for 00001.png, copying without faces
no faces found for 00002.png, copying without faces
no faces found for 00003.png, copying without faces
no faces found for 00004.png, copying without faces
Converting:   0%|                                                                       | 1/1538 [00:00<01:32, 16.55it/s]no faces found for 00005.png, copying without faces
Converting:  61%|##########################################3                          | 944/1538 [12:07<07:37,  1.30it/s]no faces found for 00948.png, copying without faces
Converting:  61%|##########################################3                          | 945/1538 [12:07<07:36,  1.30it/s]no faces found for 00949.png, copying without faces
Converting:  62%|##########################################6                          | 950/1538 [12:10<07:31,  1.30it/s]no faces found for 00954.png, copying without faces
Converting:  67%|#############################################4                      | 1029/1538 [12:50<06:21,  1.33it/s]no faces found for 01033.png, copying without faces
Converting:  67%|#############################################5                      | 1030/1538 [12:50<06:20,  1.34it/s]no faces found for 01034.png, copying without faces
Converting:  67%|#############################################5                      | 1031/1538 [12:50<06:19,  1.34it/s]no faces found for 01035.png, copying without faces
Converting:  67%|#############################################7                      | 1035/1538 [12:51<06:15,  1.34it/s]no faces found for 01039.png, copying without faces
Converting:  67%|#############################################8                      | 1037/1538 [12:52<06:13,  1.34it/s]no faces found for 01041.png, copying without faces
Converting:  68%|#############################################9                      | 1039/1538 [12:53<06:11,  1.34it/s]no faces found for 01043.png, copying without faces
Converting:  68%|#############################################9                      | 1040/1538 [12:53<06:10,  1.35it/s]no faces found for 01044.png, copying without faces
Converting:  68%|##############################################2                     | 1046/1538 [12:55<06:04,  1.35it/s]no faces found for 01050.png, copying without faces
Converting:  68%|##############################################2                     | 1047/1538 [12:55<06:03,  1.35it/s]no faces found for 01051.png, copying without faces
Converting:  68%|##############################################3                     | 1049/1538 [12:56<06:01,  1.35it/s]no faces found for 01052.png, copying without faces
Converting:  68%|##############################################4                     | 1050/1538 [12:56<06:00,  1.35it/s]no faces found for 01053.png, copying without faces
no faces found for 01054.png, copying without faces
Converting:  68%|##############################################4                     | 1051/1538 [12:56<05:59,  1.35it/s]no faces found for 01055.png, copying without faces
Converting:  68%|##############################################5                     | 1052/1538 [12:56<05:58,  1.36it/s]Converting:  69%|##############################################6                     | 1054/1538 [12:56<05:56,  1.36it/s]no faces found for 01057.png, copying without faces
Converting:  69%|##############################################6                     | 1055/1538 [12:56<05:55,  1.36it/s]no faces found for 01058.png, copying without faces
Converting:  69%|##############################################6                     | 1056/1538 [12:56<05:54,  1.36it/s]no faces found for 01059.png, copying without faces
Converting:  69%|##############################################7                     | 1057/1538 [12:56<05:53,  1.36it/s]no faces found for 01060.png, copying without faces
Converting:  69%|##############################################7                     | 1058/1538 [12:56<05:52,  1.36it/s]no faces found for 01061.png, copying without faces
Converting:  69%|##############################################8                     | 1059/1538 [12:56<05:51,  1.36it/s]no faces found for 01062.png, copying without faces
no faces found for 01063.png, copying without faces
Converting:  69%|##############################################8                     | 1060/1538 [12:56<05:50,  1.37it/s]no faces found for 01064.png, copying without faces
Converting:  69%|##############################################9                     | 1062/1538 [12:56<05:47,  1.37it/s]no faces found for 01065.png, copying without faces
Converting:  69%|##############################################9                     | 1063/1538 [12:56<05:46,  1.37it/s]no faces found for 01066.png, copying without faces
Converting:  70%|###############################################5                    | 1075/1538 [13:02<05:36,  1.37it/s]no faces found for 01079.png, copying without faces
Converting:  71%|################################################                    | 1087/1538 [13:08<05:27,  1.38it/s]

Converting:  71%|################################################1                   | 1088/1538 [13:09<05:26,  1.38it/sCConverting: 100%|####################################################################| 1538/1538 [17:04<00:00,  1.50it/s]
Done.
Press any key to continue . . .
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> & '.\8) converted to mp4.bat'
Bitrate of output file in MB/s ? (default:16) :
16
ffmpeg version N-89980-ge752da5464 Copyright (c) 2000-2018 the FFmpeg developers
  built with gcc 7.2.0 (GCC)
  configuration: --enable-gpl --enable-version3 --enable-sdl2 --enable-bzlib --enable-fontconfig --enable-gnutls --enable
-iconv --enable-libass --enable-libbluray --enable-libfreetype --enable-libmp3lame --enable-libopencore-amrnb --enable-li
bopencore-amrwb --enable-libopenjpeg --enable-libopus --enable-libshine --enable-libsnappy --enable-libsoxr --enable-libt
heora --enable-libtwolame --enable-libvpx --enable-libwavpack --enable-libwebp --enable-libx264 --enable-libx265 --enable
-libxml2 --enable-libzimg --enable-lzma --enable-zlib --enable-gmp --enable-libvidstab --enable-libvorbis --enable-libvo-
amrwbenc --enable-libmysofa --enable-libspeex --enable-libxvid --enable-libmfx --enable-amf --enable-cuda --enable-cuvid
--enable-d3d11va --enable-nvenc --enable-dxva2 --enable-avisynth
  libavutil      56.  7.100 / 56.  7.100
  libavcodec     58. 10.100 / 58. 10.100
  libavformat    58.  9.100 / 58.  9.100
  libavdevice    58.  1.100 / 58.  1.100
  libavfilter     7. 11.101 /  7. 11.101
  libswscale      5.  0.101 /  5.  0.101
  libswresample   3.  0.101 /  3.  0.101
  libpostproc    55.  0.100 / 55.  0.100
Input #0, image2, from 'E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\workspace\data_dst\merged\%5d.png':
  Duration: 00:01:01.52, start: 0.000000, bitrate: N/A
    Stream #0:0: Video: png, rgb24(pc), 1920x1080 [SAR 1:1 DAR 16:9], 25 fps, 25 tbr, 25 tbn, 25 tbc
Input #1, mov,mp4,m4a,3gp,3g2,mj2, from 'E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\workspace\data_dst.mp4':
  Metadata:
    major_brand     : isom
    minor_version   : 512
    compatible_brands: isomiso2avc1mp41
    encoder         : Lavf56.40.101
  Duration: 00:01:04.27, start: 0.000000, bitrate: 676 kb/s
    Stream #1:0(und): Video: h264 (High) (avc1 / 0x31637661), yuv420p(tv, bt709), 1920x1080 [SAR 1:1 DAR 16:9], 545 kb/s,
 23.99 fps, 23.98 tbr, 90k tbn, 47.95 tbc (default)
    Metadata:
      handler_name    : VideoHandler
    Stream #1:1(und): Audio: aac (LC) (mp4a / 0x6134706D), 44100 Hz, stereo, fltp, 125 kb/s (default)
    Metadata:
      handler_name    : SoundHandler
Stream mapping:
  Stream #0:0 -> #0:0 (png (native) -> h264 (libx264))
  Stream #1:1 -> #0:1 (aac (native) -> aac (native))
Press [q] to stop, [?] for help
[image2 @ 000001928addbec0] Thread message queue blocking; consider raising the thread_queue_size option (current value:
8)
[libx264 @ 000001928bab0b40] using SAR=1/1
[libx264 @ 000001928bab0b40] using cpu capabilities: MMX2 SSE2Fast SSSE3 SSE4.2 AVX FMA3 BMI2 AVX2
[libx264 @ 000001928bab0b40] profile High, level 4.1
[libx264 @ 000001928bab0b40] 264 - core 155 r2901 7d0ff22 - H.264/MPEG-4 AVC codec - Copyleft 2003-2018 - http://www.vide
olan.org/x264.html - options: cabac=1 ref=3 deblock=1:0:0 analyse=0x3:0x113 me=hex subme=7 psy=1 psy_rd=1.00:0.00 mixed_r
ef=1 me_range=16 chroma_me=1 trellis=1 8x8dct=1 cqm=0 deadzone=21,11 fast_pskip=1 chroma_qp_offset=-2 threads=6 lookahead
_threads=1 sliced_threads=0 nr=0 decimate=1 interlaced=0 bluray_compat=0 constrained_intra=0 bframes=3 b_pyramid=2 b_adap
t=1 b_bias=0 direct=1 weightb=1 open_gop=0 weightp=2 keyint=250 keyint_min=23 scenecut=40 intra_refresh=0 rc_lookahead=40
 rc=abr mbtree=1 bitrate=16000 ratetol=1.0 qcomp=0.60 qpmin=0 qpmax=69 qpstep=4 ip_ratio=1.40 aq=1:1.00
Output #0, mp4, to 'E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX\workspace\result.mp4':
  Metadata:
    encoder         : Lavf58.9.100
    Stream #0:0: Video: h264 (libx264) (avc1 / 0x31637661), yuv420p(progressive), 1920x1080 [SAR 1:1 DAR 16:9], q=-1--1,
16000 kb/s, 23.98 fps, 24k tbn, 23.98 tbc
    Metadata:
      encoder         : Lavc58.10.100 libx264
    Side data:
      cpb: bitrate max/min/avg: 0/0/16000000 buffer size: 0 vbv_delay: -1
    Stream #0:1(und): Audio: aac (LC) (mp4a / 0x6134706D), 48000 Hz, stereo, fltp, 192 kb/s (default)
      handler_name    : SoundHandler
      encoder         : Lavc58.10.100 aac
frame= 1538 fps= 18 q=-1.0 Lsize=  105601kB time=00:01:04.27 bitrate=13458.6kbits/s speed=0.766x
video:104027kB audio:1530kB subtitle:0kB other streams:0kB global headers:0kB muxing overhead: 0.041590%
[libx264 @ 000001928bab0b40] frame I:8     Avg QP: 0.13  size:100808
[libx264 @ 000001928bab0b40] frame P:584   Avg QP: 0.06  size: 81373
[libx264 @ 000001928bab0b40] frame B:946   Avg QP: 0.29  size: 61517
[libx264 @ 000001928bab0b40] consecutive B-frames:  1.5% 42.3% 21.7% 34.6%
[libx264 @ 000001928bab0b40] mb P  I16..4: 10.0%  2.0%  3.3%  P16..4: 13.4%  3.3%  2.2%  0.0%  0.0%    skip:65.8%
[libx264 @ 000001928bab0b40] mb B  I16..4:  0.3%  0.2%  0.9%  B16..8: 12.5%  2.7%  1.2%  direct: 7.5%  skip:74.6%  L0:40.5% L1:53.3% BI: 6.2%
[libx264 @ 000001928bab0b40] final ratefactor: -6.79
[libx264 @ 000001928bab0b40] 8x8 transform intra:13.3% inter:31.2%
[libx264 @ 000001928bab0b40] coded y,uvDC,uvAC intra: 37.0% 39.5% 35.3% inter: 9.4% 13.0% 11.5%
[libx264 @ 000001928bab0b40] i16 v,h,dc,p: 62% 25%  7%  5%
[libx264 @ 000001928bab0b40] i8 v,h,dc,ddl,ddr,vr,hd,vl,hu: 31% 21% 33%  2%  2%  3%  2%  3%  2%
[libx264 @ 000001928bab0b40] Weighted P-Frames: Y:0.0% UV:0.0%
[libx264 @ 000001928bab0b40] ref P L0: 72.4%  6.9% 13.7%  7.1%
[libx264 @ 000001928bab0b40] ref B L0: 88.0% 10.5%  1.5%
[libx264 @ 000001928bab0b40] ref B L1: 98.8%  1.2%
[libx264 @ 000001928bab0b40] kb/s:13284.80
[aac @ 000001928ae73600] Qavg: 3394.612
Done.
PS E:\DeepFaceLab\DeepFaceLab\DeepFaceLabCUDA10.1AVX> Windows PowerShell
```
