# Zapbox / Unity XR Interaction Toolkit Demo
Unity project to demonstrate the [Zapbox XR SDK](https://github.com/zappar-xr/zapbox-xr-sdk) working with Unity's XR Interaction Toolkit.

Build it for iOS on a Mac with Xcode. You'll need to set up the signing configuration to your Apple Developer account in Xcode.

We recommend an iPhone 11 or later with the current version of the provider plug-in. See the readme in the SDK repository for current status and roadmap.

### Tips and tricks for the current version

- We recommend you just wake up one controller first when in the pairing UI so you can tell which is left and right.
- When the controllers are first connected (LED changes from flashing to constant low brightness state) then they should be left stationary on a stable surface for 5-10 seconds for the runtime to calibrate gyro bias.
- Kill the app (by swiping it up from the App Switcher) when you've finished to disconnect the controllers - the LEDs will return to flashing mode for 60 seconds, and then the controllers will enter deep sleep.
