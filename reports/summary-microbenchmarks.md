# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.5, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 38.37x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 23.42x |  |
| [super_method](benchmarks/super_method.md) | 20.32x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 18.10x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 16.08x | +1505.5% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 13.67x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 11.30x | +328.6% |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 10.91x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 10.63x |  |
| [str_call](benchmarks/str_call.md) | 9.00x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 8.07x |  |
| [int_list](benchmarks/int_list.md) | 7.36x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 6.67x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.03x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 5.67x |  |
| [sieve](benchmarks/sieve.md) | 5.56x |  |
| [dict_clear](benchmarks/dict_clear.md) | 5.41x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.49x |  |
| [bytes_format](benchmarks/bytes_format.md) | 4.27x | +152.9% |
| [str_format](benchmarks/str_format.md) | 4.17x | +107.2% |
| [list_insert](benchmarks/list_insert.md) | 4.09x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 3.98x | +146.5% |
| [list_append_small](benchmarks/list_append_small.md) | 3.97x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 3.95x |  |
| [method_object](benchmarks/method_object.md) | 3.89x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.84x | +165.7% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.71x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.45x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.31x |  |
| [float_abs](benchmarks/float_abs.md) | 3.20x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.08x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 2.98x |  |
| [nested_func](benchmarks/nested_func.md) | 2.97x |  |
| [in_tuple](benchmarks/in_tuple.md) | 2.90x |  |
| [in_list](benchmarks/in_list.md) | 2.76x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.75x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.64x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.58x | +47.1% |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.56x |  |
| [str_methods](benchmarks/str_methods.md) | 2.36x |  |
| [list_index](benchmarks/list_index.md) | 2.26x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.22x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.21x |  |
| [generators](benchmarks/generators.md) | 2.18x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 2.12x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.11x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.95x | +46.5% |
| [str_to_float](benchmarks/str_to_float.md) | 1.92x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.92x |  |
| [list_remove](benchmarks/list_remove.md) | 1.92x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.91x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.88x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.83x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.81x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.77x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.69x |  |
| [list_copy](benchmarks/list_copy.md) | 1.65x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.64x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.61x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.59x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.56x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.54x | +20.6% |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.51x |  |
| [readline](benchmarks/readline.md) | 1.49x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.45x |  |
| [str_searching](benchmarks/str_searching.md) | 1.40x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.40x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.39x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.31x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.29x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.25x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.20x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.20x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.18x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.17x | +17.0% |
| [read_write_text](benchmarks/read_write_text.md) | 1.15x |  |
| [list_equality](benchmarks/list_equality.md) | 1.14x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.13x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.08x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.98x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.94x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.90x |  |
| [dict_copy](benchmarks/dict_copy.md) | 0.89x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.82x | -17.4% |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.63x |  |
