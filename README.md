MessagePack.swift
=================

![License](https://img.shields.io/cocoapods/l/MessagePack.swift.svg?style=flat)
![Platform](https://img.shields.io/cocoapods/p/MessagePack.swift.svg?style=flat)

A fast, zero-dependency MessagePack implementation written in Swift 4. Supports Apple platforms and Linux.

## Fork Changes

* Uses [OrderedDictionary](https://github.com/apple/swift-collections) instead of a Dictionary
* Supports only SPM

## Installation

### SPM (Swift Package Manager)

You can easily integrate MessagePack.swift in your app with SPM. Just add MessagePack.swift as a dependency:

```swift
import PackageDescription

let package = Package(
    name: "MyAwesomeApp",
    dependencies: [
        .Package(url: "https://github.com/luckymarmot/MessagePack.swift.git", branch: "master"),
    ]
)
```

## Version

- Versions 4.x support Swift 5.2.
- Versions 3.x support Swift 4.
- Support for Swift 3 was dropped after [2.1.1](https://github.com/a2/MessagePack.swift/releases/tag/2.1.1).
- Support for Swift 2 was dropped after [1.2.0](https://github.com/a2/MessagePack.swift/releases/tag/1.2.0).

## Authors

Alexsander Akers, me@a2.io

## License

MessagePack.swift is available under the MIT license. See the LICENSE file for more info.
