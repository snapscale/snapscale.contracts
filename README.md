# Snapscale Contracts

## Version : 1.9.1

The design of the SnapScale blockchain calls for a number of smart contracts that are run at a privileged permission level in order to support functions such as block producer registration. These smart contracts are referred to as the bios, system, msig, wrap (formerly known as sudo) and token contracts.

This repository contains examples of these privileged contracts that are useful when deploying, managing, and/or using the SnapScale blockchain. They are provided for reference purposes:


   * [eosio.bios](./contracts/eosio.bios)
   * [eosio.system](./contracts/eosio.system)
   * [eosio.msig](./contracts/eosio.msig)
   * [eosio.wrap](./contracts/eosio.wrap)

The following unprivileged contract(s) are also part of the system.
   * [eosio.token](./contracts/eosio.token)

Dependencies:
* [snapscale.cdt](https://github.com/SnapScale/snapscale.cdt)
* [snapscale](https://github.com/SnapScale/snapscale) (optional dependency only needed to build unit tests)

To build the contracts follow the instructions in [`Build and deploy` section](./docs/02_build-and-deploy.md).


## License

[MIT](./LICENSE)

SnapScale is released under the Apache 2.0 license and is offered “AS IS” without warranty of any kind, express or implied. Any security provided by the SnapScale software depends in part on how it is used, configured, and deployed. SnapScale is built upon many third-party libraries such as WABT (Apache License) and WAVM (BSD 3-clause) which are also provided “AS IS” without warranty of any kind.

## Important

See [LICENSE](./LICENSE) for copyright and license terms.

All repositories and other materials are provided subject to the terms of this [IMPORTANT](./IMPORTANT.md) notice and you must familiarize yourself with its terms.  The notice contains important information, limitations and restrictions relating to our software, publications, trademarks, third-party resources, and forward-looking statements.  By accessing any of our repositories and other materials, you accept and agree to the terms of the notice.
