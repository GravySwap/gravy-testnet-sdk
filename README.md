# Specify TESTNET GravySwap SDK

`WBNB`: 0x0dE8FCAE8421fc79B29adE9ffF97854a424Cad09

`GravyFactory`: 0x5Fe5cC0122403f06abE2A75DBba1860Edb762985

`INIT_CODE_HASH`: 0xbb600ba95884f2c2837114fd2f157d00137e0b65b0fe5226523d720e4a4ce539

`GravyRouter01`: 0x3E2b14680108E8C5C45C3ab5Bc04E01397af14cB

`GravyRouter`: 0xCc7aDc94F3D80127849D2b41b6439b7CF1eB4Ae0

`Frontend`: link(https://pcs.nhancv.com)

You can refer to the Uniswap SDK documentation [uniswap.org](https://uniswap.org/docs/v2/SDK/getting-started/).

## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/Gravyswap/Gravy-swap-sdk.git
```

Move into the Gravyswap-sdk working directory

```sh
cd Gravyswap-sdk/
```

Install dependencies

```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh
yarn run v1.22.4
$ tsdx test
 PASS  test/constants.test.ts
 PASS  test/pair.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/entities.test.ts
 PASS  test/trade.test.ts

Test Suites: 1 skipped, 6 passed, 6 of 7 total
Tests:       3 skipped, 82 passed, 85 total
Snapshots:   0 total
Time:        5.091s
Ran all test suites.
✨  Done in 6.61s.
```
