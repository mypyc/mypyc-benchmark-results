# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.2, Ubuntu 20.04 LTS and Intel Core i7-2600K (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 38.29x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 18.03x |  |
| [super_method](benchmarks/super_method.md) | 16.85x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 14.09x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 11.79x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 9.31x | +1242.3% |
| [str_call](benchmarks/str_call.md) | 8.44x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 7.70x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 6.04x |  |
| [int_list](benchmarks/int_list.md) | 5.81x |  |
| [sieve](benchmarks/sieve.md) | 5.68x | -4.2% |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.81x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.53x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 4.34x | -17.5% |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.80x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.61x | +119.7% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.51x |  |
| [list_append_small](benchmarks/list_append_small.md) | 3.29x |  |
| [dict_clear](benchmarks/dict_clear.md) | 3.19x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.13x | +262.7% |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 3.01x |  |
| [float_abs](benchmarks/float_abs.md) | 2.98x | +204.8% |
| [tuple_equality](benchmarks/tuple_equality.md) | 2.71x | +232.8% |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.57x | +37.8% |
| [in_list](benchmarks/in_list.md) | 2.56x | +305.5% |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.56x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.50x | +53.3% |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.46x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.32x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.20x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.20x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 2.16x | +146.8% |
| [str_methods](benchmarks/str_methods.md) | 2.12x | +62.3% |
| [str_to_float](benchmarks/str_to_float.md) | 1.99x | +102.0% |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.92x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 1.90x |  |
| [generators](benchmarks/generators.md) | 1.90x |  |
| [list_copy](benchmarks/list_copy.md) | 1.86x | +28.9% |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.78x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.76x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.74x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.72x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.70x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 1.68x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.68x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.65x |  |
| [method_object](benchmarks/method_object.md) | 1.59x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.58x |  |
| [list_insert](benchmarks/list_insert.md) | 1.54x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.50x |  |
| [nested_func](benchmarks/nested_func.md) | 1.48x |  |
| [list_remove](benchmarks/list_remove.md) | 1.40x |  |
| [readline](benchmarks/readline.md) | 1.39x |  |
| [list_index](benchmarks/list_index.md) | 1.38x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.38x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.37x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.37x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.30x |  |
| [str_searching](benchmarks/str_searching.md) | 1.29x |  |
| [str_format](benchmarks/str_format.md) | 1.28x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.28x | +8.2% |
| [bytes_call](benchmarks/bytes_call.md) | 1.26x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.24x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.24x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.22x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.20x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.19x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.18x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.17x |  |
| [list_equality](benchmarks/list_equality.md) | 1.15x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.09x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.07x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.04x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.98x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.98x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.96x |  |
| [int_to_float](benchmarks/int_to_float.md) | 0.91x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.81x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.79x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 0.75x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 0.71x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.66x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 0.61x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 0.30x |  |
