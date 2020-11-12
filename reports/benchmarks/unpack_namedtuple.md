# Benchmark results for "unpack_namedtuple"

[Benchmark implementation](https://github.com/mypyc/mypyc-benchmarks/blob/master/microbenchmarks/namedtuples.py#L27)

**Note:** This is a microbenchmark. Results can be noisy.
A change of less than **15.0%** is considered insignificant.

| Date | Performance | Change | Mypy commit |
| --- | :---: | :---: | --- |
| **2020-11-12** | **3.01x** |  | [a79f1aaade9f](https://github.com/python/mypy/commit/a79f1aaade9fe150a4bc9bb1d5ad287824298f74) |
| 2020-11-11 | 3.02x |  | [bb3306e94809](https://github.com/python/mypy/commit/bb3306e948093b5323c0c63096c3557d890c059f) |
| 2020-11-04 | 3.00x |  | [2695e9589ac0](https://github.com/python/mypy/commit/2695e9589ac0f2c729a3c4b62903ca86a9125569) |