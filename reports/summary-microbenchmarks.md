# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.10, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 75.43x | +49.5% |
| [min_max_pair](benchmarks/min_max_pair.md) | 63.04x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 51.79x | +28.1% |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 50.55x | +62.8% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 49.76x | +64.0% |
| [attrs_method](benchmarks/attrs_method.md) | 42.58x | +19.0% |
| [dataclass_method](benchmarks/dataclass_method.md) | 42.14x | +19.7% |
| [super_method](benchmarks/super_method.md) | 37.84x | +19.6% |
| [int_to_float](benchmarks/int_to_float.md) | 34.58x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 33.76x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 25.72x | +66.3% |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 20.33x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 16.16x | +45.6% |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 14.48x |  |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 14.08x |  |
| [int_list](benchmarks/int_list.md) | 13.76x | +20.2% |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 13.59x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 10.39x | +28.1% |
| [str_call](benchmarks/str_call.md) | 10.36x |  |
| [sieve](benchmarks/sieve.md) | 9.41x | +14.3% |
| [float_abs](benchmarks/float_abs.md) | 9.34x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 9.16x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 9.14x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 8.32x | +15.3% |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 7.44x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.95x |  |
| [dict_clear](benchmarks/dict_clear.md) | 6.55x |  |
| [nested_func](benchmarks/nested_func.md) | 6.45x | +18.2% |
| [list_append_small](benchmarks/list_append_small.md) | 6.26x | +16.7% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 5.88x | +18.7% |
| [list_insert](benchmarks/list_insert.md) | 5.03x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.97x |  |
| [method_object](benchmarks/method_object.md) | 4.83x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.52x |  |
| [str_format](benchmarks/str_format.md) | 4.48x |  |
| [bytes_format](benchmarks/bytes_format.md) | 4.47x |  |
| [list_append_large](benchmarks/list_append_large.md) | 4.38x | +22.7% |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.36x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.99x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.80x |  |
| [generators](benchmarks/generators.md) | 3.79x |  |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 3.73x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.66x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.64x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 3.48x |  |
| [in_list](benchmarks/in_list.md) | 3.38x |  |
| [list_index](benchmarks/list_index.md) | 3.12x |  |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 3.03x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.98x |  |
| [int_divmod](benchmarks/int_divmod.md) | 2.90x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.79x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.71x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.70x |  |
| [str_methods](benchmarks/str_methods.md) | 2.51x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.40x |  |
| [str_to_float](benchmarks/str_to_float.md) | 2.24x |  |
| [list_remove](benchmarks/list_remove.md) | 2.19x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.16x |  |
| [encode_decode](benchmarks/encode_decode.md) | 2.04x |  |
| [map_builtin](benchmarks/map_builtin.md) | 2.03x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.96x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.95x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.93x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.90x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.85x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.80x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.79x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.72x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.68x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.67x |  |
| [readline](benchmarks/readline.md) | 1.67x |  |
| [list_copy](benchmarks/list_copy.md) | 1.67x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.58x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.57x |  |
| [str_searching](benchmarks/str_searching.md) | 1.56x |  |
| [create_attrs](benchmarks/create_attrs.md) | 1.54x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.50x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.48x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.48x |  |
| [in_set](benchmarks/in_set.md) | 1.43x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.40x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.34x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.31x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.30x |  |
| [list_equality](benchmarks/list_equality.md) | 1.25x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.20x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.19x | +21.0% |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.18x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.09x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.09x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 1.07x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 1.05x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 1.02x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.01x | +20.9% |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.66x |  |
