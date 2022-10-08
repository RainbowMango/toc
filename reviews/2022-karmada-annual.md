# Karmada 2022 Annual Review

Karmada (Kubernetes Armada) is a Kubernetes management system that enables you to run your cloud-native applications 
across multiple Kubernetes clusters and clouds, with no changes to your applications. 
By speaking Kubernetes-native APIs and providing advanced scheduling capabilities, Karmada enables truly open, 
multi-cloud Kubernetes.

Karmada was proposed and accepted as a sandbox project in September 2021. ([GitHub](https://github.com/cncf/toc/issues/721)).

## DevStats

DevStats can be found [here](https://karmada.devstats.cncf.io/d/8/dashboards?orgId=1&refresh=15m).

Here are some links worth mentioning:

- [Stars and forks](https://karmada.devstats.cncf.io/d/3/stars-and-forks-by-repository?orgId=1)
- [Issues](https://karmada.devstats.cncf.io/d/12/issues-opened-closed-by-repository-group?orgId=1)
- [PRs](https://karmada.devstats.cncf.io/d/15/new-prs-in-repository-groups?orgId=1)

Karmada currently has [182](https://karmada.devstats.cncf.io/d/22/prs-authors-table?orgId=1) PR authors from [50](https://karmada.devstats.cncf.io/d/5/companies-table?orgId=1) companies.

The community has grown since the project entered the CNCF sandbox.

* We held bi-weekly community meetings constantly (total 38 times as of September 2022). The meeting records can be found in [here](https://docs.google.com/document/d/1y6YLVC-v7cmVAdbjedoyR5WL0-q45DBRXTvz5_I7bkA/edit). The average number of meeting attendees is around 25.
* Github stars increased from **1600+ to 2600+**
* Github forks increased from **200+ to 500+**
* Number of contributors increased to **[330+](https://karmada.devstats.cncf.io/d/18/overall-project-statistics-table?orgId=1&viewPanel=1)**.

## Maintainers

Karmada currently has 7 maintainers from 4 different companies:

| Maintainer  | GitHub ID         | Affiliation | Email                    |
|-------------|-------------------|-------------|--------------------------|
| Hanbo Li    | @mrlihanbo        | Huawei      | <lihanbo2@huawei.com>    |
| Hongcai Ren | @RainbowMango     | Huawei      | <renhongcai@huawei.com>  |
| Kevin Wang  | @kevin-wangzefeng | Huawei      | <wangzefeng@huawei.com>  |
| Lei Xue     | @carmark          | Tencent     | <vfs@live.com>           |
| Shiyi Xie   | @GitHubxsy        | Huawei      | <xieshiyi1@huawei.com>   |
| Yifan Shen  | @zoroyouxi        | ICBC        | <shenyf@sdc.icbc.com.cn> |
| Yiheng Ci   | @lfbear           | VIPKID      | <ciyiheng@vipkid.com.cn> |

The full maintainer list can be found in our [GitHub repository](https://github.com/karmada-io/karmada/blob/master/MAINTAINERS.md).

## Adoption

Karmada now have 7 adopters that using Karmada in `production` environments.
We just started to collecting the adopters from last month, there are several other companies are using Karmada,
but we don't have a public confirmation available yet. So the adopters list may grow over time,
the full adopter list can be found in our [website](https://karmada.io/docs/casestudies/adopters).

## Project goals

Karmada aims to provide turnkey automation for multi-cluster application management in multi-cloud and hybrid cloud scenarios,
with key features such as centralized multi-cloud management, high availability, failure recovery, and traffic scheduling.

Following the above goals, in the last year we released a total of 6 versions and each version added the following features:

- v0.9.0(30 Sep 2021)
    - New features
        - Support upgrade from the previous version
        - Introduced karmada-scheduler-estimator to facilitate end-to-end scheduling accuracy
        - Maintainability improvements
- v0.10.0(20 Nov 2021)
    - New features
        - Introduced Resource Interpreter Webhook framework for supporting CRDs
        - Significant Scheduling Enhancement
        - Workloads Observation from Karmada Control Plane
- v1.0.0(31 Dec 2021)
    - New features
        - Aggregated Kubernetes API Endpoint
        - Promoting Workloads from Legacy Clusters to Karmada
        - Verified Integration with Ecosystem
        - OverridePolicy Improvements, introduced `RuleWithCluster` to `OverridePolicy`.
        - Introduced init command to Karmada CLI for installation.
- v1.1.0(28 Feb 2022)
    - New features
        - Aggregated Kubernetes API Endpoint
        - Promoting Workloads from Legacy Clusters to Karmada
        - Verified Integration with Ecosystem
        - OverridePolicy Improvements, introduced `RuleWithCluster` to `OverridePolicy`.
        - Introduced init command to Karmada CLI for installation.
- v1.2.0(28 May 2022)
    - New features
        - Significant improvement on scheduling capability and scalability
        - Fully adopted aggregated API
        - Distributed search and analytics engine for Kubernetes resources (alpha)
- v1.3.0(31 Aug 2022)
    - New features
        - Taint-based eviction in graceful way
        - Global proxy for resources across multi-clusters
        - Cluster resource modeling
        - Bootstrap token-based cluster registration
        - Significant improvement in system scalability

The planed new features are shown in [roadmap](https://github.com/karmada-io/karmada/blob/master/ROADMAP.md).

## How the CNCF Can Help

Similar to many other Sandbox projects, we wish to get the following help from CNCF:
- More channels to advocate the project.
- More chances to collaborate with other projects in CNCF or even out of CNCF.
- Technical writing support for project documents.

## Incubation

We are preparing for the incubation proposal.