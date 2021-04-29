# Raylib-Swift

Helpers for using the [Raylib](https://github.com/raysan5/raylib) C library in Swift originally created by [apahl](https://github.com/apahl) and updated by [x2](https://github.com/x2).

Before using Raylib-Swift ensure that you have Raylib installed on your system.
Originally it was only created for Linux, but after few tweaks I've made it possible to use it within macOS. This fork also comes with updated Raylib to version 3.7

See the original test game created by [apahl](https://github.com/apahl) -> [Dodge](https://github.com/apahl/dodge) for an example on how to use Raylib from Swift. Further examples in seprate repo.

# macOS Users:
The swift package managers OS target is v11 due to persistent warning errors that Raylib is linked to older version for those using Big Sur.
