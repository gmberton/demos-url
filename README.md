# Demos

- [AstroLoc](https://gmberton.github.io/demos-url/astroloc/)
- [MegaLoc](https://gmberton.github.io/demos-url/megaloc/)
- [FoundYou](https://gmberton.github.io/demos-url/foundyou/)

Healthcheck: `.github/workflows/healthcheck.yml` probes the three links every 30 min; a link dead for >90 min fails the run and GitHub emails the workflow creator (re-alerts every 6h while down). Test it: Actions → demos healthcheck → Run workflow → test_alert.
