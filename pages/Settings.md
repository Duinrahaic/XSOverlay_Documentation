# Settings
!>_Settings are saved as a json file located at `C:\Users\[YOURUSERNAMEHERE]\AppData\LocalLow\Xiexe\XSOverlay\config\overlaySettings.json`_
***

# Windows
>### Window Capture API
_Allows you to select between two capture methods for Window Captures, BitBlt, and Windows Graphics Capture. <br><br>Windows Graphics Capture is faster, and less resource intensive, but will put a yellow border around any winodw that is captured by it. This will not be visible in the capture, but will be visible if the captured window is also being displayed on a Desktop Capture. <br><br>BitBlt will not put a yellow border around the captured window, but is significantly slower and more resource intensive to use. <br><br>Desktop captures will always use Windows Graphics Capture if available, and will fall back to BitBlt when not. (Windows 10 builds prior to 1903)_

>### Curved Overlays
_Allows overlays to be curved. Due to SteamVR / OpenVR implementation limitations, overlays will only be curved when within a threshold in front of you, similar to Oculus Dash. Curvature will not work on overlays that are attached to devices. Curvature will not work if "Aim Movement" is turned off._

>### Auto-Recenter
_Re-centers windows to be in the same relative position and rotation automatically when opening [Layout Mode](GettingStarted#Layout-Mode). I.E. Window is in front of you. You turn around 180 degrees. You open [Layout Mode](GettingStarted#Layout-Mode). Auto-Recenter will move the window to be back in front of you. Hitting the Recenter button on the toolbar will do the same thing, but manually._

>### Invert Scale Direction
_Inverts the forward/back direction to move your hand to scale a window up or down._

>### Default Opacity
_The default opacity for freshly created overlays._

>### Curve Strength
_How strong the curve is on overlays when in the curve zone. Curvature is determined by distance from the head multiplied by the curve strength._

>### Clip Angle
_Adjusts the angle in which overlays will hide when it has the "Auto-Hide" modifier turned on._

>### Aim Movement
_Makes overlays aim at the `Window Aim Target` when held._

>### Window Aim Target
_Controls which object overlays point towards when Aim Movement is turned on._

>### Grab Sensitivity
_How hard you need to squeeze the grip in order to grab an overlay. Does not affect Vive due to being non-analog input._

>### Push/Pull Speed
_Controls the speed that you can push or pull overlays when holding them and pushing the joystick._

>### Scale Sensitivity
_Controls how sensitive the scaling input is. Lower = More movement to scale overlays up or down, but will be less accurate due to tracking inconsistencies._

>### Position Dampening
_Controls smoothing of overlay position while held. Lower = More smoothing._

>### Rotation Dampening
_Controls smoothing of overlay rotation while held. Lower = More smoothing._

>### Smart Roll Angle
_Controls the angle in which overlays will "Smart Roll". "Smart Roll" will rotate the overlays on their side. This is good for if your head is sideways, and you want all of your overlays to also be sideways. Set to 180 to disable._

>### Show Window Previews
_For streamers. Allows you to disable window capture previews in the window selection list on overlays._

***

# General
>### Dominant Hand
_Sets the dominant hand. Currently this only changes which hand the wrist overlay is on. Left will put the wrist overlay on the right hand, and vice versa. This requires a restart to change properly._

>### Automatic Mouse Control
_Allows the overlay to take control of the mouse cursor instantly when pointing at a desktop or window capture. Turning this off will mean you have to click first in order to gain control of the mouse._

>### Mouse Click Delay Time
_Freezes the mouse cursor position at the location for the duration of the Delay Time. This makes double clicking easier._

>### Discord Rich Presence
_Discord Rich Presence support. Turning this on will show XSOverlay as the played game, with a description of the game you're running it beside._

>### Haptic Feedback Strength
_Controls the global haptic feedback strength for things like hovering over buttons._

>### Toolbar Location
_Changes the location of the [Layout Mode](GettingStarted#Layout-Mode) toolbar._

***

# Wrist
>### Enable
_Enables or disables the Wrist Overlay._

>### Minimal Display
_Changes the display mode of the wrist overlay to be more minimal. Note: Features may be missing from this, as it's meant to be minimal._

>### Allow Movement
_Allows you to move the wrist overlay while it's attached to your hand._

>### Opacity
_Changes the wrist overlays opacity._

>### Clip Angle
_Changes the angle in which the wrist overlay will hide itself. Lower will mean you'll have to be closer to looking directly at it to see it._

>### 24 Hour Clock
_Changes the clock from 12 hour format to 24 hour format. I.E. 1:00PM would become 13:00_

>### Date Format
_Changes the date format_

***

# Theme
>### Dark Theme
_Enables or disables dark theme._

>### Accent Color
_Changes the accent color throughout the UI. (Button hovering, notification timer, slider colors, etc)_

***

# Notifications
!> _Notifications will **never** be visible unless an external application sends them to you, or unless you get an achievment. Please refer to the [Notifications API](NotificationsAPI) to understand more about Notifications!_

>### Scale
>Changes the overall scale of the notification popup.

>### Offsets
>Changes the offset of the notifcation popup from your head.

>### Test Notification
>Creates a test notification that lasts for 10 seconds on screen to allow for easy adjustments of the above options.

***

# Language
!>_Allows you to select the language from the list of included language files. Language files can be added in `[XSOverlayInstallationDirectory]/XSOverlay_Data/StreamingAssets/localization/`_

***

# Experimental
!>_Holds options that may be removed in the future due to SteamVR, or that may be unstable. Use at your own risk._

>### Input Blocking
_Allows XSOverlay to take control over input, and stop it from going to the background application. This will only occur if [Layout Mode](GettingStarted#Layout-Mode) is open. You will regain control over the scene application upon closing [Layout Mode](GettingStarted#Layout-Mode)._

>### Force High Quality Overlays
_Tricks SteamVR's GPU Detection in order to force a higher compositor render resolution. This will make overlays higher resolution, but will increase GPU usage on weaker GPUs. You will need to restart SteamVR in order for this to take effect once it's been turned on._

***

# Easter Eggs
!>_Holds Easter egg toggles, if they've been unlocked._

***

# Support
!>_Has links to places to get support, such as the Github issue tracker, Discord, Twitter, or SteamVR forums. These will open a link in your web browser when clicked._

***

# Debug
!>_Has debug things. Mostly UI stuff. Also where you can go to reset settings, or reset the tutorial._

***

# Bindings
!>_Opens the SteamVR bindings panel for XSOverlay. (Assuming Valve hasn't broken it again on any given day.)_
