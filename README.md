# KelvinColor

[![Language](https://img.shields.io/badge/Swift-3.1-orange.svg?style=flat)](https://swift.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

_Black body temperature to color in swift._

## Installation

### Carthage

Add the following in your project's  [Cartfile](https://github.com/Carthage/Carthage/blob/master/Documentation/Artifacts.md):

    github "DJBen/KelvinColor" ~> 0.1.0

## Usage

Temperature to color and color to temperature methods are extensions of `UIColor` class. No other classes are required!

1. Kelvin to `UIColor`

```swift
UIColor.init(temperature: 6500)
// (255, 249, 253)
```
2. UIColor to Kelvin

```swift
color.temperature
```
