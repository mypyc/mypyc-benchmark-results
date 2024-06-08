# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.10, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 75.90x | +50.7% |
| [min_max_pair](benchmarks/min_max_pair.md) | 70.12x | +16.4% |
| [super_method_alt](benchmarks/super_method_alt.md) | 52.05x | +28.8% |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 50.56x | +63.3% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 49.68x | +63.9% |
| [attrs_method](benchmarks/attrs_method.md) | 42.55x | +19.0% |
| [dataclass_method](benchmarks/dataclass_method.md) | 42.07x | +19.6% |
| [super_method](benchmarks/super_method.md) | 37.29x | +17.8% |
| [int_to_float](benchmarks/int_to_float.md) | 31.98x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 26.45x | +70.9% |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 25.32x | -25.2% |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 20.20x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 16.13x | +45.3% |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 15.27x |  |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 14.43x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 13.97x | +15.6% |
| [int_list](benchmarks/int_list.md) | 12.87x |  |
| [str_call](benchmarks/str_call.md) | 10.66x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 10.38x | +26.1% |
| [tuple_equality](benchmarks/tuple_equality.md) | 10.00x | -58.5% |
| [sieve](benchmarks/sieve.md) | 9.55x | +15.3% |
| [float_abs](benchmarks/float_abs.md) | 9.34x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 9.17x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 8.23x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 7.51x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 7.02x |  |
| [dict_clear](benchmarks/dict_clear.md) | 6.52x |  |
| [nested_func](benchmarks/nested_func.md) | 6.44x | +17.9% |
| [list_append_small](benchmarks/list_append_small.md) | 6.21x | +16.2% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 5.89x | +22.9% |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 5.01x |  |
| [method_object](benchmarks/method_object.md) | 4.85x |  |
| [list_insert](benchmarks/list_insert.md) | 4.84x |  |
| [bytes_format](benchmarks/bytes_format.md) | 4.56x |  |
| [str_format](benchmarks/str_format.md) | 4.46x |  |
| [list_append_large](benchmarks/list_append_large.md) | 4.41x | +19.5% |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.40x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.30x |  |
| [bytes_call](benchmarks/bytes_call.md) | 4.01x |  |
| [generators](benchmarks/generators.md) | 3.94x |  |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 3.77x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.77x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.67x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.62x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 3.51x |  |
| [in_list](benchmarks/in_list.md) | 3.37x |  |
| [list_index](benchmarks/list_index.md) | 3.11x |  |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 3.06x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 3.00x |  |
| [int_divmod](benchmarks/int_divmod.md) | 2.91x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.79x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.74x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.63x |  |
| [str_methods](benchmarks/str_methods.md) | 2.51x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.42x |  |
| [str_to_float](benchmarks/str_to_float.md) | 2.25x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.18x |  |
| [list_remove](benchmarks/list_remove.md) | 2.17x |  |
| [map_builtin](benchmarks/map_builtin.md) | 2.06x |  |
| [encode_decode](benchmarks/encode_decode.md) | 2.01x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.96x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.93x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.93x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.89x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.85x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.78x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.75x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.73x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.68x |  |
| [list_copy](benchmarks/list_copy.md) | 1.66x |  |
| [readline](benchmarks/readline.md) | 1.66x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.65x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.57x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.57x |  |
| [create_attrs](benchmarks/create_attrs.md) | 1.55x |  |
| [str_searching](benchmarks/str_searching.md) | 1.55x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.48x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.47x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.45x |  |
| [in_set](benchmarks/in_set.md) | 1.44x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.41x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.34x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.30x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.30x |  |
| [list_equality](benchmarks/list_equality.md) | 1.25x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.20x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.19x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.19x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.11x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.08x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 1.06x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 1.04x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 1.02x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 0.99x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.83x | -17.5% |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.66x |  |
