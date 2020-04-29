##相关环境

flutter --version
Flutter 1.18.0-7.0.pre.24 • channel master • https://github.com/flutter/flutter.git
Framework • revision f9c3c9094e (7 days ago) • 2020-04-22 04:43:01 -0400
Engine • revision 8d7071ea46
Tools • Dart 2.9.0 (build 2.9.0-2.0.dev 87b829bacd)


# Flutter Music App

First Open Source Flutter based dribbblel Design Music Player.

## Features(Android & iOS)

  * [x] search online songs (Require Network Permission)
  * [x] Beautiful UI with multiple themes includes light theme and dark theme
  * [x] multiple language includes chinese and english
  * [x] Play background
  * [x] Animation
  * [x] Full Fledged Example
  * [x] Play / Stop / Pause
  * [x] Previous / Next
  * [x] Seek
  * [x] Shuffle
  * [x] Album Art
  * [x] onComplete
  * [x] onDuration / onCurrentPosition
  * [x] Favorite
  * [x] Download

### Show some ❤️ and star the repo to support the project



## Screenshots(iOS)

- #### Light theme

| ![](screenshots/image-20200301200224147.png) | ![](screenshots/Screenshot_12.png) | ![](screenshots/Screenshot_13.png) |
| -------------------------------------------- | ---------------------------------- | ---------------------------------- |
| ![](screenshots/Screenshot_15.png)           | ![](screenshots/Screenshot_14.png) | ![](screenshots/Screenshot_16.png) |

- #### Dark theme

| ![](screenshots/Screenshot_23.png) | ![](screenshots/Screenshot_24.png) | ![](screenshots/Screenshot_25.png) |
| ---------------------------------- | ---------------------------------- | ---------------------------------- |
| ![](screenshots/Screenshot_27.png) | ![](screenshots/Screenshot_26.png) | ![](screenshots/Screenshot_28.png) |



### Add this to ios Info.plist allow https and background

```yaml
    <key>UIBackgroundModes</key>
    <array>
        <string>audio</string>
    </array>
    <key>NSAppTransportSecurity</key>
    <dict>
    <key>NSAllowsArbitraryLoads</key>
    <true/>
    </dict>
```



```
Copyright 2020 obnil

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

## Getting Started


