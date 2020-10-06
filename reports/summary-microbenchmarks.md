# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.2, Ubuntu 20.04 LTS and Intel Core i7-2600K (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [super_method_alt](benchmarks/super_method_alt.md) | 18.27x |  |
| [super_method](benchmarks/super_method.md) | 16.67x |  |
| [int_binary_ops](benchmarks/int_binary_ops.md) | 9.16x | +1162.2% |
| [str_call](benchmarks/str_call.md) | 8.09x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 6.36x |  |
| [sieve](benchmarks/sieve.md) | 6.00x | +7.0% |
| [int_list](benchmarks/int_list.md) | 5.57x | +29.0% |
| [list_comprehension](benchmarks/list_comprehension.md) | 4.99x | +22.0% |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.86x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.49x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.93x | +16.2% |
| [list_append_small](benchmarks/list_append_small.md) | 3.56x |  |
| [dict_clear](benchmarks/dict_clear.md) | 3.49x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.48x | +136.8% |
| [in_tuple](benchmarks/in_tuple.md) | 3.09x | +261.6% |
| [str_slicing](benchmarks/str_slicing.md) | 3.02x | +85.4% |
| [tuple_equality](benchmarks/tuple_equality.md) | 2.74x | +204.3% |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.71x | +58.0% |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.67x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.58x |  |
| [in_list](benchmarks/in_list.md) | 2.54x | +297.0% |
| [list_slicing](benchmarks/list_slicing.md) | 2.43x | +46.6% |
| [list_append_large](benchmarks/list_append_large.md) | 2.33x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.20x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.12x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.07x |  |
| [generators](benchmarks/generators.md) | 2.05x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.95x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.84x | +15.5% |
| [list_copy](benchmarks/list_copy.md) | 1.80x | +30.8% |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.75x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 1.73x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.71x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.66x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.65x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.63x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.58x |  |
| [method_object](benchmarks/method_object.md) | 1.52x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.52x |  |
| [nested_func](benchmarks/nested_func.md) | 1.49x |  |
| [list_insert](benchmarks/list_insert.md) | 1.49x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.43x |  |
| [readline](benchmarks/readline.md) | 1.39x |  |
| [str_methods](benchmarks/str_methods.md) | 1.37x |  |
| [list_index](benchmarks/list_index.md) | 1.35x |  |
| [str_searching](benchmarks/str_searching.md) | 1.33x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.31x |  |
| [list_remove](benchmarks/list_remove.md) | 1.29x |  |
| [str_format](benchmarks/str_format.md) | 1.28x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.28x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.27x |  |
| [list_equality](benchmarks/list_equality.md) | 1.27x |  |
| [int_long_binary_ops](benchmarks/int_long_binary_ops.md) | 1.24x |  |
| [bytes_call](benchmarks/bytes_call.md) | 1.24x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.23x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.20x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.20x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.19x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.17x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.15x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.12x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.07x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.01x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [float_abs](benchmarks/float_abs.md) | 1.01x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.00x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.00x |  |
| [int_to_float](benchmarks/int_to_float.md) | 0.97x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.80x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 0.77x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.70x |  |
