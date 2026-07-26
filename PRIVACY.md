# Privacy Policy — Fichess

**Last updated:** 26 July 2026

Fichess ("the App") is a mobile chess client for the Free Internet Chess Server
(FICS, [freechess.org](https://www.freechess.org)). This policy explains, in plain
terms, what the App does with your data.

**In short: the developer does not collect, profile or sell anything about you.
There are no analytics, no trackers and no advertising.**

---

## 1. Data stored on your device

The App keeps the following locally, on your phone only:

- **Your FICS username and password**, if you choose to stay signed in. They are
  stored in the operating system's secure storage — the **iOS Keychain** or the
  Android **EncryptedSharedPreferences** — not in plain text.
- **Your preferences**: board theme, piece set, sound and haptics, language, and
  the settings you last used when creating a game.
- **Your game history**: for each game you finish, the App saves the opponent's
  username and rating, the result, the time control, the moves, and the date. This
  database lives on your device. FICS itself only keeps your most recent games, so
  this is what lets the App show you your full history and rating trend.

None of this is sent to the developer. Uninstalling the App deletes all of it.
You can also erase the history from inside the App at any time.

## 2. Data sent to the FICS server

The App connects directly to **freechess.org on port 5000**, using the standard,
publicly documented ICS protocol — the same one desktop FICS clients have used for
decades.

What travels over that connection is what you would send from any FICS client:
your username and password when you log in, your moves, your chat messages, and
the commands the App issues on your behalf. **This goes to FICS, not to the
developer.**

FICS is operated independently by its own volunteer administrators. Your use of
that service is governed by their rules and practices, which the developer of this
App does not control. See [freechess.org](https://www.freechess.org).

## 3. Account deletion requests

FICS accounts are created and managed on FICS, not in this App, and the FICS
protocol has no self-service delete command. So when you use **Info & Support →
Account → Delete account**, the App does two things:

1. It clears your FICS profile fields on the server and flags the account for
   removal, over your existing FICS connection.
2. It sends a deletion request to the FICS administrators. To do this without
   making you write an email yourself, the App performs a single background request
   to a relay server operated by the developer
   (`api.maraffaonline.it`), which then emails the request to
   `support@freechess.org`.

**That request contains only your FICS username and your platform (iOS or
Android).** The relay server also records the originating IP address in its logs,
as any web server does, for abuse prevention. No other data is transmitted, nothing
is stored in a database, and the information is used solely to forward your
deletion request.

The App then erases your saved credentials and your local game history from the
device. That part is immediate and entirely under the App's control.

Removing the FICS account itself is not: it is decided and carried out by the
FICS administrators, at their discretion and according to their own policies.
They delete accounts only rarely. The App can send the request and erase
everything held on your device, but it cannot promise an outcome on a server it
does not operate.

## 4. Files you choose to share

If you export your game history or a single game, the App creates a JSON or PGN
file and hands it to the system share sheet — you decide where it goes. If you
import a history file, the App reads only the file you pick. The App does not
browse your storage, photos, contacts, camera, microphone or location.

## 5. Donations (Android only)

The Android version contains an optional link to **Buy Me a Coffee**. If you tap
it, you leave the App and their own privacy policy applies. Donations are entirely
voluntary and unlock nothing in the App. This link is **not present in the iOS
version**.

## 6. Children

The App is not directed at children under 13 and the developer does not knowingly
collect any information from them. The App connects to FICS, which sets its own
age requirements, and includes chat with other players that is moderated by FICS,
not by this App.

## 7. Security

Credentials are held in the platform's secure storage. The App transmits nothing to
any server other than FICS, with the single exception described in section 3. There
are no cookies, no advertising identifiers and no third-party analytics SDKs.

Please note that the FICS protocol itself is a plain-text protocol; this is a
property of the FICS service, shared by every FICS client, not a choice made by
this App.

## 8. Changes to this policy

Any change will be published on this page, with the date at the top updated. The
history of changes is visible in this repository.

## 9. Contact

Questions about this policy, or about your data:

**[casali.thomas@gmail.com](mailto:casali.thomas@gmail.com)**

For anything concerning your FICS *account* — ratings, bans, registration —
contact the FICS administrators at [freechess.org](https://www.freechess.org).

---

**Developer:** Thomas Casali
**Fichess is an independent, unofficial client and is not affiliated with or
endorsed by FICS or the operators of freechess.org.**

© 2026 Thomas Casali. All rights reserved.
