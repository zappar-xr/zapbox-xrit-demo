# Zapbox / Unity XR Interaction Toolkit Demo
Unity project to demonstrate the [Zapbox XR SDK](https://github.com/zappar-xr/zapbox-xr-sdk) working with Unity's XR Interaction Toolkit.

## Requirements
* Apple Mac
* [XCode](https://apps.apple.com/us/app/xcode/id497799835?mt=12)
* [Unity](https://unity.com/download) (works with Free personal license and above)
* [Zapbox](https://www.zappar.com/zapbox/)

## Getting started
1. Clone this repo and open the folder in Unity 
2. Go to `File -> Build` settings and select `iOS`
3. Click on `Build and Run`
4. XCode will open but it will fail to build, this is normal
5. In XCode click on the folder tab and select `Unity-iPhone` project
6. Go to `Signing and Capabilities` tab
7. In `Team` select your Apple Developer account and sign in if needed
8. Change the bundle identifier to something unique for example `com.example.zappar-sample-code.zapbox-xrit-demo-[your initials]-[the date and time]`

We recommend an iPhone 11 or later with the current version of the provider plug-in. See the readme in the SDK repository for current status and roadmap.

### Tips and tricks for the current version

- In the Zapbox box you have three square cards with QR codes on them. These are called 'world anchors'. Place the world anchor with 'Zapbox' written on it on a table (the others won't work.)
- We recommend you just wake up one controller first when in the pairing UI so you can tell which is left and right.
- When the controllers are first connected (LED changes from flashing to constant low brightness state) then they should be left stationary on a stable surface for 5-10 seconds for the runtime to calibrate gyro bias.
- Kill the app (by swiping it up from the App Switcher) when you've finished to disconnect the controllers - the LEDs will return to flashing mode for 60 seconds, and then the controllers will enter deep sleep.
