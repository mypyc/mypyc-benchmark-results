# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.2, Ubuntu 20.04 LTS and Intel Core i7-2600K (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 39.38x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 20.29x |  |
| [super_method](benchmarks/super_method.md) | 18.58x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 17.26x | +22.5% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 14.42x | +22.3% |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 10.99x | +18.0% |
| [str_call](benchmarks/str_call.md) | 8.80x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 8.55x | +185.3% |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 8.07x |  |
| [int_list](benchmarks/int_list.md) | 6.85x | +19.0% |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 6.61x |  |
| [sieve](benchmarks/sieve.md) | 6.24x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 5.27x |  |
| [list_insert](benchmarks/list_insert.md) | 5.11x | +238.8% |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 4.67x | +514.9% |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.58x |  |
| [dict_clear](benchmarks/dict_clear.md) | 4.36x | +23.6% |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.15x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.92x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 3.78x | +39.5% |
| [list_append_small](benchmarks/list_append_small.md) | 3.75x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.74x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.16x |  |
| [float_abs](benchmarks/float_abs.md) | 3.01x | +207.0% |
| [str_slicing](benchmarks/str_slicing.md) | 2.99x | -17.0% |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.96x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.75x |  |
| [in_list](benchmarks/in_list.md) | 2.67x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.60x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.52x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.47x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.27x |  |
| [str_methods](benchmarks/str_methods.md) | 2.03x |  |
| [generators](benchmarks/generators.md) | 2.02x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.97x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.96x | +95.0% |
| [dict_iteration](benchmarks/dict_iteration.md) | 1.95x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.87x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.85x |  |
| [list_copy](benchmarks/list_copy.md) | 1.85x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.76x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.76x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 1.71x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.65x |  |
| [method_object](benchmarks/method_object.md) | 1.63x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.62x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.61x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 1.58x | -16.7% |
| [nested_func](benchmarks/nested_func.md) | 1.50x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.49x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.47x |  |
| [list_index](benchmarks/list_index.md) | 1.46x |  |
| [readline](benchmarks/readline.md) | 1.39x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.35x |  |
| [list_remove](benchmarks/list_remove.md) | 1.35x |  |
| [str_format](benchmarks/str_format.md) | 1.33x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.31x |  |
| [str_searching](benchmarks/str_searching.md) | 1.31x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.30x |  |
| [list_equality](benchmarks/list_equality.md) | 1.29x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.29x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.27x |  |
| [bytes_call](benchmarks/bytes_call.md) | 1.27x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.23x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.22x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.21x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.20x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.19x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.18x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.18x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.11x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.06x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.04x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.01x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.00x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.98x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.98x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.95x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.85x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.80x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 0.75x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 0.71x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.68x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 0.61x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 0.30x |  |
