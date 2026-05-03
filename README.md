# Awesome FP JS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 461,711 | 🐛 70 | 📅 2026-04-19 with stars

This is a curated list of awesome [functional programming](https://en.wikipedia.org/wiki/Functional_programming) code and learning resources for JavaScript. As a multi-paradigm programming language, JavaScript can be written in many styles. With these resources we want to help you to make better use of JavaScript’s support for writing programs in a *functional* way.

Functional programming is a [style of programming](https://wiki.haskell.org/Functional_programming) which models computations as the evaluation of expressions. Contrast this  with imperative programming where programs are composed of statements which change global state when executed. Functional programming typically avoids using mutable state and favors *side-effect free* functions and *immutable* data instead. This encourages writing composable and declarative programs that are easy to reason about.

##### Table of Contents

* [Libraries](#libraries)
  * [Data Structures](#data-structures)
  * [Algebraic Data Types](#algebraic-data-types)
  * [Lenses](#lenses)
* [Functional Languages that Compile to JavaScript](#functional-languages-that-compile-to-javascript)
* [Programming Tools](#programming-tools)
* [Resources](#resources)
  * [Books](#books)
  * [Articles](#articles)
  * [Videos](#videos)
  * [Examples and Exercises](#examples-and-exercises)
* [Community](#community)
* [Contribution](#contribution)

##### Tags

These may be appended to entries.  Each should be preceded by a "+" or "-" to indicate presence or absence of the tag's meaning.  "-" tags should only be included when they are likely to help someone filter libraries for their needs.  For instance, `-TS` tags are probably useful for Typescript users screening for types, but `-CT` tags would be less likely to be helpful to anyone.

* **CT**.  Category Theory.  This library appears to be inspired by Haskell, Scala, or another functional language's library with a grounding in Category Theory.
* **TS**.  Typescript.  This library has typescript types.

## Libraries

* [lodash/fp](https://github.com/lodash/lodash/wiki/FP-Guide) ⭐ 61,261 | 🐛 141 | 🌐 JavaScript | 📅 2026-04-22 – An instance of [Lodash](https://github.com/lodash/lodash) ⭐ 61,261 | 🐛 141 | 🌐 JavaScript | 📅 2026-04-22 with its methods wrapped to produce immutable, auto-curried, iteratee-first, data-last methods. +TS.
* [Ramda](https://github.com/ramda/ramda) ⭐ 24,082 | 🐛 146 | 🌐 JavaScript | 📅 2026-01-22 – A practical functional library for JavaScript that is designed specifically for a functional programming style. A style that makes it easy to create functional pipelines and never mutates user data. +TS.
* [ts-pattern](https://github.com/gvergnaud/ts-pattern) ⭐ 14,967 | 🐛 67 | 🌐 TypeScript | 📅 2026-04-24 - The exhaustive Pattern Matching library for TypeScript, with smart type inference. Pattern Matching is a code-branching technique coming from FP languages.
* [effect-ts](https://github.com/Effect-TS/core) ⭐ 14,019 | 🐛 525 | 🌐 TypeScript | 📅 2026-04-23 – A Fully-fledged functional effect system for typescript with a rich standard library. +TS
* [most](https://github.com/cujojs/most) ⭐ 3,496 | 🐛 50 | 🌐 JavaScript | 📅 2022-12-06 – Ultra-high performance reactive programming to help you compose asynchronous operations on streams of values and events without many of the hazards of side effects and mutable shared state.
* [Rambda](https://github.com/selfrefactor/rambda) ⭐ 1,752 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-25 - A faster alternative to Ramda in under 10kB.
* [js-joda](https://github.com/js-joda/js-joda) ⭐ 1,658 | 🐛 15 | 🌐 JavaScript | 📅 2026-04-15 – An immutable date and time library that provides a simple, domain-driven and clean API based on the ISO8601 calendar.
* [101](https://github.com/tjmehta/101) ⭐ 1,547 | 🐛 21 | 🌐 JavaScript | 📅 2022-01-06 – A modern and modular JavaScript utility library made to work well with vanilla JavaScript methods.  -TS
* [true-myth](https://github.com/true-myth/true-myth) ⭐ 1,335 | 🐛 14 | 🌐 TypeScript | 📅 2026-04-28 A library for safe, idiomatic null and error handling in TypeScript, with `Maybe` and `Result` types, supporting both a functional style and a more traditional method-call style
* [fxts](https://github.com/marpple/FxTS) ⭐ 1,161 | 🐛 9 | 🌐 TypeScript | 📅 2026-03-27 - Lazy evaluation and concurrency. +TS
* [futil-js](https://github.com/smartprocure/futil-js) ⭐ 1,045 | 🐛 33 | 🌐 JavaScript | 📅 2024-05-02 - A collection of functional utilities that could conceivably be part of a library like lodash/fp, but for some reason or other are not.
* [1-liners](https://github.com/1-liners/1-liners) ⭐ 801 | 🐛 28 | 🌐 JavaScript | 📅 2023-04-16 – Functional tools that couldn’t be simpler. A dead simple functional utility belt, hand-crafted with love and attention.  -TS.
* [Ramda Adjunct](https://github.com/char0n/ramda-adjunct) ⭐ 685 | 🐛 89 | 🌐 JavaScript | 📅 2026-04-23 is a community-maintained extension of Ramda.
* [funfix](https://github.com/funfix/funfix) ⚠️ Archived – Funfix is a library of type classes and data types for Functional Programming in JavaScript, TypeScript and Flow.  +CT, +TS.
* [Ferrum](https://github.com/adobe/ferrum) ⚠️ Archived – Iterator library with support for objects as iterables, lazy evaulation and`pipe()`; implements Traits (from Rust)/Type Classes (from Haskell) in JS. -TS.
* [FPO.js](https://github.com/getify/fpo) ⚠️ Archived – FP library for JavaScript by Kyle Simpson (aka getify). Supports named-argument style methods.
* [fun-task](https://github.com/rpominov/fun-task) ⭐ 374 | 🐛 14 | 🌐 JavaScript | 📅 2022-05-31 – An abstraction for managing asynchronous code in JS. Tasks are similar to Promises with the key difference that Tasks can represent a computation while Promises can represent only the results of a computation. Ships with Flow type definitions.
* [lfi](https://github.com/TomerAberbach/lfi) ⭐ 349 | 🐛 4 | 🌐 TypeScript | 📅 2025-12-16 - A Lazy Functional Iteration Library Supporting Sync, Async, and Concurrent Iteration.
* [Verticalize](https://github.com/laurentpayot/verticalize) ⭐ 301 | 🐛 0 | 🌐 JavaScript | 📅 2024-05-30 - Super lightweight function that looks and behaves like a pipe operator.
* [rubico](https://github.com/a-synchronous/rubico) ⭐ 283 | 🐛 43 | 🌐 JavaScript | 📅 2026-05-02 - 🏞 \[a]synchronous functional syntax
* [react-on-lambda](https://github.com/sultan99/react-on-lambda) ⭐ 265 | 🐛 3 | 🌐 JavaScript | 📅 2024-05-08 - Replace JSX in React with functions (currying, compositions and etc).
* [pareto-js](https://github.com/concretesolutions/pareto.js/) ⭐ 260 | 🐛 2 | 🌐 TypeScript | 📅 2020-10-19 - An extremely small, intuitive and fast functional utility library for JavaScript -TS.
* [funcy](https://github.com/bramstein/funcy) ⭐ 249 | 🐛 1 | 🌐 JavaScript | 📅 2018-05-19 – An experiment in adding functional pattern matching to JavaScript. *Experimental*  :triangular\_flag\_on\_post:
* [functional.js](https://github.com/functionaljs/functional-js) ⭐ 224 | 🐛 0 | 🌐 TypeScript | 📅 2026-01-27 – A lightweight functional JavaScript library that facilitates currying and point-free / tacit programming.
* [Rambdax](https://github.com/selfrefactor/rambdax) ⭐ 223 | 🐛 0 | 🌐 JavaScript | 📅 2025-06-26 - Extended version of Rambda
* [iter-tools](https://github.com/iter-tools/iter-tools) ⭐ 186 | 🐛 16 | 🌐 JavaScript | 📅 2025-06-02 - a rich toolset for working with iterables, both sync and async. +TS.
* [Ramda-extension](https://github.com/tommmyy/ramda-extension) ⭐ 167 | 🐛 33 | 🌐 HTML | 📅 2025-04-01 is set of utility point-free functions composed only from Ramda functions.
* [TGrid](https://github.com/samchon/tgrid) ⭐ 166 | 🐛 4 | 🌐 TypeScript | 📅 2025-12-18 - Grid Computing Framework, Network & Thread extension of [TSTL](https://github.com/samchon/tstl) ⭐ 628 | 🐛 3 | 🌐 TypeScript | 📅 2025-08-13, supporting RFC (Remote Function Call). +TS.
* [Javascript Parser Combinator](https://github.com/d-plaindoux/parsec) ⭐ 150 | 🐛 13 | 🌐 JavaScript | 📅 2026-03-01 – Javascript parser combinator implementation inspired by the Haskell's Parsec
* [lambdajs](https://github.com/loop-recur/lambdajs) ⭐ 142 | 🐛 7 | 🌐 JavaScript | 📅 2014-07-09 – The full ECMAScript API done a functional way.
* [omg-curry](https://github.com/Debdut/omg-curry) ⭐ 136 | 🐛 1 | 🌐 JavaScript | 📅 2020-12-30 - Comprehensive Curry Library with Operator Curry, Curry from functions, Decurry and Infifnite Curries.
* [date-fp](https://github.com/cullophid/date-fp) ⭐ 119 | 🐛 3 | 🌐 JavaScript | 📅 2019-12-11 – A functional utility library for working with JavaScript dates. All functions in date-fp are pure, autocurried and will not mutate the date objects they are applied to.
* [barely-functional](https://github.com/cullophid/barely-functional) ⭐ 106 | 🐛 0 | 🌐 JavaScript | 📅 2017-10-26 – A tiny (2.7kb) functional programming library using native ES5/6 operations. -TS.
* [preludejs](https://github.com/alanrsoares/prelude-js) ⭐ 100 | 🐛 4 | 🌐 JavaScript | 📅 2023-08-03 - Hardcore Functional Programming for JavaScript. -TS.
* [Ditox.js](https://github.com/mnasyrov/ditox) ⭐ 100 | 🐛 1 | 🌐 TypeScript | 📅 2026-02-23 - Powerful dependency injection container for building modular apps. +TS
* [curry](https://github.com/thisables/curry) ⭐ 86 | 🐛 4 | 🌐 JavaScript | 📅 2019-11-07 – Curry your functions using function bind syntax.
* [fp-filters](https://github.com/Oaxoa/fp-filters) ⭐ 86 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-11 - A curated collection of 130+ common-use filter functions.
  Written in a functional programming style. Lightweight direct imports. Supports ES modules and CommonJS. 100% Unit
  tested. +TS
* [qio](https://github.com/tusharmath/qio) ⭐ 74 | 🐛 8 | 🌐 TypeScript | 📅 2022-08-16 – A type-safe, functional, performant, lawful, composable data structure that solves practical problems of effect-full code in node and browser. +TS
* [pico-lambda](https://github.com/trainyard/pico-lambda) ⭐ 71 | 🐛 1 | 🌐 JavaScript | 📅 2017-11-21 - Arrays, Strings and things the functional way. A 640b functional library based on native methods. -TS.
* [hyogwa](https://github.com/ENvironmentSet/hyogwa) ⭐ 62 | 🐛 10 | 🌐 TypeScript | 📅 2024-08-22 - Natural 🌿 effect system that fits TypeScript; Write codes as you write **plain typescript code**.
* [compose-function](https://github.com/stoeffel/compose-function) ⭐ 56 | 🐛 2 | 🌐 JavaScript | 📅 2019-11-07 – Compose a new function from smaller functions.
* [zen-signals](https://github.com/joaomilho/zen-signals) ⭐ 53 | 🐛 8 | 🌐 TypeScript | 📅 2023-01-06 – ☯ The simplest signal library possible
* [functionize](https://github.com/paldepind/functionize) ⭐ 50 | 🐛 0 | 🌐 JavaScript | 📅 2015-03-31 – A collection of functions which aid in making non-functional libraries functional.
* [bluebird-promisell](https://github.com/zhangchiqing/bluebird-promisell) ⭐ 44 | 🐛 3 | 🌐 JavaScript | 📅 2017-12-19 - A practical functional programming library for promises.
* [fpEs](https://github.com/TeaEntityLab/fpEs/) ⭐ 43 | 🐛 5 | 🌐 JavaScript | 📅 2023-10-12 - A small library provides simple usages of basic FP & pattern-matching/sumtype & MonadIO/Rx & Optional for Javascript. -TS.
* [\_part\_](https://github.com/AutoSponge/_part_) ⭐ 42 | 🐛 0 | 🌐 JavaScript | 📅 2014-02-11 – A micro library that encourages functional programming by making native methods available as partially applied functions.
* [RxEffects](https://github.com/mnasyrov/rx-effects) ⭐ 37 | 🐛 0 | 🌐 TypeScript | 📅 2024-07-12 - Reactive state and effect management with RxJS. +TS
* [tinyeffect](https://github.com/Snowflyt/tinyeffect) ⭐ 36 | 🐛 0 | 🌐 TypeScript | 📅 2025-03-30 - A tiny TypeScript library for handling side effects in a unified way using algebraic effects. +TS
* [trifl](https://github.com/algesten/trifl) ⭐ 34 | 🐛 4 | 🌐 JavaScript | 📅 2017-03-19 – A functional user interface library with unidirectional dataflow and a virtual dom.
* [PureEval](https://github.com/PureEval/PureEval) ⭐ 34 | 🐛 0 | 🌐 JavaScript | 📅 2024-02-27 - A powerful JavaScript functional programming toolset, including utility functions and abstract data structures.
* [rocket-pipes](https://github.com/darky/rocket-pipes) ⭐ 26 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-26 - Powerful pipes, that chain Promise and ADT like Maybe or Either from popular FP libraries. +TS
* [fnuc](https://github.com/algesten/fnuc) ⭐ 16 | 🐛 1 | 🌐 CoffeeScript | 📅 2015-12-05 – A functional library for CoffeeScript (and JavaScript) to facilitate functional composition and higher order functions.
* [fn-curry](https://github.com/thunklife/fn-curry) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2014-01-08 – A simple function to curry a function.
* [ts-fp-di](https://github.com/darky/ts-fp-di) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2025-05-23 - Tiny TypeScript functional dependency injection, based on Node.js AsyncLocalStorage. +TS
* [ts-multimethod](https://github.com/darky/ts-multimethod) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-20 - TypeScript multimethods inspired by Clojure multimethods. +TS
* [context-fp](https://github.com/darky/context-fp) ⚠️ Archived - Microscopic functional programming context aka dependency injection. +TS
* [klubok](https://github.com/darky/klubok) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-22 - Pipes with easy mocking, intended for huge amount of unit tests. +TS
* [Folktale](http://folktale.origamitower.com/) – A standard library for functional programming in JavaScript. Typescript support expected mid-2020.  -TS.
* [iterflow](https://github.com/gv-sh/iterflow) - Powerful iterator utilities for TypeScript with statistical operations, windowing, and lazy evaluation. +TS
* [prelude.ls](http://gkz.github.io/prelude-ls/) – A functionally oriented utility library somewhat based off of Haskell's Prelude module. -TS.
* [fp-dom](https://github.com/fp-dom/) – Making the DOM functional.
* [claire](https://github.com/robotlolita/claire) – A property-based testing library for clearly specifying code invariants and behaviour.
* [Creed](http://blog.briancavalier.com/creed/) – Sophisticated and functionally-minded async with advanced features: coroutines, promises, ES2015 iterables, fantasy-land. -TS.
* [fp-ts](https://gcanti.github.io/fp-ts/) - Typed functional programming in TypeScript. +CT, +TS.
* [remeda](https://remedajs.com/) A function library roughly subsetting Ramda, but written in Typescript and thus more type-friendly. +TS.
* [ts-belt](https://mobily.github.io/ts-belt/) - Fast, modern, and practical utility library for FP in TypeScript. (Uses a data-first approach like remeda, but is [faster](https://mobily.github.io/ts-belt/benchmarks/v3.7.0/macbook-air-2020) than remeda, ramda, rambda, and lodash/fp.)
* [fp-multik](https://github.com/lulldev/fp-multik) - JS/TS lightweight value-multimethod util

### Data Structures

Write performant functional code by using the right data structures for the task.

* [Immutable.js](https://github.com/facebook/immutable-js) ⭐ 33,063 | 🐛 125 | 🌐 TypeScript | 📅 2026-04-10 – Immutable persistent data collections.
* [Immer](https://github.com/mweststrate/immer) ⭐ 28,931 | 🐛 61 | 🌐 JavaScript | 📅 2026-04-14 – Immer is a tiny package for immutable state based on copy-on-write mechanism. +TS.
* [Lazy.js](https://github.com/dtao/lazy.js) ⭐ 5,978 | 🐛 59 | 🌐 JavaScript | 📅 2020-07-15 – A utility library with a lazy engine under the hood that strives to do as little work as possible while being as flexible as possible.
* [Mori](https://github.com/swannodette/mori) ⭐ 3,369 | 🐛 64 | 🌐 Clojure | 📅 2026-03-06 – ClojureScript’s persistent data structures and supporting API from the comfort of vanilla JavaScript.
* [Baobab](https://github.com/Yomguithereal/baobab) ⭐ 3,159 | 🐛 49 | 🌐 JavaScript | 📅 2022-05-10 – persistent and optionally immutable data tree with cursors.
* [List](https://github.com/funkia/list) ⭐ 1,654 | 🐛 22 | 🌐 TypeScript | 📅 2024-01-15 - An extremely fast immutable list with a comprehensive functional API. Designed to [seamlessly integrate with Ramda](https://github.com/funkia/list#seamless-ramda-integration) ⭐ 1,654 | 🐛 22 | 🌐 TypeScript | 📅 2024-01-15.
* [TSTL](https://github.com/samchon/tstl) ⭐ 628 | 🐛 3 | 🌐 TypeScript | 📅 2025-08-13 - C++ STL (Standard Template Library) is implemented in TypeScript. STL Containers, iterators, algorithms and functors, that following functional programming rule, are provided. +TS.
* [DerivableJS](https://github.com/ds300/derivablejs) ⭐ 519 | 🐛 11 | 🌐 JavaScript | 📅 2018-05-26 – Functional Reactive State for JavaScript and TypeScript. DerivableJS enables you to make elegant declarative statements about how your bits of state are related. +TS.
* [Icepick](https://github.com/aearly/icepick) ⭐ 422 | 🐛 2 | 🌐 JavaScript | 📅 2021-08-09 Utilities for treating frozen JavaScript objects as persistent immutable collections
* [prelude.ts](https://github.com/emmanueltouzery/prelude.ts) ⭐ 383 | 🐛 16 | 🌐 TypeScript | 📅 2024-03-12 - Immutable persistent collections, functional constructs such as Option and Either, and combinators. Implemented in Typescript but supports javascript too.  +CT, +TS.
* [collectable](https://github.com/frptools/collectable) ⭐ 279 | 🐛 39 | 🌐 TypeScript | 📅 2023-03-06 – Super high-performance immutable data structures for modern JavaScript and TypeScript applications. +TS.
* [imlazy](https://github.com/benji6/imlazy) ⭐ 104 | 🐛 7 | 🌐 JavaScript | 📅 2026-04-02 – Library for creating and manipulating lazy iterables using the ES2015 iteration protocols.
* [immutable-sequence.js](https://github.com/qiao/immutable-sequence.js) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2015-08-10 –  High performance implementation of Immutable Sequence in JavaScript, based on [Finger Trees](https://github.com/qiao/fingertree.js) ⭐ 45 | 🐛 5 | 🌐 JavaScript | 📅 2016-11-17.
* [Timm](http://guigrpa.github.io/timm/) – Immutability helpers with fast reads and acceptable writes.

### Algebraic Data Types

Use the laws of math instead of always reinventing your own thing. Algebraic!

* [Fantasy Land](https://github.com/fantasyland/fantasy-land) ⭐ 10,235 | 🐛 36 | 🌐 JavaScript | 📅 2024-11-10 – Not a library, but a specification of the Monad laws for libraries to follow.
* [NeverThrow](https://github.com/supermacro/neverthrow) ⭐ 7,467 | 🐛 73 | 🌐 TypeScript | 📅 2026-02-14 - This package contains a `Result` type that represents either success (`Ok`) or failure (`Err`).
* [Sanctuary](https://github.com/plaid/sanctuary) ⭐ 3,054 | 🐛 36 | 🌐 JavaScript | 📅 2024-11-10 – Sanctuary makes it possible to write safe code without null checks.  +CT, +TS.
* [Fluture](https://github.com/Avaq/Fluture) ⭐ 2,496 | 🐛 12 | 🌐 JavaScript | 📅 2024-04-22 – A Future library with included control utilities, high performance and great error messages.
* [purify](https://github.com/gigobyte/purify) ⭐ 1,601 | 🐛 2 | 🌐 TypeScript | 📅 2025-12-16 - Functional programming library for TypeScript focusing on ADTs.  +CT, +TS.
* [crocks](https://github.com/evilsoft/crocks) ⭐ 1,599 | 🐛 69 | 🌐 JavaScript | 📅 2023-01-06 – A collection of popular Algebraic Data Types with the main goal to curate and provide not only a common interface between each type, but also all of the helper functions needed to hit the ground running. -TS.
* [Static Land](https://github.com/rpominov/static-land) ⭐ 774 | 🐛 11 | 🌐 JavaScript | 📅 2019-10-29 – Specification similar to Fantasy Land but based on static methods rather than instance methods.
* [daggy](https://github.com/puffnfresh/daggy) ⭐ 705 | 🐛 2 | 🌐 JavaScript | 📅 2021-07-19 – Library for creating tagged constructors.
* [immutable-ext](https://github.com/DrBoolean/immutable-ext) ⭐ 489 | 🐛 5 | 🌐 JavaScript | 📅 2019-02-10 – FantasyLand extensions for [Immutable.js](https://github.com/facebook/immutable-js) ⭐ 33,063 | 🐛 125 | 🌐 TypeScript | 📅 2026-04-10.
* [Pratica](https://github.com/rametta/pratica) ⭐ 487 | 🐛 0 | 🌐 TypeScript | 📅 2024-06-05 - Small, simple, easy FP data types for pragmatic and productive developers who need to ship reliable code fast.  +CT, +TS.
* [union-type](https://github.com/paldepind/union-type) ⭐ 479 | 🐛 18 | 🌐 JavaScript | 📅 2019-06-05 – A small JavaScript library for defining and using union types.
* [sweet-monads](https://github.com/JSMonk/sweet-monads) ⭐ 354 | 🐛 13 | 🌐 TypeScript | 📅 2024-11-18 - A collection of popular monads (such as `Either` and `Maybe`) and the lazy iterator.
* [freeky](https://github.com/DrBoolean/freeky) ⭐ 177 | 🐛 7 | 🌐 JavaScript | 📅 2018-04-13 – A collection of Free monads.
* [MojiScript](https://github.com/joelnet/MojiScript) ⭐ 147 | 🐛 47 | 🌐 JavaScript | 📅 2023-07-19- an async-first, opinionated, and functional language designed to have 100% compatibility with JavaScript engines
* [fantasy-birds](https://github.com/fantasyland/fantasy-birds) ⚠️ Archived – Port of the Haskell package Data.Aviary.Birds. Everything for your combinatory needs.
* [fantasy-combinators](https://github.com/fantasyland/fantasy-combinators) ⚠️ Archived – Common combinators.
* [kudo-js](https://github.com/blitzritz/kudojs) ⭐ 23 | 🐛 4 | 🌐 TypeScript | 📅 2026-01-21 - A small utility library with a set of Algebraic Data Types and Helper functions to help you write code in a functional programming style in Javascript
* [monet.js](http://cwmyers.github.io/monet.js/) – A library that assists functional programming by providing a rich set of Monads and other useful functions.  +CT, +TS.
* [Tifi](https://github.com/mobily/tifi) - Tifi is a library for functional programming in TypeScript. It solves a problem of the existence of both `undefined` and `null`. Tifi is inspired by the OCaml/Reason utilities for the option data type. +CT, +TS.

### Lenses

* [partial.lenses](https://github.com/calmm-js/partial.lenses) ⭐ 920 | 🐛 23 | 🌐 JavaScript | 📅 2021-11-18 – Partial lenses is a comprehensive, high-performance optics library for JavaScript.
* [shades](https://github.com/jamesmcnamara/shades) ⭐ 418 | 🐛 3 | 🌐 JavaScript | 📅 2024-06-13 – A lodash-inspired lens-like library for Javascript.
* [lenses](https://github.com/DrBoolean/lenses) ⭐ 216 | 🐛 3 | 🌐 JavaScript | 📅 2015-09-28 – Composable [kmett](https://github.com/ekmett/lens) ⭐ 2,080 | 🐛 110 | 🌐 Haskell | 📅 2026-03-02 style lenses.
* [ramda-lens](https://github.com/ramda/ramda-lens) ⭐ 184 | 🐛 4 | 🌐 JavaScript | 📅 2017-06-13 – :ram: :mag\_right: Lens library built on Ramda.
* [nanoscope](https://github.com/5outh/nanoscope) ⭐ 177 | 🐛 5 | 🌐 CSS | 📅 2016-12-09 – Lenses with dotty support.
* [fantasy-lenses](https://github.com/fantasyland/fantasy-lenses) ⚠️ Archived – Composable, immutable getters and setters. (Profunctor lenses WIP)
* [optics](https://github.com/flunc/optics) ⭐ 87 | 🐛 1 | 🌐 JavaScript | 📅 2016-05-05 – Profunctor optics (Lens, Prism, iso).

## Functional Languages that Compile to JavaScript

* [ClojureScript](https://github.com/clojure/clojurescript) ⭐ 9,386 | 🐛 7 | 🌐 Clojure | 📅 2026-05-01 – Compiles [Clojure](http://clojure.org/), a hosted Lisp with immutable persistent data structures, to JavaScript.
* [GHCJS](https://github.com/ghcjs/ghcjs) ⭐ 2,617 | 🐛 292 | 🌐 Haskell | 📅 2023-01-21 – [Haskell](https://www.haskell.org/) to JavaScript compiler, based on GHC.
* [ElixirScript](https://github.com/bryanjos/elixirscript) ⭐ 1,566 | 🐛 19 | 🌐 Elixir | 📅 2019-08-20 – Compiles a subset of [Elixir](http://elixir-lang.org/), a dynamic, functional language designed for building scalable and maintainable applications, to JavaScript.
* [Quack](https://github.com/quack/quack) ⭐ 325 | 🐛 7 | 🌐 PHP | 📅 2020-09-30 - A multi-paradigm programming language with gradual and duck typing that targets PHP and JS.
* [RamdaScript](https://github.com/yosbelms/ramdascript) ⭐ 131 | 🐛 4 | 🌐 JavaScript | 📅 2018-01-23 - A Lisp that compiles to opinionated JavaScript on top of RamdaJS
* [ion](https://github.com/ion-lang/ion) ⭐ 80 | 🐛 2 | 🌐 JavaScript | 📅 2017-09-13 - no BS JS
* [RacketScript](https://github.com/vishesh/racketscript) ⭐ 14 | 🐛 0 | 🌐 Racket | 📅 2021-08-30 – RacketScript aims to leverage both JavaScript and Racket's ecosystem, and make interoperability between them clean and smooth.
* [Elm](http://elm-lang.org/) – A type-safe functional programming language for declaratively creating web browser-based graphical user interfaces. Implemented in Haskell.
* [Fable](http://fable.io/) - Compiles [F#](http://fsharp.org) to readable JavaScript.
* [PureScript](http://www.purescript.org/) – A small strongly typed programming language that compiles to JavaScript.
* [Idris](http://www.idris-lang.org/) – A general purpose pure functional programming language with dependent types.
* [Js\_of\_ocaml](http://ocsigen.org/js_of_ocaml/) – Compiles [OCaml](http://ocaml.org/) bytecode to JavaScript, making it possible to run OCaml programs in the browser.
* [Reason](https://reasonml.github.io) – Reason is a new interface to OCaml, a highly expressive dialect of the ML language featuring type inference and static type checking.
* [ReScript](https://rescript-lang.org/) – (previously known as [Bucklescript](https://rescript-lang.org/bucklescript-rebranding)) ReScript is a type-safe language that compiles to the highest quality of clean, readable and performant JavaScript code.
* [Scala.js](http://www.scala-js.org/) – Compiles [Scala](http://www.scala-lang.org/) to JavaScript.
* [LiveScript](http://gkz.github.io/LiveScript/) – LiveScript has a straightforward mapping to JavaScript and allows you to write expressive code devoid of repetitive boilerplate.
* [Koka](https://www.microsoft.com/en-us/research/project/koka/) – Koka is a function-oriented programming language that seperates pure values from side-effecting computations with a familiar JavaScript like syntax.
* [TypeScript](https://www.typescriptlang.org/) - TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.
* [Gleam](https://gleam.run) - Gleam is a typed, functional language that compiles to Erlang and JavaScript.

## Programming Tools

* [eslint-plugin-fp](https://github.com/jfmengels/eslint-plugin-fp) ⭐ 969 | 🐛 31 | 🌐 JavaScript | 📅 2021-01-01 - ESLint rules for functional programming
* [hm-def](https://github.com/xodio/hm-def) ⭐ 203 | 🐛 13 | 🌐 JavaScript | 📅 2022-12-03 – Runtime type checking for JS with Hindley Milner signatures.
* [4.5](https://github.com/TylorS/4.5) ⭐ 21 | 🐛 0 | 🌐 TypeScript | 📅 2017-03-03 – A functional assertions library. If you prefer functional style APIs and practices in JavaScript, this library aims to solve this with functionally-oriented assertions that are lazy and monadic.
* [ftor](https://github.com/kongware/ftor) - A pluggable runtime type checker and functional debugging tool that supports parametric and row polymorphism, implicit rank-2 types and algebraic data types via Scott Encoding.

## Resources

### Books

* [Professor Frisby’s Mostly Adequate Guide to Functional Programming](https://github.com/MostlyAdequate/mostly-adequate-guide) ⭐ 23,840 | 🐛 90 | 🌐 JavaScript | 📅 2024-09-17 – This is a book on the functional paradigm in general using the world’s most popular functional programming language: JavaScript. It’s a practical introduction that builds up intuition through real-world examples. Strongly recommended. By [Brian Lonsdorf](https://twitter.com/drboolean) (2016)
* [Functional-Light JavaScript](https://github.com/getify/functional-light-js) ⭐ 16,772 | 🐛 26 | 🌐 JavaScript | 📅 2023-12-26 – This book explores the core principles of functional programming (FP) that can be applied to JavaScript. But what makes this book different is that it approaches these principles without all the heavy terminology.
* [scriptum](https://github.com/kongware/scriptum/blob/master/README.md) ⭐ 381 | 🐛 0 | 🌐 JavaScript | 📅 2025-08-13 - a no-frills functional programming library and a online course based on it
* [JavaScript Allongé](https://leanpub.com/javascriptallongesix), the “Six” edition. Starts with as little as possible about functions – but no less! – and builds up towards powerful combinators and decorators. A foundational book. By [Reginald  Braithwaite](https://github.com/raganwald) (2016)
* [Functional Programming in JavaScript](https://www.manning.com/books/functional-programming-in-javascript) teaches JavaScript developers functional techniques that will improve extensibility, modularity, reusability, testability, and performance. Through concrete examples and jargon-free explanations, this book teaches you how to apply functional programming to real-life development tasks. By Luis Atencio (2016)
* [Eloquent JavaScript](http://eloquentjavascript.net/). A modern introduction to programming using JavaScript. By Marijn Haverbeke (2014)
* [Functional JavaScript](http://shop.oreilly.com/product/0636920028857.do) teaches how to create code that’s beautiful, safe, and simple to understand and test by using JavaScript’s functional programming support. By [Michael Fogus](https://github.com/fogus) (2013)
* [Grokking Simplicity](https://www.manning.com/books/grokking-simplicity) teaches functional programming from first principles. It uses JavaScript for all code examples and it uses real-world scenarios. By [Eric Normand](https://github.com/ericnormand) (2019)

### Articles

* [Functional Programming Jargon](https://github.com/hemanth/functional-programming-jargon) ⭐ 18,637 | 🐛 27 | 📅 2023-10-17 – Jargon from the functional programming world explained in JavaScript.
* [You don't (may not) need loops ➿](https://github.com/you-dont-need/You-Dont-Need-Loops) ⭐ 1,170 | 🐛 5 | 📅 2024-10-15 - Loops are one of the first constructs that junior programmers learn, but they can pose many potential issues in the software development process, and could be avoided in many cases.
* [FP Concepts in JavaScript](https://medium.com/@collardeau/intro-to-functional-programming-concepts-in-javascript-b0650773139c) – An introduction to Functional Programming Concepts in JavaScript. Uses the Ramda library to teach the concepts of composition, pointfree style, and functors through the simplest of examples.
* [Functional programming with JavaScript](http://stephen-young.me.uk/2013/01/20/functional-programming-with-javascript.html) – Another introduction to Functional Programming in JavaScript with a focus on three key themes: computation as the application of functions, statelessness, avoiding side effects.
* [A gentle introduction to functional JavaScript](http://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-intro/) – A four-part series introduction functional programming in JavaScript that gets you up to speed what all the hype about functional programming is all about.
* [Functors from first principle - explained with JS](https://dev.to/snird/functors-from-first-principle-37lh) - Explaining functors concept using JavaScript.
* [Why Curry Helps](https://hughfdjackson.com/javascript/why-curry-helps/) – A short overview of how to write reusable and declarative code using currying.
* [Favoring Curry](http://fr.umio.us/favoring-curry/) - Practical applications of currying using Ramda.
* [Functional Mumbo Jumbo – ADTs](http://blog.jenkster.com/2016/06/functional-mumbo-jumbo-adts.html) – A beginner-friendly introduction to Algebraic Data Types.
* [JavaScript and Type Thinking](https://medium.com/@yelouafi/javascript-and-type-thinking-735edddc388d) – Learn to reason about your JavaScript code with *type thinking*. Algebraic Data Types are introduced as a conceptual basis to reason about program entities.
* [Lazy, composable, and modular JavaScript](https://codewords.recurse.com/issues/four/lazy-composable-and-modular-javascript) – Use four new features of ES6 – iterables, generators, fat arrows, and for-of – in conjunction with higher-order functions, function composition, and lazy evaluation, to write cleaner and more modular JavaScript.
* [Why Ramda](http://fr.umio.us/why-ramda/) – To those not used to functional programming, Ramda seems to serve no purpose whatsoever. However, it does offer a different style of coding, a style that’s taken for granted in purely functional programming languages: Ramda makes it simple for you to build complex logic through functional composition.
* [Monads in JavaScript](https://curiosity-driven.org/monads-in-javascript) – An introduction to the Monad design pattern in JavaScript.
* [A Monad in Practicality: First-Class Failures](https://web.archive.org/web/20241118045403/https://robotlolita.me/articles/2013/a-monad-in-practicality-first-class-failures/) – A walk through some practical use cases for specific monadic structures in JavaScript: use the `Maybe` monad to handle simple failure cases and model more complex scenarios with the `Either` monad or the `Validation` applicative functor.
* [Functional programming](https://glebbahmutov.com/blog/tags/functional/) – Many articles on various aspects of functional programming in JavaScript by Gleb Bahmutov.
* [Data Structures in JavaScript](http://blog.benoitvallon.com/data-structures-in-javascript/data-structures-in-javascript/) – A series of blog posts that reimplements various data structures in JavaScript to better understand their benefits and downsides.
* [So You Want to be a Functional Programmer](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536) - Easy to understand, with some examples, introduction to Functional Programming in Javascript and Elm.
* [Functional Programming for JavaScript People](https://medium.com/@chetcorcos/functional-programming-for-javascript-people-1915d8775504) - A complete introduction to functional programming patterns by Chet Corcos with a lot of javascript examples.
* [Introduction to Immutable.js and Functional Programming Concepts](https://auth0.com/blog/intro-to-immutable-js/) - Learn about functional data structures and their uses in this overview of Facebook's popular library for JavaScript: Immutable.js.
* [Master the JavaScript Interview: What is Functional Programming?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0) - A simple introduction by @ericelliott to functional principles and vocabulary.
* [Composing Software](https://medium.com/javascript-scene/the-rise-and-fall-and-rise-of-functional-programming-composable-software-c2d91b424c8c) - A series of articles on learning functional programming and compositional software techniques in JavaScript ES6+ from the ground up by @ericelliott.
* [Anonymous Recursion in JavaScript](https://dev.to/simov/anonymous-recursion-in-javascript) - Short and easy to understand article about implementing anonymous recursion in JavaScript.
* [Functional Composition in Javascript](https://joecortopassi.com/articles/functional-composition-in-javascript/) – Step by step explanation of how to compose functions in javascript.
* [Functional Programming Principles in Javascript](https://medium.freecodecamp.org/functional-programming-principles-in-javascript-1b8fc6c3563f) - Practical code examples to learn functional programming concepts like pure function, immutability, first-class entities, and higher order functions
* [Basic Monads in Javascript](https://dev.to/rametta/basic-monads-in-javascript-3el3) - Introduction to 2 easy monads in Javascript, Maybe & Either.
* [F# for JavaScript Devs](https://dev.to/rametta/f-for-js-devs-2b88) - Showcasing the similarities between F# and JavaScript
* [A practical guide to writing more functional Javascript](https://medium.com/@nadeesha/a-practical-guide-to-writing-more-functional-javascript-db49409f71) - A step by step guide to convert imperative JavaScript to more declarative, functional JavaScript.

### Videos

* [Classroom Coding with Prof. Frisby](https://www.youtube.com/watch?v=h_tkIpwbsxY\&list=PLK_hdtAJ4KqX0JOs_KMAmUNTNMRYhWEaC) – A series that builds a “practical” web application with React and functional programming in JavaScript.
* [Hey Underscore, You're Doing It Wrong!](https://www.youtube.com/watch?v=m3svKOdZijA) – Underscore.js claims to be a functional programming library, but is it really?
* [Functional programming patterns for the non-mathematician](https://www.youtube.com/watch?v=AvgwKjTPMmM) – Learn about practical use cases for functors, applicatives, and monads.
* [Pure JavaScript](https://vimeo.com/49384334) – Christian Johansen will show you how you can significantly up your game by leaving loops behind and embracing functions as the primary unit of abstraction.
* [Functional programming in JavaScript](https://www.youtube.com/playlist?list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84) - A series by Mattias Petter Johansson, from the youtube channel FunFunFunction, that is specifically about popularization of functional programming in JavaScript.
* [Functional Programming in TypeScript](https://www.youtube.com/playlist?list=PLuPevXgCPUIMbCxBEnc1dNwboH6e2ImQo) - Discover functional programming with Typescript and create a library like fp-ts alongside Sahand Javid in this beginner-friendly YouTube playlist.
* [Anjana Vakil: Learning Functional Programming with JavaScript - JSUnconf 2016](https://www.youtube.com/watch?v=e-5obm1G_FY) - A simple and understandable introduction of functional proramming in javascript.
* [Functional Programming Basics In ES6](https://www.youtube.com/watch?v=FYXpOjwYzcs) - A complete introduction to functional programming in javascript made it easy by ES6.
* [JavaScript Programmers Should Learn Algebraic Data Types -- May 2018 -- UtahJS Lehi](https://www.youtube.com/watch?v=B0VoyujJWIE) - Seth House explains how ADTs (Algebraic Data Types) can be useful to JavaScript developers.

### Examples and Exercises

* [functional-javascript-workshop](https://github.com/timoxley/functional-javascript-workshop) ⭐ 2,042 | 🐛 83 | 🌐 JavaScript | 📅 2020-10-08 – The goal of this workshop is to create realistic problems that can be solved using terse, vanilla, idiomatic JavaScript to teach fundamental functional programming features of JavaScript.
* [cube-composer](https://github.com/sharkdp/cube-composer) ⭐ 2,031 | 🐛 10 | 🌐 PureScript | 📅 2022-12-08 – A puzzle game inspired by functional programming.
* [functional-frontend-architecture](https://github.com/paldepind/functional-frontend-architecture) ⭐ 1,444 | 🐛 9 | 🌐 JavaScript | 📅 2019-07-02 – A functional frontend framework. Based on Ramda + union-type-js + Flyd + Snabbdom
* [Escape from Callback Mountain](https://github.com/justsml/escape-from-callback-mountain) ⭐ 256 | 🐛 12 | 🌐 JavaScript | 📅 2023-02-24 - Design & refactoring tips for Promise-based Functional JavaScript. Key benefits include better readability, testability, and reusability. MIT.
* [FPJS-Class](https://github.com/loop-recur/FPJS-Class) ⭐ 94 | 🐛 0 | 🌐 JavaScript | 📅 2015-08-01 – Functional Programming learned through JavaScript.
* [FP Youtube Search](https://github.com/jaysoo/example-fp-youtube-search) ⭐ 57 | 🐛 1 | 🌐 JavaScript | 📅 2017-01-26 – YouTube search app with ReactJS, Redux, and FP concepts
* [Hardcore Functional Programming in JavaScript](https://frontendmasters.com/courses/functional-javascript/) – Learn to apply techniques from the forefront of computer science research to solve practical problems in Javascript. Discover functional programming and see it demonstrated step-by-step with how to build an example web app using abstract interfaces like Monads, Functors, Monoids and Applicatives. (*commercial*)
* [Learn Rx](http://reactivex.io/learnrx/) – A series of interactive exercises introducing five basic ingredients of functional (reactive) programming: the `map`, `filter`, `concatAll`, `reduce`, and `zip` functions.
* [Holdem Evaluator](https://github.com/laberin/holdem-eval) - Yet another Holdem Evaluator with Ramda functional style

## Community

### Related Lists

* [xgrommx/Awesome Functional Programming](https://github.com/xgrommx/awesome-functional-programming) ⭐ 3,524 | 🐛 12 | 📅 2024-01-16 – A ton of articles on functional programming, as well as a huge list of functional libraries for many programming languages.
* [tk-learning-center/Functional Programming Learning Path](https://github.com/tk-learning-center/functional-programming-learning-path) ⭐ 1,041 | 🐛 1 | 🌐 Clojure | 📅 2024-10-22 - A Learning Path for Functional Programming
* [lucasviola/Awesome Functional Programming](https://github.com/lucasviola/awesome-functional-programming) ⭐ 1,002 | 🐛 1 | 📅 2024-04-22 – Awesome resources on functional programming theory and learning materials.
* [Functional Programming Resources In JavaScript](https://github.com/busypeoples/functional-programming-javascript) ⭐ 305 | 🐛 2 | 📅 2020-10-01
* [Awesome FRP JS](https://github.com/stoeffel/awesome-frp-js) ⭐ 288 | 🐛 9 | 📅 2019-10-29 – A curated list of awesome (functional) reactive programming stuff in JavaScript.

### Talk

* [Functional Programming Slack channel](https://fpslack.com/) – Community with a friendly channel for JavaScript as well as many other channels about functional programming in general.

## Contribution

:star: Suggestions and PRs are welcome! :star:

Please read the [contribution guidelines](origin/contributing.md) to get started.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Christoph Hermann](http://stoeffel.github.io/) has waived all copyright and related or neighboring rights to this work.
