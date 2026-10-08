# MagicLink CI

Separate public CI evidence for exact commits from
[`IamAngusU/MagicLink`](https://github.com/IamAngusU/MagicLink).

<p align="center"><a href="https://github.com/angusu-de/MagicLink-CI/actions/workflows/ci.yml"><img src="https://raw.githubusercontent.com/angusu-de/MagicLink-CI/ci-proof/proof/ci-proof.svg" alt="MagicLink public CI proof"></a></p>

The workflow receives one exact public commit SHA and checks it out without a
deploy key or repository secret. It runs PHP 8.2–8.4 with SQLite, real MySQL
8.4, a sensitive-file package-boundary build and a workflow-security audit.

This repository does not duplicate MagicLink source, a release ZIP or another
source-bearing artifact. The orphan `ci-proof` branch contains only the SVG and
machine-readable evidence for the latest completed run. Both accounts have the
same maintainer; this is CI evidence, not an independent audit.
