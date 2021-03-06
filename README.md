# ZSwiftKit

## Overview

Toolkit Collection ( Helpers, Extensions, Snippets ) for Swift

## Requirements
* Swift3
* iOS8

## Installation with CocoaPods

ZSwiftKit is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "ZSwiftKit"
```

## Usage

```Swift
import ZSwiftKit

let formattedDateString = Helper.Date.stringFromDate(   messageData.date,
                                                        format: "E',' MMM d',' yyyy",
                                                        calendarIdentifier: Calendar.Identifier.gregorian,
                                                        timeZone: TimeZone(abbreviation: "ICT")!)

```

## Example Project

An example project is included with this repo.  To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Author

Peerapat Atawatana

## License

ZSwiftKit is available under the MIT license. See the LICENSE file for more info.
