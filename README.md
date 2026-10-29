# stack-sentinel-test

Test app for the Stack Sentinel fix pull requests (`SENTINEL_FIX_MODE=pr`).
`ui5.yaml` pins UI5 1.120.51 and `webapp/index.html` loads 1.108.45, so a run of the
`stack-sentinel` workflow should open one pull request that updates UI5.
