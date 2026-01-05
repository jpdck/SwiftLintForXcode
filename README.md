# SwiftLint for Xcode
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)

SwiftLint for Xcode is a Xcode Extension that was created to run [SwiftLint](https://github.com/realm/SwiftLint).

## Requirements
- Xcode 26.0 or later
- macOS 26.0 or later (macOS Redwood or later)
- [SwiftLint](https://github.com/realm/SwiftLint)

## Install

1. Install Xcode 26.0 or later
2. Clone this repository.
3. Open `SwiftLintForXcode.xcodeproj` by double clicking on it.
4. Configure signing with your own developer ID on all three targets (SwiftLintForXcode, SwiftLint and SwiftLintHelper).
5. Quit Xcode.
6. Open a terminal, change to the directory where you cloned and run `xcodebuild -scheme SwiftLintForXcode install DSTROOT=~` to compile the extension.
7. Run `~/Applications/SwiftLintForXcode.app` and quit.
8. Go to System Preferences -> Extensions -> Xcode Source Editor and enable the extension.
9. Open Xcode and the extension should be found in Editor -> SwiftLint.

## Author

Norio Nomura

## License

SwiftLint for Xcode is available under the MIT license. See the [LICENSE](LICENSE) file for more info.
