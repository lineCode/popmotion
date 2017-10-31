# <a href="https://popmotion.io"><img src="https://cloud.githubusercontent.com/assets/7850794/21642571/1910a15e-d27b-11e6-84c7-19e88e207c14.png" height="52" width="243" alt="Popmotion" /></a>

### A **functional**, **reactive** motion library.

[![npm version](https://img.shields.io/npm/v/popmotion.svg?style=flat-square)](https://www.npmjs.com/package/popmotion)
[![npm downloads](https://img.shields.io/npm/dm/popmotion.svg?style=flat-square)](https://www.npmjs.com/package/popmotion)
[![Twitter Follow](https://img.shields.io/twitter/follow/espadrine.svg?style=social&label=Follow)](http://twitter.com/popmotionjs)

### [Get Started](https://popmotion.io/learn/get-started)
### [Full API documentation](https://popmotion.io/api)

### Popmotion does:
- **[Tween](https://popmotion.io/api/tween):** Change values over specific duration of time. Full suite of [easing functions](https://popmotion.io/api/easing) included.
- **[Physics](https://popmotion.io/api/physics):** Integrated, mutable simulation of velocity, acceleration, friction and springs.
- **[Keyframes](https://popmotion.io/api/keyframes):** Define a series of keyframes to animate between.
- **[Spring](https://popmotion.io/api/spring):** An accurate spring-mass system ported from Apple's CASpringAnimation.
- **[Decay](https://popmotion.io/api/decay):** Exponentially-decayed velocity for smooth deceleration.
- **[Pointer](https://popmotion.io/api/pointer):** Full support for mouse and multitouch inputs.

### Popmotion is:
- **Tiny:** At 9kb **max**, it's 75% smaller than GreenSock TweenMax. Everything is also importable individually.
- **Reactive:** Super-simple Rx-inspired API for subscribing to streams of animation events.
- **Composable:** All actions can be **delayed**, **staggered** **merged**, **crossfaded** and **chained**.
- **Cross-platform:** Runs on **IE9+**, plus **Node**-based environments like Arduino.
- **Versatile:** Animate raw numbers, colors, objects or n-dimensional arrays.
- **Performant af:** Batches jobs on the [Framesync](https://github.com/popmotion/framesync) `update` render step. Stands up to popular alternatives in [performance tests](http://codepen.io/popmotion/pen/zNYXmR).
- **Typesafe and tested:** Written in TypeScript, with Flow definitions available on [flow-typed](https://github.com/flowtype/flow-typed). Full test coverage.
- **Supported:** Full ecosystem of awesome plugins.

## Beta TODOs
- Learn docs
- Support color
- Introduce remaining compositors
- Figure out stagger interface
- Figure out timeline interface
- Update Learn documentation
- Write upgrade guide
- Investigate vector support for keyframe

## Examples
TODO

## Official plugins
TODO: Not yet compatible with Popmotion 8

## Installation

```bash
npm install --save popmotion
```

In your javascript module:

```javascript
import { tween } from 'popmotion';
```

### [Get Started](https://popmotion.io/learn/get-started)
### [Full API documentation](https://popmotion.io/api)
