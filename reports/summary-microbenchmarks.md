# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.2, Ubuntu 20.04 LTS and Intel Core i7-2600K (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 39.16x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 20.60x |  |
| [super_method](benchmarks/super_method.md) | 18.23x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 16.66x | +18.2% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 14.42x | +22.3% |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 10.99x | +18.1% |
| [str_call](benchmarks/str_call.md) | 8.83x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 8.79x | +191.8% |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 8.27x |  |
| [sieve](benchmarks/sieve.md) | 6.34x | +11.3% |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 6.23x |  |
| [int_list](benchmarks/int_list.md) | 6.22x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 5.23x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.89x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 4.73x | +77.4% |
| [list_insert](benchmarks/list_insert.md) | 4.62x | +203.7% |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.39x |  |
| [dict_clear](benchmarks/dict_clear.md) | 4.39x | +37.3% |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.88x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 3.77x | +39.1% |
| [list_append_small](benchmarks/list_append_small.md) | 3.76x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.75x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.26x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.20x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.91x |  |
| [nested_func](benchmarks/nested_func.md) | 2.80x | +89.8% |
| [method_object](benchmarks/method_object.md) | 2.78x | +74.7% |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.78x |  |
| [in_list](benchmarks/in_list.md) | 2.67x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.64x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 2.59x | +54.0% |
| [list_append_large](benchmarks/list_append_large.md) | 2.52x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.43x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.42x |  |
| [float_abs](benchmarks/float_abs.md) | 2.41x | -19.2% |
| [list_index](benchmarks/list_index.md) | 2.39x | +66.7% |
| [generators](benchmarks/generators.md) | 2.13x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.12x |  |
| [str_methods](benchmarks/str_methods.md) | 2.03x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.97x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.96x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.90x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.90x |  |
| [list_remove](benchmarks/list_remove.md) | 1.86x | +35.6% |
| [list_copy](benchmarks/list_copy.md) | 1.85x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 1.81x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.79x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.79x | +44.4% |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.73x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.71x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.66x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.60x | +126.3% |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.58x | +157.7% |
| [list_from_range](benchmarks/list_from_range.md) | 1.58x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.51x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.49x |  |
| [readline](benchmarks/readline.md) | 1.40x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.38x | +18.0% |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.35x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.33x |  |
| [bytes_call](benchmarks/bytes_call.md) | 1.33x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.32x |  |
| [str_searching](benchmarks/str_searching.md) | 1.32x |  |
| [str_format](benchmarks/str_format.md) | 1.31x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.28x |  |
| [list_equality](benchmarks/list_equality.md) | 1.27x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.25x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.23x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.22x | +309.5% |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.18x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.17x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.11x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.10x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.10x | +20.4% |
| [read_write_text](benchmarks/read_write_text.md) | 1.10x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.09x | +44.7% |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.09x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.07x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.99x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.98x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.98x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.94x | +16.2% |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.80x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.71x |  |
