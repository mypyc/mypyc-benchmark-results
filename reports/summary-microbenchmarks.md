# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.10, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 77.25x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 63.04x |  |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 49.44x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 48.63x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 46.95x |  |
| [attrs_method](benchmarks/attrs_method.md) | 36.66x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 36.26x |  |
| [super_method](benchmarks/super_method.md) | 35.20x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 33.70x | +23.2% |
| [int_to_float](benchmarks/int_to_float.md) | 32.00x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 25.72x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 20.24x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 16.16x |  |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 15.07x |  |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 14.44x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 13.96x |  |
| [int_list](benchmarks/int_list.md) | 13.66x |  |
| [str_call](benchmarks/str_call.md) | 10.57x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 10.38x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 10.04x |  |
| [sieve](benchmarks/sieve.md) | 9.77x |  |
| [float_abs](benchmarks/float_abs.md) | 9.31x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 9.13x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 8.33x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 7.49x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.95x |  |
| [dict_clear](benchmarks/dict_clear.md) | 6.77x |  |
| [nested_func](benchmarks/nested_func.md) | 6.48x |  |
| [list_append_small](benchmarks/list_append_small.md) | 6.21x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 5.89x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.94x |  |
| [list_insert](benchmarks/list_insert.md) | 4.80x |  |
| [method_object](benchmarks/method_object.md) | 4.78x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.49x |  |
| [list_append_large](benchmarks/list_append_large.md) | 4.40x |  |
| [bytes_format](benchmarks/bytes_format.md) | 4.39x |  |
| [str_format](benchmarks/str_format.md) | 4.39x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.31x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 4.17x | +114.1% |
| [bytes_call](benchmarks/bytes_call.md) | 3.98x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.84x |  |
| [generators](benchmarks/generators.md) | 3.78x |  |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 3.69x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.67x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.63x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 3.58x |  |
| [in_list](benchmarks/in_list.md) | 3.38x |  |
| [list_index](benchmarks/list_index.md) | 3.11x |  |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 3.05x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 3.02x |  |
| [int_divmod](benchmarks/int_divmod.md) | 2.93x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.77x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.69x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.61x |  |
| [encode_decode](benchmarks/encode_decode.md) | 2.61x | +28.3% |
| [str_methods](benchmarks/str_methods.md) | 2.54x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.39x |  |
| [str_to_float](benchmarks/str_to_float.md) | 2.26x |  |
| [list_remove](benchmarks/list_remove.md) | 2.19x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.13x |  |
| [map_builtin](benchmarks/map_builtin.md) | 2.04x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.95x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.93x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.87x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.85x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.84x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.80x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.73x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.67x |  |
| [readline](benchmarks/readline.md) | 1.67x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.66x |  |
| [list_copy](benchmarks/list_copy.md) | 1.65x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.57x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.56x |  |
| [str_searching](benchmarks/str_searching.md) | 1.55x |  |
| [create_attrs](benchmarks/create_attrs.md) | 1.52x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.51x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.47x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.45x |  |
| [in_set](benchmarks/in_set.md) | 1.44x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.40x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.34x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.31x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.30x |  |
| [list_equality](benchmarks/list_equality.md) | 1.27x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.20x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.19x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.19x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 1.15x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.11x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 1.04x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 1.02x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.01x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.00x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 0.92x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.66x |  |
