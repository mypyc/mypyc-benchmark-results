# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.10, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 77.29x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 63.49x |  |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 49.43x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 48.70x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 46.82x |  |
| [attrs_method](benchmarks/attrs_method.md) | 36.65x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 36.28x |  |
| [super_method](benchmarks/super_method.md) | 35.18x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 33.71x | +23.2% |
| [int_to_float](benchmarks/int_to_float.md) | 32.02x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 25.73x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 20.32x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 16.16x |  |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 15.10x |  |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 14.32x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 13.98x |  |
| [int_list](benchmarks/int_list.md) | 13.66x |  |
| [str_call](benchmarks/str_call.md) | 10.57x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 10.39x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 10.03x |  |
| [sieve](benchmarks/sieve.md) | 9.77x |  |
| [float_abs](benchmarks/float_abs.md) | 9.29x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 9.13x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 8.34x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 7.48x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 7.05x |  |
| [dict_clear](benchmarks/dict_clear.md) | 6.78x |  |
| [nested_func](benchmarks/nested_func.md) | 6.49x |  |
| [list_append_small](benchmarks/list_append_small.md) | 6.22x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 5.89x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 5.00x |  |
| [list_insert](benchmarks/list_insert.md) | 4.80x |  |
| [method_object](benchmarks/method_object.md) | 4.79x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.49x |  |
| [list_append_large](benchmarks/list_append_large.md) | 4.40x |  |
| [bytes_format](benchmarks/bytes_format.md) | 4.39x |  |
| [str_format](benchmarks/str_format.md) | 4.39x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.32x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 4.19x | +114.5% |
| [bytes_call](benchmarks/bytes_call.md) | 3.98x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.84x |  |
| [generators](benchmarks/generators.md) | 3.78x |  |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 3.76x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.67x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.63x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 3.57x |  |
| [in_list](benchmarks/in_list.md) | 3.37x |  |
| [list_index](benchmarks/list_index.md) | 3.11x |  |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 3.06x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 3.02x |  |
| [int_divmod](benchmarks/int_divmod.md) | 2.91x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.78x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.67x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.61x |  |
| [encode_decode](benchmarks/encode_decode.md) | 2.60x | +27.9% |
| [str_methods](benchmarks/str_methods.md) | 2.54x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.40x |  |
| [str_to_float](benchmarks/str_to_float.md) | 2.26x |  |
| [list_remove](benchmarks/list_remove.md) | 2.19x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.12x |  |
| [map_builtin](benchmarks/map_builtin.md) | 2.04x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.95x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.93x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.87x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.86x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.85x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.80x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.74x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.68x |  |
| [readline](benchmarks/readline.md) | 1.67x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.65x |  |
| [list_copy](benchmarks/list_copy.md) | 1.65x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.58x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.57x |  |
| [str_searching](benchmarks/str_searching.md) | 1.56x |  |
| [create_attrs](benchmarks/create_attrs.md) | 1.52x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.50x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.49x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.48x |  |
| [in_set](benchmarks/in_set.md) | 1.44x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.40x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.34x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.31x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.30x |  |
| [list_equality](benchmarks/list_equality.md) | 1.26x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.20x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.19x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.18x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 1.15x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.14x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 1.04x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 1.02x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.01x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.00x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 0.98x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.66x |  |
