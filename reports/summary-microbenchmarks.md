# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.2, Ubuntu 20.04 LTS and Intel Core i7-2600K (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [super_method](benchmarks/super_method.md) | 16.32x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 6.38x |  |
| [str_call](benchmarks/str_call.md) | 4.80x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.76x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.57x | +111.6% |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.43x |  |
| [dict_clear](benchmarks/dict_clear.md) | 3.32x |  |
| [list_append_small](benchmarks/list_append_small.md) | 3.16x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.70x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.55x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.29x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.22x | +60.8% |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.94x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 1.91x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.90x |  |
| [generators](benchmarks/generators.md) | 1.89x |  |
| [list_slicing](benchmarks/list_slicing.md) | 1.82x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 1.79x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.75x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.75x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.72x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.70x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.65x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 1.62x |  |
| [list_insert](benchmarks/list_insert.md) | 1.62x |  |
| [method_object](benchmarks/method_object.md) | 1.51x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.48x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.46x |  |
| [str_slicing](benchmarks/str_slicing.md) | 1.45x |  |
| [list_index](benchmarks/list_index.md) | 1.44x |  |
| [nested_func](benchmarks/nested_func.md) | 1.42x |  |
| [list_copy](benchmarks/list_copy.md) | 1.40x |  |
| [str_methods](benchmarks/str_methods.md) | 1.40x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.36x |  |
| [readline](benchmarks/readline.md) | 1.33x |  |
| [str_format](benchmarks/str_format.md) | 1.33x |  |
| [str_searching](benchmarks/str_searching.md) | 1.32x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.32x |  |
| [list_remove](benchmarks/list_remove.md) | 1.29x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 1.28x |  |
| [bytes_call](benchmarks/bytes_call.md) | 1.28x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.27x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.23x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.23x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.20x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.19x |  |
| [int_long_binary_ops](benchmarks/int_long_binary_ops.md) | 1.12x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.09x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.08x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.00x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.00x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.84x |  |
| [in_tuple](benchmarks/in_tuple.md) | 0.82x |  |
| [int_binary_ops](benchmarks/int_binary_ops.md) | 0.77x |  |
| [in_list](benchmarks/in_list.md) | 0.64x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.63x |  |
