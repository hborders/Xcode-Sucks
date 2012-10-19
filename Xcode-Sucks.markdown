# Xcode Sucks: Reasons you don't want to develop in iOS

Heath Borders  
Senior Software Engineer  
Asynchrony Solutions, Inc.  
[@heathborders](https://twitter.com/heathborders)

<https://github.com/hborders/Xcode-Sucks/>

[@StealthMountain](https://twitter.com/StealthMountain)

## Setup Sucks

* On-device development requires an [Apple Developer Account](http://developer.apple.com/ios)

* Can only support 100 devices per account

* The simulator doesn't support gestures, accelerometer, camera

* Also has very different performance profile

## Editing Text with Xcode Sucks

* No Refactoring Support

	* Not even renaming

	* Xcode claims to support renaming, but lies

* No auto-import

* Terrible code suggestions (NSStream instead of NSString)

## Xcode Projects Suck

* Everything in an Xcode project is managed by a single XML file

	* Conflicts galore!

* Xcode has virtual groups that aren't linked to the filesystem

	* Missing files galore!

## Xcode Stability Sucks

* It crashes all the time (for some once per hour)

* bootstrapserver crashes require restarting device

## Xcode Debugging Sucks

* LLDB crashes

* LLDB claims to support Objective-C syntax, but doesn't due to runtime erasure

* No hotswapping code

## Xcode Command Line Sucks

* No command line interface for:

	* Installing apps on device or simulator

	* Manipulating device data

	* Accepting permission to track location 

## Xcode Testing Sucks

* OCUnit (Apple's preferred Unit Testing Framework) is terrible (could be a whole talk)

* UIAutomation is crashy/half-baked

* Objective-C Sucks

* Interfaces are required for all classes

* No abstract methods

* Frameworks take unparsed code instead of lambdas

* No Generics

* Can't add null to Collections or Maps

* Circular imports are errors

* No language spec, just Clang parser code.

* Method calls to null are legal, all respond the same

* Everything you hate about C

* (Java metaphors used)

## Apple Sucks

* No roadmaps for releases

* Barely any visibility into bug fixes

* Radar is a terrible bug tracking tool

* Rewrote Xcode in 2010, many broken features are still broken 2 years later.

* Developer Forums are private, not googleable