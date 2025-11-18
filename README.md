# The list of US services, software, and goods I use (+ their non-US alternatives)

This list is created to keep track of the US dependencies I use. 

### GitHub 

- Well, there's no escape from GitHub. This I have to accept.

### MacBook

- Good Alternatives: Lenovo ThinkPad + Linux
  - is Linux Mint still good for me as it was in good old days?
  - or maybe Linux from DHH? https://www.youtube.com/watch?v=DC2p3kFjcK0

### iPhone

- Good Alternatives: Yes. This actually needs to be done soon. No reasons to stay here.

### DigitalOcean

- ✅ Migrated to Lithuanian 🇱🇹🇪🇺 Hostinger

### Cloudflare

- Good alternatives: TODO the research

### Stripe

- Good alternatives: TODO the research

### Gmail

- Solid alternative: ProtonMail 🇨🇭

### Google Analytics

- ✅ Migrated to self hosted Umami: https://github.com/umami-software/umami

### Google Photos

- Good Alternatives: self-hosted https://github.com/immich-app/immich/ 👍

### Laravel Herd

- ✅ Migrated to ddev: https://github.com/ddev/ddev

### Google Fonts

Just don't. Absolutely no reasons [to make your software illegal](https://thehackernews.com/2022/01/german-court-rules-websites-embedding.html). Spend 10 minutes to install npm deps instead.

```diff
- @import url('https://fonts.googleapis.com/css?family=Montserrat');
- @import url('https://fonts.googleapis.com/css?family=Source+Code+Pro'); // Source Code Pro font
+ @import '@fontsource/montserrat/latin-400.css';
+ @import '@fontsource/source-code-pro/latin-400.css';
```
