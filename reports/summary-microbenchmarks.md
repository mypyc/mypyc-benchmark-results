# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.5, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [min_max_pair](benchmarks/min_max_pair.md) | 58.85x |  |
| [enums](benchmarks/enums.md) | 52.76x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 40.43x | +17.0% |
| [attrs_method](benchmarks/attrs_method.md) | 35.55x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 35.09x |  |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 31.41x |  |
| [super_method](benchmarks/super_method.md) | 31.22x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 30.33x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 30.00x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 23.89x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 20.07x | +20.2% |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 15.11x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 12.05x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 11.09x |  |
| [int_list](benchmarks/int_list.md) | 10.82x |  |
| [str_call](benchmarks/str_call.md) | 10.18x |  |
| [sieve](benchmarks/sieve.md) | 8.33x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 8.20x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 6.63x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.60x |  |
| [dict_clear](benchmarks/dict_clear.md) | 6.07x |  |
| [list_append_small](benchmarks/list_append_small.md) | 5.22x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 4.88x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.65x |  |
| [method_object](benchmarks/method_object.md) | 4.46x |  |
| [list_insert](benchmarks/list_insert.md) | 4.30x |  |
| [str_format](benchmarks/str_format.md) | 4.29x |  |
| [bytes_format](benchmarks/bytes_format.md) | 4.15x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.14x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.13x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 4.08x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.93x |  |
| [nested_func](benchmarks/nested_func.md) | 3.60x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.60x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.55x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.53x |  |
| [generators](benchmarks/generators.md) | 3.48x |  |
| [in_list](benchmarks/in_list.md) | 3.46x |  |
| [float_abs](benchmarks/float_abs.md) | 3.44x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 3.27x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.94x |  |
| [list_index](benchmarks/list_index.md) | 2.91x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.91x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.78x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.75x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.61x |  |
| [str_methods](benchmarks/str_methods.md) | 2.39x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.39x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.18x |  |
| [list_remove](benchmarks/list_remove.md) | 2.13x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.98x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.98x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.96x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.90x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.90x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.89x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.87x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.83x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.83x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.82x | +36.0% |
| [list_copy](benchmarks/list_copy.md) | 1.70x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.68x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.66x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.66x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.62x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.57x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.56x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.50x |  |
| [create_attrs](benchmarks/create_attrs.md) | 1.50x |  |
| [readline](benchmarks/readline.md) | 1.49x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.46x |  |
| [str_searching](benchmarks/str_searching.md) | 1.46x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.44x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.32x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.27x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.27x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.24x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.24x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.19x |  |
| [list_equality](benchmarks/list_equality.md) | 1.17x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.15x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.13x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 1.05x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.01x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.00x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.99x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.98x | -16.3% |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.97x |  |
| [dict_copy](benchmarks/dict_copy.md) | 0.91x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.64x |  |
