# Musafirkhana Lab Companion — Official Windows Releases

This **public repository contains Windows Companion release downloads only**.
The application's source code and backend are maintained separately.

## Download the Windows Companion

[Latest published release](https://github.com/Sohan2416/musafirkhana-companion-releases/releases/latest)

Download the Windows **Setup** installer when one is available. Verify its
`*.sha256` checksum before running the installer. Do not disable Windows
security protections to install the application.

## Updating

New versions are announced on the Releases page. Companion versions with the
public update checker can detect new releases and ask permission to open this
page. **Automatic installation is not enabled yet.**

**Release publishing rules**
1. Only publish installers built from the official private project.
2. Test installation, single-instance behavior, and upgrade compatibility.
3. Attach the installer `*.exe` and its matching `*.exe.sha256` file.
4. Prefer a certificate-signed and timestamped installer. Unsigned builds may
   trigger Windows security warnings.
5. Tag each release `vMAJOR.MINOR.PATCH` and keep it aligned with the app version.

## Current release status

The latest public version may be older than the private project's build.
Check the Releases page for the currently available version. Never download
a binary from an unverified third-party source.
