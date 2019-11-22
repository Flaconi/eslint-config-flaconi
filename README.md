# 🚧 REPO UNDER CONSTRUCTION..... 🚧 

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
[![license](https://img.shields.io/npm/l/eslint-config-flaconi)](LICENSE)
    
# eslint-config-flaconi

> [Flaconi's](https://www.flaconi.de/) shareable eslint config


## Install
#### 1. Install the package:
```
yarn add -D eslint-config-flaconi
```
or
```
npm i -D eslint-config-flaconi
```

#### 2. Install the correct versions of each package, which are listed by the command:

```sh
npx install-peerdeps --dev eslint-config-flaconi
```
If using **yarn**, you can also use the shortcut described above, as the command will detect that you are using yarn and will act accordingly.
Otherwise, run `npm info "eslint-config-flaconi@latest" peerDependencies` to list the peer dependencies and versions, then run `yarn add --dev <dependency>@<version>` for each listed peer dependency.


## Usage
Add the following to your `.eslintrc`
```json
{
    "extends": [
        "eslint-config-flaconi"
    ]
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

## Develop
Developing or testing locally the repo is possible using the `yarn link` command.
1. clone the repo
2. `yarn link` and copy the output command
3. go to any project, paste the command and run it
4. your `.eslintrc` file must look like this:
```json
{
    "extends": [
        "eslint-config-flaconi"
    ]
}
```


## Contributing

PRs are welcome. Please read the [code of conduct](./.github/CODE_OF_CONDUCT.md) and [contribution guidelines](./.github/CONTRIBUTING.md).

## License

[MIT](LICENSE) © Flaconi GmbH
