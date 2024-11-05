# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.10, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 74.71x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 68.11x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 51.69x |  |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 50.55x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 49.74x |  |
| [attrs_method](benchmarks/attrs_method.md) | 42.57x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 42.24x |  |
| [super_method](benchmarks/super_method.md) | 37.65x |  |
| [int_to_float](benchmarks/int_to_float.md) | 34.11x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 27.33x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 25.74x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 20.35x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 16.09x |  |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 15.18x |  |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 14.19x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 13.71x |  |
| [int_list](benchmarks/int_list.md) | 13.66x |  |
| [str_call](benchmarks/str_call.md) | 10.52x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 10.39x |  |
| [sieve](benchmarks/sieve.md) | 9.55x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 9.40x |  |
| [float_abs](benchmarks/float_abs.md) | 9.34x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 9.15x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 8.27x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 7.53x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.99x |  |
| [dict_clear](benchmarks/dict_clear.md) | 6.81x |  |
| [nested_func](benchmarks/nested_func.md) | 6.43x |  |
| [list_append_small](benchmarks/list_append_small.md) | 6.19x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 5.90x |  |
| [list_insert](benchmarks/list_insert.md) | 5.10x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.95x |  |
| [method_object](benchmarks/method_object.md) | 4.85x |  |
| [bytes_format](benchmarks/bytes_format.md) | 4.54x |  |
| [str_format](benchmarks/str_format.md) | 4.47x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.43x |  |
| [list_append_large](benchmarks/list_append_large.md) | 4.40x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.27x |  |
| [bytes_call](benchmarks/bytes_call.md) | 4.02x |  |
| [generators](benchmarks/generators.md) | 3.87x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.79x |  |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 3.68x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.66x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.61x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 3.56x |  |
| [in_list](benchmarks/in_list.md) | 3.37x |  |
| [list_index](benchmarks/list_index.md) | 3.12x |  |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 3.01x |  |
| [int_divmod](benchmarks/int_divmod.md) | 2.91x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.90x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.81x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.80x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.71x |  |
| [str_methods](benchmarks/str_methods.md) | 2.47x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.35x |  |
| [str_to_float](benchmarks/str_to_float.md) | 2.22x |  |
| [list_remove](benchmarks/list_remove.md) | 2.18x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.13x |  |
| [map_builtin](benchmarks/map_builtin.md) | 2.04x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.98x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.96x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.94x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.94x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.88x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.86x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.79x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.79x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.73x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.67x |  |
| [list_copy](benchmarks/list_copy.md) | 1.67x |  |
| [readline](benchmarks/readline.md) | 1.67x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.64x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.58x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.55x |  |
| [create_attrs](benchmarks/create_attrs.md) | 1.54x |  |
| [str_searching](benchmarks/str_searching.md) | 1.52x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.52x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.49x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.49x |  |
| [in_set](benchmarks/in_set.md) | 1.45x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.41x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.34x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.31x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.29x |  |
| [list_equality](benchmarks/list_equality.md) | 1.29x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.23x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.20x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.18x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.18x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 1.15x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.13x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 1.05x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.01x | +19.6% |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 1.01x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.66x |  |
