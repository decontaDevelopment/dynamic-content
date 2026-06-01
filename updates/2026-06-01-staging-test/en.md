---
title: Staging feed test
summary: Temporary update used to verify the staging dynamic-content pipeline.
---

## Staging publish check

This test article confirms that the app can load update content from the public staging branch.

- The source lives in the app repository.
- GitHub Actions publishes it to the public dynamic-content repository.
- Development and preview builds read the staging channel.
