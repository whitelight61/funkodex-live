Public Live feed mirror for The FunkoDex.

The production app and the iPad app read:

https://raw.githubusercontent.com/whitelight61/funkodex-live/main/live-feed.json

Regenerate with the Funko-Reseller script (no paid APIs required):

    node scripts/refresh-live-feed.mjs --out live-feed.json --max-new-covers 0
