# KEEZI App Downloads

Official Windows and macOS installers for KEEZI, the free piano learning and music visualization app from KEEZI LLC.

Installers will be available in this repository's Releases when the first public release is published. No installer has been published yet.

- Website: https://keezishop.com
- App privacy policy: https://keezishop.com/pages/keezi-app-privacy
- Support: support@keezishop.com

This repository hosts installer downloads and release notes. Application source code is maintained separately in a private repository.

## Publishing releases

1. Build and test the Windows and macOS installers from the intended source revision.
2. Create a draft release with the app version as its tag, for example v1.0.0.
3. Attach the tested installers as release assets using these exact names:
   - KEEZI-Windows-Setup.exe
   - KEEZI-Mac.dmg
4. Attach SHA256SUMS.txt with the SHA-256 checksums of both files. Include supported operating systems, build numbers, changes, and known limitations in the release notes.
5. Publish the release and mark it as the latest release only after both installers are attached. Check both direct downloads without signing in.
6. Preserve each released version. Publish a new version for changed installers instead of replacing a previously released file.

Store installers as release assets, not files committed to this repository. Keep source archives, signing keys, credentials, and internal build logs in private storage.

## Website download buttons

These URLs become available after the first public, non-prerelease release containing the named assets is published:

Windows:

https://github.com/KEEZI-LLC/KEEZI-App-Downloads/releases/latest/download/KEEZI-Windows-Setup.exe

macOS:

https://github.com/KEEZI-LLC/KEEZI-App-Downloads/releases/latest/download/KEEZI-Mac.dmg

Use these URLs as the destinations of the download buttons on keezishop.com. They download the installers directly without requiring a GitHub account or a visit to a GitHub release page. Keep both filenames consistent in every latest release so the website buttons continue to work.
