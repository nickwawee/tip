# Pre-work - *tip*

**tip** is a tip calculator application for iOS.

Submitted by: **Nick Wawee**

Time spent: **20+** hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [x] Settings page to change the default tip percentage.
* [ ] UI animations
* [x] Remembering the bill amount across app restarts (if <10mins)
* [x] Using locale-specific currency and currency thousands separators.
* [x] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [x] Tip slider implemented with graphics on both ends
- [x] Default number of people is on settings page and is saveable
- [x] Default light or dark color theme choice on settings page
- [x] Different font formats and layout from original app



## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='http://g.recordit.co/5SlS2RKNeO.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

The challenges encountered when building the app are listed below:

- Performing segues on embedded navigation controller posed an issue.
- Formatting the currency with the correct thousands separator took some time to establish a working method for this application.
- Saving the defaults and using DateFormatter also took a bit to get used to. The implementation into the application life cycle also took some time.
- The decimal pad is not always visible in this application because of the transition to the number pad for party size, as well as to access the tip slider.

Future improvements and remaining questions include: 

- Formatting the bill amount field to a currency format and have it perform a calculation with the currency format showing. This was left undone because of it is unlikely that the bill amount will meet or exceed 1000.
- The usage of the ! or ? operator is still somewhat unclear on what they actually do.
- Turning the navigation controller to the light or dark theme was left unknown on how to do.

## License

    Copyright [2020] [Nick Wawee]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
