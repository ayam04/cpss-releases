# CPSS releases

This repository only hosts the Windows installer for CPSS (Stage 1, Stage 2 and Admin in one app),
published by oorik Technologies. It contains no source code and no settings.

- Each release has `CPSS-Setup.exe` and `latest.json` (version, download address, SHA-256 and size
  of the installer). From 1.3.0 on, the older separate CPSS Stage 1 and CPSS Stage 2 apps update
  themselves into this one app.
- Installed copies read
  `https://github.com/ayam04/cpss-releases/releases/latest/download/latest.json` when they start
  and offer the new version.
- Releases are built by `.github/workflows/build.yml` whenever `source.json` changes. The private
  source repository writes that file after every push to its `main` branch.

Install by downloading the setup from the newest release and double-clicking it. No administrator
rights are needed.
