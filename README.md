# the-zyrah.com public site

Public pages that Google Play and AdMob need:

- `index.html`: developer website (set it as the website in Play Console).
- `tvremote/privacy.html`: TV Remote privacy policy (Play Console › App content › Privacy policy).
- `app-ads.txt`: must be served at `https://the-zyrah.com/app-ads.txt`. Put the real AdMob publisher ID in it first.

Not yet hosted. `apk.the-zyrah.com` is private (Cloudflare Access), so it can't serve these.
New apps: add a card to `index.html` and a `<app>/privacy.html`.
