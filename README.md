# MPD Handbook (user guide)

Part of **My Property Doctors (MPD)**, a property-management platform for NRIs and owners of property in India.

A public, friendly HTML guide for website users, NRI owners, partners and non-technical stakeholders: what My Property Doctors does, features, what admin / master franchise / franchise / provider / worker / customer can do, how onboarding works, plans, payments and the document vault.

## Stack
Static HTML + CSS + a little JS (no build step)

## Structure
```
index.html                      overview, what you can do, who does what, how a request reaches a worker
pages/getting-started.html      sign up, add a property
pages/document-vault.html       folders, uploads, versions, share links, activity
pages/identity-verification.html  KYC for customers
pages/builders-and-societies.html project owners, units, registering owners
pages/our-team.html             staff console guide (network, areas, prices, reviews)
pages/faq.html                  common questions
assets/style.css                shared styles
assets/screens/                 screenshots, added as features ship
```
Only live features are described. Anything not built is marked "Coming soon". Update it at the end of every milestone step.

## Getting started
```bash
open index.html in a browser
```

## Configuration
None. Hosted at help.<domain> (public).

## Related repos
mpd-backend · mpd-frontend · mpd-mobile · mpd-global · mpd-infra · mpd-handbook-developer · mpd-handbook

## Status
Scaffold created 20-Nov-2026. Roadmap: First version at M4 (onboarding live), then updated every milestone.
