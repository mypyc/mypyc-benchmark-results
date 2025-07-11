# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.13.1, Ubuntu 24.04.1 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 30.19x |  |
| [attrs_method](benchmarks/attrs_method.md) | 19.66x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 19.60x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 18.62x |  |
| [int_to_float](benchmarks/int_to_float.md) | 16.36x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 15.92x |  |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 15.80x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 15.57x | +84.0% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 15.00x |  |
| [super_method](benchmarks/super_method.md) | 13.96x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 13.54x |  |
| [sieve](benchmarks/sieve.md) | 12.58x |  |
| [int_list](benchmarks/int_list.md) | 12.23x |  |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 11.55x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 11.08x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 8.27x |  |
| [enums](benchmarks/enums.md) | 7.58x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 6.63x | +46.8% |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 5.88x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 5.87x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 5.68x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 5.52x |  |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 5.50x |  |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 5.48x |  |
| [generators](benchmarks/generators.md) | 5.38x | +173.4% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 5.20x |  |
| [float_abs](benchmarks/float_abs.md) | 4.93x |  |
| [nested_func](benchmarks/nested_func.md) | 4.80x | +22.7% |
| [list_comprehension](benchmarks/list_comprehension.md) | 4.55x |  |
| [str_call](benchmarks/str_call.md) | 4.29x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.11x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.75x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 3.65x |  |
| [str_format](benchmarks/str_format.md) | 3.65x |  |
| [in_list](benchmarks/in_list.md) | 3.57x |  |
| [list_insert](benchmarks/list_insert.md) | 3.25x |  |
| [dict_clear](benchmarks/dict_clear.md) | 3.25x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.24x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 3.17x |  |
| [bytes_format](benchmarks/bytes_format.md) | 3.04x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 3.00x |  |
| [list_append_small](benchmarks/list_append_small.md) | 2.95x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 2.88x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.81x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.79x | +16.2% |
| [ord_builtin](benchmarks/ord_builtin.md) | 2.69x |  |
| [list_index](benchmarks/list_index.md) | 2.69x |  |
| [str_slicing](benchmarks/str_slicing.md) | 2.66x |  |
| [method_object](benchmarks/method_object.md) | 2.60x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.53x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.41x |  |
| [encode_decode](benchmarks/encode_decode.md) | 2.27x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 2.15x |  |
| [str_methods](benchmarks/str_methods.md) | 2.14x | +10.0% |
| [list_append_large](benchmarks/list_append_large.md) | 2.14x |  |
| [str_searching](benchmarks/str_searching.md) | 2.14x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.11x |  |
| [int_divmod](benchmarks/int_divmod.md) | 2.06x |  |
| [list_copy](benchmarks/list_copy.md) | 2.00x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.84x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.77x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.77x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.76x |  |
| [list_remove](benchmarks/list_remove.md) | 1.75x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.73x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 1.71x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.64x |  |
| [in_set](benchmarks/in_set.md) | 1.62x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.58x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.55x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.45x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.43x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.43x | +5.3% |
| [str_to_float](benchmarks/str_to_float.md) | 1.40x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.40x |  |
| [readline](benchmarks/readline.md) | 1.35x |  |
| [list_equality](benchmarks/list_equality.md) | 1.26x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.17x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.14x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.13x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.08x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.06x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.04x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.03x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.00x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.00x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 0.97x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 0.97x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.93x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 0.90x |  |
| [create_attrs](benchmarks/create_attrs.md) | 0.89x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 0.74x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.74x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.48x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.42x |  |
