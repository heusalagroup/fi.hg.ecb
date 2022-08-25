# fi.hg.ecb

HG Git Module for NodeJS backends using [ecb-euro-exchange-rates](https://www.npmjs.com/package/ecb-euro-exchange-rates?activeTab=readme) as a dependency.

### Install the module

This module depends on `ecb-euro-exchange-rates` module:

```shell
npm i ecb-euro-exchange-rates
```

Our [fi.hg.core](https://github.com:heusalagroup/fi.hg.core) is also required dependency:

```shell
mkdir -p src/fi/hg
git submodule add git@github.com:heusalagroup/fi.hg.core.git src/fi/hg/core
git config -f .gitmodules submodule.src/fi/hg/core.branch main
```

Finally, you can set up the module itself:

```shell
git submodule add git@github.com:heusalagroup/fi.hg.ecb.git src/fi/hg/ecb
git config -f .gitmodules submodule.src/fi/hg/ecb.branch main
```

See also [@heusalagroup/create-backend](https://github.com/heusalagroup/create-backend) for how to initialize your own backend project.
