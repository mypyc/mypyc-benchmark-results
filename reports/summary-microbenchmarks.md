# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.5, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 38.52x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 23.39x |  |
| [super_method](benchmarks/super_method.md) | 19.46x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 19.38x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 15.72x | +1283.0% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 12.77x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 11.58x | +347.1% |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 10.82x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 10.72x |  |
| [str_call](benchmarks/str_call.md) | 9.18x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 8.50x |  |
| [int_list](benchmarks/int_list.md) | 7.36x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 6.88x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 5.79x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 5.79x |  |
| [sieve](benchmarks/sieve.md) | 5.55x | -5.3% |
| [dict_clear](benchmarks/dict_clear.md) | 4.95x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.49x |  |
| [str_format](benchmarks/str_format.md) | 4.10x | +200.7% |
| [list_insert](benchmarks/list_insert.md) | 4.05x |  |
| [bytes_format](benchmarks/bytes_format.md) | 3.96x | +136.9% |
| [list_append_small](benchmarks/list_append_small.md) | 3.94x |  |
| [method_object](benchmarks/method_object.md) | 3.94x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 3.90x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.85x | +163.5% |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 3.73x | +125.4% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.71x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.34x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.31x |  |
| [float_abs](benchmarks/float_abs.md) | 3.10x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 2.95x |  |
| [nested_func](benchmarks/nested_func.md) | 2.94x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 2.93x |  |
| [in_tuple](benchmarks/in_tuple.md) | 2.89x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.73x |  |
| [in_list](benchmarks/in_list.md) | 2.69x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.61x | +47.7% |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.59x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.47x |  |
| [list_index](benchmarks/list_index.md) | 2.37x |  |
| [str_methods](benchmarks/str_methods.md) | 2.36x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.22x |  |
| [generators](benchmarks/generators.md) | 2.15x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 2.13x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.03x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.02x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.95x | +45.3% |
| [split_and_join](benchmarks/split_and_join.md) | 1.94x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.92x |  |
| [list_remove](benchmarks/list_remove.md) | 1.92x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.92x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.84x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.81x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.80x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.77x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.69x |  |
| [list_copy](benchmarks/list_copy.md) | 1.66x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.60x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.58x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.54x | +19.1% |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.52x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.52x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.50x |  |
| [readline](benchmarks/readline.md) | 1.48x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.45x |  |
| [str_searching](benchmarks/str_searching.md) | 1.41x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.40x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.39x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.31x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.29x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.25x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.25x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.21x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.20x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.20x |  |
| [list_equality](benchmarks/list_equality.md) | 1.14x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.13x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.11x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.02x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.98x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.98x | -18.0% |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.94x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.91x |  |
| [dict_copy](benchmarks/dict_copy.md) | 0.90x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.82x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.62x |  |
