# Batonly releases

This repository holds signed Batonly desktop releases. Installed Batonly apps check here for updates. The source code lives elsewhere.

Every file is signed with the Batonly release key (minisign key ID `D18D30DE150034F6`). Each release includes `minisign.pub`. To verify a download:

```sh
minisign -Vm SHA256SUMS -p minisign.pub
sha256sum -c --ignore-missing SHA256SUMS
```

Releases are published here automatically. Please don't open issues or pull requests in this repository.
