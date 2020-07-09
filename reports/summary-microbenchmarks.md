# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.2, Ubuntu 20.04 LTS and Intel Core i7-2600K (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [super_method_alt](benchmarks/super_method_alt.md) | 17.80x | +1258.4% |
| [super_method](benchmarks/super_method.md) | 15.59x |  |
| [str_call](benchmarks/str_call.md) | 8.57x | +49.6% |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 5.86x |  |
| [sieve](benchmarks/sieve.md) | 5.60x | -3.8% |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.61x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.39x | +102.9% |
| [int_list](benchmarks/int_list.md) | 4.32x | -18.3% |
| [list_comprehension](benchmarks/list_comprehension.md) | 4.09x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.38x |  |
| [list_append_small](benchmarks/list_append_small.md) | 3.31x |  |
| [dict_clear](benchmarks/dict_clear.md) | 3.29x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.78x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.33x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.22x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.14x | +54.6% |
| [generators](benchmarks/generators.md) | 2.06x | +21.1% |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.05x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.92x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 1.91x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.88x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.86x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.74x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.74x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 1.72x |  |
| [list_slicing](benchmarks/list_slicing.md) | 1.66x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 1.63x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.63x |  |
| [str_slicing](benchmarks/str_slicing.md) | 1.63x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.59x |  |
| [list_insert](benchmarks/list_insert.md) | 1.57x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.55x |  |
| [method_object](benchmarks/method_object.md) | 1.50x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.50x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 1.47x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.45x | -17.2% |
| [nested_func](benchmarks/nested_func.md) | 1.44x |  |
| [list_copy](benchmarks/list_copy.md) | 1.37x |  |
| [str_methods](benchmarks/str_methods.md) | 1.37x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.36x |  |
| [list_index](benchmarks/list_index.md) | 1.35x |  |
| [readline](benchmarks/readline.md) | 1.34x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.33x |  |
| [str_searching](benchmarks/str_searching.md) | 1.32x |  |
| [str_format](benchmarks/str_format.md) | 1.31x |  |
| [bytes_call](benchmarks/bytes_call.md) | 1.30x |  |
| [list_remove](benchmarks/list_remove.md) | 1.28x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.27x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.22x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.21x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.21x |  |
| [list_equality](benchmarks/list_equality.md) | 1.19x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.18x |  |
| [int_long_binary_ops](benchmarks/int_long_binary_ops.md) | 1.16x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.15x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.12x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.09x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.04x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.00x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.99x |  |
| [str_to_float](benchmarks/str_to_float.md) | 0.98x |  |
| [int_to_float](benchmarks/int_to_float.md) | 0.96x |  |
| [float_abs](benchmarks/float_abs.md) | 0.92x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 0.90x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 0.86x |  |
| [in_tuple](benchmarks/in_tuple.md) | 0.85x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.82x |  |
| [int_binary_ops](benchmarks/int_binary_ops.md) | 0.73x |  |
| [in_list](benchmarks/in_list.md) | 0.64x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.62x |  |
