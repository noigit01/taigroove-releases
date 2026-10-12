# TaiGroove: release builds

**Find your flow.** A movement game for the Solana Seeker, built for the Solana Mobile **CLOCK IN** hackathon.
This repository only hosts the downloadable builds and the pitch deck. The source code is in a private repository
(`noigit01/TaiGroove`) that is shared with the hackathon judges through Radiants Align.

## Download

- **Android APK (0.8.1, signed release):** [taigroove-0.8.1-release.apk](https://github.com/noigit01/taigroove-releases/releases/download/v0.8.1/taigroove-0.8.1-release.apk)
  (about 31.3 MB).
- **SHA-256:** `24aef419b444bf6e922229efe18d2ccbe259be78bcbe66375202d534a9eb87f6`
- **Pitch deck (PDF):** attached to the releases as `TaiGroove.pitch.deck.pdf`.
- Earlier build: 0.8.0, see the *Releases* page.

Install on a Seeker or any Android 10+ phone with a Mobile Wallet Adapter wallet (Seed Vault Wallet on the Seeker):
open the APK from the phone's Downloads, or run `adb install -r taigroove-0.8.1-release.apk`.

Verify the download:

```bash
shasum -a 256 taigroove-0.8.1-release.apk
```

## What to try

1. **Train, Ranked**: pick a minute and move smoothly and variedly. Only **Ranked** sessions are uploaded to the
   leaderboard; **Training** stays on the phone and needs no wallet.
2. **Wallet**: connect your wallet, then **Records > Ranking > Synchronize** to publish a ranked result.
3. **Compete > Live duel (devnet)**: tap *Get free test tokens*, then *Find a rival* (a second player with the same
   stake is needed). Duels run on Solana devnet with a test token. A scripted *Duel simulation* needs no wallet.

Devnet duel program: `G22C5DtqXzD1GfzaMT2uJBrDiQFfqpo6D8j46sVq4Jao`. Backend: https://taigroove.onrender.com
(the free server may need a few seconds to wake up).

## What changed in 0.8.1

- Training results no longer appear in the ranking (only signed Ranked results waiting for upload do).
- The synchronisation message is accurate: it says when there was nothing to upload, or when a wallet is needed.

Nothing in the app moves real funds. The only mainnet transaction is the optional on-chain Memo proof of a ranked
result.
