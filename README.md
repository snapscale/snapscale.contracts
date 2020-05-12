
<a href="#chinese">点击此处直达中文版 </a>


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

All repositories and other materials are provided subject to the terms of this [IMPORTANT](./IMPORTANT.md) notice and you must familiarize yourself with its terms.  The notice contains important information, limitations and restrictions relating to our software, publications, trademarks, third-party resources, and forward-looking statements.  By accessing any of our repositories and other materials, you accept and agree to the terms of the notice. <br>

<br>

---

<a id="chinese"></a><br>
# SnapScale 智能合约

## Version : 1.9.1

SnapScale 的设计需要支持很多特权合约的部署，比如支持区块生产者注册之类的功能。SnapScale的 基础智能合约包括：boot, bios, system, msig, wrap 和 token。

该存储库包含这些特权合约的示例，这些示例在部署，管理和/或使用SnapScale 区块链时非常有用，以下仅供参考：

   * [boot](./contracts/eosio.boot)
   * [bios](./contracts/eosio.bios)
   * [system](./contracts/eosio.system)
   * [msig](./contracts/eosio.msig)
   * [wrap](./contracts/eosio.wrap)


以下非特权合约也是系统的一部分
   * [eosio.token](./contracts/eosio.token)

依存关系：
* [snapscale.cdt](https://github.com/SnapScale/snapscale.cdt)
* [snapscale](https://github.com/SnapScale/snapscale) (可选依赖项仅用于构建单元测试)

构建合约，请遵循[`构建和部署`](./docs/02_build-and-deploy.md)中的说明。


## 许可协议

SnapScale 遵循Apache 2.0 开源协议发布，按“原样”提供，没有任何明示或暗示的担保。SnapScale 软件提供的任何安全性部分取决于它的使用，配置和部署方式。 SnapScale 建立在许多第三方库上，如Binaryen（Apache许可证）和WAVM（BSD 3-clause），它们也是“按现状”提供的，没有任何形式的保证。


## 重要事项

有关版权和许可条款，请参考[许可协议](./LICENSE) 。

我们提供的所有信息都受限于本[重要通知](./IMPORTANT.md) 您必须熟悉其中的条款。该通知包含了关于我们的软件、发布、商标、第三方资源和前瞻性声明的重要信息、条件和限制。您获取任何材料的时候就意味着您接受并同意该通知的条款。
