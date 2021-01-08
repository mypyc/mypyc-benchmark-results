# Benchmark results for "create_namedtuple"

[Benchmark implementation](https://github.com/mypyc/mypyc-benchmarks/blob/master/microbenchmarks/namedtuples.py#L11)

**Note:** This is a microbenchmark. Results can be noisy.
A change of less than **15.0%** is considered insignificant.

| Date | Performance | Change | Mypy commit |
| --- | :---: | :---: | --- |
| **2021-01-08** | **1.07x** |  | [0c5936e08975](https://github.com/python/mypy/commit/0c5936e08975ce1936c86f559d128cf25d30000e) |
| 2021-01-08 | 1.06x |  | [0996c426e1ce](https://github.com/python/mypy/commit/0996c426e1cea4ccaaad54dec6b1318c3d377562) |
| 2021-01-07 | 1.06x |  | [5e20a26b922e](https://github.com/python/mypy/commit/5e20a26b922e2f5b71425ea7f57d2b4cba5a9324) |
| 2021-01-07 | 1.05x |  | [55a1b8126741](https://github.com/python/mypy/commit/55a1b8126741912329b2d271e04730f563807109) |
| 2021-01-07 | 1.05x |  | [5f5d90eee23b](https://github.com/python/mypy/commit/5f5d90eee23b809185145f6da7b18a3ca41b4879) |
| 2021-01-07 | 1.04x |  | [cfdb1f1f4c46](https://github.com/python/mypy/commit/cfdb1f1f4c46f170f2501fcf503440b2c37a6a96) |
| 2021-01-07 | 1.05x |  | [1f5115b90f3e](https://github.com/python/mypy/commit/1f5115b90f3e984e7d79ddca84b5dbe5eeddf9ec) |
| 2021-01-06 | 1.05x |  | [6e8c0cd3ef7a](https://github.com/python/mypy/commit/6e8c0cd3ef7a375e143faf237312004adcfca7d6) |
| 2021-01-06 | 1.04x |  | [28f92acae611](https://github.com/python/mypy/commit/28f92acae611ab06a72ac827e36373c198a9e4f4) |
| 2021-01-06 | 1.04x |  | [b55bfe0796dd](https://github.com/python/mypy/commit/b55bfe0796ddf6236bc21b46a48c6b961372fe79) |
| 2021-01-06 | 1.04x |  | [2853e5aa1896](https://github.com/python/mypy/commit/2853e5aa18969b56bb471e2eb2b85e6c251e33df) |
| 2021-01-05 | 1.05x |  | [3c275a3dce23](https://github.com/python/mypy/commit/3c275a3dce233ab6d53abc623069ccef3250f127) |
| 2021-01-04 | 1.04x |  | [8296a3123a10](https://github.com/python/mypy/commit/8296a3123a1066184a6c5c4bc54da1ff14983c56) |
| 2020-12-30 | 1.05x |  | [07a64450cec6](https://github.com/python/mypy/commit/07a64450cec61fafc98838d9e32d6dae63568a93) |
| 2020-12-30 | 1.05x |  | [e9f8a177d79d](https://github.com/python/mypy/commit/e9f8a177d79df978c64ff924d3fb39b2e3cd0cbc) |
| 2020-12-30 | 1.05x |  | [3c99f126ce3f](https://github.com/python/mypy/commit/3c99f126ce3f5c0b6d3fadf96525b0f831b7c524) |
| 2020-12-30 | 1.05x |  | [4f3fcdabcac4](https://github.com/python/mypy/commit/4f3fcdabcac4f21c97fed91cbe5758df2f587962) |
| 2020-12-29 | 1.05x |  | [48312289155b](https://github.com/python/mypy/commit/48312289155bb203ad12249a87692fa841e7478c) |
| 2020-12-29 | 1.04x |  | [755a9908371b](https://github.com/python/mypy/commit/755a9908371b226c3eca4f1abb85842b4c69544f) |
| 2020-12-29 | 1.04x |  | [7d99ab2b0dca](https://github.com/python/mypy/commit/7d99ab2b0dca37075347d6e50c7ec6f9716a934f) |
| 2020-12-29 | 1.05x |  | [87f867c54882](https://github.com/python/mypy/commit/87f867c548824adecca6420383abba1662c33fa5) |
| 2020-12-29 | 1.04x |  | [392883e9a958](https://github.com/python/mypy/commit/392883e9a9583f8f7a18031aa804e632e254c533) |
| 2020-12-29 | 1.04x |  | [b7c6fa3d2822](https://github.com/python/mypy/commit/b7c6fa3d2822662a510223fbf82f5d0d08af7bb5) |
| 2020-12-29 | 1.04x |  | [c3534643e219](https://github.com/python/mypy/commit/c3534643e2197319e9923bb38a0f1590f78d4696) |
| 2020-12-29 | 1.05x |  | [18ab589d0c5c](https://github.com/python/mypy/commit/18ab589d0c5c4b00ae597740fb7624791d2ad7ad) |
| 2020-12-29 | 1.06x |  | [7c0c1e7a1e86](https://github.com/python/mypy/commit/7c0c1e7a1e867dbd0469713f0bc99887b0020634) |
| 2020-12-29 | 1.06x |  | [c179eb894c98](https://github.com/python/mypy/commit/c179eb894c9878e353898e9e7898af7730b87e62) |
| 2020-12-28 | 1.06x |  | [fe8fac161784](https://github.com/python/mypy/commit/fe8fac16178447bb0abab3e759221294d4a70f3c) |
| 2020-12-28 | 1.06x |  | [7664031adfb2](https://github.com/python/mypy/commit/7664031adfb2f7082a066b53dfa41ce30449bf21) |
| 2020-12-21 | 1.06x |  | [dc251783ccb9](https://github.com/python/mypy/commit/dc251783ccb9baa48fc62d109a88854ac514816d) |
| 2020-12-19 | 1.06x |  | [28d123f025c8](https://github.com/python/mypy/commit/28d123f025c8f2ed8bb1e6b4590f3ba023f27b3a) |
| 2020-12-18 | 1.05x |  | [39698d52e933](https://github.com/python/mypy/commit/39698d52e933a30cd744c25c388c514997b6b95f) |
| 2020-12-18 | 1.06x |  | [efa62358bd98](https://github.com/python/mypy/commit/efa62358bd98943edd624779684b58be38799072) |
| 2020-12-17 | 1.06x |  | [eb0bf114743e](https://github.com/python/mypy/commit/eb0bf114743e4b2a65582e83feacb184eb5c6d64) |
| 2020-12-17 | 1.06x |  | [38409ba32469](https://github.com/python/mypy/commit/38409ba324699a42c47571bbc1b1bab7d0b032f6) |
| 2020-12-16 | 1.06x |  | [990b6a6f03ad](https://github.com/python/mypy/commit/990b6a6f03ad82c10cb8edbe70508b943336f7f3) |
| 2020-12-13 | 1.06x |  | [05d9fb15dcec](https://github.com/python/mypy/commit/05d9fb15dcec8bde4e7184ca387e7d8acea68792) |
| 2020-12-13 | 1.06x |  | [ac324950a7c9](https://github.com/python/mypy/commit/ac324950a7c95f0e51d72ae18fbd8652d37f7847) |
| 2020-12-12 | 1.06x |  | [9c54cc3f1c73](https://github.com/python/mypy/commit/9c54cc3f1c73150992345350be834f2987b3967d) |
| 2020-12-12 | 1.06x |  | [cdd5badebee3](https://github.com/python/mypy/commit/cdd5badebee3ed62be8671eb0236fe16e7510eae) |
| 2020-12-10 | 1.06x |  | [35e5031b30e2](https://github.com/python/mypy/commit/35e5031b30e25faf9aff6caacfe9b8f185fa430e) |
| 2020-12-08 | 1.06x |  | [eac1897cff2b](https://github.com/python/mypy/commit/eac1897cff2b0a24584737ba0afd1a3004d37ad1) |
| 2020-12-02 | 1.06x |  | [98eee40c8e6b](https://github.com/python/mypy/commit/98eee40c8e6b111361b3e2d69059b445852fbda3) |
| 2020-11-30 | 1.08x |  | [88f76ee0e956](https://github.com/python/mypy/commit/88f76ee0e95674cc1ff4c723a86156823fb06291) |
| 2020-11-29 | 1.07x |  | [f0c78c14588b](https://github.com/python/mypy/commit/f0c78c14588bc73541eccf24c2bf790396ddfde3) |
| 2020-11-28 | 1.07x |  | [06589112d251](https://github.com/python/mypy/commit/06589112d2513edeb90386613c2f201e72b08059) |
| 2020-11-28 | 1.08x |  | [fc212ef893a0](https://github.com/python/mypy/commit/fc212ef893a0c3e6d500be89aa4d9302c1219595) |
| 2020-11-28 | 1.07x |  | [98beb8e8febf](https://github.com/python/mypy/commit/98beb8e8febfd39992b0ba69ba15c0b2362b847d) |
| 2020-11-27 | 1.07x |  | [fdba3cd495b6](https://github.com/python/mypy/commit/fdba3cd495b657995a7283063afd1e86ff49165d) |
| 2020-11-27 | 1.07x |  | [109d05edca23](https://github.com/python/mypy/commit/109d05edca23d6f94542fb28e11e3cb0b6f7e159) |
| 2020-11-27 | 1.07x |  | [d1d999c0baaf](https://github.com/python/mypy/commit/d1d999c0baaf7218a750bbdf8df7b78e03bfe8fb) |
| 2020-11-27 | 1.07x |  | [6e5286e52425](https://github.com/python/mypy/commit/6e5286e5242519bcba8f005900312a375b0e7688) |
| 2020-11-26 | 1.07x |  | [52225ab91703](https://github.com/python/mypy/commit/52225ab91703a7283c9e4bd129402a4e43abdb66) |
| 2020-11-25 | 1.07x |  | [dbca5a54cb34](https://github.com/python/mypy/commit/dbca5a54cb343dcee4a1f93af569a9dcf13ce242) |
| 2020-11-25 | 1.06x |  | [705f8812e6ce](https://github.com/python/mypy/commit/705f8812e6ceb4aa52f729a4a1de5ea0cad15c0b) |
| 2020-11-25 | 1.07x |  | [3144640fdee1](https://github.com/python/mypy/commit/3144640fdee12700c56ea75ad238384ea1b429cc) |
| 2020-11-23 | 1.07x |  | [83b30ee6a60b](https://github.com/python/mypy/commit/83b30ee6a60bdd7c1070ce39d41c79d489183966) |
| 2020-11-20 | 1.07x |  | [40fd841a0059](https://github.com/python/mypy/commit/40fd841a005936d95e7c351435f1b7b7b4bdd43d) |
| 2020-11-18 | 1.06x |  | [6e99a2db100d](https://github.com/python/mypy/commit/6e99a2db100d794b1bf900746470527cd03fce16) |
| 2020-11-17 | 1.06x |  | [849a7f73d864](https://github.com/python/mypy/commit/849a7f73d864603ea4feae99a98ef5d74869e2af) |
| 2020-11-17 | 1.07x |  | [0c80091ee4d9](https://github.com/python/mypy/commit/0c80091ee4d99462db093fce4334890fb9e2411d) |
| 2020-11-17 | 1.07x |  | [fadb27f1b5c9](https://github.com/python/mypy/commit/fadb27f1b5c933d5efb4d5910b3d3d540c5f7a72) |
| 2020-11-16 | 1.07x |  | [260ac5fda39c](https://github.com/python/mypy/commit/260ac5fda39c0b0314fe85af2c18c4e25195a155) |
| 2020-11-16 | 1.06x |  | [6272beb59cd3](https://github.com/python/mypy/commit/6272beb59cd3721c1ce73934f4988602b212a21d) |
| 2020-11-14 | 1.07x |  | [d4dc00f63b70](https://github.com/python/mypy/commit/d4dc00f63b70c6a95b0cf463a64e94872a42d5eb) |
| 2020-11-14 | 1.06x |  | [37c4e2f702ae](https://github.com/python/mypy/commit/37c4e2f702ae2c188f6a79b35d18a766cc019407) |
| 2020-11-12 | 1.07x |  | [a79f1aaade9f](https://github.com/python/mypy/commit/a79f1aaade9fe150a4bc9bb1d5ad287824298f74) |
| 2020-11-11 | 1.06x |  | [bb3306e94809](https://github.com/python/mypy/commit/bb3306e948093b5323c0c63096c3557d890c059f) |
| 2020-11-04 | 1.07x |  | [2695e9589ac0](https://github.com/python/mypy/commit/2695e9589ac0f2c729a3c4b62903ca86a9125569) |