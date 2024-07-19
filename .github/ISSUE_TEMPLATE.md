---
title: Release ${{ github.run_number }}
---

Date: {{ github.event.created_at}}
Author: {{ tools.context.actor }}
Version: ${{ github.run_number }}
Commits: ${{ env.COMMITS }}
Docker Image: cr.yandex/${{ vars.CR_ID }}/app:${{ env.RELEASE_VERSION }}"
