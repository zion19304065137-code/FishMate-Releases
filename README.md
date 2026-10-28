# FishMate Windows releases

Official public distribution repository for FishMate. Development is maintained separately.

Download the latest Windows package from [Releases](https://github.com/zion19304065137-code/FishMate-Releases/releases/latest).
Extract the entire FishMate folder and run FishMate.exe. Version 0.6.0 and newer can check, download and install signed updates inside the application without a GitHub account.

Every release includes the matching complete source archive, Windows package, SHA256SUMS.txt, update-manifest.json and its Ed25519 signature. FishMate is distributed under AGPL-3.0 with retained third-party notices in the source and binary distributions. Source archives are provided beside the binaries for each version.

The updater verifies signatures against a pinned public key. An update signature is separate from Windows Authenticode signing; current executables are not Authenticode-signed.

The application must remain running and connected for local automatic tasks. Real Xianyu transaction acceptance tests and platform authorization are separate from packaging and updater validation.
