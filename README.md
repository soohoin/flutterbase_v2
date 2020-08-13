# flutterbase_v2


## Installation

* Follow the [Flutter + Firebase Installation](https://docs.google.com/document/d/e/2PACX-1vQuzuqmI0mgKt82ZI6silmBLrsJuroAZa2XR7OsqoMGPAKb-DVtXUsjjH7TjSd_9pD_0e04qq9gaTKx/pub)
* Enable `Anonymous` in `Firebase Authentication Sign-in Method`.


## Coding guide

* Most of the codes are derived from [Flutterbase Version 1](https://github.com/thruthesky/flutterbase). You can refer to it for details.

* See the code in [fchat](https://github.com/thruthesky/fchat) app.


## Installation

### Login

* Enable `Google` in firebase if you want users to login with google account.
* To enable `Facebook` login
  * You need to create and set an App in Facebook developers account.
  * And then update `Info.plist` for `flutter_webview_plugin: ^0.3.11`
  * And enable `Facebook` in firebase.

* To enable `Kakaotalk` login
  * You need to create and set an App in Kakaotalk developers account.
  * And set for `kakao_flutter_sdk` and its dependencies.
  * And you need to enable `Email/Password` under Firebase > Authentication > Sign-in method.

### Chat

