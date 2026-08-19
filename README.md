# Demos

- [AstroLoc](https://gmberton.github.io/demos-url/astroloc/)
- [MegaLoc](https://gmberton.github.io/demos-url/megaloc/)
- [FoundYou](https://gmberton.github.io/demos-url/foundyou/)

Healthcheck: `.github/workflows/healthcheck.yml` probes the three links every 30 min; a link dead for >90 min fails the run and GitHub emails the workflow creator — ONE email per outage (silent until a relaunch pushes a new url.txt). Test it: Actions → demos healthcheck → Run workflow → test_alert.
