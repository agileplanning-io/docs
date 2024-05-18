---
title: "Under Development"
description: "Usage caveats while this product is under development."
summary: ""
date: 2024-05-18T16:13:18+02:00
lastmod: 2024-05-18T16:13:18+02:00
draft: false
menu:
  docs:
    parent: ""
    identifier: "under-development"
weight: 920
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

Right now, Jira Flow Metrics is on version 0. Until it reaches major version 1, there are some caveats to be aware of.

## Project data may not be backwards compatible

Project data, including synced issues and project settings, are not guaranteed to be backwards compatible between versions. This could result in errors when viewing reports, syncing data, or updating project settings.

If this happens, it takes just a few seconds to resolve:

1. Delete the project.
2. Re-add and sync the project.
3. Reconfigure the project.

Then you can carry on as before.
