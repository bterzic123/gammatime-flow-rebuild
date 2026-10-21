# Growth Audit — GammaTime

**Live:** https://bterzic123.github.io/gammatime-flow-rebuild/

Five ideas to unlock more revenue from the traffic GammaTime already has, plus a clickable prototype of the first-open flow and the paywall rebuilt in GammaTime's own design. Prepared by Adapty, October 2026.

## The five ideas

| # | Idea | Screen | Potential outcome |
| :-- | :-- | :-- | :-- |
| 01 | Catch the close with your $5 coin pack | Offer on close | ARPU +10–15% |
| 02 | Put the show they are watching on the paywall | Paywall | CR +15–20% |
| 03 | Put your 4.9 and "Never AI-generated" above the plans | Paywall | CR +10–15% |
| 04 | Open on the genre they pick | Genre, Suggested for you | CR +10–15% |
| 05 | Ask for tracking after the first episode | Tracking prompt | CR +10–15% |

## Grounding

Every price, rating, quote, poster and screen element comes from GammaTime's own published material: the App Store listing and screenshots, the web player and paywall at gammatime.live, and the iOS app itself. The app blocks screen recording, so in-app screens are rebuilt from the App Store screenshots and the paywall from the one on gammatime.live.

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps — not measured lift for GammaTime.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Add `?open=proto` to land on the prototype.
