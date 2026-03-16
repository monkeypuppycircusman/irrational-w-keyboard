Three fixes in this build:
Keyup black key bug — the main one. Black keys (W/E/T/Y/U) now properly release on keyup so notes don't hang.
Touch support — keyboard now fires on mobile with touchstart/touchend/touchcancel, so the whole instrument is playable on phone or tablet.
Header label — removed O and P from the key hints since they weren't actually mapped, so the UI was lying to people.
