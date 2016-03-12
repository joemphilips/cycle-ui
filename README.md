eldarlabs/cycle-ui
====
[![circleci build](https://circleci.com/gh/eldarlabs/cycle-ui.svg?style=shield)](https://circleci.com/gh/eldarlabs/cycle-ui)
[![version](https://img.shields.io/npm/v/@eldarlabs/cycle-ui.svg)](http://npm.im/@eldarlabs/cycle-ui)
[![MIT License](https://img.shields.io/npm/l/starwars-names.svg)](https://raw.githubusercontent.com/eldarlabs/cycle-ui/master/LICENSE)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

A Cycle.js HTML component library.

An **experimental work in progress** conversion of react-toolbox components to
Cycle.js components. Currently using the Material Design styles from react-toolbox that are written with PostCSS. Future work may define an interface for interchangeable styles.

How to use
----------

Note: I want to bring a proposal to Cycle-DOM to allow removal of the .DOM boilerplate.

    // Import components you want to use
    import { Input, RadioButton } from '@eldarlabs/cycle-ui';

    // Use components in your Cycle.js view

    return div([
      h3('.example', [`Using Cycle-UI`]),
      Input(sources, {
          label: `Answer to life`,
          maxLength: 50,
      }).DOM,
      RadioButton(sources, {
        label: 'Radio easy',
        checked: true,
      }).DOM,
    ])



Related projects
----------------

- [cycle-ui-typescript-webpack](https://github.com/eldarlabs/cycle-ui-typescript-webpack) - Cycle.js Starter Project for using Cycle-UI, TypeScript and WebPack.
- [Cycle.js](http://cycle.js.org) - required to use the Cycle-UI components. Declarative programming with data flow.
- [React Toolbox Components](http://react-toolbox.com/#/components) - uses the PostCSS/SASS styles from this library.
- [RxJS](http://reactivex.io/intro.html) - Functional, Reactive, Observable streams of data that power Cycle.js
- [TypeScript](http://www.typescriptlang.org/Handbook) - Types, Interfaces, static checking and other good stuff.
- [Typings](https://github.com/typings/typings) - Trying to make TypeScript Type definitions easier to deal with.
- [Semantic Release](https://github.com/semantic-release/semantic-release) - Trying out this tool for streamlining a release.
- [Commitizen](https://github.com/commitizen/cz-cli) - Commit tool that works well with Semantic Release.

License
=======

[The MIT License](https://raw.githubusercontent.com/eldarlabs/cycle-ui/master/LICENSE)

Copyright (c) 2016 [Eldar Labs](https://eldarlabs.com)
