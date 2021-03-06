# generator-easily [![Build Status](https://secure.travis-ci.org/kristw/generator-easily.svg?branch=master)](https://travis-ci.org/kristw/generator-easily) [![Coverage Status](https://coveralls.io/repos/kristw/generator-easily/badge.svg?branch=master&service=github)](https://coveralls.io/github/kristw/generator-easily?branch=master)


> Yeoman generator generating a Yeoman generator (with [yeoman-easily](https://github.com/kristw/yeoman-easily))

## Getting started

- Install: `npm install -g generator-easily`
- Run: `yo easily`

## Commands

* `yo easily` shows a wizard for generating a new generator, with yeoman-easily included and ready to use via `this.easily`.
* `yo easily:subgenerator <name>` generates a subgenerator with the name `<name>`. The new subgenerator will have yeoman-easily as `this.easily`.


## What do you get?

Scaffolds out a complete generator directory structure for you:

```
.
├── generators/
│   └── app/
│       ├── index.js
│       └── templates/
│           └── __package.json
├── .editorconfig
├── .gitattributes
├── .gitignore
├── .eslintrc
├── .travis.yml
├── .yo-rc.json
├── package.json
├── gulpfile.js
├── README.md
├── LICENSE
└── test/
    └── app.js
```

Refer to [Yeoman documentation](http://yeoman.io/authoring/) to learn more about creating a Yeoman generator.

### Running tests

Run `npm test` to run your test suite.

These tests will be run automatically in your git repository if you connect [Travis CI](https://travis-ci.org/profile). You can also track test coverage using [Coveralls](https://coveralls.io).

## License

Apache-2 © [Krist Wongsuphasawat](http://kristw.yellowpigz.com)

Forked from generator-generator

MIT © Pascal Hartig <phartig@rdrei.net> and other contributors
