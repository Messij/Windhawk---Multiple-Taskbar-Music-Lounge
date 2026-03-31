// ==WindhawkModReadme==
/*
This mod is a fork of the original "Taskbar Music Lounge" by Hashah2311
As the github page https://github.com/Hashah2311 and Hashah2311 profile are unfoundable, I decided to fork the original "Taskbar Music Lounge" and create a new mod.
Thanks to the original creator of the mod.

# Taskbar Music Lounge
A media controller that uses Windows 11 native DWM styling for a seamless look.

## 🌟 Multiple Taskbar Music Lounge
- Title and Artist-Album on two lines
- Multiple medias view and control
- Each media session has it's own dedicated art
- Clic an art will play it and pause the others
- Pause current media session when launching a new one
- Middle clic to close media (in the mode, not the app)
Trailer : https://www.youtube.com/watch?v=ujvPYtALrno
Github : https://github.com/Messij/Windhawk---Multiple-Taskbar-Music-Lounge/tree/main

## 🚀 v3 vs v4: Major Architecture Shift
| Feature | v3 (Legacy) | v4 (Current) |
| :--- | :--- | :--- |
| **Performance** | Polling Loop (High CPU wakeups) | **Event-Driven** (0% CPU
when idle) | | **Smoothness** | 1-second delay on moves | **Instant** sync with
Taskbar animations | | **Compatibility** | Chrome/Spotify only | **Universal**
supports all media players | | **Visuals** | Square Art, Fixed Size | **Rounded
Art**, 4K Scalable Icons, Acrylic Blur, Rounded Art | | **Behavior** | Always
visible (Clunky) | **Smart Auto-Hide** Hides on fullscreen (Idle, Games, Taskbar
Hide) |

## ✨ Features
* **Universal Support:** Smart scanning detects active playback from any app,
not just the "focused" one.
* **Album Art:** Displays current track cover art.
* **Fullscreen Mode:** Hides automatically when running full-screen
applications.
* **Native Look:** Uses Windows 11 hardware-accelerated rounding and acrylic
blur.
* **Idle Timeout:** Optional setting to fade out the widget when music is paused
for X seconds.
* **Controls:** Play/Pause, Next, Previous.
* **Volume:** Scroll over widget to adjust volume.


## ⚠️ Requirements
* **Disable Widgets:** Taskbar Settings -> Widgets -> Off.
* **Windows 11:** Required for rounded corners.
*/
// ==/WindhawkModReadme==


Todo:
- Define a main media that will resume when current media ends (right clic)
- Control session volune with mouse wheele (like: Taskbar Volume Control Per-App)
- Add a volume slider
- Add a progerssion slider with timers
- Video in the media Art
- Assess to current media window (Clic on Text or double clic art)
- 16/9 art
- Anchor right/left with widget width detection
