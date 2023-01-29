# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.10, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [min_max_pair](benchmarks/min_max_pair.md) | 61.58x |  |
| [enums](benchmarks/enums.md) | 52.75x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 39.44x |  |
| [attrs_method](benchmarks/attrs_method.md) | 35.80x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 35.04x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 33.84x |  |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 31.00x |  |
| [super_method](benchmarks/super_method.md) | 30.85x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 30.44x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 24.24x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 19.43x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 15.10x |  |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 14.39x |  |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 13.50x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 12.20x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 11.10x |  |
| [int_list](benchmarks/int_list.md) | 10.66x |  |
| [str_call](benchmarks/str_call.md) | 10.21x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 8.30x |  |
| [sieve](benchmarks/sieve.md) | 8.10x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 7.17x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.92x |  |
| [dict_clear](benchmarks/dict_clear.md) | 5.98x |  |
| [list_append_small](benchmarks/list_append_small.md) | 5.19x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.87x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 4.83x |  |
| [list_insert](benchmarks/list_insert.md) | 4.79x |  |
| [method_object](benchmarks/method_object.md) | 4.64x |  |
| [bytes_format](benchmarks/bytes_format.md) | 4.39x |  |
| [str_format](benchmarks/str_format.md) | 4.37x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.16x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 4.08x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 3.98x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.88x |  |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 3.69x |  |
| [list_append_large](benchmarks/list_append_large.md) | 3.64x | +21.0% |
| [nested_func](benchmarks/nested_func.md) | 3.63x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.62x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.52x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.52x |  |
| [in_list](benchmarks/in_list.md) | 3.46x |  |
| [generators](benchmarks/generators.md) | 3.45x |  |
| [float_abs](benchmarks/float_abs.md) | 3.33x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 3.25x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 3.14x | +145.6% |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 2.99x |  |
| [list_index](benchmarks/list_index.md) | 2.97x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.79x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.70x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.68x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.65x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.37x |  |
| [str_methods](benchmarks/str_methods.md) | 2.33x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.23x |  |
| [list_remove](benchmarks/list_remove.md) | 2.19x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.99x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.94x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.93x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.93x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.93x | +112.5% |
| [int_divmod](benchmarks/int_divmod.md) | 1.93x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.90x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.86x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.81x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.80x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.77x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.76x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.70x |  |
| [list_copy](benchmarks/list_copy.md) | 1.70x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.69x |  |
| [readline](benchmarks/readline.md) | 1.67x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.67x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.56x |  |
| [str_searching](benchmarks/str_searching.md) | 1.55x |  |
| [create_attrs](benchmarks/create_attrs.md) | 1.52x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.51x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.51x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.49x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.47x |  |
| [in_set](benchmarks/in_set.md) | 1.45x | +136.5% |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.39x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.30x |  |
| [list_equality](benchmarks/list_equality.md) | 1.30x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.29x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.27x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.19x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.19x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.17x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.16x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 1.09x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.08x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 1.05x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 1.01x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.01x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 0.98x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.65x |  |
