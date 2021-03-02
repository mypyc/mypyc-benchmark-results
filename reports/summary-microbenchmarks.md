# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.2, Ubuntu 20.04 LTS and Intel Core i7-2600K (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 38.28x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 20.56x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 17.57x | +24.7% |
| [super_method](benchmarks/super_method.md) | 17.14x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 14.47x | +22.7% |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 10.80x | +16.0% |
| [str_call](benchmarks/str_call.md) | 8.74x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 8.67x | +192.9% |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 8.01x |  |
| [int_list](benchmarks/int_list.md) | 6.85x | +17.9% |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 6.45x |  |
| [sieve](benchmarks/sieve.md) | 6.20x | +10.2% |
| [list_comprehension](benchmarks/list_comprehension.md) | 5.19x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 4.97x | +88.0% |
| [list_insert](benchmarks/list_insert.md) | 4.84x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.81x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.39x |  |
| [dict_clear](benchmarks/dict_clear.md) | 4.28x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.92x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 3.90x | +42.1% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.86x |  |
| [list_append_small](benchmarks/list_append_small.md) | 3.70x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.65x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.23x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.98x |  |
| [float_abs](benchmarks/float_abs.md) | 2.97x |  |
| [method_object](benchmarks/method_object.md) | 2.84x | +85.8% |
| [nested_func](benchmarks/nested_func.md) | 2.69x | +84.4% |
| [in_list](benchmarks/in_list.md) | 2.67x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.61x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.59x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.51x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 2.51x | +49.2% |
| [list_slicing](benchmarks/list_slicing.md) | 2.45x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.40x |  |
| [list_index](benchmarks/list_index.md) | 2.33x | +63.4% |
| [str_methods](benchmarks/str_methods.md) | 2.22x | +12.6% |
| [dict_copy](benchmarks/dict_copy.md) | 2.19x | +34.0% |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.10x |  |
| [generators](benchmarks/generators.md) | 2.09x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.99x | +19.3% |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.97x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.90x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.87x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 1.86x |  |
| [list_remove](benchmarks/list_remove.md) | 1.85x | +34.2% |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.84x |  |
| [list_copy](benchmarks/list_copy.md) | 1.84x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.76x | +45.5% |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.75x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.75x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.68x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.59x | +161.8% |
| [list_from_range](benchmarks/list_from_range.md) | 1.59x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.59x | +128.4% |
| [readline](benchmarks/readline.md) | 1.39x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.37x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.36x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.35x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.35x |  |
| [bytes_call](benchmarks/bytes_call.md) | 1.33x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.32x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.32x | +4.9% |
| [str_format](benchmarks/str_format.md) | 1.31x |  |
| [str_searching](benchmarks/str_searching.md) | 1.31x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.24x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.24x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.23x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.21x | +306.7% |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.18x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.14x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.11x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.11x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.10x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.09x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.09x | +40.6% |
| [list_equality](benchmarks/list_equality.md) | 1.07x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.03x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.00x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.98x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.97x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.95x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.94x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.80x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.68x |  |
