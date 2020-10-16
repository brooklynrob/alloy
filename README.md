[![Build Status](https://travis-ci.org/finos/alloy.svg?branch=master)](https://travis-ci.org/finos/alloy)
[![FINOS - Incubating](https://cdn.jsdelivr.net/gh/finos/contrib-toolbox@master/images/badge-forming.svg)](https://finosfoundation.atlassian.net/wiki/spaces/FINOS/pages/75530756/Project+Lifecycle)

# Legend Background
On November 20, 2019, at FINOS' flagship conference, the [Open Source Strategy](https://opensourcestrategyforum.org/) Forum, FINOS Platinum member [Goldman Sachs](https://developer.gs.com/docs/products/) announced [its intention](https://www.finos.org/press/goldman-announces-pure-alloy-contribution) to open source two closely related products into FINOS:
* its logical modeling language, internally named "PURE"
* a suite and workbench of tools, including a visual modeling platform, internally named "Alloy".

Together this language and overall platform are now named "LEGEND". 

# Roadmap
## Phase 0 (October 2019 - January 2020) - COMPLETED:
  * Deployed an external instance of Alloy to AWS for Phase 1 shared modeling
  * Announced the intention to open source PURE/Alloy (now named Legend) at the [Open Source Strategy Forum](https://opensourcestrategyforum.org/)
  * Internal code evaluation and preparation for open sourcing.

## Phase 1 (January 2020 - September 2020):
During the pilot phase, modelers collaborated on Alloy to build shared models. Modeling occurred in two work streams: FX Options and Commodities Reference Data. The batch of modeling work undertaken by the FX Options Working Group concluded in August 2020, and the Commodities Reference Data Working Group completed their roadmap in September 2020. We expect that further working groups may use Alloy for data modeling in these and/or other areas after the first wave of code has been open sourced in late September 2020. 

The two areas that the pilot group modeled during the pilot were:

* Using the FX Option in the Common Domain Model (CDM), developed by the International Swaps and Derivatives Association (ISDA) as a starting point, extended and expanded the FX Option model, specifically the Averaging Modeling. The extensions built during the pilot have since been proposed and accepted by the ISDA Architecture Review Committee into the CDM.
* Commodity Reference Data, especially in the context of a Fixed vs Float swap, including defining a payout model to be proposed into the CDM.

Other areas that the pilot group have discussed as potential areas to model together in Alloy include Environmental, Social and Governance (ESG) data as well as potentially continuing some of the work started by the FINOS Financial Objects program on RFQ in the context of interest rate swaps.

* Phase 2 (October 2020 -): ; make underlying PURE and Alloy code bases available as open source under an Apache 2.0 license into a FINOS GitHub repository (targetted to happen in September 2020). Begin accepting pull requests into Alloy from developers outside Goldman Sachs.

# Code (and Model) Repositories
[This repository (finos/legend)](www.github.com/finos/legend) is the "parent" repository for the project and is used principly for documentation and issue tracking. The code itself for the 5 modules thusfar open sourced can found in the following 5 "child repositories"
* Shared Module: https://github.com/finos/legend-shared
* SDLC Module: https://github.com/finos/legend-sdlc
* Studio Module: https://github.com/finos/legend-studio
* Engine Module: https://github.com/finos/legend-engine
* Legend Language: https://github.com/finos/legend-pure

Additionally, the Legend models developed during Phase 1 are themselves open source code and available in the following GitLab repositories:
* FX Options extensions to the CDM: https://gitlab.legend.finos.org/alloy-pilot/cdm
* Commodities Reference Data: https://gitlab.legend.finos.org/alloy-pilot/commonrefdata

To access these GitLab repos direclty, you'll need an account on the Legend shared instance, which can be requested at https://www.finos.org/legend


# Documentation Strategy

## [Legend Documentation Site (legend.finos.org)](https://legend.finos.org/)
The [documentation site](https://legend.finos.org) is built using Docusaurus based on the markdown files in the [`docs`](/docs/) folder. 

## [This Repository - GitHub.com (github.com/finos/legend)](https://github.com/finos/legend)

[This repository (github.com/finos/legend)](github.com/finos/legend) hosts:
* The underling files for the [Alloy Documentation site](https://legend.finos.org) (composed in markdown file format and stored in the `docs/` folder)
* The [shared issues list](https://github.com/finos/legend/issues) used for task management to track project activity around documentation, deployments, and the overall effort associated with open sourcing PURE and Alloy
*  These issues are organized in various kanban boards, including the [overall project kanban](https://github.com/orgs/finos/projects/5).

## [FINOS Hosted GitLab Repository (gitlab.alloy.finos.org)](https://gitlab.alloy.finos.org)
A separate [hosted Gitlab repository, gitlab.alloy.finos.org](gitlab.alloy.finos.org) hosts shared models being developed by the [Alloy project pilot team](https://groups.google.com/a/finos.org/forum/#!forum/alloy-pilot).

## [gitlab.com (https://gitlab.com/finosfoundation)](gitlab.com/finosfoundation) [Not Yet Used]
Documentation specific to particular families and groups of models will be created and curated on GitLab.com at [https://gitlab.com/finosfoundation](https://gitlab.com/finosfoundation). In Phase 2, it's possible that the shared model definitions themselves may be migrated from the hosted GitLab instance to Gitlab.com. 

# Contributing
See our [CONTRIBUTING.md](CONTRIBUTING.md)

# Installation
(Coming Soon; Information on running and installing your own instance of Alloy, either on premise or in a cloud provider such as AWS, Azure, OpenShift, Google, etc.)

# Usage example
(Coming Soon)

# Development setup
(Coming Soon)

# Training materials
Thanks for your interest in Alloy. We have been developing training materials and resources since Goldman Sachs [announced their intenton to open source Alloy into FINOS](https://www.cnbc.com/2019/11/20/goldman-sachs-is-giving-away-software-to-wall-street-for-free.html#:~:text=Finance-,Goldman%20Sachs%20is%20planning%20on%20giving%20some%20of%20its%20most,to%20Wall%20Street%20for%20free&text=%E2%80%9CWe're%20using%20Alloy%20because,chief%20data%20officer%2C%20Jeff%20Wecker.) in November 2019. If you have any questions on how to get started using Alloy, please follow the below steps:

#### 1. Review the existing materials
* [Alloy Demo by Pierre de Belen of Goldman Sachs at OSSF 2019](https://www.youtube.com/watch?v=na4DCgvdDJ4) (video)
* [Replay from May 6th Alloy Pilot Call Presentation - Part 1 of Open Source Fundamentals & Concepts for Alloy Modeling](https://www.finos.org/hubfs/FINOS/2020%20Video%20Uploads/FINOS%20-%20Open%20Source%20Fundamentals%20-%20Part%201%20-%2006%20May%2020.mp4) (video)
* [Replay from May 20th Alloy Pilot Call Presentation - Part 2 of Open Source Fundamentals & Concepts for Alloy Modeling](https://www.finos.org/hubfs/FINOS/2020%20Video%20Uploads/FINOS%20-%20Open%20Source%20Fundamentals%20-%20Part%202%20-%2013%20May%2020.mp4) (video)
* [Alloy Documentation site](https://alloy.finos.org/)
* Alloy meeting minutes:
  * [prior to July 2020](https://github.com/finos/legend/tree/master/meeting-minutes)
  * [July 2020 and later](https://github.com/finos/legend/issues?q=label%3Ameeting)
  
#### 2. [Raise an issue](https://github.com/finos/legend/issues)
* If you cannot find the answer to your question in the above materials, please raise an issue at https://github.com/finos/legend/issues

#### 3. Join Legend Office Hours _(more information coming soon)_

# License
Copyright 2020 Goldman Sachs

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

SPDX-License-Identifier: [Apache-2.0](https://spdx.org/licenses/Apache-2.0)
