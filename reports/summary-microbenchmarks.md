# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.13.1, Ubuntu 24.04.1 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 30.18x |  |
| [attrs_method](benchmarks/attrs_method.md) | 19.65x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 19.60x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 18.61x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 15.97x |  |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 15.79x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 15.00x |  |
| [int_to_float](benchmarks/int_to_float.md) | 14.53x |  |
| [super_method](benchmarks/super_method.md) | 13.94x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 13.49x |  |
| [sieve](benchmarks/sieve.md) | 12.34x | -10.3% |
| [int_list](benchmarks/int_list.md) | 12.11x |  |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 11.56x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 10.84x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 8.46x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 8.26x |  |
| [enums](benchmarks/enums.md) | 7.58x |  |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 5.90x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 5.89x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 5.69x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 5.51x |  |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 5.45x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 5.19x |  |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 5.03x |  |
| [float_abs](benchmarks/float_abs.md) | 4.90x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 4.51x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 4.46x |  |
| [str_call](benchmarks/str_call.md) | 4.24x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.10x |  |
| [nested_func](benchmarks/nested_func.md) | 3.91x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.79x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 3.64x |  |
| [str_format](benchmarks/str_format.md) | 3.55x |  |
| [in_list](benchmarks/in_list.md) | 3.55x |  |
| [dict_clear](benchmarks/dict_clear.md) | 3.27x |  |
| [list_insert](benchmarks/list_insert.md) | 3.24x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.16x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 3.16x |  |
| [bytes_format](benchmarks/bytes_format.md) | 3.14x |  |
| [list_append_small](benchmarks/list_append_small.md) | 2.95x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 2.91x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 2.88x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.75x |  |
| [list_index](benchmarks/list_index.md) | 2.72x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 2.69x |  |
| [str_slicing](benchmarks/str_slicing.md) | 2.65x |  |
| [method_object](benchmarks/method_object.md) | 2.58x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.54x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.40x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.40x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 2.16x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.15x |  |
| [str_searching](benchmarks/str_searching.md) | 2.12x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.07x |  |
| [encode_decode](benchmarks/encode_decode.md) | 2.05x |  |
| [int_divmod](benchmarks/int_divmod.md) | 2.05x |  |
| [list_copy](benchmarks/list_copy.md) | 2.00x | +36.4% |
| [generators](benchmarks/generators.md) | 1.97x |  |
| [str_methods](benchmarks/str_methods.md) | 1.95x | +26.4% |
| [dict_copy](benchmarks/dict_copy.md) | 1.83x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.79x |  |
| [list_remove](benchmarks/list_remove.md) | 1.75x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.74x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.72x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 1.69x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.66x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.65x |  |
| [in_set](benchmarks/in_set.md) | 1.62x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.55x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.48x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.42x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.42x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.41x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.40x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.35x | +12.4% |
| [readline](benchmarks/readline.md) | 1.34x |  |
| [list_equality](benchmarks/list_equality.md) | 1.27x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.17x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.14x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.13x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.09x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.06x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.05x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.01x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.00x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.00x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.99x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 0.99x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 0.98x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 0.98x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 0.89x |  |
| [create_attrs](benchmarks/create_attrs.md) | 0.88x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 0.74x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.73x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.49x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.43x |  |
