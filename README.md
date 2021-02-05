# commitlint-config-bowen-lint

commitlint config

## Installation

```
$ npm install commitlint-config-bowen-lint --save-dev

// yarn
$ yarn add commitlint-config-bowen-lint -D
```

## Usage

Add `bowen-lint` to the extends section of your `.commitlintrc.js ` configuration file. You can omit
the `commitlint-config-` prefix:

```json
{
    "extends": [
        "bowen-lint"
    ]
}
```

## Configuration

```
extends: ['@commitlint/config-conventional'],
rules: {
    'type-enum': [
        2,
        'always',
        [
            'feat', 
            'fix', 
            'docs',
            'style', 
            'refactor', 
            'test', 
            'chore', 
        ],
    ],
    'scope-empty': [1, 'always'],
    'body-leading-blank': [2, 'always'],
    'footer-leading-blank': [2, 'always'],
}
```






