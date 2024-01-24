<p align="center">
  <a href="https://algebra.finance/"><img alt="Algebra" src="logo.svg" width="360"></a>
</p>

<p align="center">
Innovative DEX with concentrated liquidity and customizable plugins.
</p>
 
<p align="center">
<a href="https://github.com/cryptoalgebra/Algebra/actions/workflows/tests_plugin.yml"><img alt="Tests status" src="https://github.com/cryptoalgebra/Algebra/actions/workflows/tests_plugin.yml/badge.svg"></a>
</p>
<p align="center">
<a href="https://github.com/cryptoalgebra/Algebra/actions/workflows/echidna_plugin.yml"><img alt="Echidna status" src="https://github.com/cryptoalgebra/Algebra/actions/workflows/echidna_plugin.yml/badge.svg"></a>
</p>


- [Docs](#docs)
- [Build](#build)
- [Tests](#tests)

## Docs

The documentation page is located at: <a href="https://cryptoalgebra.gitbook.io/algebra-integral/">https://cryptoalgebra.gitbook.io/algebra-integral/</a>


## Build

*Requires npm >= 8.0.0*

To install dependencies, you need to run the command in the root directory:
```
$ npm run bootstrap
```
This will download and install dependencies for all modules and set up husky hooks.



To compile a specific module, you need to run the following command in the module folder:
```
$ npm run compile
```


## Tests

Tests for a specific module are run by the following command in the module folder:
```
$ npm run test
```

