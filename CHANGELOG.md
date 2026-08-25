# Changelog

## CartDump v0.1.5

### Changes
- Complete Mod Revamp, old system got reworked
- Added a Quick Deposit action for the cart, usable only while the cart is in Strong mode (not while Weak/Dragged).
- Cart briefly disappears when used, letting all items inside fall to the ground, then reappears near the triggering player after a short delay.
- Added an interact prompt above the cart that shows only when Quick Deposit is available, and hides itself automatically a few seconds after appearing.
- Fully multiplayer-synced: the action plays out identically for every player in the lobby.
- Added a debug logging option (toggleable in the BepInEx Config Manager) to help trace what's happening during testing.

### Bug Fixes
- Fixed a crash when using Quick Deposit caused by a Unity API not available in this game's Unity version (`Rigidbody.linearVelocity`).
- Fixed the cart respawning on top of / inside the player instead of a short distance in front of them, by using look direction instead of body direction and snapping to the ground.

## CartDump v0.1.4

### Changes
- Renamed some enemy names.

### Bug Fixes
- Fixed an issue where the cart was not equippable even though it was in the ExtractionPoint.

---

## CartDump v0.1.3

### Changes
- Changed force unequip time to 5 seconds (previously 10 seconds).
- Added a check so the cart can only be equipped when in extraction.

### Bug Fixes
- Minor fixes and adjustments.

---

## CartDump v0.1.2

### Changes
- Added force unequip after 10 seconds when the cart is equipped.

---

## CartDump v0.1.1

### Changes
- Renamed some enemy names (just for fun).

---

## CartDump v0.1.0

### Changes
- Initial release.