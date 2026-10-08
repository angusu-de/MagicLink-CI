# MagicLink CI

Public, source-free CI evidence for the private
[`IamAngusU/MagicLink`](https://github.com/IamAngusU/MagicLink) repository.

<p align="center"><a href="https://github.com/angusu-de/MagicLink-CI/actions/workflows/ci.yml"><img src="https://raw.githubusercontent.com/angusu-de/MagicLink-CI/ci-proof/proof/ci-proof.svg" alt="MagicLink public CI proof"></a></p>

The workflow receives one exact private commit SHA and checks it out with a
read-only deploy key scoped only to MagicLink. It runs PHP 8.2–8.4 with SQLite,
real MySQL 8.4, a private package-boundary build and a workflow-security audit.

This repository stores no MagicLink source, deploy key, release ZIP or
source-bearing artifact. The orphan `ci-proof` branch contains only the SVG and
machine-readable evidence for the latest completed run. Both accounts have the
same maintainer; this is CI evidence, not an independent audit.

