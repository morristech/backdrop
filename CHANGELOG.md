## [0.4.6] - 19 September 2020

* `_MeasureSize`: removed `_OnWidgetSizeChange` in favour of `ValueChanged<Size>`
* `_MeasureSize`: fix: not working properly with Animation [https://github.com/fluttercommunity/backdrop/pull/57]
* `BackdropScaffold`: fix: layout issue for strict constraint `backLayer` [https://github.com/fluttercommunity/backdrop/pull/58]

## [0.4.5] - 16 September 2020

* `BackdropScaffold`: exposed `key` property [https://github.com/fluttercommunity/backdrop/pull/53]
* `BackdropScaffold`: fix: `headerHeight` not updating once built [https://github.com/fluttercommunity/backdrop/pull/52]

## [0.4.4] - 10 September 2020

* `BackdropToggleButton`: exposed `color` property of `AnimatedIcon` [https://github.com/fluttercommunity/backdrop/issues/48]
* `BackdropScaffold`: added all missing properties from material `Scaffold` [https://github.com/fluttercommunity/backdrop/pull/51]
* `BackdropScaffold`: added property `inactiveOverlayOpacity`.[https://github.com/fluttercommunity/backdrop/pull/51]

## [0.4.3] - 15 August 2020

* Demo app with use cases [https://github.com/fluttercommunity/backdrop/pull/37]
* `BackdropNavigationBackLayer`: directly expose `separatorBuilder` instead of `separator` [https://github.com/fluttercommunity/backdrop/pull/44]

## [0.4.2] - 10 August 2020

* fix toggle from front layer bug [https://github.com/fluttercommunity/backdrop/pull/41]

## [0.4.1] - 6 June 2020

* making `_BackdropScaffoldState` class public [https://github.com/fluttercommunity/backdrop/pull/36] 

## [0.4.0] - 6 June 2020

* refactor `backdrop.dart` to smaller dart files [https://github.com/fluttercommunity/backdrop/pull/32]

## [0.3.4] - 5 June 2020

* `subHeader` attribute added to `BackdropScaffold` [https://github.com/fluttercommunity/backdrop/pull/29]
* `BackdropSubHeader` provided to implement sub header following MDG [https://github.com/fluttercommunity/backdrop/pull/29]

## [0.3.3] - 4 June 2020

* refactor `showFrontLayer` to `concealBackLayer` and `showBackLayer` to `revealBackLayer` [https://github.com/fluttercommunity/backdrop/pull/30]
* added `onBackLayerConcealed` and `onBackLayerRevealed` callbacks [https://github.com/fluttercommunity/backdrop/pull/30]
 
## [0.3.2] - 28 May 2020

* fix typo [https://github.com/fluttercommunity/backdrop/pull/27]

## [0.3.1] - 27 May 2020

* `floatingActionButton` and other related attributes to `BackdropScaffold` [https://github.com/fluttercommunity/backdrop/pull/21]

## [0.3.0] - 27 May 2020

* `BackdropAppBar` added [https://github.com/fluttercommunity/backdrop/pull/23]

## [0.2.17] - 26 May 2020

* animation duration fix [https://github.com/fluttercommunity/backdrop/pull/19]
* configurable inactive layer color with animating color change [https://github.com/fluttercommunity/backdrop/pull/20]
* Improve the front layer border radius [https://github.com/fluttercommunity/backdrop/pull/22]

## [0.2.15] - 15 May 2020

* bug fix: unfocusing keyboard before fling. [https://github.com/fluttercommunity/backdrop/pull/16]
 
## [0.2.14] - 21 April 2020

* Moved package from `gitlab.com/daadu/backdrop` to `github.com/fluttercommunity/backdrop`

## [0.2.13] - 21 April 2020

* Moved package to Flutter Community

## [0.2.11] - 18 April 2020

* Reverting to v0.2.9

## [0.2.10] - 18 April 2020

* Added documentation link in `pubspec.yaml`

## [0.2.9] - 18 April 2020

* Documentation of classes and attributes

## [0.2.8] - 16 January 2020

* disabling focus on `backLayer` when not visible

## [0.2.7] - 18 December 2019

* updated README.md

## [0.2.0] - 18 December 2019

* `NavigationBackLayer` widget - for easily implement navigation with backdrop
* `stickyFrontLayer` - dynamic height for backdrop - based on height of backLayer
* `animationCurve` for backdrop can be passed as parameter
* minor bug fixes

## [0.1.0] - 28 July 2018.

* opacity fixes in `BackdropScaffold`.
* `headerHeight` option added in BackdropScaffold.
* `frontLayerBorderRadius` option added in BackdropScaffold
* refactor: `body` -> `frontLayer`
* refactor: `backpanel` -> `backLayer`
* `BackdropToggleButton` widget implemented.

## [0.0.1] - 21 July 2018.

* Basic backdrop implementation.
* `BackdropScaffold` widget implemented.
