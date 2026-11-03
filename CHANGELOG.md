# Changelog

## 2.0.1 — UI improvements (released 2026-10-30)

### Improved

- Refined the Windows application frontend across login, employee self-service, signature generation and administration.
- Introduced a shared editorial design: ink masthead, warm paper surfaces, serif headings, restrained vermilion actions and open sections separated by fine rules.
- Updated both light and dark modes, including readable native controls and a paper login form against ink surroundings.
- Clarified workflow hierarchy, template/group configuration, variable mapping, loading/empty states, validation, errors and generation results.
- Improved responsive navigation, keyboard focus, skip navigation, live status announcements and reduced-motion behavior.

### Fixed

- Prevented mobile save controls from covering or extending beyond configuration fields.
- Preserved hidden-state behavior for conditional controls such as configuration activation.
- Corrected initial signature headings to identify their configured template.
- Removed legacy blue-theme overrides and low-contrast selected-signature labels in dark mode.

### Compatibility and verification

- No authentication, permission, API or directory-contract changes. Existing signature templates and generated formatting are retained; previews remain isolated from application styling.
- No production dependency additions. The independent experimental Linux edition is unchanged.
- Local Node tests and Chromium frontend workflows pass. Browser coverage uses explicitly fictional, loopback-only API fixtures, including both themes, mobile layouts, expanded editors and generated-result states.
- Stable Windows release v2.0.1 was published on 2026-10-30 from commit `8392bcfba8f30cd524b3a900e5937231ab8c1b45`. Check the [published release](https://github.com/ffworker/signaturee-win/releases/tag/v2.0.1), its packaged checksum and [release procedure](docs/windows-release.md). Every new installation still requires local Windows/AD/SMB/Classic Outlook acceptance.

## 2.0.0

Previous published Windows baseline. Existing tags and release assets remain unchanged.
