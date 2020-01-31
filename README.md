[![Build Status](https://travis-ci.org/finos/purealloy.svg?branch=master)](https://travis-ci.org/finos/purealloy)
[![FINOS - Incubating](https://cdn.jsdelivr.net/gh/finos/contrib-toolbox@master/images/badge-incubating.svg)](https://finosfoundation.atlassian.net/wiki/display/FINOS/Incubating)

# PURE/Alloy

On November 20, 2019, at FINOS' flagship conference, the Open Source Strategy Forum, FINOS Platinum member [Goldman Sachs](https://developer.gs.com/docs/products/) announced its intention to open source two closely related products - its internal logical modeling language internally named "PURE", and a visual modeling platform that generates PURE models known in Goldman Sachs as "Alloy" - into FINOS.

More information about this decision and announcement can be found at https://www.finos.org/alloy.

# Open Sourcing Roadmap
- Phase 0 (Q4 2019): Stand-up and deploy external "sandbox" instance of Alloy for shared modeling; Open Source Strategy Forum announcement; internal code evaluation and preparation for open sourcing
- Phase 1 (Q1 2020): Pilot using the external sandbox instance of Alloy development of common, shared models, licensed under and Apache 2.0 license, written in PURE with interested industry participants; continue to prepare code for open sourcing. Develop initial shared roadmap for PURE and Alloy extensions and new features for project developers to work on; identify priority areas for further collaborative model development.
- Phase 2 (Mid 2020): Complete technical and legal reviews of code for release per FINOS contribution process; make underlying PURE and Alloy code bases available as open source under an Apache 2.0 license into a FINOS GitLab or GitHubrepository. Begin accepting pull requests into PURE and Alloy from developers outside Goldman Sachs.

For more information about PURE/Alloy, including some of the motivations behind the decision to open source these two products, see the [PURE/Alloy press release](https://www.finos.org/press/goldman-announces-pure-alloy-contribution).

# Documentation Strategy
## [This Repository - GitHub.com (github.com/finos/purealloy)](github.com/finos/purealloy)

This repository (github.com/finos/purealloy) hosts:
* The underling files for the [PURE/Alloy Documenation site](alloy.finos.org) (composed in markdown file format and stored in the `docs/` folder)
    * The [shared issues list](https://github.com/finos/purealloy/issues) used for task management to track project activity around documentation, deployments, and the overall effort associated with open sourcing PURE and AlloyT
*  These issues are organized in various kanban boards, including the [overall project kanban](https://github.com/orgs/finos/projects/5), will are configued to pull from the repository as well as other FINOS repositories if and as needed. 

## [FINOS Hosted GitLab Repository (gitlab.alloy.finos.org)](gitlab.alloy.finos.org)
A separate [hosted Gitlab repository, gitlab.alloy.finos.org](gitlab.alloy.finos.org) hosts shared models being developed by the [Alloy project pilot team](https://groups.google.com/a/finos.org/forum/#!forum/alloy-pilot).

## [GitLab.com (gitlab.com/finosfoundation)](gitlab.com/finosfoundation)
Documentation specific to particiular families and groups of models will be created and curated with Gitlab.com at [https://gitlab.com/finosfoundation](https://gitlab.com/finosfoundation).
In Phase 2 it's expected models themselves will be migrated from the hosted GitLab instance to Gitlab.com. 

## [Alloy Documentation Site (alloy.finos.org/)](https://alloy.finos.org/)
The [documentation site](alloy.finos.org) is built using Docusaurus based on the markdown files in the [`docs`](/docs/) folder. 
* Note: [The documentation build script](https://github.com/finos/purealloy/blob/master/build-site.sh) can be configued to pull in and include files from GitLab.com repositories housing modeling documentation into the GitHub pages / Docusaurus powered site. For more information on the documentation build process, the site's use of Docusaurus, and how to contribute to the docs, see the ["Help Build the Documentation" section of CONTRIBUTING.md](.github/CONTRIBUTING.md).

# Contributing
See [CONTRIBUTING.md](.github/CONTRIBUTING.md)

# Installation
(Coming Soon; Information on running and installing your own instance of Alloy, either on premise or in a cloud provider such as AWS, Azure, or Google).

# Usage example
(Coming Soon)

# Development setup
(Coming Soon)

# License
Copyright 2020 Goldman Sachs

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

SPDX-License-Identifier: [Apache-2.0](https://spdx.org/licenses/Apache-2.0)
