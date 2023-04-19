## Silverstripe Collaboration Recipe

[![CI](https://github.com/silverstripe/recipe-collaboration/actions/workflows/ci.yml/badge.svg)](https://github.com/silverstripe/recipe-collaboration/actions/workflows/ci.yml)
[![Silverstripe supported module](https://img.shields.io/badge/silverstripe-supported-0071C4.svg)](https://www.silverstripe.org/software/addons/silverstripe-commercially-supported-module-list/)

Extra CMS functionality recipe for a [CWP 2](https://www.cwp.govt.nz) installation. This includes the following core Silverstripe and community modules:

 * [silverstripe/recipe-cms](https://github.com/silverstripe/recipe-cms): Recipe containing CMS, versioned, asset-admin, etc
 * [silverstripe/contentreview](https://github.com/silverstripe/silverstripe-contentreview/): Mark a page in
   Silverstripe CMS with a date and an owner for future review
 * [silverstripe/sharedraftcontent](https://github.com/silverstripe/silverstripe-sharedraftcontent/): Share draft page
   content with non-CMS users
 * [symbiote/silverstripe-advancedworkflow](https://github.com/symbiote/silverstripe-advancedworkflow/): A highly
   configurable step-based workflow module.

This can be either added to an existing project or used as a project base for creating a
basic CWP install.

## Installation

```sh
composer create-project silverstripe/recipe-collaboration ./myproject
```

## More information

See the [recipe plugin](https://github.com/silverstripe/recipe-plugin) page for instructions on how
Silverstripe recipes work.
