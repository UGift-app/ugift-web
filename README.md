# U GIFT web test build

The U GIFT app built for the web, for testing on staging. **Compiled output only.** The source is in the private repo [UGift-app/ugift-application](https://github.com/UGift-app/ugift-application).

- Live at https://ugift-app.github.io/ugift-web/
- Talks to the staging API (`api-staging.ugift.app`). Payments are the mock gateway; no money moves.
- Built from `ugift-application` `ff4e576` with:
  `flutter build web --release --dart-define=API_BASE_URL=https://api-staging.ugift.app/v1 --base-href /ugift-web/`
