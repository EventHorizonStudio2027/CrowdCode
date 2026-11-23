# Active issues — focused functional MVP

Completed implementation is recorded in Git history and the completed-work section below. Outstanding priorities restart at #1; permanent GitHub issue IDs are unchanged.

1. **Execute and fix browser regression suite** — new Chromium/WebKit GitHub Actions tests must be observed running and failures repaired; not yet verified green.
2. **Expand save/recovery coverage** — corrupt storage, quota failure, import/export round trips and editor draft restoration.
3. **Verify interactive sandbox behavior** — app/game preview controls, input and error reporting on real browsers.
4. **Implement real shared collaboration** — Showrunner authorization, contributor identity and synchronized proposals need a backend.
5. **AI provider and deployment readiness** — server-side model integration, secrets, hosted API and verified published Pages.

## Completed this iteration — 2026-11-23
- Added Playwright core workflow tests covering source editing, interactive preview, autosave, reload, named project library, restore, export and starter reset.
- Added GitHub Actions matrix for Chromium and WebKit on push and pull request.
- Fixed tracked reset save, project timestamp validation and restore confirmation in preceding commits.
- CI test execution is **not yet verified**; adding tests does not prove they pass.
- Separate final UI polish is committed after this document.

