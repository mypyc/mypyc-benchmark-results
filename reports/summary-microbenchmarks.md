# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.5, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 38.61x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 22.19x |  |
| [super_method](benchmarks/super_method.md) | 19.26x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 19.17x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 12.96x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 10.82x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 10.43x |  |
| [str_call](benchmarks/str_call.md) | 9.11x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 7.88x |  |
| [int_list](benchmarks/int_list.md) | 7.04x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 6.69x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.13x |  |
| [sieve](benchmarks/sieve.md) | 5.87x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 5.67x |  |
| [dict_clear](benchmarks/dict_clear.md) | 5.07x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.50x |  |
| [str_format](benchmarks/str_format.md) | 4.19x | +214.8% |
| [method_object](benchmarks/method_object.md) | 4.04x |  |
| [list_insert](benchmarks/list_insert.md) | 4.02x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 3.99x |  |
| [list_append_small](benchmarks/list_append_small.md) | 3.97x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.84x | +166.2% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.67x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 3.52x | +33.2% |
| [str_slicing](benchmarks/str_slicing.md) | 3.38x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.35x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.04x |  |
| [float_abs](benchmarks/float_abs.md) | 3.04x |  |
| [nested_func](benchmarks/nested_func.md) | 2.91x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 2.89x |  |
| [in_tuple](benchmarks/in_tuple.md) | 2.82x |  |
| [in_list](benchmarks/in_list.md) | 2.75x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.63x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.57x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.54x |  |
| [list_index](benchmarks/list_index.md) | 2.36x |  |
| [str_methods](benchmarks/str_methods.md) | 2.32x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 2.26x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.23x |  |
| [generators](benchmarks/generators.md) | 2.21x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.05x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.02x | +26.7% |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.02x |  |
| [list_remove](benchmarks/list_remove.md) | 1.95x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.92x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.91x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.86x | +18.9% |
| [str_to_float](benchmarks/str_to_float.md) | 1.85x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.82x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.80x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.77x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.70x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.66x |  |
| [list_copy](benchmarks/list_copy.md) | 1.66x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.65x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.62x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.59x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.56x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.56x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.51x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.50x |  |
| [str_searching](benchmarks/str_searching.md) | 1.47x |  |
| [readline](benchmarks/readline.md) | 1.47x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.41x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.40x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.39x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.34x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.27x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.25x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.24x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.22x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.20x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.19x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.18x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.13x |  |
| [list_equality](benchmarks/list_equality.md) | 1.11x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.11x | +15.4% |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 1.09x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.98x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.98x | -17.0% |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.95x |  |
| [dict_copy](benchmarks/dict_copy.md) | 0.91x | -52.0% |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.90x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.82x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.68x |  |
