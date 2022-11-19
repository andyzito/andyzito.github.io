---
type: contribution
layout: page
title: OpenPath
permalink: /openpath/
linkout: https://github.com/greenriver/hmis-warehouse
excerpt: test
---

[GitHub repository (HMIS Warehouse) »](https://github.com/greenriver/hmis-warehouse)

[GitHub repository (CAS) »](https://github.com/greenriver/boston-cas)

> Open Path is a data integration platform that provides improved care coordination, prioritization of services, and in-depth analysis.

— [openpath.host/about](https://www.openpath.host/about)

OpenPath is composed of two distinct but integrated applications. The Coordinated Access System (CAS) is the client-facing application which "brings together the organizations, housing resources, and services available to assist homeless people into a permanent home." ([greenriver.com](https://www.greenriver.com/portfolio/the-city-of-boston)). It is supported by the HMIS (Homeless Management Information System) Warehouse, which "collects, combines, and aggregates data from multiple sources for analysis." ([openpath.host/about](https://www.openpath.host/about))

I contributed most to the custom deployment tool supporting the platform, including but not limited to:

- [Tagging deployed Docker images (to ECS) as `--latest`](https://github.com/greenriver/hmis-warehouse/pull/1881)
- [Improving generation and use of the `pre-cache` image to speed up image builds in GitHub Actions](https://github.com/greenriver/hmis-warehouse/pull/2244)
- [Updating the AWS CLI usage to remove several manual checkpoints](https://github.com/greenriver/hmis-warehouse/pull/2234/files) and [cut down deployment time significantly](https://github.com/greenriver/hmis-warehouse/pull/2157)
- [Precompiling the Ruby on Rails application assets ahead of time](https://github.com/greenriver/hmis-warehouse/pull/1967)
 [in the GitHub Actions pipeline](https://github.com/greenriver/hmis-warehouse/pull/2157)