<img width="60" height="52" alt="image" src="https://github.com/user-attachments/assets/2c9c6c1f-16c9-4b18-93dc-7e2365d8e920" /> 

# Transform Fold: live fold/unfold transition effects for Android foldables
A new way to transform how fold and unfold transitions on an android foldable phone. The app offers:
1. A variety of fold/unfold transition effects for a foldable phone.
2. The effect is rendered independently of the launcher and sits over whatever is currently being displayed, so you can use it with any launcher/app.
3. It renders everything live, and it does not take screenshots of your screen to create the animation.

So it's up to the user if they want to match their inner and outer screen layouts, the app will simply render the background.
The app doesn't request standard Android runtime permissions. It requires Shizuku to be installed, running, and authorised.

<img width="150" height="600" alt="image" src="https://github.com/user-attachments/assets/92850ce4-96ea-47a9-a9bb-60c7db0379f9" />
<img width="150" height="600" alt="image" src="https://github.com/user-attachments/assets/c2ab1f12-7aff-439e-bf88-0164285c220c" />

Here are the list of effects the app currently offers:

**Effects:**
1. Glass - Closest to iPhone Duo effect
2. Frosted Crystal - Crystal frost pattern
3. Liquid Mercury - Metallic fluid effect
4. Parallax Curtain - Curtain effect that stretches
5. Spring Door - Spring loaded door effect
6. Live Blur - Real time blur effect
7. Blur Panel - Blur overlay panel

**Status:** Users can enable/disable the effects. It also shows whether the selected effect is currently running, stopped, or has encountered an error.

**Settings:** 
1. Blur Strength - Controls the blur intensity
2. Outer Rotation - Controls the rotation intensity for outer panel
3. Inner Rotation - Controls the rotation intensity for inner panel
4. Outer Shade - Controls the shade depth and intensity for outer panel
5. Inner Shade - Controls the shade depth and intensity for inner panel

**Theme:** Enable/Disable dark mode for the app

**Requirement:**
1. Android foldable device
2. Shizuku must be installed and running, and the app must be authorised in Shizuku. Follow the steps to set up Shizuku: https://shizuku.rikka.app/guide/setup/

**Known issues:**
1. Orientation lock - Currently the transition is not locked to portrait mode, and it moves to landscape orientation, breaking the effect visually.
2. Complete darkness - Sometimes the complete effect goes black, especially at high rotation percentages. It gets fixed if the phone is completely folded/unfolded again, or by disabling/enabling the effect.
3. There is a slight lag between live contents shown on the left panel and right panel. It's because of real time rendering.
4. Inner and outer screen lighting at the same time - I haven't been able to fully test this because my fold phone turns off the outer display when the inner display is activated.

**Report bugs:** 
In order to report any bugs, repro the issue on your device and then tap on 'Report Bug' under 'Status' card. It will generate a log txt file, which you can upload with the Github issue you create.

**Tested on devices:**
1. Vivo X Fold 3 Pro

Official APKs are published through GitHub Releases. You can use the SHA-256 value to verify that your downloaded APK matches the official release.

**Buy me a coffee:** If you want to support further development, bug fixes and new suggestions on unique effects that I can implement on the app 🙂
: https://buymeacoffee.com/code.robby.code
