# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.10, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [min_max_pair](benchmarks/min_max_pair.md) | 59.98x |  |
| [enums](benchmarks/enums.md) | 50.71x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 40.37x |  |
| [attrs_method](benchmarks/attrs_method.md) | 35.77x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 35.19x |  |
| [int_to_float](benchmarks/int_to_float.md) | 34.35x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 33.84x |  |
| [super_method](benchmarks/super_method.md) | 31.62x |  |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 31.08x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 30.31x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 24.16x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 19.60x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 15.48x |  |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 13.69x |  |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 13.65x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 12.12x |  |
| [int_list](benchmarks/int_list.md) | 11.44x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 11.09x |  |
| [str_call](benchmarks/str_call.md) | 10.24x |  |
| [float_abs](benchmarks/float_abs.md) | 9.33x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 9.11x |  |
| [sieve](benchmarks/sieve.md) | 8.27x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 8.25x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 7.27x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 7.26x | +121.9% |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.98x |  |
| [dict_clear](benchmarks/dict_clear.md) | 5.85x |  |
| [nested_func](benchmarks/nested_func.md) | 5.45x | +49.8% |
| [list_append_small](benchmarks/list_append_small.md) | 5.35x |  |
| [list_insert](benchmarks/list_insert.md) | 5.01x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.86x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 4.80x |  |
| [method_object](benchmarks/method_object.md) | 4.59x |  |
| [str_format](benchmarks/str_format.md) | 4.41x |  |
| [bytes_format](benchmarks/bytes_format.md) | 4.29x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.25x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.20x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.89x |  |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 3.76x |  |
| [list_append_large](benchmarks/list_append_large.md) | 3.68x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.58x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.54x |  |
| [generators](benchmarks/generators.md) | 3.53x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.51x |  |
| [in_list](benchmarks/in_list.md) | 3.47x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 3.10x |  |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 3.05x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.99x |  |
| [list_index](benchmarks/list_index.md) | 2.93x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.80x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.78x |  |
| [int_divmod](benchmarks/int_divmod.md) | 2.78x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.76x |  |
| [str_methods](benchmarks/str_methods.md) | 2.41x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.29x |  |
| [str_to_float](benchmarks/str_to_float.md) | 2.21x |  |
| [list_remove](benchmarks/list_remove.md) | 2.16x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.13x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.96x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.95x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.93x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.91x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.90x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.87x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.86x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.78x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.76x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.70x |  |
| [list_copy](benchmarks/list_copy.md) | 1.70x |  |
| [readline](benchmarks/readline.md) | 1.67x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.64x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.62x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.55x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.55x |  |
| [create_attrs](benchmarks/create_attrs.md) | 1.53x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.52x |  |
| [str_searching](benchmarks/str_searching.md) | 1.48x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.46x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.45x |  |
| [in_set](benchmarks/in_set.md) | 1.44x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.41x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.33x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.30x |  |
| [list_equality](benchmarks/list_equality.md) | 1.30x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.29x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.21x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.20x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.19x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.18x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.09x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 1.08x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 1.06x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 1.01x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.01x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.65x |  |
