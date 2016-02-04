# libsalamander

Salamander is a secure messaging protocol for mobile devices.  It uses
the Axolotl Ratchet designed by Trevor Perrin and Moxie Marlinspike.

This library, libsalamander, is an implementation of the Salamander
protocol, and is used in the Silent Circle suite of applications.

Silent Circle is releasing libsalamander under the Apache License
Version 2.0 to help build a community around secure mobile messaging
and to encourage community review of the protocol and this
implementation.

This implementation is by Werner Dittmann.

The design of Salamander is a collaboration between Werner Dittmann,
Phil Zimmermann, and Travis Cross.

## Building libsalamander

This project is configured to be built for use with Android.  To
build, edit android-build.sh and set the ANDROID_NDK path
appropriately for your environment, then run ./android-build.sh.

## License

    Copyright 2016 Silent Circle, LLC

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
