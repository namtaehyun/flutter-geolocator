## 2.1.1

- Upgrade the `geolocator_platform_interface` dependency to version 3.0.1.

## 2.1.0

- Made changes to the implementation of the `getCurrentPosition` and `getPositionStream` method to match new platform interface. 
- Fixes issues where geolocator doesn't work on Safari due to missing implementation of `query` method in the browser.

## 2.0.6

- Fixes a bug where the `LocationAccuracy.reduced` accuracy value is treated as high accuracy on web.

## 2.0.5

- Ensure the `requestPermission` method correctly awaits the users input and not return prematurely (see issue [#783](https://github.com/Baseflow/flutter-geolocator/issues/783)).

## 2.0.4

- Added an example App to demonstrate how to directly use the geolocator_web package in a Flutter application.

## 2.0.3

- Implement missing `isLocationServiceEnabled` for web implementation (see issue [#694](https://github.com/Baseflow/flutter-geolocator/issues/694)).

## 2.0.2

- Solve bug receiving same location from stream when using `distantFilter` (see issue [#674](https://github.com/Baseflow/flutter-geolocator/issues/674)).

## 2.0.1

- Solve bug causing error when requesting permissions (see issue [#673](https://github.com/Baseflow/flutter-geolocator/issues/673)). 

## 2.0.0

- Stable release for null safety.

## 1.0.1

- Solve bug causing error when requesting permissions (see issue [#673](https://github.com/Baseflow/flutter-geolocator/issues/673)).

## 1.0.0

- Initial release of the geolocator web implementation.