# Changelog

All notable user-facing changes to **Fichess - Online Chess** are documented here, newest first.

> Since version 2.2.0 the app is called **Fichess** (previously "FICS Chess"). It's the same app —
> just a new name and icon.

## 2.2.1

### Changed
- Interface wording updated after the rename: the app now calls itself Fichess
  consistently, on every screen.

## 2.2.0

### Changed
- The app is now called **Fichess** (previously "FICS Chess").
- On iOS, the "Buy Me a Coffee" donation card is now hidden, per Apple's App Store rules. It's
  still available on Android.

## 2.1.4

### Fixed
- Games that were aborted or adjourned before a real result (for example when an opponent never
  replies) no longer show up in your local game history.

## 2.1.3

### Added
- The challenge screen has been redesigned to match the "Create game" screen: choose time and
  increment, rated or unrated, your color (random/white/black), and the game variant, with a
  live summary before you send the challenge.

## 2.1.2

### Fixed
- Made the account-deletion request more reliable: it is now relayed through a
  dedicated server before reaching the FICS administrators.

## 2.1.1

### Added
- Deleting your account no longer requires you to write anything: the app sends the
  deletion request to the FICS administrators for you, in the background. Your saved
  credentials and local game history are erased from the device at the same time.
  (The FICS administrators are the ones who actually remove the account.)

## 2.1.0

### Added
- **Takeback**: you can now request a takeback of 1 or 2 moves during a game, right from the
  in-game menu.
- **Online players list**: bots are now hidden by default, with a toggle to show them (tagged
  as BOT when shown).
- **Watching games**: added filters for game type (all/blitz/bullet/standard), a rated-only
  toggle, and a hide-bots toggle (on by default) when browsing games to observe.

### Changed
- The unread-message badge on in-game chat is now bolder and easier to notice.

---

Earlier versions are not listed here. See the in-app "Info & Support" screen for the current
app version.
