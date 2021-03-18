# flutter_ios_video_freeze

This is a repository that group 3 applications for Flutter that were created to test a freeze bug on newer Flutter version that is present when run on older iOS devices (Tested on: iPad 2 and iPad 4)

3 versions of Flutter were used for the testing and each directory represent the corresponding application which was built on each version.

1. `flutter_ios_video_freeze-1_23`: Application created for Flutter version 1_23_0-7_0_pre and which work great on old iOS devices
2. `flutter_ios_video_freeze-stable_2_0_2`: Application created for the stable version of Flutter (version 2.0.2) and which doesn't work great on old iOS devices
3. `flutter_ios_video_freeze_master`: Application created for the Master version of Flutter as of 2021-03-17 (which is version: 2.1.0-13.0.pre.149) and which doesn't work great on old iOS devices

This repository was created to add further information to this Flutter issue: https://github.com/flutter/flutter/issues/78507
