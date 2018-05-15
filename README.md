# Awesome Ember.js [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


> A curated list of delightful Ember.js [packages](#packages) and [resources](#resources).

Just type [`ember.cool`](https://ember.cool) to go here ✨

*You might also like [awesome-npm](https://github.com/sindresorhus/awesome-npm).*
*Please read the [contribution guidelines](contributing.md) before contributing.*

---

## Contents
- [Packages](#packages)
	- [AST](#ast)
	- [Adapters](#adapters)
	- [Animations](#animations)
	- [Authentication](#authentication)
	- [Automation](#automation)
	- [Benchmarking](#benchmarking)
	- [Blogging](#blogging)
	- [Broccoli](#broccoli)
	- [Broccoli read](#broccoli-read)
	- [Build tools](#build-tools)
	- [Charts](#charts)
	- [CI/CD](#ci-cd)
	- [Code Splitting](#code-splitting)
	- [Codestyle](#codestyle)
	- [Command-line apps](#command-line-apps)
	- [Command-line utilities](#command-line-utilities)
	- [Component addons](#component-addons)
	- [Compression](#compression)
	- [Content management systems](#content-management-systems)
	- [Control flow](#control-flow)
	- [CSS & etc](#css-&-etc)
	- [Data Management](#data-management)
	- [Data manipulation & Computed](#)
	- [Data validation](#data-validation)
	- [Database](#database)
	- [Date](#date)
	- [Debugging / Profiling](#)
	- [Documentation](#documentation)
	- [Email](#email)
	- [Ember-inspector roadmaps & overview](#)
	- [End-user customization](#end-user-customization)
	- [ES6](#es6)
	- [Filesystem](#filesystem)
	- [Forms](#forms)
	- [Forum](#forum)
	- [Functional programming](#functional-programming)
	- [HTTP](#http)
	- [Hardware](#hardware)
	- [Helpers](#helpers)
	- [Humanize](#humanize)
	- [Image](#image)
	- [Include external JS code](#include-external-js-code)
	- [Infinite Scroll](#infinite-scroll)
	- [Internalization & Localization](#)
	- [Job queues](#job-queues)
	- [Logging](#logging)
	- [Mad science](#mad-science)
	- [Math](#math)
	- [Metrics](#metrics)
	- [Minifiers](#minifiers)
	- [Miscellaneous](#miscellaneous)
	- [Mobile](#mobile)
	- [Natural language processing](#natural-language-processing)
	- [Network](#network)
	- [Node.js management](#nodejs-management)
	- [Number](#number)
	- [Parsing](#parsing)
	- [Payments](#payments)
	- [Polyfills](#polyfills)
	- [PWA](#pwa)
	- [Process management](#process-management)
	- [Query Params](#query-params)
	- [Real-time](#real-time)
	- [Security](#security)
	- [SSR / Server Side Rendering](#)
	- [Static site generators](#s)
	- [Streams](#streams)
	- [Styling](#styling)
	- [Templating](#templating)
	- [Testing](#testing)
	- [Text](#text)
	- [TypeScript](#typeScript)
	- [UI components](#ui-components)
	- [UI libs](#ui-libs)
	- [URL](#url)
	- [UX](#ux)
	- [VS Code addons](#vs-code-addons)
	- [Web frameworks](#web-frameworks)
	- [Webpack](#webpack)
	- [Weird](#weird)
- [Resources](#resources)
	- [Articles](#articles)
	- [Best-practices](#best-practices)
	- [Blogs](#blogs)
	- [Books](#books)
	- [Cheatsheets](#cheatsheets)
	- [Codemods](#codemods)
	- [Community](#community)
	- [Courses](#courses)
	- [Discovery](#discovery)
	- [Examples](#examples)
	- [Gists](#gists)
	- [Miscellaneous](#miscellaneous)
	- [Newsletters](#newsletters)
	- [Podcasts](#podcasts)
	- [Screencasts](#screencasts)
	- [Slides](#slides)
	- [Styleguides](#styleguides)
	- [Tools](#tools)
	- [Tutorials](#tutorials)
	- [Twitter](#twitter)
	- [Videos](#videos)
	- [YouTube channels](#youTube-channels)


## Packages
### AST

- [ember-ast-helpers](https://github.com/cibernox/ember-ast-helpers) - This library is a utility belt to make AST transforms and shield users as much as possible from the nuances of the AST, as it is still private API.
- [jscodeshift](https://github.com/facebook/jscodeshift) - A JavaScript codemod toolkit.

### Adapters

- [ember-cli-markdown-resolver](https://github.com/willviles/ember-cli-markdown-resolver) - Ember CLI addon for resolving markdown files in custom folders and retrieving content via a service.
- [ember-cloud-firestore-adapter](https://github.com/rmmmp/ember-cloud-firestore-adapter) - Unofficial Ember Data Adapter and Serializer for Cloud Firestore
- [ember-data-hal-9000](https://github.com/201-created/ember-data-hal-9000) - An ember-data compatible ember-cli addon that provides a HAL adapter (HATEOAS)
- [ember-django-adapter](https://github.com/dustinfarris/ember-django-adapter) - Ember CLI addon adapter for Django REST Framework
- [ember-graphql-adapter](https://github.com/alphasights/ember-graphql-adapter) - GraphQL adapter for Ember Data
- [ember-indexeddb](https://github.com/mydea/ember-indexeddb) - Utilities & adapter to work with IndexedDB in ember & ember-data
- [ember-local-storage](https://github.com/funkensturm/ember-local-storage) - The addon provides a storageFor computed property that returns a proxy and persists the changes to localStorage or sessionStorage.
- [ember-pouch](https://github.com/pouchdb-community/ember-pouch) - PouchDB/CouchDB adapter for Ember Data
- [ember-wordpress](https://github.com/oskarrough/ember-wordpress) - The bridge between Ember.js and Wordpress
- [emberfire](https://github.com/firebase/emberfire) - Official Ember Data adapter for Firebase

### Animations

- [ember-animated](ttps://github.com/ember-animation/ember-animated) - [Web Animations with Ember js](https://www.youtube.com/watch?v=TSvnutA9PUE)
- [liquid-fire](https://github.com/ember-animation/liquid-fire) - Animations & transitions for ambitious Ember applications.

### Authentication

- [ember-cli-simple-auth-extensions](https://emberobserver.com/categories/ember-cli-simple-auth-extensions)
- [ember-simple-auth](https://github.com/simplabs/ember-simple-auth) - A library for implementing authentication/authorization in Ember.js applications.
- [tori](https://github.com/Vestorly/torii) - A set of clean abstractions for authentication in Ember.js

### Automation

- [ember-cli-deploy](https://github.com/ember-cli-deploy/ember-cli-deploy) - A deployment pipeline for Ember CLI apps
- [ember-cli-release](https://github.com/shipshapecode/ember-cli-release) - Ember CLI addon for versioned release management
- [ember-cli-sri](https://github.com/jonathanKingston/ember-cli-sri) - This plugin is used to generate Subresource Integrity (SRI) hashes for ember applications.
- [ember-cli-dependency-lint](https://github.com/salsify/ember-cli-dependency-lint) - Lint your app's addon dependencies, making sure you only have one version of each.

### Benchmarking

- [ember-macro-benchmark](https://github.com/krisselden/ember-macro-benchmark) - Benchmark recording of an ember app with running with 2 versions of Ember.
- [ember-performance](https://github.com/eviltrout/ember-performance) - A suite of tests for EmberJS to help with performance
- [emberperf](http://emberperf.eviltrout.com) - EmberPerformance (Between versions)

### Blogging

- [ember-tumblr](https://github.com/elwayman02/ember-tumblr) - Ember Addon for integrating a Tumblr blog

### Broccoli

- [broccoli-assembler](https://github.com/twokul/broccoli-assembler) - A build utility to allow for more flexible builds and better composition.
- [broccoli-concat-analyser](https://github.com/stefanpenner/broccoli-concat-analyser) - Assets profiling
- [broccoli-debug](https://github.com/broccolijs/broccoli-debug) - Utility for build pipeline authors to allow trivial debugging of the Broccoli pipelines they author.
- [broccoli-stew](https://github.com/stefanpenner/broccoli-stew) - Provides commonly used convenience functions for developing broccoli based build pipelines.
- [broccolijs-tutorial](https://github.com/oligriffiths/broccolijs-tutorial) - Broccoli.js Tutorial repository
- [broccoli-rollup](https://github.com/chadhietala/broccoli-rollup) - Broccoli Plugin For Rollup
- [broccoli-manifest](https://github.com/racido/broccoli-manifest) - HTML5 cache-manifest compilation for broccoli

### Broccoli read

- [Eat Your Greens - A Broccoli.js tutorial](http://www.oligriffiths.com/broccolijs/)
 
### Build tools

- [Broccoli](https://github.com/broccolijs/broccoli) - Fast, reliable asset pipeline, supporting constant-time rebuilds and compact build definitions.

### Charts

- [ember-sparkles](https://github.com/LocusEnergy/ember-sparkles) - Collection of composable D3 components built with ember-d3-helpers 

### CI/CD

- [ember-cli-server-variables](https://github.com/blimmer/ember-cli-server-variables) - An Ember CLI add-on to support adding variables to the generated index.html file's head tag.

### Code Splitting

- [ember-engines](https://github.com/ember-engines/ember-engines) - This Ember addon implements the functionality described in the Ember Engines RFC. Engines allow multiple logical applications to be composed together into a single application from the user's perspective.

### Codestyle

- [ember-cli-alex](https://github.com/yohanmishkin/ember-cli-alex) - alex for Ember apps

### Command-line apps

- [@ember/optional-features](https://github.com/emberjs/ember-optional-features) - This addon allows you to easily enable/disable optional features in ember-source. To clarify what we mean by optional, these are features that will be opt-in/opt-out and optional for the forseeable future, not features that will be enabled by default. It is intended for use with apps only not addons.
- [ember-cli-rename](https://github.com/trabus/ember-cli-rename) - Addon for ember-cli that provides an `ember rename` command

### Command-line utilities

- [ember-cli-update](https://github.com/ember-cli/ember-cli-update) - Update Ember CLI Ember.js apps and addons (and Glimmer.js apps)

### Component addons

- [ember-diff-attrs](https://github.com/workmanw/ember-diff-attrs)
- [ember-compatibility-helpers](https://github.com/pzuraq/ember-compatibility-helpers) - Helpers that allow you to write backwards compat Ember addons

 ### Compression

- [ember-cli-deploy-brotli](https://github.com/mfeckie/ember-cli-deploy-brotli) - Ember deploy plugin to support brotli compression


### Content management systems

### Control flow

- Promises
	- [?](#) - ????.
- Observables
	- [?](#) - ????.
- Generators
	- [?](#) - ????.
- Streams
	- [?](#) - ????.
- Callbacks
	- [?](#) - ????.
- Channels
	- [?](#) - ????.
- Other
	- [?](#) - ????.

### CSS & etc

 - [ember-cli-stylelint](https://github.com/billybonks/ember-cli-stylelint) - Adds styleint to your ember app, to lint all kinds of css
 - [ember-cli-autoprefixer](https://github.com/kimroen/ember-cli-autoprefixer) - Automatically run your styles through autoprefixer
 - [ember-cli-sass](https://github.com/aexmachina/ember-cli-sass) - Use node-sass to preprocess your ember-cli app's files, with support for sourceMaps and include paths
 - [ember-cli-sass-pods](https://github.com/justtal/ember-cli-sass-pods) - Enjoy styling your pods with the sass style file in the pod directory.
 - [ember-component-css](https://github.com/ebryn/ember-component-css) - An Ember CLI addon which allows you to specify styles for individual components.
 - [ember-cli-postcss](https://github.com/jeffjewiss/ember-cli-postcss) - A Postcss integration for ember-cli
 - [ember-css-modules](https://github.com/salsify/ember-css-modules) - CSS Modules for ambitious applications.
 - [ember-cli-tailwind](https://github.com/embermap/ember-cli-tailwind) - Tailwind is a utility-first CSS framework for rapidly building custom user interfaces.


### Data Management

- [ember-apollo-client](https://github.com/bgentry/ember-apollo-client) - An ember-cli addon for Apollo Client and GraphQL
- [ember-buffered-proxy](https://github.com/yapplabs/ember-buffered-proxy)
- [ember-changeset](https://github.com/poteto/ember-changeset)
- [ember-cli-sofa](https://github.com/ampatspell/ember-cli-sofa) - CouchDB persistence library for Ember.js
- [ember-orbit](https://github.com/orbitjs/ember-orbit) - Ember.js data layer built with Orbit.js
- [ember-redux](http://www.ember-redux.com/) - Predictable state management for ember apps
- [ember-state-services](https://github.com/stefanpenner/ember-state-services)
- [ember-time-machine](https://github.com/offirgolan/ember-time-machine)

 ### Data manipulation & Computed

- [ember-awesome-macros](https://github.com/kellyselden/ember-awesome-macros) - A collection of Ember computed macros
- [ember-cpm](https://github.com/cibernox/ember-cpm) - ComputedProperty Macros for Ember
- [ember-macaroni](https://github.com/poteto/ember-macaroni) - Keep your app code DRY and copypasta free with computed property macaronis (macros)

### Data validation

- [ember-cp-validations](https://github.com/offirgolan/ember-cp-validations) - Ember computed property based validations
- [ember-model-validator](https://github.com/esbanarango/ember-model-validator) - Add validations to your Ember Data models on an explicit and easy way, without a bunch a validations files around or complicated structure.
- [ember-validated-form](https://github.com/adfinis-sygroup/ember-validated-form) - Easily create forms with client side validations.

 ### Database

- [?](#) - ????

 ### Date

- [ember-moment](https://github.com/stefanpenner/ember-moment) - moment.js template helpers and computed property macros for Ember


### Debugging / Profiling

- [ember-debug-logger](https://github.com/salsify/ember-debug-logger) - Exposes the visionmedia/debug library for use in your Ember.js application.
- [ember-devtools](https://github.com/aexmachina/ember-devtools) - A collection of useful Ember.js debugging functions.
- [ember-perf-timeline](https://github.com/ember-best-practices/ember-perf-timeline) - Add performance information to Chrome's Timeline for Ember applications

### Documentation

- [ember-cli-addon-docs](https://github.com/ember-learn/ember-cli-addon-docs) - Easy, beautiful docs for your Ember addon
- [ember-cli-jsdoc](https://github.com/softlayer/ember-cli-jsdoc) - An Ember CLI addon to generate HTML documentation from JSDoc comments in the source code.
- [ember-freestyle](https://github.com/chrislopresto/ember-freestyle) - Ember Freestyle is an Ember addon that allows you to quickly create a component explorer for your Ember app.

 ### Email

 - [?](#) - ????

### Ember-inspector roadmaps & overview

- [Ember Inspector Pairing](https://www.youtube.com/watch?v=rFNR_Fj1G84)
- [Ember Inspector Sync](https://www.youtube.com/watch?v=PvsfQrKxl_8)

 ### End-user customization
- [ember-cli-hot-loader](https://github.com/toranb/ember-cli-hot-loader) - An early look at what hot reloading might be like in the ember ecosystem
- [ember-cli-build-notifications](https://github.com/pdud/ember-cli-build-notifications) - Notifications when ember-cli has a buildError
- [ember-feature-flags](https://github.com/kategengler/ember-feature-flags) An ember-cli addon to provide feature flags.
- [ember-named-yields](https://github.com/knownasilya/ember-named-yields) - Named Yields for Ember Components.
- [ember-glimmer-component](https://github.com/smfoote/ember-glimmer-component) - Glimmer.js-like components in Ember.
- [ember-islands](https://github.com/mitchlloyd/ember-islands) - Render Ember components anywhere on a server-rendered page to create "Islands of Richness"
- [ember-wormhole](https://github.com/yapplabs/ember-wormhole) - Render a child view somewhere else in the DOM.

### ES6

- [ember-decorators](https://github.com/ember-decorators/ember-decorators) - Useful decorators for Ember applications. 

 ### Filesystem

- [?](#) - ????.

### Forms

- [ember-form-for](https://github.com/martndemus/ember-form-for) - This Ember.js addon will give you an easy way to build good forms.
 
### Forum

- [?](#) - ????

### Functional programming

- [Bacon.js](http://baconjs.github.io) - Functional reactive programming.
- [Folktale](http://folktale.origamitower.com) - Suite of libraries for generic functional programming in JavaScript that allows you to write elegant, modular applications with fewer bugs, and more reuse.
- [immutable](https://github.com/facebook/immutable-js) - Immutable data collections.
- [Kefir.js](https://github.com/rpominov/kefir) - Reactive library with focus on high performance and low memory usage.
- [Lazy.js](https://github.com/dtao/lazy.js) - Utility library similar to lodash/Underscore but with lazy evaluation, which can translate to superior performance in many cases.
- [lodash](https://lodash.com) - Utility library delivering consistency, customization, performance, & extras. A better and faster Underscore.js.
- [mori](http://swannodette.github.io/mori/) - Library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
- [Mout](http://moutjs.com) - Utility library with the biggest difference between other existing solutions is that you can choose to load only the modules/functions that you need, no extra overhead.
- [Ramda](http://ramdajs.com) - Utility library with a focus on flexible functional composition enabled by automatic currying and reversed argument order. Avoids mutating data.
- [RxJS](http://reactivex.io) - Functional reactive library for transforming, composing, and querying various kinds of data.
- [underscore-contrib](http://documentcloud.github.io/underscore-contrib/) - The brass buckles on Underscore's utility belt.

### HTTP

- [ember-ajax](https://github.com/ember-cli/ember-ajax) - Service for making AJAX requests in Ember 1.13+ applications.
- [ember-socket-guru](https://github.com/netguru/ember-socket-guru) - Addon for easy integration with Pusher.js, ActionCable, Socket.io and Phoenix Channels

## Hardware

### Helpers

- [ember-composable-helpers](https://github.com/DockYard/ember-composable-helpers) - Composable helpers for declarative templating in Ember
- [ember-d3-helpers](https://github.com/LocusEnergy/ember-d3-helpers) - Collection of Ember.js helpers for building composable D3 charts.
- [ember-math-helpers](https://github.com/shipshapecode/ember-math-helpers) - Ember HTMLBars helpers for basic arithmetic
- [ember-route-action-helper](https://github.com/DockYard/ember-route-action-helper) - Bubble closure actions in routes
- [ember-root-url](https://github.com/ef4/ember-root-url) - A template helper to keep your URLs relative to the app's rootURL.
- [ember-store-helpers](https://github.com/ember-sapporo/ember-store-helpers) - This add-on provides helpers related to ember-data.
- [ember-truth-helpers](https://github.com/jmurphyau/ember-truth-helpers) - Ember HTMLBars Helpers for {{if}} & {{unless}}: not, and, or, eq & is-array
- [ember-cli-string-helpers](https://github.com/romulomachado/ember-cli-string-helpers) - Set of the String helpers extracted from DockYard's ember-composable-helpers.

### Humanize

- [?](#) - ????.

### Image

- [ember-svg-jar](https://github.com/ivanvotti/ember-svg-jar) - The best way to embed SVG images into your Ember application

### Include external JS code

- [ember-cli-cjs-transform](https://github.com/rwjblue/ember-cli-cjs-transform) - CommonJS imports
- [ember-cli-es6-transform](https://github.com/sandydoo/ember-cli-es6-transform) - Import ES6 modules from npm, bower or anywhere else in your app.
- [ember-browserify](https://github.com/ef4/ember-browserify) - ember-cli addon for easily loading CommonJS packages from npm via browserify.

### Infinite Scroll

- [vertical-collection](https://github.com/html-next/vertical-collection) - Infinite Scroll and Occlusion at > 60FPS
- [smoke-and-mirrors](https://github.com/html-next/smoke-and-mirrors) - Ambitious infinite-scroll and svelte rendering for ambitious applications.

### Internalization & Localization

- [ember-i18n](https://github.com/jamesarosen/ember-i18n) - Internationalization for Ember
- [ember-intl](https://github.com/ember-intl/ember-intl) - Translate complex messages string. Localized formatting for date/time, number, and relative time.

### Job queues

- [ember-concurrency](http://ember-concurrency.com)
- [ember-pipeline](https://github.com/poteto/ember-pipeline)
- [ember-lifeline](https://github.com/ember-lifeline/ember-lifeline) - An ember addon for managing the lifecyle of asynchronous behavior in your objects

### Logging

- [console.re](https://console.re/)
- [ember-debug-logger](https://emberobserver.com/addons/ember-debug-logger) - An Ember addon to expose the Visionmedia debug logger.
- [ember-logging-service](https://github.com/acquia/ember-logging-service/) - This addon provides a general and extensible logging service that can be used throughout your application
- [raygun](https://raygun.com/)

### Mad science

- [?](#) - ????.

### Math

- [ember-a11y-landmarks](https://github.com/ember-a11y/ember-a11y-landmarks) - https://github.com/ember-a11y/ember-a11y-landmarks
- [ember-a11y](https://github.com/ember-a11y/ember-a11y) - A collection of tools to build accessible Ember applications.
- [ember-gestures](https://github.com/html-next/ember-gestures) - Ember Gestures provides an easy way to use gestures by making it simple to define and use HammerJS managers and recognizers throughout your app.
- [ember-katex](https://github.com/firecracker/ember-katex) - Render your LaTeX formulas using KaTeX
- [ember-keyboard](https://github.com/patience-tema-baron/ember-keyboard) - An Ember.js addon for the painless support of keyboard events
- [ember-steps](https://github.com/rwjblue/ember-steps) - Declarative create wizards, tabbed UIs, and more

### Metrics

 - [ember-user-activity](https://github.com/elwayman02/ember-user-activity) - Ember Addon for tracking user activity & idling
 - [ember-metrics](https://github.com/poteto/ember-metrics) - Send data to multiple analytics services without re-implementing new API

### Minifiers
- [?](#) - ????

### Miscellaneous

- [diagonal routes](https://alexspeller.com/ember-diagonal/) - See what route structure, templates and route hooks are for a given ember route definition.
- [ember data model maker](https://github.com/andycrum/ember-data-model-maker/) - Ember Data Model Maker (EDMM).

### Mobile

- [corber](https://github.com/isleofcode/corber) - Tooling for cordova and crosswalk hybrid applications built with Ember
- [ember-mobile-bar](https://github.com/nickschot/ember-mobile-bar) - Managed fixed (tool)bars with mobile app-like behaviour
- [ember-mobile-core](https://github.com/nickschot/ember-mobile-core) - Provides a pan recognizer and some utils for the ember-mobile-* addons
- [ember-mobile-menu](https://github.com/nickschot/ember-mobile-menu) - Draggable sidebar specifically tailored to mobile devices
- [ember-mobile-pane](https://github.com/nickschot/ember-mobile-pane) - ember-mobile-pane
- [ember-responsive](https://github.com/freshbooks/ember-responsive) - Easy responsive layouts with Ember

### Natural language processing
- [?](#) - ????.

### Network

- [?](#) - ????.

### Node.js management
- [?](#) - ????.

### Number

- [?](#) - ????.

### Parsing

- [?](#) - ????.

### Payments

- [ember-credit-card](https://github.com/esbanarango/ember-credit-card) - "make your credit card form dreamy in one line of code"

### Polyfills

- [ember-router-service-polyfill](https://github.com/rwjblue/ember-router-service-polyfill) - This addon provides a best effort polyfill for the ember-routing-router-service feature added in Ember 2.15.

 ### Process management
- [?](#) - ????

 ### PWA

- [ember-service-worker-asset-cache](https://github.com/DockYard/ember-service-worker-asset-cache)
- [ember-service-worker-cache-fallback](https://github.com/DockYard/ember-service-worker-cache-fallback)
- [ember-service-worker-cache-first](https://github.com/DockYard/ember-service-worker-cache-first)
- [ember-service-worker-index](https://github.com/DockYard/ember-service-worker-index)
- [ember-service-worker-prember](https://github.com/shipshapecode/ember-service-worker-prember)
- [ember-service-worker](https://github.com/DockYard/ember-service-worker) - A pluggable approach to Service Workers for Ember.js
- [ember-web-app](https://github.com/san650/ember-web-app) - This Ember addon helps you configure and manage the manifest.json and meta tags needed to create progressive web applications

### Query Params

- [ember-parachute](https://github.com/offirgolan/ember-parachute) - Improved Query Params for Ember
- [ember-href-to](https://github.com/intercom/ember-href-to) - A lightweight alternative to {{link-to}}

### Real-time

- [ember-cli-flash](https://github.com/poteto/ember-cli-flash) - Simple, highly configurable flash messages for ember-cli.

### Security

- [ember-can](https://github.com/minutebase/ember-can) - Simple [authorisation addon](http://ember-can.com) for Ember apps.

### SSR / Server Side Rendering

 - [ember-fastboot](https://github.com/ember-fastboot/ember-cli-fastboot) - Server-side rendering for Ember.js apps

### Static site generators & SEO

- [ember-meta](https://github.com/shipshapecode/ember-meta) - Setup meta for your Prember/Ember blog to support opengraph, microdata, Facebook, Twitter, Slack etc.
- [prember-rss-feed](https://github.com/shipshapecode/prember-rss-feed) - Ship RSS feeds for your Prember site
- [prember](https://github.com/ef4/prember) - Prerender Ember apps with Fastboot at build time.

### Streams

- [?](#) - ????.

### Styling

- [ember-cli-sass](https://github.com/aexmachina/ember-cli-sass) - Use node-sass to preprocess your ember-cli app's files, with support for sourceMaps and include paths

### Templating

- [?](#) - ????.

### Testing

- [ember-a11y-testing](https://github.com/ember-a11y/ember-a11y-testing) - A suite of accessibility tests that can be run within the Ember testing framework
- [ember-cli-code-coverage](https://github.com/kategengler/ember-cli-code-coverage) - Code coverage for ember apps using Istanbul
- [ember-cli-mirage](http://www.ember-cli-mirage.com/) - Build, test and demo your app using a [JSON API](http://jsonapi.org/)-compliant client-side server.
- [ember-cli-mocha](https://github.com/ember-cli/ember-cli-mocha) - Mocha and Chai tests for ember-cli applications
- [ember-cli-page-object](https://github.com/san650/ember-cli-page-object) - This ember-cli addon eases the construction of page objects on your acceptance and integration tests
- [ember-cli-yadda](https://github.com/albertjan/ember-cli-yadda) - Write cucumber specs for ember-cli applications
- [ember-exam](https://github.com/trentmwillis/ember-exam) - Run your tests with randomization, splitting, and parallelization for beautiful tests.
- [ember-percy](https://github.com/percy/ember-percy) - Ember addon for visual regression testing with Percy
- [ember-qunit](https://github.com/emberjs/ember-qunit) - QUnit test helpers for Ember
- [ember-test-selectors](https://github.com/simplabs/ember-test-selectors) - Enabling better element selectors in Ember.js tests
- [ember-test-setup](https://github.com/kellyselden/ember-test-setup) - Testing shorthands to reduce duplication

### Text

- [?](#) - ????

### TypeScript

- [ember-cli-typescript](https://github.com/typed-ember/ember-cli-typescript) - Use TypeScript in your Ember.js apps!
- [ember-typings](https://github.com/typed-ember/ember-typings) - Typescript type definitions for ember.js


### UI libs

- [ember-bootstrap](http://www.ember-bootstrap.com/) - Provides a collection of native Ember components that mimic the original Bootstrap plugins and components in an ember friendly way
- [ember-paper](https://github.com/miguelcobain/ember-paper) - The Ember approach to Material Design.
- [ember-radical](https://github.com/healthsparq/ember-radical) - Feather light, fully accessible DDAU component library for your Ember apps.
- [Nomad UI](https://github.com/hashicorp/nomad/tree/master/ui) - https://demo.nomadproject.io
- [Semantic-UI-Ember](https://github.com/Semantic-Org/Semantic-UI-Ember) - This is the official Ember library for the Semantic-UI modules.

### UI components

- [ember-burger-menu](https://github.com/offirgolan/ember-burger-menu) - An off-canvas sidebar component with a collection of animations and styles using CSS transitions.
- [ember-flatpickr](https://github.com/shipshapecode/ember-flatpickr) - An Ember addon that wraps the Flatpickr date picker.
- [ember-power-select](https://github.com/cibernox/ember-power-select) - The extensible select component built for ember.
- [ember-basic-dropdown](https://github.com/cibernox/ember-basic-dropdown) - The basic dropdown you ember app needs

### URL

- [?](#) - ????

### UX
- [ember-onbeforeunload](https://github.com/jasonmit/ember-onbeforeunload) - invoke logic when transitioning between routes or closing window


### VS Code addons

 - [ember-module-snippets](https://github.com/candidmetrics/ember-module-snippets) - Snippets to make importing Ember modules a snap in VSCode

### Web frameworks

- [?](#) - ????

### Webpack

- [glimmer-compiler-webpack-plugin](https://github.com/tomdale/glimmer-compiler-webpack-plugin)

### Weird

- [?](#) - ????

## Resources

- [?](#) - ????

### Articles

- [Top 10 Ember.js Development Companies](https://medium.com/@henryw1990/top-10-ember-js-development-companies-d07826a87f24)
- [16 Opensource EmberJS Projects to Learn From](https://www.icicletech.com/blog/16-opensource-emberjs-projects-to-learn-from)
- [5 Essential Ember Concepts You Must Understand](https://emberigniter.com/5-essential-ember-concepts/)
- [Adding AWS Amplify to an Ember.js Application](https://itnext.io/adding-aws-amplify-to-an-ember-js-application-72683167c476)
- [Adopting ember-concurrency or: How I Learned to Stop Worrying and Love the Task](https://engineering.linkedin.com/blog/2016/12/ember-concurrency--or--how-i-learned-to-stop-worrying-and-love-t)
- [An Interview with Tom Dale of Ember.js](https://javascriptreport.com/interview-with-tom-dale/)
- [Animations in Ember.js with liquid-fire](https://www.airpair.com/ember.js/posts/animations-in-emberjs-with-liquidfire)
- [Async or Swim: Replacing your Route models with Ember Concurrency Tasks](https://medium.com/@AveryBloom/async-or-swim-replacing-your-route-models-with-ember-concurrency-tasks-5a230252893a)
- [Awesome Ember Addons](https://www.codementor.io/gowiem/awesome-ember-addons-bwhiofit9)
- [Building a performant real-time web app with Ember Fastboot and Phoenix](https://medium.com/peep-stack/building-a-performant-web-app-with-ember-fastboot-and-phoenix-part-1-fa1241654308)
- [Creating Web Components with Glimmer](https://simplabs.com/blog/2017/08/28/creating-web-components-with-glimmer.html)
- [Debug Ember app with VSCode](https://medium.com/@minhdn/debug-ember-app-with-vscode-5f4fde511f9f)
- [Debugging Ember.js applications in Visual Studio Code](http://blog.firstiwaslike.com/debugging-ember-js-application-in-visual-studio-code/)
- [DEPLOYING WITH EMBER.JS: A STORY](https://blogs.library.ucsf.edu/ckm/2017/09/06/deploying-with-ember-js-a-story/)
- [Do not confuse environment for deploy target](https://lolma.us/en/blog/class-and-attribute-bindings)
- [Ember and Yarn Workspaces](https://medium.com/square-corner-blog/ember-and-yarn-workspaces-fca69dc5d44a)
- [Ember Best Practices: Computed Properties with Dynamic Dependent Keys](https://dockyard.com/blog/2015/10/23/ember-best-practices-dynamic-dependent-keys-for-computed-properties)
- [Ember CLI Addon Docs: Shared Documentation for the Ember Ecosystem](https://medium.com/build-addepar/ember-cli-addon-docs-shared-documentation-for-the-ember-ecosystem-6f29aa0cee87)
- [Ember Inspector - The Journey so Far](https://shipshape.io/blog/ember-inspector-the-journey-so-far/)
- [Ember on Medium](https://medium.com/front-end-hacking/tagged/ember)
- [Ember Timer Leaks: The Bad Apples in Your Test Infrastructure](https://engineering.linkedin.com/blog/2018/01/ember-timer-leaks)
- [EmberCamp Module Unification Update](https://madhatted.com/2017/7/12/embercamp-module-unification-update)
- [EmberJS-Router Wildcard/Globbing Routes](https://www.tutorialspoint.com/emberjs/route_glbng_rut.htm)
- [ES Classes in Ember.js](https://medium.com/build-addepar/es-classes-in-ember-js-63e948e9d78e)
- [Extracting Metadata from a Custom API with Ember Data](https://thejsguy.com/2018/04/06/extracting-metadata-from-a-custom-api-with-ember-data.html)
- [Set your Ember.js project up to use TypeScript](http://www.chriskrycho.com/2017/typing-your-ember-part-1.html)
- [Skeleton Screen Loading in Ember.js](https://emberway.io/skeleton-screen-loading-in-ember-js-2f7ac2384d63)
- [Static Blogs with Prember and Markdown](https://shipshape.io/blog/static-blogs-with-prember-and-markdown/)
- [The Glimmer Binary Experience](https://engineering.linkedin.com/blog/2017/12/the-glimmer-binary-experience)
- [The simplest possible Ember Data CRUD Tutorial](https://medium.com/ember-ish/the-simplest-possible-ember-data-crud-16eacee33ae6)
- [Tom Dale on Ember and JavaScript Frameworks](https://www.infoq.com/interviews/tom-dale-ember) - Y 2013
- [Using ember-freestyle as a component playground](https://simplabs.com/blog/2018/01/24/ember-freestyle.html)
- [Using npm libraries in Ember CLI](https://simplabs.com/blog/2017/02/13/npm-libs-in-ember-cli.html)
- [We have a new EmberJS front-end!](https://medium.com/@appaloosastore/we-have-a-new-emberjs-front-end-c7246e76cdbd)
- [What you didn't know about passing dynamic classname and attribute bidings from parent template](https://lolma.us/en/blog/class-and-attribute-bindings)
- [You can only change what you can measure](https://blog.201-created.com/you-can-only-change-what-you-can-measure-6be8826503a7)
- [Secrets of the Ember-CLI server: Express middleware with Ember-CLI](https://blog.201-created.com/secrets-of-the-ember-cli-server-bde80bb546dd)
- [How I added whitelabel theming to my Ember app](https://medium.com/@simeonberns/how-i-added-whitelabel-theming-to-my-ember-app-97bfca9e263a)
- [Customising Ember Power Select](https://medium.com/life-at-kayako/customising-ember-power-select-3d570c7c4c0c)

- [A list of EmberJS2018 blog posts and ideas](https://github.com/zinyando/emberjs2018-posts)

- [A collection of links that summarize EmberConf 2017](https://github.com/poteto/emberconf-2017)
- [A collection of links that summarize EmberConf 2016](https://github.com/poteto/emberconf-2016)
- [A collection of links that summarize EmberConf 2015](https://github.com/poteto/emberconf-2015)

### Best-practices 

- [ember-best-practices](https://github.com/ember-best-practices)

### Blogs

- [201-created.com](https://blog.201-created.com/)
- [airpair.com](https://www.airpair.com/ember.js)
- [alexdiliberto.com](https://alexdiliberto.com/)
- [balinterdi.com](https://balinterdi.com/blog/) - Balint Erdi blog.
- [codeburst.io](https://codeburst.io/tagged/emberjs)
- [codementor.io](https://www.codementor.io/community/topic/emberjs)
- [dockyard.com](https://dockyard.com/blog/categories/ember)
- [emberigniter.com](https://emberigniter.com/articles/)
- [engineering.linkedin.com](https://engineering.linkedin.com/blog/topic/ember)
- [hackernoon.com](https://hackernoon.com/tagged/ember)
- [lolma.us](https://lolma.us/en/blog)
- [madhatted.com](https://madhatted.com/)
- [medium.com/ember-ish](https://medium.com/ember-ish) - Ember.js essentials for beginners and intermediate devs
- [netguru.co](https://www.netguru.co/blog/topic/ember-js)
- [programwitherik.com](https://www.programwitherik.com) - Ember.js tuts
- [rwjblue.com](http://rwjblue.com/)
- [shipshape.io](https://shipshape.io/blog/)
- [simplabs.com](https://simplabs.com/blog/)
- [thejsguy.com](https://thejsguy.com/)

### Books

- [A deep dive into the Ember JS runloop](https://github.com/eoinkelly/ember-runloop-handbook)
- [Deliver Audacious Web Apps with Ember 2](https://pragprog.com/book/mwjsember/deliver-audacious-web-apps-with-ember-2) by Matthew White
- [Developing an Ember.js Edge](https://gumroad.com/l/xlsx)
- [Ember Data in the Wild](https://leanpub.com/emberdatainthewild)
- [ember-cli 101](https://leanpub.com/ember-cli-101) by Adolfo Builes
- [Ember for Artisans](https://leanpub.com/emberforartisans) - Creating Single Page Apps backed by Laravel
- [Ember.js in Action](http://manning.com/skeie/) by Joachim Haagen Skeie
- [Professor Frisby's Mostly adequate guide to Functional Programming](https://drboolean.gitbooks.io/mostly-adequate-guide-old/)
- [Rock and Roll with Ember.js](http://rockandrollwithemberjs.com/)

### Cheatsheets

- [API](https://emberjs.com/api/)
- [Glimmer](https://glimmerjs.com/)
- [guides](https://guides.emberjs.com/)

### Codemods
- [ember-mocha-codemods](https://github.com/Turbo87/ember-mocha-codemods) - Codemod scripts for ember-mocha
- [ember-module-migrator](https://github.com/rwjblue/ember-module-migrator) - Automated migration for new Ember application layout.
- [ember-qunit-codemod](https://github.com/rwjblue/ember-qunit-codemod) - This codemod is intended to automatically convert your projects from the older moduleFor* syntax of ember-qunit@2 to the newer syntax.
- [ember-test-helpers-codemod](https://github.com/simonihmig/ember-test-helpers-codemod) - Codemod to transform your Ember tests to use @ember/test-helpers
- [es5-getter-ember-codemod](https://github.com/rondale-sc/es5-getter-ember-codemod) - This codemod is intended to automatically convert your usage of get, and getProperties to use traditional object dot notation.
- [qunit-dom-codemod](https://github.com/simplabs/qunit-dom-codemod) - Basic codemod to automatically convert your assertions to qunit-dom assertions.
- [test-selectors-codemod](https://github.com/lorcan/test-selectors-codemod) - A codemode for fixing the ember-test-selectors testSelector helper deprecation.

### Community

- [Forum](http://discuss.emberjs.com/)
- [GitHub issues](https://github.com/emberjs/ember.js/issues)
- [Reddit](https://www.reddit.com/r/emberjs/)
- [Slack](https://embercommunity.slack.com)
- [StackOverflow](http://stackoverflow.com/questions/tagged/ember.js)
- [Telegram](https://t.me/ember_js)

### Courses

- [Emberschool.com](https://www.emberschool.com/)
- [Frontend Masters: Advanced Ember 2.x - Mike North](https://frontendmasters.com/courses/advanced-ember-2/)
- [Frontend Masters: Ember 2.x - Mike North](https://frontendmasters.com/courses/ember-2/)

### Discovery

- [emberaddons](https://www.emberaddons.com/) - Ember Addons.
- [emberobserver](https://emberobserver.com/) - Ember Observer.

### Examples

- [API Docs](https://github.com/ember-learn/ember-api-docs) - This application was built to display our versioned API docs.
- [guides-app](https://github.com/ember-learn/guides-app) - Replacement for emberjs/guides and the Ember Guides
- [Builds](https://github.com/ember-learn/builds) - This is the application that the Ember.js team built to display our various release channels.
- [HospitalRun](https://github.com/HospitalRun/hospitalrun-frontend) - Ember front end for HospitalRun [hospitalrun.io](http://hospitalrun.io/)
- [Rancher](https://github.com/rancher/ui) - [Rancher](http://rancher.com) is enterprise management for Kubernetes.
- [Super Rentals](https://github.com/ember-learn/super-rentals) - Super Rentals is a good starter project to get acclimated to the Ember.js way of doing things
- [Travis CI](https://github.com/travis-ci/travis-web) - The Ember web client for [Travis CI](https://travis-ci.org/)
- [Vault](https://github.com/hashicorp/vault/tree/master/ui/app) - A Tool for Managing Secrets (Hashicorp)
- [ember-osf-web](https://github.com/CenterForOpenScience/ember-osf-web) - Ember front-end for the Open Science Framework

### Gists

- [@listochkin/Ember.js Video Collection (Ru/En)](https://gist.github.com/listochkin/87e47cdbf986fb2e9905)
- [@rwjblue/ember_examples](https://gist.github.com/rwjblue/8816372)
- [@wycats/A small sampling of external projects initially built for Ember use but designed to be used standalone](https://gist.github.com/wycats/b58d56e5a47db4128a0a)
- [Ember publishing tools](https://gist.github.com/anulman/1e1da1d38178e7242d4701638bb29391)
- [ember-cli es6 imports](https://gist.github.com/lifeart/949d867ba5f5455f8d955d9c9dc3610d)
- [Ember-cli Windows speedup](https://gist.github.com/lifeart/f436306a92f62610d65caaa699c17065)

### Miscellaneous

- [builtwithember](http://builtwithember.io/) - Apps powered by Ember.js.
- [emberwatch](https://github.com/emberwatch) - The community hub for Ember.js content

### Newsletters

- [Ember Weekly](http://www.emberweekly.com/) - The latest Ember.js news, tips, and code delivered directly to your inbox.
- [Official Ember Blog](https://emberjs.com/blog/) - Big announcements like new Ember.js version release notes or State of the Union information.
- [statusboard](https://emberjs.com/statusboard/) - STATUS BOARD
- [The Ember Times](https://the-emberjs-times.ongoodbits.com/) - Updates from the Ember.js Learning Team.

### Podcasts

- [embermap](https://embermap.com/topics/the-embermap-podcast)
- [emberweekend](https://emberweekend.com/episodes)

### Screencasts

- [BuildLab: EmberJS Screencasts for the determined.](https://www.youtube.com/channel/UC1ssGKlQh87Ubyuv1lEiY0g)
- [Ember 101](http://ember101.com/) - Short introductory screencasts for Ember.
- [Ember Screencasts](https://www.emberscreencasts.com/) - Weekly Screencasts for the Busy Developer.
- [EmberCasts](http://www.embercasts.com/) - Currently on hiatus whilst the author works on the next version of Handlebars.
- [EmberWatch - Screencasts](http://emberwatch.com/screencasts.html) - A collection of Ember screencasts.

### Slides

- [Building Realtime Apps with Ember.js and WebSockets](https://www.slideshare.net/BenLimmer/building-realtime-apps-with-emberjs-and-websockets) - Ben Limmer
- [Deploying a Location-Aware Ember Application](https://www.slideshare.net/BenLimmer/deploying-a-locationaware-ember-application) -  Ben Limmer
- [Developing Desktop Apps with Electron & Ember.js - FITC WebU2017](https://www.slideshare.net/anulman/developing-desktop-apps-with-electron-emberjs-fitc-webu2017) - Aidan Nulman
- [Developing Desktop Apps with Electron & Ember.js](https://www.slideshare.net/fitc_slideshare/developing-desktop-apps-with-electron-emberjs)
- [Ember addons, served three ways](https://www.slideshare.net/mikelnorth/ember-addons-served-three-ways) - Mike North
- [Ember At Scale](https://www.slideshare.net/chadhietala/ember-at-scale) - Chad Hietala, LinkedIn
- [EmberConf 2015 – Ambitious UX for Ambitious Apps](https://www.slideshare.net/sugarpirate/emberconf-2015-ambitious-ux-for-ambitious-apps) - Lauren Elizabeth Tan
- [EmberConf 2016 – Idiomatic Ember: Finding the Sweet Spot of Performance & Productivity](https://www.slideshare.net/sugarpirate/emberconf-2016-idiomatic-ember-finding-the-sweet-spot-of-performance-productivity) - Lauren Elizabeth Tan
- [Fun with Ember 2.x Features](https://www.slideshare.net/BenLimmer/fun-with-ember-2x-features) - Ben Limmer
- [How do I Even Web App](https://www.slideshare.net/lydiaguarino/how-do-i-even-web-app) - An introduction to web programming with Ember CLI by Lydia Guarino
- [Rapid prototyping and easy testing with ember cli mirage](https://www.slideshare.net/KrzysztofBiaek1/rapid-prototyping-and-easy-testing-with-ember-cli-mirage) -  Krzysztof Bialek
- [Start Me Up - Building an MVP with EmberJS, Firebase and Material Design](https://www.slideshare.net/PickNBook/start-me-up-building-an-mvp-with-emberjs-firebase-and-material-design) - Brendan O'Hara
- [Upgrading Ember.js Apps](https://www.slideshare.net/BenLimmer/upgrading-emberjs-apps) - Ben Limmer

 ### Styleguides

- [ember-styleguide](https://github.com/ember-learn/ember-styleguide)
- [Softlayer Ember.js](https://github.com/softlayer/ember-style-guide)
- [Netguru Ember.js](https://github.com/netguru/ember-styleguide)
- [DockYard Ember.js](https://github.com/DockYard/styleguides/blob/master/engineering/ember.md)
- [JavaScript Style Guide](https://github.com/DockYard/styleguides/blob/master/engineering/javascript.md)

### Tools

- [Ember Data Sails Adapter](https://github.com/bmac/ember-data-sails-adapter) - An Ember data adaptor for the Sails.js sockets.
- [Ember Data WordPress Adapter](https://github.com/HeyHumanAgency/Ember-Data-WordPress) - An Ember data adapter for the WordPress JSON API.
- [Ember Gist](http://ember-gist.joostdvrs.com/) - Demo Ember CLI'eque apps using Github Gist.
- [Ember Inspector](https://github.com/emberjs/ember-inspector) - Adds an Ember tab to Chrome or Firefox Developer Tools that allows you to inspect Ember objects in your application. - Officially maintained.
- [Ember Perf](https://github.com/mike-north/ember-perf) - Measure user-percieved performance data in your ember.js app
- [Ember Twiddle](https://ember-twiddle.com/) - An Ember Twiddle for multiples files which lets you save your work in Github.
- [ember-cli-diff](http://www.ember-cli-diff.org/) - A simple tool to see differences between new ember apps.
- [ember-cli](https://ember-cli.com/) - The command line interface for ambitious web applications.
- [ember-data-model-maker](https://andycrum.github.io/ember-data-model-maker/) - UI to make ember-data models & payload examples
- [Glimmer Playground](https://try.glimmerjs.com/) - An Glimmer.js playground.
- [gulp-ember-handlebars](https://github.com/fuseelements/gulp-ember-handlebars) - Compiles Handlebars templates to JS ready for Ember.
- [remote-inspector](https://github.com/joostdevries/ember-cli-remote-inspector) - Lets you inspect apps running on different devices/browsers over the network using websockets.

### Tutorials

- [Discover Ember 2](https://www.ludu.co/course/ember) - Learn how to build a Twitter clone from scratch
- [Ember Components: A Deep Dive](http://code.tutsplus.com/tutorials/ember-components-a-deep-dive--net-35551) - A closer look at using Ember Components.
- [Ember runloop handbook](https://github.com/eoinkelly/ember-runloop-handbook) - A deep dive into the Ember JS runloop.
- [Ember with Phoenix (AKA The PEEP Stack)](https://medium.com/peep-stack) - Developing an Ember front-end alongside a [JSON API](http://jsonapi.org/)-compliant [Phoenix](http://www.phoenixframework.org/) backend.
- [Getting into Ember.js](http://code.tutsplus.com/tutorials/getting-into-emberjs--net-30709) - A five part introductory course to Ember.
- [Getting Started with Ember.js using Ember CLI](http://thetechcofounder.com/getting-started-with-ember-js-using-ember-cli/) - Building a Todo app with Ember CLI.
- [yoember.com/](http://yoember.com/) - Ember.js Tutorial - From beginner to advance.

### Twitter

- [Adolfo Builes](https://twitter.com/abuiles)
- [Alex Matchneer](https://twitter.com/machty)
- [Alex Navasardyan](https://twitter.com/twokul)
- [alexspeller](https://twitter.com/alexspeller)
- [Brian Cardarella](https://twitter.com/bcardarella)
- [Ember Talk](https://twitter.com/emberjstalk)
- [Ember Watch](https://twitter.com/EmberWatch)
- [EmberSherpa](https://twitter.com/EmberSherpa)
- [Erik Bryn](https://twitter.com/ebryn)
- [Gavin Joyce](https://twitter.com/gavinjoyce)
- [Jamie White](https://twitter.com/jgwhite)
- [Jo Liss](https://twitter.com/jo_liss)
- [mixonic](https://twitter.com/mixonic)
- [Robin Ward](https://twitter.com/eviltrout)
- [Stefan Penner](https://twitter.com/stefanpenner)
- [Tom Dale](https://twitter.com/tomdale)
- [Trek Glowacki](https://twitter.com/trek)

### Videos

- [Global Ember Meetup](https://vimeo.com/globalembermeetup)
- [Ember @ Netflix](https://pusher.com/sessions/meetup/emberfest/ember-netflix)
- [Ember Engines at Scale](https://pusher.com/sessions/meetup/ember-london/ember-engines-at-scale)
- [Ember Test Recorder](https://pusher.com/sessions/meetup/ember-london/ember-test-recorder)
- [ember-content-placeholders](https://pusher.com/sessions/meetup/emberfest/ember-content-placeholders)
- [Ember.JS in the Year 2020](https://pusher.com/sessions/meetup/emberfest/emberjs-in-the-year-2020)
- [EmberConf 2014](https://www.youtube.com/playlist?list=PLE7tQUdRKcyaOyfBnAndJxQ9PNVmKva0d) - Videos of the sessions from EmberConf 2014.
- [EmberConf 2015](https://www.youtube.com/playlist?list=PLE7tQUdRKcyacwiUPs0CjPYt6tJub4xXU) - Videos of the sessions from EmberConf 2015.
- [EmberConf 2016](https://www.youtube.com/playlist?list=PL4eq2DPpyBblc8aQAd516-jGMdAhEeUiW) - Videos of the sessions from EmberConf 2016.
- [EmberConf 2017](https://www.youtube.com/playlist?list=PL4eq2DPpyBbna_5fLPqOqensqSZpGf-hT) - Videos of the sessions from EmberConf 2017.
- [EmberConf 2018](https://www.youtube.com/watch?v=NhtpXs0ZtUc&list=PL4eq2DPpyBbnjD5iLp55as9OvIdEDI_Kt)  - Videos of the sessions from EmberConf 2018.
- [ReactiveConf 2017 - Tom Dale: Secrets of the Glimmer VM](https://www.youtube.com/watch?v=nXCSloXZ-wc)
- [ReactiveConf 2017](https://youtu.be/62xd25kEZ3o?t=27618)
- [Tim Thomas - Using Ember.js to build Electron Apps](https://www.youtube.com/watch?v=ER1V_u0N7u4)
- [Tom Dale on Static Analysis, Upstreaming Glimmer, and Ember in 2018](https://embermap.com/topics/the-embermap-podcast/tom-dale-on-static-analysis-upstreaming-glimmer-and-ember-in-2018)
- [Tom Dale Talks EmberJS](https://www.slideshare.net/LinkedInPulse/tom-dale-ember-javascript-emberjs-linkedin)
- [Using TypeScript in Ember](https://pusher.com/sessions/meetup/ember-london/using-typescript-in-ember)
- [Web App Performance & Ember.js](https://www.youtube.com/watch?v=BelKk7dvA1A) - Web App Performance & Ember.js
- [Why Ember CLI uses Broccoli](https://embermap.com/topics/intro-to-broccoli/why-ember-uses-broccoli)
- [Developing ember apps on glitch.com](https://www.youtube.com/watch?v=uhXA6ECaknw)
- [Chris Krycho: TypeScript and Ember js - Why and How?](https://www.youtube.com/watch?v=fFzxbBrvytU)
- [Isaac Lee: Use D3 with Ember](https://www.youtube.com/watch?v=vD7H9O--tu4)

### YouTube channels

- [Amsterdam Ember.js](https://www.youtube.com/channel/UCx9sVlEZLOKxw8OGCtoqULw)
- [Boston Ember](https://www.youtube.com/channel/UCp_L_YjmXTKR4Q2fg1XahsA)
- [Denver Ember](https://www.youtube.com/channel/UCsy4OVL_kNXsxr0a5LNKWpw)
- [Ember Videos](https://www.youtube.com/channel/UCMmzJ82sCmooDdtzVY8FxEA)
- [Ember.js Dublin](https://www.youtube.com/channel/UCQeD0i9ltSV1aOfX6FGeiOA)
- [EmberATX](https://www.youtube.com/channel/UCl7qY85b7KLJV3xnn1Xh_Cw)
- [EmberJSSeattleMeetup](https://www.youtube.com/channel/UC_EzRy1fCQPRPOD-uqk-E5w)
- [EmberSchool](https://www.youtube.com/channel/UCntNIA2acwPDIY77bX2uLmw)
- [EmberSherpa](https://www.youtube.com/user/EmberSherpa/videos)
- [Silicon Valley Ember.js meetup](https://www.youtube.com/channel/UCi12gVD9jIDwJLVTNnKvhlw)
- [So Ember 2017](https://www.youtube.com/watch?v=UpUtVGW43hY&list=PLXOJZupxSq204IxtG80UfIW-gU0IxAScY)
- [Wicked Good Ember 2016](https://www.youtube.com/playlist?list=PLXOJZupxSq22zfW2KVnXFgLbu--DA7q0G)
- [May I ask a Question](https://www.youtube.com/channel/UCyErLHzPqLAkL1F-SivFDcA)
