An attempt to compile the \*.emu emulators as a flatpak (targeting the Steam Deck).

I got NES.emu built and packaged, but for whatever reason (gamescope-related?) even basic NES games stutter just enough to be unplayable.

Tried playing with framerates, audio latencies, etc to no avail.

Seems to work ok in desktop mode with native X11 KDE, although it can't see the controllers in desktop mode. Possibly XWayland funkiness?

Could be the controllers somehow causing the lag I suppose (as I recall touch control haptics blocking the main thread on Android somehow).

Either way, not really usable on the Deck currently.
