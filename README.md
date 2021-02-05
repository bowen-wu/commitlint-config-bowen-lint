# eslint-plugin-bowen-lint

commitlint bowen plugin

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-bowen-lint`:

```
$ npm install eslint-plugin-bowen-lint --save-dev
```


## Usage

Add `bowen-lint` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "bowen-lint"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "bowen-lint/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





