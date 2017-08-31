---
layout: post
title: "React Native: Set RootView Background Color"
category: React Native
---

In the RootView of a React Native app, the default background color is white. We can change this to another color by following the steps below.

**Note:** _Changing the background color may resolve issues related to launch screen flicker/flash and background color during orientation change._

## iOS

1. Open `AppDelegate.m` located in `PROJECT_DIR/ios/AppName/`
2. Locate line that matches or is similar to:
        `rootView.backgroundColor = [[UIColor alloc] initWithRed:1.0f green:1.0f blue:1.0f alpha:1];`
3. Adjust UIColor values!
  - [UIColor](http://uicolor.xyz/) is a handy website that can be used to convert HEX & RGB colors to UIColor for both Objective-C and Swift.
