# Juris Protocol documentation hosting

Published website: https://jurisprotocol.github.io/

This repository contains only generated static website files. The authoritative source is the `main` branch of the private `JurisProtocol/public-docs` repository.

Current source commit: `c44052378ca364bf9a300ffa2cfe5a7a9cda9c71`.

## Publication

Build and validate the approved `main` revision in the source repository with `npm run validate`, then run its browser smoke checks against the production preview. Copy only the resulting `dist/` contents here, preserving `.nojekyll` and this provenance record. Commit and push the generated files to this repository's `main` branch. GitHub Pages publishes that branch from its root.

Source changes are not deployed automatically. Never copy source history, engineering notes, local runtimes, credentials, or workspace records into this public repository.

The website currently retains `noindex, nofollow`. This is public hosting, not access-controlled hosting. No custom domain is configured.
