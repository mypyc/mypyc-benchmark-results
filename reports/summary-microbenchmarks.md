# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.2, Ubuntu 20.04 LTS and Intel Core i7-2600K (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 38.01x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 19.84x |  |
| [super_method](benchmarks/super_method.md) | 18.01x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 17.38x | +23.4% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 14.52x | +23.1% |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 10.79x | +15.9% |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 8.78x | +196.3% |
| [str_call](benchmarks/str_call.md) | 8.75x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 8.44x |  |
| [int_list](benchmarks/int_list.md) | 6.51x |  |
| [sieve](benchmarks/sieve.md) | 6.35x | +12.9% |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 6.32x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 5.18x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.85x |  |
| [list_insert](benchmarks/list_insert.md) | 4.78x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 4.69x | +77.7% |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.54x |  |
| [dict_clear](benchmarks/dict_clear.md) | 4.37x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.92x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 3.90x | +42.1% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.85x |  |
| [list_append_small](benchmarks/list_append_small.md) | 3.79x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.24x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.19x |  |
| [nested_func](benchmarks/nested_func.md) | 3.11x | +113.1% |
| [float_abs](benchmarks/float_abs.md) | 2.96x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.90x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.77x |  |
| [method_object](benchmarks/method_object.md) | 2.70x | +76.6% |
| [in_list](benchmarks/in_list.md) | 2.70x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.59x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 2.58x | +53.7% |
| [list_slicing](benchmarks/list_slicing.md) | 2.53x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.51x |  |
| [list_index](benchmarks/list_index.md) | 2.36x | +65.2% |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.24x |  |
| [dict_copy](benchmarks/dict_copy.md) | 2.20x | +34.4% |
| [generators](benchmarks/generators.md) | 2.18x |  |
| [str_methods](benchmarks/str_methods.md) | 2.10x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.05x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.96x |  |
| [list_remove](benchmarks/list_remove.md) | 1.93x | +40.4% |
| [str_to_float](benchmarks/str_to_float.md) | 1.93x |  |
| [list_copy](benchmarks/list_copy.md) | 1.84x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 1.82x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.80x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.76x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.75x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.74x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.72x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.71x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.70x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.66x | +37.2% |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.64x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.60x | +162.9% |
| [int_divmod](benchmarks/int_divmod.md) | 1.49x | +25.8% |
| [bytes_call](benchmarks/bytes_call.md) | 1.48x | +17.3% |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.46x | +110.7% |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.38x | +78.2% |
| [readline](benchmarks/readline.md) | 1.35x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.34x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.34x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.33x |  |
| [str_searching](benchmarks/str_searching.md) | 1.31x |  |
| [list_equality](benchmarks/list_equality.md) | 1.29x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.29x |  |
| [str_format](benchmarks/str_format.md) | 1.25x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.24x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.23x | +22.9% |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.22x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.22x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.21x | +304.6% |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.20x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.17x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.14x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.11x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.10x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.10x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.00x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.99x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.98x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.98x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.98x | +17.8% |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.81x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.74x |  |
