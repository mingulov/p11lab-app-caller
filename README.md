# p11lab-app-caller (test caller repo, M09 pilots)

Setup-only scaffold for M09 pilot (b) preparation. NOT an official caller;
SHAs from this repo never become upstream authority.

- `.github/workflows/app-pilot.yml`: byte-exact copy of the P11Lab caller
  template (`examples/application-ci/action.yml` at control `10017b1`).
  Placeholders `REQUIRED_PUBLISHED_ACTION_COMMIT` and
  `REQUIRED_ELIGIBLE_HANDOFF_MANIFEST_SHA256` are intact: no runs are
  possible until publication (ASK-9, deferred) lands reviewed pins.
- `ci-application/run-tests`: PLACEHOLDER fixture, not a reviewed control.
  Reviewed case variants arrive with the execution brief.

Trigger: `workflow_dispatch` only. No runs have been dispatched from setup.
