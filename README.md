# create-typescript-npm-library

Simple typescript app with jest to create a npm library with types

## Installation

```sh
npx degit https://github.com/TheSmartMonkey/create-typescript-npm-library app
```

## Getting started

1. Install nodejs : https://nodejs.org/en/

1. Install node_modules with `npm install`

1. Avalable commands with `npm run` (`npm run start` runes your code from `main.ts`)

```
start
  npm run build && node dist/main.js
test
  jest
lint
  eslint src --ext .ts
clear
  rmdir /s "dist"
build
  tsc
```

## Publish your library

```sh
npm run pub
```

## Folder tree

```
|   .eslintrc.json
|   .gitignore
|   .prettierignore
|   .prettierrc.json
|   jest.config.ts
|   junit.xml
|   LICENSE
|   main.ts
|   package-lock.json
|   package.json
|   README.md
|   tree.txt
|   tsconfig.json
|   tsconfig.paths.json
|
+---src
    |   tree.txt
    |
    +---functions
    |       hello.test.ts
    |       hello.ts
    |
    +---libs
    |       .gitkeep
    |
    +---models
            hello.model.ts
```
