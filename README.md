# The list of US services and good I use (+ alternatives)

This list is created to keep track of the US dependencies I use. 

Ideally, there should be 0. It does seem really challenging, but not impossible.

### GitHub 

- Good alternatives: none ❌ What could go wrong with US-owned MS-owned SPOF? 🤦

### MacBook

- Good Alternatives: Lenovo ThinkPad + Linux (is Linux Mint still good for me as it was in good old days?)

### iPhone

- Good Alternatives: Yes. This actually needs to be done soon. No reasons to stay here.

### DigitalOcean

- ✅ Migrated to Lithuanian 🇱🇹🇪🇺 Hostinger

### Cloudflare

- Good alternatives: TODO the research

### Stripe

- Good alternatives: TODO the research

### Gmail

- Good alternatives: ProtonMail 🇨🇭

### Google Analytics

> Google Analytics is installed on and is tracking website traffic on 85% of all websites.
> A majority of web traffic is tracked by a single company.
> And that one company is also the largest advertising company in the world.
> What could possibly go wrong?

- ✅ Migrated SweetAlert2 to [Plausible](https://plausible.io/) (Made and hosted in the EU 🇪🇺): https://plausible.io/sweetalert2.github.io
- ✅ Migrated personal projects to [self-hosted Matomo](https://matomo.org/guide/installation-maintenance/matomo-on-premise-self-hosted/)

### Google Photos

- Good Alternatives: self-hosted https://github.com/immich-app/immich/ 👍

### Google Fonts

Just don't. Absolutely no reasons [to make your software illegal](https://thehackernews.com/2022/01/german-court-rules-websites-embedding.html). Spend 10 minutes to install npm deps instead.

```diff
- @import url('https://fonts.googleapis.com/css?family=Montserrat');
- @import url('https://fonts.googleapis.com/css?family=Source+Code+Pro'); // Source Code Pro font
+ @import '@fontsource/montserrat/latin-400.css';
+ @import '@fontsource/source-code-pro/latin-400.css';
```
