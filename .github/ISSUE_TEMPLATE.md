---
title: Release ${{ github.run_number }}
---

Date: ${{ date }}
Author: {{ env.ISSUE_AUTHOR }}
Version: {{ env.RELEASE_VERSION }}
Commits: {{ env.COMMITS }}
Docker Image: cr.yandex/${{ vars.CR_ID }}/app:${{ env.RELEASE_VERSION }}"
