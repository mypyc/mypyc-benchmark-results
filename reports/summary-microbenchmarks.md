# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.5, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [min_max_pair](benchmarks/min_max_pair.md) | 56.99x | +6204.0% |
| [enums](benchmarks/enums.md) | 48.80x | +27.0% |
| [super_method_alt](benchmarks/super_method_alt.md) | 35.23x | +58.8% |
| [attrs_method](benchmarks/attrs_method.md) | 33.13x | +1805.6% |
| [dataclass_method](benchmarks/dataclass_method.md) | 32.88x | +69.9% |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 29.96x | +162.8% |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 29.80x | +1276.6% |
| [super_method](benchmarks/super_method.md) | 28.76x | +46.7% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 28.75x | +121.8% |
| [tuple_equality](benchmarks/tuple_equality.md) | 24.06x | +1039.1% |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 19.51x | +22.0% |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 15.33x | +47.0% |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 12.03x |  |
| [int_list](benchmarks/int_list.md) | 11.27x | +60.4% |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 11.04x | +33.4% |
| [str_call](benchmarks/str_call.md) | 10.18x |  |
| [sieve](benchmarks/sieve.md) | 8.31x | +42.0% |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 8.25x | +22.6% |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 6.68x | +19.3% |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.63x |  |
| [dict_clear](benchmarks/dict_clear.md) | 5.91x | +15.9% |
| [list_append_small](benchmarks/list_append_small.md) | 5.05x | +28.7% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 4.88x | +31.1% |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.81x |  |
| [bytes_format](benchmarks/bytes_format.md) | 4.50x |  |
| [method_object](benchmarks/method_object.md) | 4.37x |  |
| [str_format](benchmarks/str_format.md) | 4.33x |  |
| [list_insert](benchmarks/list_insert.md) | 4.23x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.18x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.11x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.92x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.74x | +11.5% |
| [nested_func](benchmarks/nested_func.md) | 3.72x | +27.6% |
| [str_slicing](benchmarks/str_slicing.md) | 3.55x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.55x |  |
| [generators](benchmarks/generators.md) | 3.50x | +58.2% |
| [float_abs](benchmarks/float_abs.md) | 3.34x | +15.1% |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 3.29x |  |
| [list_append_large](benchmarks/list_append_large.md) | 3.14x | +20.5% |
| [in_tuple](benchmarks/in_tuple.md) | 3.12x |  |
| [in_list](benchmarks/in_list.md) | 3.03x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.85x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.78x | +36.0% |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.78x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.61x |  |
| [list_index](benchmarks/list_index.md) | 2.61x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.34x |  |
| [str_methods](benchmarks/str_methods.md) | 2.33x |  |
| [list_remove](benchmarks/list_remove.md) | 2.15x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.13x |  |
| [encode_decode](benchmarks/encode_decode.md) | 2.00x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.99x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.96x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.94x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.93x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.88x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.87x | +21.2% |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.84x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.81x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.69x |  |
| [list_copy](benchmarks/list_copy.md) | 1.69x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.65x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.63x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.59x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.58x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.56x |  |
| [create_attrs](benchmarks/create_attrs.md) | 1.51x | +27.2% |
| [readline](benchmarks/readline.md) | 1.51x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.47x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.46x |  |
| [str_searching](benchmarks/str_searching.md) | 1.45x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.44x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.32x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.32x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.26x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.24x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.22x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.22x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.19x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.19x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.16x |  |
| [list_equality](benchmarks/list_equality.md) | 1.15x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.11x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 1.05x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 1.00x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.97x |  |
| [dict_copy](benchmarks/dict_copy.md) | 0.91x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.83x | -17.0% |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.63x |  |
