# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.5, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 40.94x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 22.42x |  |
| [super_method](benchmarks/super_method.md) | 19.29x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 18.92x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 13.95x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 10.91x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 9.91x |  |
| [str_call](benchmarks/str_call.md) | 9.02x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 8.08x |  |
| [int_list](benchmarks/int_list.md) | 7.75x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 6.80x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.01x |  |
| [sieve](benchmarks/sieve.md) | 5.87x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 5.73x |  |
| [dict_clear](benchmarks/dict_clear.md) | 5.03x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.57x |  |
| [str_format](benchmarks/str_format.md) | 4.23x | +217.7% |
| [list_insert](benchmarks/list_insert.md) | 4.04x |  |
| [list_append_small](benchmarks/list_append_small.md) | 3.98x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 3.94x |  |
| [method_object](benchmarks/method_object.md) | 3.87x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.86x | +167.0% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.63x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 3.53x | +34.2% |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.35x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.32x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.05x |  |
| [float_abs](benchmarks/float_abs.md) | 2.97x |  |
| [in_tuple](benchmarks/in_tuple.md) | 2.91x |  |
| [nested_func](benchmarks/nested_func.md) | 2.89x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 2.88x |  |
| [in_list](benchmarks/in_list.md) | 2.79x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.63x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.59x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.52x |  |
| [list_index](benchmarks/list_index.md) | 2.34x |  |
| [str_methods](benchmarks/str_methods.md) | 2.34x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 2.29x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.24x |  |
| [generators](benchmarks/generators.md) | 2.17x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.05x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.02x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.01x | +25.7% |
| [list_remove](benchmarks/list_remove.md) | 1.94x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.92x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.92x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.91x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.85x | +18.5% |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.83x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.79x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.74x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.70x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.66x |  |
| [list_copy](benchmarks/list_copy.md) | 1.66x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.63x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.62x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.58x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.54x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.52x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.52x |  |
| [readline](benchmarks/readline.md) | 1.47x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.47x |  |
| [str_searching](benchmarks/str_searching.md) | 1.43x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.43x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.40x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.39x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.32x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.31x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.25x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.24x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.22x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.21x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.20x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.18x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.13x |  |
| [list_equality](benchmarks/list_equality.md) | 1.13x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.12x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.12x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 1.09x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.99x | +18.7% |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.99x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.96x |  |
| [dict_copy](benchmarks/dict_copy.md) | 0.91x | -52.4% |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.91x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.67x |  |
