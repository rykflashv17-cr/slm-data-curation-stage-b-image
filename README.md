# EgoStandard Stage B container image

This private repository holds release archives of the Stage B operator image.
The image includes a snapshot of the private `StridingAI/SLM_data_curation`
repository, so its archive is distributed here as a private Release asset.

## 2026-10-20 image

- Tag inside the archive: `localhost/egostandard-stage-b-operators:20261020`
- Platform: Linux/amd64; CPU; Python 3.12; FFmpeg with libx264
- Upstream revision: `0e694dbc9706b2a5bac8e550f8cd9de18f5b7473`
- Operator code revision: `d93510f`
- Container definition revision: [`32302b7`](https://github.com/rykflashv17-cr/slm-data-curation-stage-b-operators/commit/32302b7)
- Archive SHA-256: `51d99d80b92986da095bd659b4ce4b76e22c76a0121c6443ad9374ca9635edcb`

Download the `.tar.gz` archive and `.sha256` file from the Release, then run:

```bash
sha256sum -c egostandard-stage-b-operators_20261020_amd64.sha256
docker load -i egostandard-stage-b-operators_20261020_amd64.tar.gz
```

Usage instructions are in the [operator repository](https://github.com/rykflashv17-cr/slm-data-curation-stage-b-operators/blob/main/container/README.md).
