<!--lint disable double-link-->
# Awesome Aptos [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of code and resources from the [Aptos](https://github.com/aptos-labs/aptos-core) and [Move](https://github.com/move-language/move) communities.

## Move

- [Awesome Move](https://github.com/MystenLabs/awesome-move) - Resource list maintained by MystenLabs, we drew much inspiration from here and copied several resources here for easy access.
- [Move Book](https://move-language.github.io/move/) - Introductory e-book to Move by the official team
- [The Move Book](https://move-book.com/) - E-book to learn Move by the community 

## Reference Smart Contracts

- [Aubrium Uniswap V2 implementation](https://github.com/pentagonxyz/xyk-amm-move/blob/main/aptos/sources/xyk_amm.move) - Uniswap V2 implemented in Move, great to understand Aptos if you come from ETH and know the solidity Uniswap V2 implementation
- [Pancakeswap MasterChef](https://github.com/pancakeswap/pancake-contracts-move/blob/main/pancake-masterchef/sources/masterchef.move) - A reference MasterChef implementation (slightly bloated)

## Bug Bounty Programs

- [LiquidSwap (Pontem)](https://immunefi.com/bounty/liquidswap/) - AMM with volatile (`xy=k`) and stable pairs (`x^3y+xy^3=k`) audited by [Ottersec](https://1969469778-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7hOyaMi2Pz1hDJkk7WIF%2Fuploads%2FmvEWDi25tfOGjACf57ga%2Fpontem-liquidswap-ottersec-audit.pdf?alt=media&token=494969dd-10e2-42f9-91b3-00c1d51f7560), [Halborn](https://1969469778-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7hOyaMi2Pz1hDJkk7WIF%2Fuploads%2Fgu3YmcQ9v62UveeIy6pG%2Fpontem-liquidswap-halborn-audit.pdf?alt=media&token=7929b8c9-5073-4b36-9353-27e191d8774a) ([2](https://1969469778-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7hOyaMi2Pz1hDJkk7WIF%2Fuploads%2FXMUwFtm3tS06WYdFeuKB%2Fpontem-liquidswap-flashloan-halborn-audit.pdf?alt=media&token=88bab0a4-7853-4cda-a260-a0b1e40027db), [3](https://1969469778-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7hOyaMi2Pz1hDJkk7WIF%2Fuploads%2F9ZKrZdfRnqOFX2Z0fQ6c%2Fpontem-liquidswap-dynamic-fees-config.pdf?alt=media&token=cfe8c319-60e6-4196-82c1-721d3e11c481)) and [Zellic](https://drive.google.com/file/d/1CSnJZ_-YzUM9HZTeKXr7L4cBf3N-QFYU/view)
- [PancakeSwap](https://immunefi.com/bounty/pancakeswap/) - AMM with `xy=k` pairs and MasterChef logic.