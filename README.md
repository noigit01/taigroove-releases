# TaiGroove: release builds

**Find your flow.** A movement game for the Solana Seeker, built for the Solana Mobile **CLOCK IN** hackathon.
This repository only hosts the downloadable builds and the pitch deck. The source code is in a private repository that is
shared with the hackathon judges through Radiants Align.

## Download

- **Android APK (0.8.0, signed release):** see the *Releases* page of this repository, file `taigroove-0.8.0-release.apk`
  (about 31.3 MB).
- **SHA-256:** `93fb78365dcaeb93d8d06973a6f7dad04017ad75903103d4b6b84fb874f6c408`
- **Pitch deck:** `TaiGroove-pitch-deck.pdf` in this repository.

Install on a Seeker or any Android 10+ phone with a Mobile Wallet Adapter wallet (Seed Vault Wallet on the Seeker):
open the APK from the phone's Downloads, or run `adb install -r taigroove-0.8.0-release.apk`.

## What to try

1. **Train**: pick a minute and move smoothly and variedly. Training needs no wallet.
2. **Wallet**: connect your wallet, then **Records > Ranking > Synchronize** to publish a ranked result.
3. **Compete > Live duel (devnet)**: tap *Get free test tokens*, then *Find a rival*. Duels run on Solana devnet with a test token.
   A scripted *Duel simulation* needs no wallet.

Devnet duel program: `G22C5DtqXzD1GfzaMT2uJBrDiQFfqpo6D8j46sVq4Jao`. Backend: https://taigroove.onrender.com
(the free server may need a few seconds to wake up).

Nothing in the app moves real funds. The only mainnet transaction is the optional on-chain Memo proof of a ranked result.
