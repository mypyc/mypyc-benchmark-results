# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.10, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [min_max_pair](benchmarks/min_max_pair.md) | 57.75x |  |
| [enums](benchmarks/enums.md) | 52.33x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 39.73x |  |
| [attrs_method](benchmarks/attrs_method.md) | 35.72x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 35.09x |  |
| [int_to_float](benchmarks/int_to_float.md) | 31.61x | +1650.5% |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 31.21x |  |
| [super_method](benchmarks/super_method.md) | 31.17x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 30.91x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 30.63x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 24.06x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 19.20x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 15.10x |  |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 14.45x |  |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 12.90x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 12.21x |  |
| [int_list](benchmarks/int_list.md) | 11.38x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 11.12x |  |
| [str_call](benchmarks/str_call.md) | 10.08x |  |
| [float_abs](benchmarks/float_abs.md) | 9.34x | +181.1% |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 9.17x | +124.7% |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 8.15x |  |
| [sieve](benchmarks/sieve.md) | 8.12x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 7.21x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.95x |  |
| [dict_clear](benchmarks/dict_clear.md) | 5.98x |  |
| [list_append_small](benchmarks/list_append_small.md) | 5.32x |  |
| [list_insert](benchmarks/list_insert.md) | 4.94x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.87x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 4.84x |  |
| [method_object](benchmarks/method_object.md) | 4.58x |  |
| [str_format](benchmarks/str_format.md) | 4.29x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.13x |  |
| [bytes_format](benchmarks/bytes_format.md) | 4.11x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.09x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.89x |  |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 3.70x |  |
| [list_append_large](benchmarks/list_append_large.md) | 3.67x |  |
| [nested_func](benchmarks/nested_func.md) | 3.62x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.59x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.55x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.53x |  |
| [generators](benchmarks/generators.md) | 3.49x |  |
| [in_list](benchmarks/in_list.md) | 3.42x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 3.22x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 3.19x |  |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 3.04x |  |
| [list_index](benchmarks/list_index.md) | 2.94x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.89x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.78x |  |
| [int_divmod](benchmarks/int_divmod.md) | 2.71x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.70x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.69x |  |
| [str_methods](benchmarks/str_methods.md) | 2.47x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.36x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.23x |  |
| [str_to_float](benchmarks/str_to_float.md) | 2.22x |  |
| [list_remove](benchmarks/list_remove.md) | 2.19x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.98x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.97x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.94x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.93x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.88x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.88x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.82x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.79x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.77x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.70x |  |
| [list_copy](benchmarks/list_copy.md) | 1.70x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.69x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.68x |  |
| [readline](benchmarks/readline.md) | 1.67x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.57x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.55x |  |
| [create_attrs](benchmarks/create_attrs.md) | 1.54x |  |
| [str_searching](benchmarks/str_searching.md) | 1.48x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.47x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.46x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.46x |  |
| [in_set](benchmarks/in_set.md) | 1.44x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.39x |  |
| [list_equality](benchmarks/list_equality.md) | 1.29x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.28x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.28x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.27x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.20x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.19x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.18x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 1.08x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.07x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 1.04x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 1.01x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.01x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 0.99x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 0.99x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.65x |  |
