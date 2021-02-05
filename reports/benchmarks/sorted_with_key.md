# Benchmark results for "sorted_with_key"

[Benchmark implementation](https://github.com/mypyc/mypyc-benchmarks/blob/master/microbenchmarks/sequences.py#L350)

**Note:** This is a microbenchmark. Results can be noisy.
A change of less than **15.0%** is considered insignificant.

| Date | Performance | Change | Mypy commit |
| --- | :---: | :---: | --- |
| **2021-02-04** | **1.13x** |  | [38bad9caab9b](https://github.com/python/mypy/commit/38bad9caab9b14b9fe4efdc620a003c373fbec8a) |
| 2021-02-02 | 1.12x |  | [9e0e23e97653](https://github.com/python/mypy/commit/9e0e23e97653dab3a558d34340486e7a66f7d6f0) |
| 2021-01-29 | 1.13x |  | [e43be0df1d28](https://github.com/python/mypy/commit/e43be0df1d288e8610308da334f89660a70ed3d8) |
| 2021-01-27 | 1.13x |  | [4d5a1bc75224](https://github.com/python/mypy/commit/4d5a1bc75224e1c532557861261becac7d8fdf47) |
| 2021-01-27 | 1.13x |  | [dad898605d6d](https://github.com/python/mypy/commit/dad898605d6d195e8cbf3f7e66bd61aeda208533) |
| 2021-01-27 | 1.13x |  | [844960680c1d](https://github.com/python/mypy/commit/844960680c1d5e24d05f1fa9d1357c4383cba2fe) |
| 2021-01-27 | 1.13x |  | [56061c90094b](https://github.com/python/mypy/commit/56061c90094b0d0e6ae5b4f8607892703d1e9e6b) |
| 2021-01-27 | 1.13x |  | [3bf6e7911978](https://github.com/python/mypy/commit/3bf6e7911978abfbc412119bedf8745cdde508d1) |
| 2021-01-26 | 1.13x |  | [90feccd665a0](https://github.com/python/mypy/commit/90feccd665a0abde58d5ccabb7cfde872a3aa075) |
| 2021-01-26 | 1.13x |  | [0e7b8674e27a](https://github.com/python/mypy/commit/0e7b8674e27a28320ba483c063690e6fcc35fd27) |
| 2021-01-26 | 1.13x |  | [ba037888eccd](https://github.com/python/mypy/commit/ba037888eccd0f63e193d0fefd8f4e9265b8e3d3) |
| 2021-01-25 | 1.13x |  | [68a0c654f2c7](https://github.com/python/mypy/commit/68a0c654f2c73b0ee6afaaf50a02102bc8ac6ef6) |
| 2021-01-25 | 1.13x |  | [1cebbf2285c9](https://github.com/python/mypy/commit/1cebbf2285c97ead7feaf03baeff584a159e095b) |
| 2021-01-24 | 1.13x |  | [37d29fcb30dc](https://github.com/python/mypy/commit/37d29fcb30dce646573b487f2c9375cee457724c) |
| 2021-01-24 | 1.13x |  | [91fd3445d20d](https://github.com/python/mypy/commit/91fd3445d20d6d83317a76541a252578f4ad7cb8) |
| 2021-01-24 | 1.07x |  | [9e1324d4566c](https://github.com/python/mypy/commit/9e1324d4566c1dcafaeaf2ec75ad14f2969eec0a) |
| 2021-01-24 | 1.02x |  | [e9785109fd82](https://github.com/python/mypy/commit/e9785109fd8298e73ddb2d41729ab80c514f553a) |
| 2021-01-23 | 1.04x |  | [f2a4272086a3](https://github.com/python/mypy/commit/f2a4272086a30064caaaae56274b8c01ab23a303) |
| 2021-01-23 | 0.95x |  | [e1b34b5ced06](https://github.com/python/mypy/commit/e1b34b5ced06515d9a41fb0b26f842c81b37c15e) |
| 2021-01-23 | **0.95x** | **+28.7%** | [5aa707d8223c](https://github.com/python/mypy/commit/5aa707d8223c3be8d52b26e444f3b8c67f50d2f2) |
| 2021-01-23 | 0.74x |  | [5d2ea1690f3f](https://github.com/python/mypy/commit/5d2ea1690f3fb0d6c4ba2c588cfdda8bdf22e5f5) |
| 2021-01-22 | 0.75x |  | [b53507213ed8](https://github.com/python/mypy/commit/b53507213ed805bdfb377aec48ade44a3ccd7424) |
| 2021-01-21 | 0.75x |  | [051ed611441e](https://github.com/python/mypy/commit/051ed611441e27a7e6335cbdcee35b84a8947300) |
| 2021-01-21 | 0.76x |  | [fa44143bf727](https://github.com/python/mypy/commit/fa44143bf72756ff13bd18c3b86b63d7d9c5e566) |
| 2021-01-21 | 0.75x |  | [bd47eb7bf827](https://github.com/python/mypy/commit/bd47eb7bf827b01f5560d5e5973fc30072a2e52d) |
| 2021-01-20 | 0.76x |  | [3442b70c0ea8](https://github.com/python/mypy/commit/3442b70c0ea8179ea6ddd6ec86fd65be75dd24de) |
| 2021-01-20 | 0.75x |  | [a540a1a33d5d](https://github.com/python/mypy/commit/a540a1a33d5df2611975a74b8234154fd86722cd) |
| 2021-01-19 | 0.75x |  | [37a107e49a15](https://github.com/python/mypy/commit/37a107e49a15ecde6b10643bc9b25bee1c270672) |
| 2021-01-18 | 0.75x |  | [fffbe88fc548](https://github.com/python/mypy/commit/fffbe88fc54807c8b10ac40456522ad2faf8d350) |
| 2021-01-18 | 0.76x |  | [734e4add93ac](https://github.com/python/mypy/commit/734e4add93ac88398f204f404ce7130963f147b3) |
| 2021-01-15 | 0.75x |  | [92923b2ed808](https://github.com/python/mypy/commit/92923b2ed8085a38c353382f805c9e2e8716e717) |
| 2021-01-12 | 0.76x |  | [e9edcb957f34](https://github.com/python/mypy/commit/e9edcb957f341dcf7a14bb7b7acfd4186fb1248b) |
| 2021-01-10 | 0.76x |  | [3497675c5f79](https://github.com/python/mypy/commit/3497675c5f7917eb0e8ad4b7e2b7f3bc4cfd52dc) |
| 2021-01-10 | 0.76x |  | [a4a5fd67b3ed](https://github.com/python/mypy/commit/a4a5fd67b3edea1ea39ae6a700e80d65d0ef2121) |
| 2021-01-09 | 0.75x |  | [f491f352ee99](https://github.com/python/mypy/commit/f491f352ee995d174e94b4f78290d9ce534c2e4f) |
| 2021-01-08 | 0.74x |  | [0c5936e08975](https://github.com/python/mypy/commit/0c5936e08975ce1936c86f559d128cf25d30000e) |
| 2021-01-08 | 0.74x |  | [0996c426e1ce](https://github.com/python/mypy/commit/0996c426e1cea4ccaaad54dec6b1318c3d377562) |
| 2021-01-07 | 0.74x |  | [5e20a26b922e](https://github.com/python/mypy/commit/5e20a26b922e2f5b71425ea7f57d2b4cba5a9324) |
| 2021-01-07 | 0.75x |  | [55a1b8126741](https://github.com/python/mypy/commit/55a1b8126741912329b2d271e04730f563807109) |
| 2021-01-07 | 0.75x |  | [5f5d90eee23b](https://github.com/python/mypy/commit/5f5d90eee23b809185145f6da7b18a3ca41b4879) |
| 2021-01-07 | 0.75x |  | [cfdb1f1f4c46](https://github.com/python/mypy/commit/cfdb1f1f4c46f170f2501fcf503440b2c37a6a96) |
| 2021-01-07 | 0.75x |  | [1f5115b90f3e](https://github.com/python/mypy/commit/1f5115b90f3e984e7d79ddca84b5dbe5eeddf9ec) |
| 2021-01-06 | 0.75x |  | [6e8c0cd3ef7a](https://github.com/python/mypy/commit/6e8c0cd3ef7a375e143faf237312004adcfca7d6) |
| 2021-01-06 | 0.75x |  | [28f92acae611](https://github.com/python/mypy/commit/28f92acae611ab06a72ac827e36373c198a9e4f4) |
| 2021-01-06 | 0.75x |  | [b55bfe0796dd](https://github.com/python/mypy/commit/b55bfe0796ddf6236bc21b46a48c6b961372fe79) |
| 2021-01-06 | 0.75x |  | [2853e5aa1896](https://github.com/python/mypy/commit/2853e5aa18969b56bb471e2eb2b85e6c251e33df) |
| 2021-01-05 | 0.75x |  | [3c275a3dce23](https://github.com/python/mypy/commit/3c275a3dce233ab6d53abc623069ccef3250f127) |
| 2021-01-04 | 0.75x |  | [8296a3123a10](https://github.com/python/mypy/commit/8296a3123a1066184a6c5c4bc54da1ff14983c56) |
| 2020-12-30 | 0.75x |  | [07a64450cec6](https://github.com/python/mypy/commit/07a64450cec61fafc98838d9e32d6dae63568a93) |
| 2020-12-30 | 0.75x |  | [e9f8a177d79d](https://github.com/python/mypy/commit/e9f8a177d79df978c64ff924d3fb39b2e3cd0cbc) |
| 2020-12-30 | 0.75x |  | [3c99f126ce3f](https://github.com/python/mypy/commit/3c99f126ce3f5c0b6d3fadf96525b0f831b7c524) |
| 2020-12-30 | 0.75x |  | [4f3fcdabcac4](https://github.com/python/mypy/commit/4f3fcdabcac4f21c97fed91cbe5758df2f587962) |
| 2020-12-29 | 0.75x |  | [48312289155b](https://github.com/python/mypy/commit/48312289155bb203ad12249a87692fa841e7478c) |
| 2020-12-29 | 0.75x |  | [755a9908371b](https://github.com/python/mypy/commit/755a9908371b226c3eca4f1abb85842b4c69544f) |
| 2020-12-29 | 0.75x |  | [7d99ab2b0dca](https://github.com/python/mypy/commit/7d99ab2b0dca37075347d6e50c7ec6f9716a934f) |
| 2020-12-29 | 0.75x |  | [87f867c54882](https://github.com/python/mypy/commit/87f867c548824adecca6420383abba1662c33fa5) |
| 2020-12-29 | 0.75x |  | [392883e9a958](https://github.com/python/mypy/commit/392883e9a9583f8f7a18031aa804e632e254c533) |
| 2020-12-29 | 0.75x |  | [b7c6fa3d2822](https://github.com/python/mypy/commit/b7c6fa3d2822662a510223fbf82f5d0d08af7bb5) |
| 2020-12-29 | 0.75x |  | [c3534643e219](https://github.com/python/mypy/commit/c3534643e2197319e9923bb38a0f1590f78d4696) |
| 2020-12-29 | 0.75x |  | [18ab589d0c5c](https://github.com/python/mypy/commit/18ab589d0c5c4b00ae597740fb7624791d2ad7ad) |
| 2020-12-29 | 0.74x |  | [7c0c1e7a1e86](https://github.com/python/mypy/commit/7c0c1e7a1e867dbd0469713f0bc99887b0020634) |
| 2020-12-29 | 0.74x |  | [c179eb894c98](https://github.com/python/mypy/commit/c179eb894c9878e353898e9e7898af7730b87e62) |
| 2020-12-28 | 0.74x |  | [fe8fac161784](https://github.com/python/mypy/commit/fe8fac16178447bb0abab3e759221294d4a70f3c) |
| 2020-12-28 | 0.76x |  | [7664031adfb2](https://github.com/python/mypy/commit/7664031adfb2f7082a066b53dfa41ce30449bf21) |
| 2020-12-21 | 0.78x |  | [dc251783ccb9](https://github.com/python/mypy/commit/dc251783ccb9baa48fc62d109a88854ac514816d) |
| 2020-12-19 | 0.78x |  | [28d123f025c8](https://github.com/python/mypy/commit/28d123f025c8f2ed8bb1e6b4590f3ba023f27b3a) |
| 2020-12-18 | 0.78x |  | [39698d52e933](https://github.com/python/mypy/commit/39698d52e933a30cd744c25c388c514997b6b95f) |
| 2020-12-18 | 0.78x |  | [efa62358bd98](https://github.com/python/mypy/commit/efa62358bd98943edd624779684b58be38799072) |
| 2020-12-17 | 0.78x |  | [eb0bf114743e](https://github.com/python/mypy/commit/eb0bf114743e4b2a65582e83feacb184eb5c6d64) |
| 2020-12-17 | 0.78x |  | [38409ba32469](https://github.com/python/mypy/commit/38409ba324699a42c47571bbc1b1bab7d0b032f6) |
| 2020-12-16 | 0.78x |  | [990b6a6f03ad](https://github.com/python/mypy/commit/990b6a6f03ad82c10cb8edbe70508b943336f7f3) |
| 2020-12-13 | 0.78x |  | [05d9fb15dcec](https://github.com/python/mypy/commit/05d9fb15dcec8bde4e7184ca387e7d8acea68792) |
| 2020-12-13 | 0.78x |  | [ac324950a7c9](https://github.com/python/mypy/commit/ac324950a7c95f0e51d72ae18fbd8652d37f7847) |
| 2020-12-12 | 0.78x |  | [9c54cc3f1c73](https://github.com/python/mypy/commit/9c54cc3f1c73150992345350be834f2987b3967d) |
| 2020-12-12 | 0.78x |  | [cdd5badebee3](https://github.com/python/mypy/commit/cdd5badebee3ed62be8671eb0236fe16e7510eae) |
| 2020-12-10 | 0.78x |  | [35e5031b30e2](https://github.com/python/mypy/commit/35e5031b30e25faf9aff6caacfe9b8f185fa430e) |
| 2020-12-08 | 0.78x |  | [eac1897cff2b](https://github.com/python/mypy/commit/eac1897cff2b0a24584737ba0afd1a3004d37ad1) |
| 2020-12-02 | 0.78x |  | [98eee40c8e6b](https://github.com/python/mypy/commit/98eee40c8e6b111361b3e2d69059b445852fbda3) |
| 2020-11-30 | 0.74x |  | [88f76ee0e956](https://github.com/python/mypy/commit/88f76ee0e95674cc1ff4c723a86156823fb06291) |
| 2020-11-29 | 0.74x |  | [f0c78c14588b](https://github.com/python/mypy/commit/f0c78c14588bc73541eccf24c2bf790396ddfde3) |
| 2020-11-28 | 0.74x |  | [06589112d251](https://github.com/python/mypy/commit/06589112d2513edeb90386613c2f201e72b08059) |
| 2020-11-28 | 0.74x |  | [fc212ef893a0](https://github.com/python/mypy/commit/fc212ef893a0c3e6d500be89aa4d9302c1219595) |
| 2020-11-28 | 0.74x |  | [98beb8e8febf](https://github.com/python/mypy/commit/98beb8e8febfd39992b0ba69ba15c0b2362b847d) |
| 2020-11-27 | 0.74x |  | [fdba3cd495b6](https://github.com/python/mypy/commit/fdba3cd495b657995a7283063afd1e86ff49165d) |
| 2020-11-27 | 0.74x |  | [109d05edca23](https://github.com/python/mypy/commit/109d05edca23d6f94542fb28e11e3cb0b6f7e159) |
| 2020-11-27 | 0.76x |  | [d1d999c0baaf](https://github.com/python/mypy/commit/d1d999c0baaf7218a750bbdf8df7b78e03bfe8fb) |
| 2020-11-27 | 0.75x |  | [6e5286e52425](https://github.com/python/mypy/commit/6e5286e5242519bcba8f005900312a375b0e7688) |
| 2020-11-26 | 0.76x |  | [52225ab91703](https://github.com/python/mypy/commit/52225ab91703a7283c9e4bd129402a4e43abdb66) |
| 2020-11-25 | 0.75x |  | [dbca5a54cb34](https://github.com/python/mypy/commit/dbca5a54cb343dcee4a1f93af569a9dcf13ce242) |
| 2020-11-25 | 0.75x |  | [705f8812e6ce](https://github.com/python/mypy/commit/705f8812e6ceb4aa52f729a4a1de5ea0cad15c0b) |
| 2020-11-25 | 0.75x |  | [3144640fdee1](https://github.com/python/mypy/commit/3144640fdee12700c56ea75ad238384ea1b429cc) |
| 2020-11-23 | 0.75x |  | [83b30ee6a60b](https://github.com/python/mypy/commit/83b30ee6a60bdd7c1070ce39d41c79d489183966) |
| 2020-11-20 | 0.75x |  | [40fd841a0059](https://github.com/python/mypy/commit/40fd841a005936d95e7c351435f1b7b7b4bdd43d) |