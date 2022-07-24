# @colussi/tsconfig

[![npm version](https://badge.fury.io/js/@colussi%2Ftsconfig.svg)](https://badge.fury.io/js/@colussi%2Ftsconfig) [![CI](https://github.com/JonatanColussi/tsconfig/actions/workflows/main.yml/badge.svg?event=workflow_dispatch)](https://github.com/JonatanColussi/tsconfig/actions/workflows/main.yml)

Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)

## Install

```sh
$ npm install --save-dev @colussi/tsconfig
```


## Usage

`tsconfig.json`

```json
{
	"extends": "@colussi/tsconfig",
	"compilerOptions": {
		"outDir": "build",
		"target": "es5",
	}
}
```


## License

MIT
