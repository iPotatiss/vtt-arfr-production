# VTT ARFR production deployment

This public repository contains only the compiled static frontend deployed to
GitHub Pages. The application source and its Git history remain in the private
source repository.

- Production URL: <https://ipotatiss.github.io/vtt-arfr-production/>
- Production branch: `main`
- Published files: `site/`
- Deployment workflow: `.github/workflows/deploy-pages.yml`
- Exact private source commit and artifact digest: `PROVENANCE.json`

The workflow checks out the pinned private source commit, installs the locked
dependencies, runs the production gates, rebuilds and scans the assets, proves
they exactly match `site/`, and uploads only the compiled directory to Pages.

No license is granted for the application by this deployment repository.
Third-party licenses and notices are recorded in `THIRD_PARTY_NOTICES.md`.
