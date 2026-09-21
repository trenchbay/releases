# TrenchBay releases

Installers for [TrenchBay](https://trenchbay.com), a self-custodial desktop app for launching and
trading pump.fun tokens on Solana. This repository holds the released binaries and nothing else; the
application source is not public.

## Downloads

The current release is on the [releases page](../../releases) and linked from
[trenchbay.com/download](https://trenchbay.com/download/).

## Verify what you downloaded

Each release lists a SHA-256 checksum for every file, and the same value is published on
[trenchbay.com/download](https://trenchbay.com/download/). Check it before you run the installer:

```bash
shasum -a 256 TrenchBay-<version>-arm64.dmg
```

If the two values differ, do not run the file. Downloading from anywhere other than this repository
or trenchbay.com means you are trusting whoever put the copy there.

## Security

TrenchBay is self-custodial: private keys are generated and stored encrypted on your own computer,
and no server holds them. See the [security model](https://trenchbay.com/security/) for what the app
sends and what it never sends.

Trading memecoins is high risk. This software is a tool, not financial advice — see the
[risk disclosure](https://trenchbay.com/risk-disclosure/).
