<p align="center">
<img height="300" width="300" src="https://raw.githubusercontent.com/lbrndnr/Rooftop Underground-macos/master/Rooftop Underground/Assets.xcassets/AppIcon.appiconset/RooftopUndergroundSpeaker.png" />
</p>

<h1 align="center">Rooftop Underground</h1>
<p align="center">A native SoundCloud app for macOS, written in SwiftUI</p>

---

[![Twitter: @lbrndnr](https://img.shields.io/badge/contact-@lbrndnr-blue.svg?style=flat)](https://twitter.com/lbrndnr)
[![License](http://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://github.com/lbrndnr/Rooftop Underground-macos/blob/master/LICENSE)

## About
Rooftop Underground is a project to build a native SoundCloud client for macOS using SwiftUI. Its overall goal is to make listening to tracks on SoundCloud more enjoyable by providing a light-weight and beautiful interface. As of now, the app is still very much in development, lots of features are still missing and the UI needs a lot of work too. So if you want to learn a little bit of SwiftUI or if you have a suggestion regarding the user experience, feel free to open an issue or a merge request.

Note that Rooftop Underground is not affiliated in any way to SoundCloud. Rooftop Underground uses private APIs which I have not been granted access to, so functionality may break in the future.

## Installation

You can install RooftopUnderground using brew:
```console
$ brew install RooftopUnderground
```
or by downloading the latest version right [here](https://github.com/cadavidf/Rooftop Underground-macos/releases). Note that Rooftop Underground is still in heavy development and on top of that written in SwiftUI, a very young framework. If you encounter a bug or miss a feature, don't hesitate to open a pull request.

## Dependencies

Rooftop Underground uses [StackNavigationView](https://github.com/cadavidf/StackNavigationView) to push views onto the view hierarchy (which is not currently possible with SwiftUI 2) and [SoundCloud](https://github.com/cadavidf/soundcloud) to access SoundCloud's private API.

## Code & Design
Developed and Designed by Felipe Cadavid, Initially Developed by [Laurin Brandner](https://twitter.com/lbrndnr)

## License
Rooftop Underground is licensed under the [MIT License](http://opensource.org/licenses/mit-license.php).
