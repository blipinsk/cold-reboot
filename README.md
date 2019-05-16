# cold-reboot

A simple tool to quickly reboot your Android emulator with Cold Boot option (without restoring emulator's state snapshot).

![cold-reboot](https://i.imgur.com/7wY1tXH.gif)

## Usage

```
$ cold-reboot
```

that's it.

_(For now, if there's more than one emulator running, it will reboot all of them...)_

## Installation

(*The installation process is kind of manual for now, but will be improved in the future. The goal is to be able to install this script with `brew`*)

1. Make sure you've got `python` (at least 2.7)
2. Add `<your_path_to_android_sdk>/tools` to your `PATH` env variable
3. Add `<your_path_to_android_sdk>/platform-tools` to your `PATH` env variable
4. Add `<your_path_to_android_sdk>/emulator` to your `PATH` env variable
5. Copy the `cold-reboot` script to a destination of your choice
6. Add `path/to/the/script` (chosen in step 3.) to your `PATH` env variable

Contributing
------------

I am no python developer, I just glued together this script from what I could find in Google.
Feel free to contribute optimising this script as much as you want.


Developed by
------------
 * Bartek Lipiński

License
-------

    Copyright 2019 Bartosz Lipiński

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
