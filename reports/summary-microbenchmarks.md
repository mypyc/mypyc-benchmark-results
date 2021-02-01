# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.2, Ubuntu 20.04 LTS and Intel Core i7-2600K (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 40.29x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 20.57x |  |
| [super_method](benchmarks/super_method.md) | 19.16x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 17.57x | +24.7% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 14.50x | +22.9% |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 10.68x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 8.84x | +195.1% |
| [str_call](benchmarks/str_call.md) | 8.73x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 7.90x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 6.61x |  |
| [int_list](benchmarks/int_list.md) | 6.52x |  |
| [sieve](benchmarks/sieve.md) | 6.18x | +8.6% |
| [list_comprehension](benchmarks/list_comprehension.md) | 5.21x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.87x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 4.72x | +77.2% |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.59x |  |
| [list_insert](benchmarks/list_insert.md) | 4.29x | +182.8% |
| [dict_clear](benchmarks/dict_clear.md) | 3.97x | +24.1% |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.88x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 3.78x | +39.3% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.75x |  |
| [list_append_small](benchmarks/list_append_small.md) | 3.71x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.24x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.11x |  |
| [method_object](benchmarks/method_object.md) | 2.83x | +77.7% |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.78x |  |
| [nested_func](benchmarks/nested_func.md) | 2.74x | +85.7% |
| [in_list](benchmarks/in_list.md) | 2.68x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 2.63x | +57.3% |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.59x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.56x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.51x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.51x |  |
| [list_index](benchmarks/list_index.md) | 2.41x | +67.9% |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.40x |  |
| [float_abs](benchmarks/float_abs.md) | 2.28x | +131.9% |
| [generators](benchmarks/generators.md) | 2.08x |  |
| [str_methods](benchmarks/str_methods.md) | 2.05x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.98x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.98x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.97x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 1.93x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 1.91x |  |
| [list_remove](benchmarks/list_remove.md) | 1.86x | +35.8% |
| [list_copy](benchmarks/list_copy.md) | 1.86x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.81x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.76x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.75x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.73x | +39.5% |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.67x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.66x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.64x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.64x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.61x | +128.0% |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.59x | +158.8% |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.49x |  |
| [readline](benchmarks/readline.md) | 1.40x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.34x |  |
| [bytes_call](benchmarks/bytes_call.md) | 1.33x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.32x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.31x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.31x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.30x |  |
| [str_searching](benchmarks/str_searching.md) | 1.29x |  |
| [list_equality](benchmarks/list_equality.md) | 1.27x |  |
| [str_format](benchmarks/str_format.md) | 1.26x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.24x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.24x | +316.6% |
| [encode_decode](benchmarks/encode_decode.md) | 1.23x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.21x | -5.0% |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.19x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.19x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.15x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.13x | +49.5% |
| [int_to_float](benchmarks/int_to_float.md) | 1.12x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.11x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.09x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.08x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.00x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.98x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.98x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.97x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.95x | +17.5% |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.80x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.70x |  |
