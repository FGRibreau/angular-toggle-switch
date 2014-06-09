# angular-toggle-switch2 [![Build Status](https://travis-ci.org/fgribreau/angular-toggle-switch.png?branch=master)](https://travis-ci.org/fgribreau/angular-toggle-switch)

Toggle Switches for AngularJS.  Based off [Bootstrap switch](http://www.larentis.eu/switch/) by Matt Lartentis.

**FORK**
- added a `toggle` attr evaluated each time the user click on the toggle.
- now `toggle-switch` does NOT change the boolean value of the `model` attribute and use it only as a read-only property.

```
<toggle-switch model="alert.active" toggle="toggleActive(alert)" on-label="Active" off-label="Inactive"><toggle-switch>
```

## Demo
[cgarvis.github.io/angular-toggle-switch](http://cgarvis.github.io/angular-toggle-switch)

## Installation

```bash
$ bower install angular-toggle-switch2 --save
```

```javascript
angular.module('app', ['toggle-switch']);
```

See [demo](http://cgarvis.github.io/angular-toggle-switch) for usage.

## Development

Testing is done using Karma Test Runner.

```bash
$ grunt test
```

## Release

```bash
$ grunt release
```
