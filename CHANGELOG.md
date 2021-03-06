# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## 0.3.0
* Changed: Breaking! `declaration-block-property-groups-structure` now uses `declaration-block-properties-specified-order` rather stylelint's deprecated `declaration-block-properties-order`. Flexible group order isn't supported anymore
* Added: `declaration-block-order` support new `rule` extended object, which have new `selector` option. Rules in order can be specified by their selector
* Added: New keyword `at-variables` in `declaration-block-order`
* Added: New keyword `less-mixins` in `declaration-block-order`

## 0.2.2
* Fixed tests for `declaration-block-property-groups-structure` which were broken by previous fix ¯﻿\﻿_﻿(﻿ツ﻿)﻿_﻿/﻿¯

## 0.2.1
* Fixed incorrect severity level for `declaration-block-properties-order` which is called from `declaration-block-property-groups-structure`

## 0.2.0
* Breaking: Renamed `property-groups-structure` to `declaration-block-property-groups-structure`
* Added `declaration-block-properties-specified-order` rule
* Fixed unavailability of `declaration-block-properties-alphabetical-order` rule

## 0.1.0
* Initial release.
