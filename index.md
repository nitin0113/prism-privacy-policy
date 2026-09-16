# Prism privacy policy

Effective 2026-09-16 · applies to Prism for Android, version 0.1.0 and later
Published by Nitin · contact: nitin.ydv011@gmail.com

Prism has no accounts, no ads, no analytics and no servers of its own. We, the
developer, do not receive any information about you or how you use the app. This page
explains what stays on your device and which outside servers the app contacts.

## What stays on your device

Prism stores the following in its private app storage. It is never sent to us or
anyone else.

- **Reading history:** which articles you opened, from which outlet, that outlet's
  rating at the time, when, and for how long. This powers the reading-balance charts
  and blindspots.
- **Interests:** topics and outlets you follow or mute, and interest levels learned from
  what you read, used to rank your feed.
- **Downloaded news:** headlines, short summaries, links and image addresses from
  publishers' public feeds, plus the stories Prism groups them into. Articles older
  than about seven days are deleted automatically.
- **Settings:** whether topic alerts are on, and which stories have already been
  considered for an alert; whether screenshots are blocked everywhere and whether
  alert text is kept vague (see "Notifications and the home-screen widget" below).
- **Optional grouping model:** if you download it, the model file (about 184 MB) and
  the numeric representations it computes for each article.
- **Image cache:** copies of article images, kept in the app's cache.

Prism's database, settings and model are excluded from Android cloud backup and from
device-to-device transfer, so this data does not leave your device that way either.

You can clear your reading history and learned interests in Settings or on the
Balance screen. You can remove the grouping model in Settings. Uninstalling Prism, or
clearing its storage in Android settings, deletes everything above.

## Servers Prism contacts

Every connection uses HTTPS. None of these requests contain your reading history,
interests or any identifier created by Prism.

- **News publishers and fact-checkers.** Prism downloads the public RSS or Atom feeds
  of the outlets listed in the app, in the app and periodically in the background.
  Like any web request, this reveals your IP address and a generic app identifier
  ("PrismReader") to each publisher's servers.
- **Image hosts.** Article images are loaded from the addresses given in those feeds,
  usually the publisher's own servers or content delivery networks, which likewise see
  your IP address.
- **Opening an article.** When you tap an article, it opens on the publisher's website
  in your browser (as a Chrome Custom Tab or your default browser). From then on you
  are on the publisher's site, and its own privacy policy, cookies and advertising
  apply. Prism does not see what you do there.
- **Google, only if you choose the optional model.** If you tap "Agree and download"
  for the grouping model, Prism downloads it from Google's storage servers
  (storage.googleapis.com), over Wi-Fi only. Google sees your IP address as part of
  that download. Google's own privacy policy applies to that request. After the
  download, articles are analysed on your device; no article text is uploaded.
- **Links you tap.** The Methodology screen and the model's licence links open web
  pages in your browser, which contact those sites.

The library that runs the grouping model (Google's MediaPipe) normally sends usage
statistics to Google: the app's name and version, which task ran, and timing. Prism
disables this. Its upload component is removed from the app, so the statistics are
discarded on the device before they are stored or sent.

## Notifications and the home-screen widget

These reach outside Prism's own app storage, so they deserve a specific note even
though nothing here leaves your device to us or to anyone over the network.

- **Notification content is readable by apps you've granted notification access.**
  Android lets you grant an app permission to read your notifications (for a smartwatch
  companion, for example). If you have granted that to any app, it can read a topic
  alert's headline and topic name — this is an Android capability Prism cannot block,
  not a network transmission. In Settings, "Keep alert text vague" makes alerts say
  only that new stories arrived, with no headline or topic name, while tapping one
  still opens the story.
- **The home-screen widget is rendered by your launcher app**, which is how Android
  widgets work: your launcher, not Prism, draws the top stories and their coverage
  split onto your home screen. Anyone who can see your home screen can see it, the same
  as any other widget's content.
- **Screenshots and screen recording.** Balance and Interests — the screens that
  describe your reading politics — always block screenshots, screen recording and
  their Recents-list thumbnail. "Block screenshots everywhere" in Settings extends
  that to every screen.

## Permissions

- **Internet and network state:** to download feeds, images and the optional model, and
  to wait for Wi-Fi before the model download.
- **Notifications (Android 13 and later):** requested only if you turn on alerts for
  followed topics. Alerts are worked out on your device; there is no push service.

Prism does not request location, contacts, camera, microphone, storage or account
access.

## Children

Prism is a general news app and is not directed at children under 13.

## Changes

If this policy changes, the new version will be published at this address with a new
effective date. A change that would send any of your data off your device would be
stated in the app before it happens.

## Contact

Questions about this policy: nitin.ydv011@gmail.com
