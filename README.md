# react-typescript-starteroni

A react & typescript starter project.

## Frameworks & Toolchain

 - Typescript
 - Foundation 6 & SCSS
 - Webpack 4
 - Jest & Enzyme
 - React 16
 - Redux 4 & redux-thunk

## Features
 
 - Testing with Jest
 - Code Coverage with Jest
 - Pre-commit and pre-push hooks
 - Cross-platform commands (Windows & Linux supported)
 
 ## Usage
 
 ### Installing
 
 1. Clone the repository
 
 ```
 cd /your/project/directory
 git clone https://github.com/hdpinto/react-typescript-starteroni.git .
 ```
 
 2. Delete the `.git` folder, you don't want to be making commits to this project ;)
 
 **Windows Powershell**: `rm -Force -r .\.git\`
 
 **Linux**: `rm -fr ./.git/`
 
 3. Initialize your own repository (optional)
 ```
 git init
 ```
 
 ### Available Commands

all commands must be run using `npm run`

`test` &rarr; `npm run test`
 
| Command       | Action                                                                               |
|---------------|--------------------------------------------------------------------------------------|
| `test`        | Runs `jest --watch`, will run the test suite and watch for changes to code and tests |
| `build`       | Production build                                                                     |
| `copy-static` | Copies static assets from `./fonts/` and `./img/` to `./webroot/` folder             |
| `dev-build`   | Development build, runs tests before building & `copy-static`                        |
| `dev-watch`   | Development watch command, runs webpack in watch mode                                |
| `deploy`      | Alias for `build`                                                                    |
| `deploy-dev`  | Alias for `dev-build`                                                                |
| `coverage`    | Runs all tests & code coverage                                                       |
| `tslint`      | Lints your project, runs on precommit hook                                           |
