# Changelog

All notable user-facing changes to **Fichess - Online Chess** are documented here, newest first.

> Since version 2.2.0 the app is called **Fichess** (previously "FICS Chess"). It's the same app —
> just a new name and icon.

## 2.4.4

### Changed
- Fichess now requires iOS 15 or later. No device is affected: iOS 15 runs on exactly the same
  iPhones and iPads as iOS 14, back to the iPhone 6s. If you have deliberately stayed on iOS 14,
  the App Store will keep offering you version 2.4.3. Apple stops accepting apps built for iOS 14
  in spring 2027, so this moves ahead of that.

## 2.4.3

### Fixed
- The channel directory was wrong. Nine of its fourteen entries named the wrong topic, and four
  channels listed as Italian, Spanish, German and Youth do not exist on FICS at all — tapping them
  dropped you into an empty, undefined channel. Every number now comes from the server's own
  channel list. The language channels are 72 to 77, the Youth channel is 51, and the Chess channel
  is 55.

### Added
- You can now join any channel by number from the Channels tab, not only the ones in the list.
  A curated list will always be missing somebody's channel — channel 39, Politics, is a busy one
  that was not there. Thanks to the player who reported it.

## 2.4.2

### Fixed
- The clocks no longer start before the game has really begun. FICS holds both clocks until each
  player has made a move — a game only counts from Black's reply — and the app was starting the
  opponent's clock as soon as the first move was played.
- The right clock now runs. When you were playing Black, the app could show White's clock ticking
  on your turn.

## 2.4.1

### Changed
- Fichess now identifies itself to the FICS server by its real name, version and platform
  (for example "Fichess 2.4.1 on iOS"). It had been announcing an old internal name and the
  wrong version number, which made life harder for the FICS administrators when a Fichess user
  asked them for help. Thanks to mattuc, Head Administrator of FICS, for spotting it.

## 2.4.0

### Added
- **Flood protection.** If someone buries you in messages, or in repeated draw and takeback
  requests while your clock is running, Fichess now notices. Their messages are muted for as
  long as the burst lasts, and a strip appears offering to block them or send the incident for
  review. It sits at the bottom of the screen: it will never cover the board or the clocks, and
  it is never a dialog you have to dismiss before you can move.

### Fixed
- A premove can now be cancelled by tapping the board, the way it works in other chess apps.
  Previously the only way was the small ✕ on the banner above the board.
- The board, clocks and move list no longer redraw every time a message arrives. On a busy
  connection this could delay your own move — and with it, cost you time on the clock.
- Draw, takeback and abort requests from your opponent are now recognised properly.

## 2.3.1

### Changed
- "Rate the app" now opens the App Store review page directly.
- The GitHub link now opens the app's public page, with the privacy policy,
  terms of use and support guide.

## 2.3.0

### Added
- **Terms of Use**, shown before your first login. They set out plainly that
  there is no tolerance for objectionable content or abusive behaviour. You can
  re-read them any time from Info & Support.
- **Report a message**: press and hold any message you receive and choose
  *Report message*. Reports are reviewed within 24 hours.
- **Block a player**: press and hold one of their messages and choose *Block
  player*. Their messages disappear from the app immediately, and the block is
  applied on the FICS server too, so they can no longer reach you there either.
  Manage the list from Settings → Blocked players.
- **Automatic filtering** of offensive language. A caught message is hidden
  behind a warning, which you can reveal if you want to.

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
