# FOUNDRY Updates

This public repository contains signed update manifests, release notes, and
immutable installer artifacts for **FOUNDRY by ACAS Tools**.

Application source code is maintained separately and remains private. Never add
source archives, credentials, signing private keys, customer data, or product
workspaces to this repository.

## Trust model

- `latest.json` is authenticated with Ed25519 before FOUNDRY trusts its fields.
- Every installer is independently verified against its SHA-256 digest.
- Release assets are immutable; a changed build receives a new version.
- The signing private key is not stored in this repository.

Current signing key identifier: `acas-foundry-v1`.
