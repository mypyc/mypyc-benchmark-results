# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.5, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [min_max_pair](benchmarks/min_max_pair.md) | 59.65x |  |
| [enums](benchmarks/enums.md) | 52.78x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 40.58x | +17.4% |
| [attrs_method](benchmarks/attrs_method.md) | 35.52x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 35.08x |  |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 31.43x |  |
| [super_method](benchmarks/super_method.md) | 31.35x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 30.42x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 29.99x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 23.94x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 20.03x | +19.8% |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 15.11x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 12.10x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 11.09x |  |
| [int_list](benchmarks/int_list.md) | 10.83x |  |
| [str_call](benchmarks/str_call.md) | 10.16x |  |
| [sieve](benchmarks/sieve.md) | 8.33x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 8.23x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.64x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 6.64x |  |
| [dict_clear](benchmarks/dict_clear.md) | 6.08x |  |
| [list_append_small](benchmarks/list_append_small.md) | 5.23x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 4.87x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.74x |  |
| [method_object](benchmarks/method_object.md) | 4.50x |  |
| [list_insert](benchmarks/list_insert.md) | 4.31x |  |
| [str_format](benchmarks/str_format.md) | 4.29x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.15x |  |
| [bytes_format](benchmarks/bytes_format.md) | 4.15x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.13x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 4.09x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.94x |  |
| [nested_func](benchmarks/nested_func.md) | 3.60x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.60x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.55x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.52x |  |
| [generators](benchmarks/generators.md) | 3.48x |  |
| [in_list](benchmarks/in_list.md) | 3.48x |  |
| [float_abs](benchmarks/float_abs.md) | 3.44x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 3.29x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.94x |  |
| [list_index](benchmarks/list_index.md) | 2.91x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.91x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.77x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.75x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.61x |  |
| [str_methods](benchmarks/str_methods.md) | 2.39x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.39x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.18x |  |
| [list_remove](benchmarks/list_remove.md) | 2.13x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.98x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.97x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.96x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.90x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.89x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.87x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.85x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.84x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.83x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.81x | +36.2% |
| [list_copy](benchmarks/list_copy.md) | 1.70x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.67x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.67x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.66x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.62x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.57x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.55x |  |
| [readline](benchmarks/readline.md) | 1.50x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.49x |  |
| [create_attrs](benchmarks/create_attrs.md) | 1.49x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.47x |  |
| [str_searching](benchmarks/str_searching.md) | 1.46x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.44x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.32x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.27x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.27x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.24x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.24x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.24x |  |
| [list_equality](benchmarks/list_equality.md) | 1.20x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.15x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.05x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 1.05x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.02x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.01x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 1.00x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.97x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 0.94x |  |
| [dict_copy](benchmarks/dict_copy.md) | 0.91x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.64x |  |
