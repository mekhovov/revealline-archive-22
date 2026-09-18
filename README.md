# RevealLine archive 22

Preserve the exact original v0.60.9 and v0.61.0 releases for comparison and historical play. Both game links remain available; Release explorer returns to the current main catalog. Every original v0.60.9 game and metadata byte stays unchanged. Only the archive landing page adds the v0.61.0 link.

The expected site contains **1,393 files / 626,457,828 bytes**, leaving **173,542,172 bytes** under the unchanged 800,000,000-byte cap. The source qualification and original manifest, checksum and release record are retained for each edition. These are candidate expectations, not deployment or browser acceptance.

## Verification and deployment

The inherited main-only workflow and bounded tools remain unchanged. Hosted preparation downloads each published original ZIP, checks its annotated tag and metadata, validates all extracted bytes and removes temporary payloads. It never rebuilds a historical game. The pinned extractor remains a13ab970, with the existing 3 GiB runner free-space floor and 20,000-file limit. Local checks use small fixtures only.

Review this append against actual accepted archive commit 625fb9aeeef8915f65c3a14cf5d9525bda911778. Stage only the related metadata, inventory, lock, landing-page and documentation changes, then create and merge the source PR. The single main push performs deployment. Preserve actual commit, workflow, deployment and original receipt identities; do not duplicate a running deployment.

After deployment, audit the complete public inventory, independently reconcile all retained v0.60.9 rows, and exercise both archived game routes and Release explorer return. Update the main archive admission only after these checks pass. The current-main selector and accepted release have their own gates. A successful build alone does not qualify public play, offline use, audio or physical devices.

`input-authority.json` remains the original v0.60.9 preparation record. `append-v0610-authority.json` records this append's exact source metadata and capacity; it does not rewrite that history. The game and archive share the github.io origin, so save isolation or migration is not inferred from different paths. Published source archives, assets, tags and historical game URLs remain immutable.
