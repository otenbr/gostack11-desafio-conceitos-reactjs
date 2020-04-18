<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/otenbr/gostack11-desafio-conceitos-reactjs?color=%2304D361">

  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/otenbr/gostack11-desafio-conceitos-reactjs?color=%2304D361">

  <img alt="Made by José Antonio" src="https://img.shields.io/badge/made%20by-José%20Antonio-%2304D361">

  <img alt="GitHub" src="https://img.shields.io/github/license/otenbr/gostack11-desafio-conceitos-reactjs?color=%2304D361">

</p>

# GoStack 11: Desafio Conceitos ReactJS

Terceiro desafio do bootcamp GoStack 11: Conceitos React.js

_Thrid challenge of the GoStack 11 bootcamp: ReactJS Concepts_

## Getting Started

### Prerequisites

-   Node.js
-   Yarn (_optional_)

### Install

Clone the repository to your machine.

```sh
git clone https://github.com/otenbr/gostack11-desafio-conceitos-reactjs.git
```

Change to solution directory

```sh
$ cd gostack11-desafio-conceitos-reactjs
```

Run the command `npm` or `yarn`.

```sh
$ yarn
yarn install v1.22.4
[1/4] Resolving packages...
[2/4] Fetching packages...
info fsevents@2.1.2: The platform "linux" is incompatible with this module.
info "fsevents@2.1.2" is an optional dependency and failed compatibility check. Excluding it from installation.
info fsevents@1.2.12: The platform "linux" is incompatible with this module.
info "fsevents@1.2.12" is an optional dependency and failed compatibility check. Excluding it from installation.
[3/4] Linking dependencies...
warning "react-scripts > @typescript-eslint/eslint-plugin > tsutils@3.17.1" has unmet peer dependency "typescript@>=2.8.0 || >= 3.2.0-dev || >= 3.3.0-dev || >= 3.4.0-dev || >= 3.5.0-dev || >= 3.6.0-dev || >= 3.6.0-beta || >= 3.7.0-dev || >= 3.7.0-beta".
warning " > @testing-library/user-event@7.2.1" has unmet peer dependency "@testing-library/dom@>=5".
[4/4] Building fresh packages...
Done in 9.68s.
```

### Run

Run the command `npm run start` or `yarn start`.

```sh
$ yarn start
yarn run v1.22.4
$ react-scripts start
Compiled successfully!

You can now view frontend in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://192.168.31.190:3000

Note that the development build is not optimized.
To create a production build, use yarn build.
```

### Test

To execute the unit tests, run the command `npm run test` or `yarn test`.

```sh
$ yarn test
yarn run v1.22.4
$ react-scripts test --watchAll=false
 PASS  src/__tests__/App.test.js
  App component
    ✓ should be able to add new repository (30ms)
    ✓ should be able to remove repository (5ms)

Test Suites: 1 passed, 1 total
Tests:       2 passed, 2 total
Snapshots:   0 total
Time:        1.79s, estimated 2s
Ran all test suites.
Done in 2.48s.
```

## Credits

This software uses the following open source packages:

-   [Node.js](https://nodejs.org/)
-   [reactjs](reactjs.org/)
-   [axios](https://github.com/axios/axios)
-   [testing-library](https://github.com/testing-library)

## License

[MIT](LICENSE.md)
