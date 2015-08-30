BlackHawk-Plugin-Vibration
----------

Vibration plugin of [BlackHawk](https://github.com/Lucky-Orange/BlackHawk).

##Install

1. Copy js/Vibration.js into www/plugins directory in your project.
2. Drag swift/Vibration.swift into your Xcode project.
3. add "Vibration" to the params of self.runPluginJS(["Base"]) in BlackHawkViewController class.

##Use

```swift
// js code
navigator.vibrate();
```
iOS system support this method only.

##LICENSE
BlackHawk is open-sourced software licensed under the MIT license.

Copyright (c) 2015 Leqicheng Inc. 乐其橙科技（北京）有限公司

