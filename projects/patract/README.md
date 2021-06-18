# [Patract](https://patract.io/)

## Project Introduction

Patract is a Wasm Contract Technology Lab for Polkadot. We provides full-stack support for the Wasm contract ecosystem, including on-chain contract modules, off-chain tools and services, and user-side products.

## Wasm contract technical support

**Redspot (scaffold) v0.4** [Check the codes](https://github.com/patractlabs/redspot)

Add Multi-contracts compilation support for ink! and solang.

Automatically adds types of known chains like Canvas, Jupiter, Europa, Edgeware, Plasm and Clover.

Using docker to compile contracts to ensure result's consistency.

Provide a more specialized UI explorer than Polkadot Apps and Canvas UI to assist in debugging.

Add @redspot/decimals plug-in to automatically converts the precision of numbers.

**Ask!(AssemblyScript e-DSL) v0.2** [Check the codes](https://github.com/patractlabs/ask)

Improve the sub-options of @storage, @message annotations, and add @event annotations.

Add composite data types of StorableMap, StorableArray.

Implement contract inheritance to enable contract reuse

Implement the cross-contract call function through the @dynamic annotation.

Provide example contracts such as ERC20, ERC721, crosscall, etc.

**Europa (sandbox) v0.3**  [Check the codes](https://github.com/patractlabs/europa)

Strengthen the functions related to the contract execution system in the contract UI section.

Provide the interface and UI to operate Europa's special RPC functions and display state changes.

Combined with Europa's workspace function, you can create and select different workspaces through the UI interface.

Similar to Ganache, Europa and UI will be made into binary packages for different platforms for distribution

**Ceres(Independent ink! contract environment)** [Check the codes](https://github.com/patractlabs/ceres)

the runtime of Ceres supports both wasmtime and wasmi, with the wasmi feature of Ceres, you can run your ink! contract anywhere, even in the browser.

**ZoPatract (ZoKrates for ink!) ** [Check the codes](https://github.com/patractlabs/zkmega)

ZoPatract is a toolbox adapted to ink! contract for zkSNARKs on jupiter. It is a side project for zkMega. 

**Metis(ink! and Ask! standard library) M1** [Check the codes](https://github.com/patractlabs/metis）

[M1] Implement basic component macros and components, improve component testing support, developers can build regular DAPPs based on Metis.

**PatraStore DApp store**

DApp store framework has been completed.Multi-chain account management and DApp convenient interactive system, supporting the community to carry out secondary development and independent operation. 

**PatraScan(Explorer)**

Finished Patract-Archive.

Product docs about Chain, Account, Governance.

UI Prototype Design about Chain, Account.


## Developer activity

Patract has organized PatraShare & PatraTalk courses。[Check the codes](https://www.youtube.com/channel/UCnvwkuLKx6k56M5rErH9AoQ/videos)

Patract plans to provide developers with Wasm contract guidance courses and online teaching guidance in the second half of the year.

Patract plans to launch a Wasm contract technology hackathon in the future. Please see the [official website](https://patract.io/) for the latest news.

