# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.2, Ubuntu 20.04 LTS and Intel Core i7-2600K (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [super_method_alt](benchmarks/super_method_alt.md) | 18.24x | +1325.1% |
| [super_method](benchmarks/super_method.md) | 16.80x |  |
| [str_call](benchmarks/str_call.md) | 7.96x | +65.9% |
| [sieve](benchmarks/sieve.md) | 6.16x | +5.9% |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 6.16x |  |
| [int_list](benchmarks/int_list.md) | 5.58x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 5.05x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.86x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.27x | +97.1% |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.90x | +13.7% |
| [list_append_small](benchmarks/list_append_small.md) | 3.43x |  |
| [dict_clear](benchmarks/dict_clear.md) | 3.39x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.65x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.56x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.31x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.31x |  |
| [generators](benchmarks/generators.md) | 2.08x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.08x | +50.8% |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.08x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.92x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.83x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.82x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.78x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.72x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.71x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 1.69x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.68x |  |
| [str_slicing](benchmarks/str_slicing.md) | 1.67x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.61x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 1.60x |  |
| [list_slicing](benchmarks/list_slicing.md) | 1.55x |  |
| [list_insert](benchmarks/list_insert.md) | 1.54x |  |
| [method_object](benchmarks/method_object.md) | 1.53x |  |
| [nested_func](benchmarks/nested_func.md) | 1.47x |  |
| [list_copy](benchmarks/list_copy.md) | 1.45x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.43x |  |
| [readline](benchmarks/readline.md) | 1.39x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.38x |  |
| [list_index](benchmarks/list_index.md) | 1.38x |  |
| [str_methods](benchmarks/str_methods.md) | 1.36x |  |
| [str_searching](benchmarks/str_searching.md) | 1.33x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.33x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 1.31x |  |
| [list_remove](benchmarks/list_remove.md) | 1.30x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.30x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.29x |  |
| [list_equality](benchmarks/list_equality.md) | 1.26x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.24x |  |
| [str_format](benchmarks/str_format.md) | 1.24x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.24x | -3.3% |
| [bytes_call](benchmarks/bytes_call.md) | 1.23x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.21x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.16x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.15x |  |
| [int_long_binary_ops](benchmarks/int_long_binary_ops.md) | 1.14x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.13x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.10x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.07x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.00x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.00x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.00x |  |
| [float_abs](benchmarks/float_abs.md) | 1.00x |  |
| [str_to_float](benchmarks/str_to_float.md) | 0.98x |  |
| [int_to_float](benchmarks/int_to_float.md) | 0.98x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 0.90x |  |
| [in_tuple](benchmarks/in_tuple.md) | 0.84x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 0.83x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.83x |  |
| [int_binary_ops](benchmarks/int_binary_ops.md) | 0.80x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.72x |  |
| [in_list](benchmarks/in_list.md) | 0.62x |  |
