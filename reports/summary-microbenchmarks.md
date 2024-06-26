# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.10, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 74.72x | +47.9% |
| [min_max_pair](benchmarks/min_max_pair.md) | 65.95x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 51.19x | +26.6% |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 50.47x | +62.9% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 49.70x | +63.9% |
| [attrs_method](benchmarks/attrs_method.md) | 42.63x | +19.1% |
| [dataclass_method](benchmarks/dataclass_method.md) | 42.21x | +19.8% |
| [super_method](benchmarks/super_method.md) | 37.29x | +17.7% |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 33.73x |  |
| [int_to_float](benchmarks/int_to_float.md) | 33.62x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 25.73x | +66.3% |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 20.44x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 16.08x | +44.9% |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 15.27x |  |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 14.18x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 14.01x | +15.2% |
| [int_list](benchmarks/int_list.md) | 13.06x |  |
| [str_call](benchmarks/str_call.md) | 10.59x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 10.40x | +27.8% |
| [sieve](benchmarks/sieve.md) | 9.55x | +16.1% |
| [tuple_equality](benchmarks/tuple_equality.md) | 9.49x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 9.10x |  |
| [float_abs](benchmarks/float_abs.md) | 8.99x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 8.27x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 7.50x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 7.03x |  |
| [dict_clear](benchmarks/dict_clear.md) | 6.53x |  |
| [nested_func](benchmarks/nested_func.md) | 6.45x | +18.2% |
| [list_append_small](benchmarks/list_append_small.md) | 6.19x | +15.5% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 5.88x | +19.0% |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.97x |  |
| [list_insert](benchmarks/list_insert.md) | 4.95x |  |
| [method_object](benchmarks/method_object.md) | 4.82x |  |
| [bytes_format](benchmarks/bytes_format.md) | 4.54x |  |
| [str_format](benchmarks/str_format.md) | 4.50x |  |
| [list_append_large](benchmarks/list_append_large.md) | 4.46x | +24.9% |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.37x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.34x |  |
| [bytes_call](benchmarks/bytes_call.md) | 4.01x |  |
| [generators](benchmarks/generators.md) | 3.82x |  |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 3.74x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.67x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.66x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.61x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 3.53x |  |
| [in_list](benchmarks/in_list.md) | 3.37x |  |
| [list_index](benchmarks/list_index.md) | 3.13x |  |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 3.05x |  |
| [int_divmod](benchmarks/int_divmod.md) | 2.94x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.94x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.81x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.79x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.70x |  |
| [str_methods](benchmarks/str_methods.md) | 2.43x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.33x |  |
| [str_to_float](benchmarks/str_to_float.md) | 2.22x |  |
| [list_remove](benchmarks/list_remove.md) | 2.18x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.17x |  |
| [encode_decode](benchmarks/encode_decode.md) | 2.05x |  |
| [map_builtin](benchmarks/map_builtin.md) | 2.03x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.96x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.94x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.94x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.91x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.88x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.79x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.75x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.71x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.68x |  |
| [list_copy](benchmarks/list_copy.md) | 1.67x |  |
| [readline](benchmarks/readline.md) | 1.67x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.65x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.60x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.55x |  |
| [create_attrs](benchmarks/create_attrs.md) | 1.54x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.52x |  |
| [str_searching](benchmarks/str_searching.md) | 1.51x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.49x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.47x |  |
| [in_set](benchmarks/in_set.md) | 1.45x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.41x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.34x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.31x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.30x |  |
| [list_equality](benchmarks/list_equality.md) | 1.28x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.20x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.19x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.19x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.12x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.08x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 1.08x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 1.05x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 1.02x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.01x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.66x |  |
