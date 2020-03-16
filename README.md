[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
[![license](https://img.shields.io/npm/l/eslint-config-flaconi)](LICENSE)
    
# eslint-config-flaconi

> [Flaconi's](https://www.flaconi.de/) shareable eslint config


## Install
#### Flow based projects
```
yarn add -D babel-eslint@10.0.3 eslint-config-flaconi eslint@6.7.2 eslint-config-prettier@6.7.0 eslint-config-react-app@5.0.2 eslint-config-standard@14.1.0 eslint-plugin-flowtype@3.13.0 eslint-plugin-import@2.18.2 eslint-plugin-jsx-a11y@6.2.3 eslint-plugin-node@10.0.0 eslint-plugin-prettier@3.1.1 eslint-plugin-promise@4.2.1 eslint-plugin-react@7.17.0 eslint-plugin-react-hooks@2.3.0 eslint-plugin-standard@4.0.1 prettier@1.19.1 stylelint@12.0.0 
```
or
```
npm i -D babel-eslint@10.0.3 eslint-config-flaconi eslint@6.7.2 eslint-config-prettier@6.7.0 eslint-config-react-app@5.0.2 eslint-config-standard@14.1.0 eslint-plugin-flowtype@3.13.0 eslint-plugin-import@2.18.2 eslint-plugin-jsx-a11y@6.2.3 eslint-plugin-node@10.0.0 eslint-plugin-prettier@3.1.1 eslint-plugin-promise@4.2.1 eslint-plugin-react@7.17.0 eslint-plugin-react-hooks@2.3.0 eslint-plugin-standard@4.0.1 prettier@1.19.1 stylelint@12.0.0
```

#### Typescript based projects
```
yarn add -D babel-eslint@10.0.3 eslint-config-flaconi eslint@6.7.2 eslint-config-prettier@6.7.0 eslint-config-react-app@5.0.2 eslint-config-standard@14.1.0 eslint-plugin-flowtype@3.13.0 eslint-plugin-import@2.18.2 eslint-plugin-jsx-a11y@6.2.3 eslint-plugin-node@10.0.0 eslint-plugin-prettier@3.1.1 eslint-plugin-promise@4.2.1 eslint-plugin-react@7.17.0 eslint-plugin-react-hooks@2.3.0 eslint-plugin-standard@4.0.1 prettier@1.19.1 stylelint@12.0.0 @typescript-eslint/eslint-plugin@2.10.0 @typescript-eslint/parser@2.10.0 tslint@6.0.0 tslint-config-prettier@1.18.0
```
or
```
npm i -D babel-eslint@10.0.3 eslint-config-flaconi eslint@6.7.2 eslint-config-prettier@6.7.0 eslint-config-react-app@5.0.2 eslint-config-standard@14.1.0 eslint-plugin-flowtype@3.13.0 eslint-plugin-import@2.18.2 eslint-plugin-jsx-a11y@6.2.3 eslint-plugin-node@10.0.0 eslint-plugin-prettier@3.1.1 eslint-plugin-promise@4.2.1 eslint-plugin-react@7.17.0 eslint-plugin-react-hooks@2.3.0 eslint-plugin-standard@4.0.1 prettier@1.19.1 stylelint@12.0.0 @typescript-eslint/eslint-plugin@2.10.0 @typescript-eslint/parser@2.10.0 tslint@6.0.0 tslint-config-prettier@1.18.0
```


## Usage
Add the following to your `.eslintrc`:
```json
{
    "extends": [
        "flaconi"
    ]
}
```

or to the `package.json`:
```json
{
  "eslintConfig": {
    "extends": "flaconi"
  }
}
```
or to `.eslintrc.js`:
```js
module.exports = {
    extends: 'flaconi',
}
```


## Contains
Our default export contains all of our ESLint rules, including ECMAScript 6+ and React. It requires: 
* `@typescript-eslint/eslint-plugin` 
* `@typescript-eslint/parser`
* `babel-eslint`
* `eslint`
* `eslint-config-prettier`
* `eslint-config-react-app`
* `eslint-config-standard`
* `eslint-plugin-flowtype`
* `eslint-plugin-import`
* `eslint-plugin-jsx-a11y`
* `eslint-plugin-node`
* `eslint-plugin-prettier`
* `eslint-plugin-promise`
* `eslint-plugin-react`
* `eslint-plugin-react-hooks`
* `eslint-plugin-standard`
* `prettier`
* `stylelint`

## Limitations
[eslint-config-flaconi](https://github.com/Flaconi/eslint-config-flaconi) works based on the following:
1. [react](https://github.com/facebook/react) project
2. [jest](https://github.com/facebook/jest) for tests
3. [babel-eslint](https://github.com/babel/babel-eslint) parser

## Develop
Developing or testing locally the repo is possible using the `yarn link` command.
1. `git clone https://github.com/Flaconi/eslint-config-flaconi.git && cd eslint-config-flaconi`
2. `yarn link`
3. `cd` to any project and run `yarn link "eslint-config-flaconi"`
4. Install all plugins (except `eslint-config-flaconi`)   
5. your `.eslintrc` file must look like this:
```json
{
    "extends": [
        "flaconi"
    ]
}
```


## Contributing

PRs are welcome. Please read the [code of conduct](./.github/CODE_OF_CONDUCT.md) and [contribution guidelines](./.github/CONTRIBUTING.md).

## License

[MIT](LICENSE) © Flaconi GmbH
