# Free code signing: preparation only

## Status
**Not yet applied. Not yet approved. This repository does not contain signed new installers.**

SignPath Foundation may offer code signing free to eligible, genuinely open-source Windows projects. Acceptance and every release signing remain subject to review and approval.

Official eligibility criteria: https://signpath.org/terms.html
Service information: https://signpath.org/

## Before application
- Publish the *complete distributable desktop application's source code and deterministic build scripts* in a dedicated **public** repository under an OSI-approved license, with appropriate third-party licensing.
- Security review: confirm Supabase Row Level Security restricts reads/writes by authenticated user, review the public client key and API design, remove hardcoded sensitive or internal values, and test using a non-production account.
- Document privacy, installer side effects, network endpoints, opt-in Windows startup, release process, uninstall behavior, and maintainers/reviewers/approvers.
- Publish and test at least one transparent, downloadable unsigned build with matching public source.
- Require two-factor authentication, protected release branch, documented code signing policy, and reproducible trusted GitHub Actions builds.
- Request SignPath Foundation evaluation via its official application process. The publisher on any resulting certificate would be SignPath Foundation, not the app author.
- After acceptance, build and sign the companion executable, installer, and **uninstaller**, timestamp and verify signatures, and test install/uninstall on a clean Windows machine with security protections enabled.

## Distribution security
This release repo contains **download artifacts**, not a public copy of the current private production client source. It is not sufficient by itself to satisfy public-source requirements. Do not publish production source or credentials without the security and license audit.

Never disable or bypass Smart App Control to install/uninstall.
