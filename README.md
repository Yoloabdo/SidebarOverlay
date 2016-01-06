# SidebarOverlay

[![Travis CI](https://api.travis-ci.org/aperechnev/SidebarOverlay.svg?branch=develop)](https://travis-ci.org/aperechnev/SidebarOverlay) [![CocoaPods](https://img.shields.io/cocoapods/v/SidebarOverlay.svg)](http://cocoapods.org/pods/SidebarOverlay) ![CocoaPods](https://img.shields.io/cocoapods/p/SidebarOverlay.svg) [![CocoaDocs](https://img.shields.io/cocoapods/metrics/doc-percent/SidebarOverlay.svg)](http://cocoadocs.org/docsets/SidebarOverlay/)

`SidebarOverlay` is an implementation of sidebar menu, similar to `ECSlidingViewController`. The difference is that in `SidebarOverlay` the sidebar menu covers the top view when user opens it, like on the picture below:

![SidebarOverlay application example](https://habrastorage.org/files/812/9c0/7da/8129c07da55f4a95a110bea8eb4a8e5b.gif)

## Installation

The easiest way to start development using `SidebarOverlay` is to install it via CocoaPods. Just add it to your `Podfile`:

```Podspec
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'

pod 'SidebarOverlay'
```

## Getting Started

It's quit simple to start developing with `SidebarOverlay`. First, you have to subclass `SOContainerViewController`:

```Swift
import SidebarOverlay

class ViewController: SOContainerViewController {
}
```

This is the root view controller, that makes all magic.

## How To Contribute

## Versioning

We are using [semantic versioning](http://semver.org).