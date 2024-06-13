# WTF-CallKit
Tracking CallKit related issues.

Most of the issues have been reported to the Apple, and they can be reproduced through the speaker box.


| Tilte                                                                                                          | Reproducibility | Affects Version | Device           | Fix Version | Detail/Feedback                                                 | Can be reproduced in SpeakerBox |
| -------------------------------------------------------------------------------------------------------------- | --------------- | --------------- | ---------------- | ----------- | --------------------------------------------------------------- | ------------------------------- |
| lock screen -> answer an incoming VIDEO call -> don't lock screen -> No Duration                               | Always          | iOS 15.1        | Any              |             |                                                                 | YES                             |
| mute -> answer native call -> start new call -> No Audio                                                       | Always          | iOS 15.1        | Any              | iOS 17.0    |                                                                 | YES                             |
| make a call -> answer another native call & hold -> caller ends the native call -> unhold the call -> No audio | Always          | iOS 15.1        | Any              |             |                                                                 | YES                             |
| Can't activate audio session after disconnecting continuity camera                                             | Always          | iOS 16.0        | Any              |             |                                                                 | YES                             |
| Can't play video in CallKit                                                                                    | Always          | iOS 17.0        | Any              | iOS 17.4.1  |                                                                 | YES                             |
| Received twice callback when mute/unmute                                                                       | Always          | iOS 17.0        | Any              |             | [Link](https://forums.developer.apple.com/forums/thread/734873) | YES                             |
| Connect/disconnect the headset causes an media service reset                                                   | Always          | iOS 17.4        | iPad16,3 M4 chip |             |                                                                 | YES                             |

