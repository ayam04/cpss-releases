# CPSS releases

This repository only hosts the Windows installers for CPSS Stage 1 and CPSS Stage 2, published by
oorik Technologies. It contains no source code and no settings.

- Each release has `CPSS-Stage1-Setup.exe`, `CPSS-Stage2-Setup.exe` and `latest.json` (version,
  download addresses, SHA-256 and size of each installer).
- Installed copies read
  `https://github.com/ayam04/cpss-releases/releases/latest/download/latest.json` when they start
  and offer the new version.
- Releases are built by `.github/workflows/build.yml` whenever `source.json` changes. The private
  source repository writes that file after every push to its `main` branch.

Install by downloading the setup from the newest release and double-clicking it. No administrator
rights are needed.
