# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.5, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 40.48x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 22.52x |  |
| [super_method](benchmarks/super_method.md) | 19.99x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 18.10x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 13.51x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 10.80x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 10.35x |  |
| [str_call](benchmarks/str_call.md) | 9.05x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 8.07x |  |
| [int_list](benchmarks/int_list.md) | 7.37x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 6.70x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 5.94x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 5.65x |  |
| [sieve](benchmarks/sieve.md) | 5.59x |  |
| [dict_clear](benchmarks/dict_clear.md) | 5.04x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.49x |  |
| [str_format](benchmarks/str_format.md) | 4.32x | +225.8% |
| [method_object](benchmarks/method_object.md) | 4.07x |  |
| [list_append_small](benchmarks/list_append_small.md) | 4.00x |  |
| [list_insert](benchmarks/list_insert.md) | 3.99x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 3.97x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.59x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.36x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.29x |  |
| [float_abs](benchmarks/float_abs.md) | 3.10x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.04x |  |
| [nested_func](benchmarks/nested_func.md) | 2.89x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 2.88x |  |
| [in_list](benchmarks/in_list.md) | 2.80x |  |
| [in_tuple](benchmarks/in_tuple.md) | 2.80x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.63x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.63x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.62x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.55x |  |
| [str_methods](benchmarks/str_methods.md) | 2.38x |  |
| [list_index](benchmarks/list_index.md) | 2.36x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 2.21x |  |
| [generators](benchmarks/generators.md) | 2.19x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.18x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.05x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.01x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.94x |  |
| [list_remove](benchmarks/list_remove.md) | 1.93x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.92x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.91x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.86x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.82x | +15.9% |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.80x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 1.75x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.75x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.69x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.67x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.66x |  |
| [list_copy](benchmarks/list_copy.md) | 1.64x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.63x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.62x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.62x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.51x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.51x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.48x |  |
| [readline](benchmarks/readline.md) | 1.47x |  |
| [bytes_call](benchmarks/bytes_call.md) | 1.45x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.43x |  |
| [str_searching](benchmarks/str_searching.md) | 1.42x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.40x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.36x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.30x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.28x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.24x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.23x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.23x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.21x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.20x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.18x |  |
| [list_equality](benchmarks/list_equality.md) | 1.15x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.14x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.05x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.00x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 1.00x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.98x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.98x | -17.6% |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.96x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.90x |  |
| [dict_copy](benchmarks/dict_copy.md) | 0.89x | -53.3% |
| [read_write_close](benchmarks/read_write_close.md) | 0.84x | -16.2% |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.69x |  |
