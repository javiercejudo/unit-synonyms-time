# unit-synonyms-time

[![Build Status](https://travis-ci.org/javiercejudo/unit-synonyms-time.svg)](https://travis-ci.org/javiercejudo/unit-synonyms-time)
[![Coverage Status](https://coveralls.io/repos/javiercejudo/unit-synonyms-time/badge.svg?branch=master)](https://coveralls.io/r/javiercejudo/unit-synonyms-time?branch=master)
[![Code Climate](https://codeclimate.com/github/javiercejudo/unit-synonyms-time/badges/gpa.svg)](https://codeclimate.com/github/javiercejudo/unit-synonyms-time)

Time units synonyms

## Install

    npm i unit-synonyms-time

## Units

- [Second](https://en.wikipedia.org/wiki/Second)
- [Nanosecond](https://en.wikipedia.org/wiki/Nanosecond)
- [Microsecond](https://en.wikipedia.org/wiki/Microsecond)
- [Millisecond](https://en.wikipedia.org/wiki/Millisecond)
- [Minute](https://en.wikipedia.org/wiki/Minute)
- [Hour](https://en.wikipedia.org/wiki/Hour)
- [Day](https://en.wikipedia.org/wiki/Day)
- [Week](https://en.wikipedia.org/wiki/Week)
- [Month](https://en.wikipedia.org/wiki/Month)
- [Year](https://en.wikipedia.org/wiki/Year)
- [Decade](https://en.wikipedia.org/wiki/Decade)
- [Century](https://en.wikipedia.org/wiki/Century)
- [Millennium](https://en.wikipedia.org/wiki/Millennium)

## Usage

```js
var synonyms = require('unit-synonyms-time').synonyms;

synonyms['μs']; // => microsecond
synonyms['months']; // => month
```

## Related projects

- [linear-presets](https://github.com/javiercejudo/linear-presets): linear presets for common units.
- [linear-converter](https://github.com/javiercejudo/linear-converter): flexible linear converter.
