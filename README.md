# fix-package-lock

Fix package-lock.json by regenerating it

<img src="fix-package-lock.gif" width="688">

[![Node.js CI](https://github.com/Miguelzamora13/fix-package-lock/actions/workflows/node.js.yml/badge.svg)](https://github.com/Miguelzamora13/fix-package-lock/actions/workflows/node.js.yml)

## Getting Started

### Prerequisites

Tested on Node v9 with npm 5.

### Installing

Installing `fix-package-lock` globally will install the `fix-package-lock` command:
```
# Using npm
npm install -g fix-package-lock
# Using Yarn
yarn global add fix-package-lock
```

Run using:
```
fix-package-lock
```

`fix-package-lock` can also be run using `npx`:
```
npx fix-package-lock
```

## Built With

* [execa](https://github.com/sindresorhus/execa) - A better `child_process`
* [Listr](https://github.com/SamVerschueren/listr) - Terminal task list 
* [rimraf](https://github.com/isaacs/rimraf) - To delete things

## Versioning

We use [SemVer](http://semver.org/) for versioning.

## Authors

* **Hugo Di Francesco** - [HugoDF](https://github.com/HugoDF)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* [Sindre Sorhus](https://github.com/sindresorhus) for the CLI app inspiration (and execa)
* [Sam Verschueren](https://github.com/SamVerschueren) for Listr

