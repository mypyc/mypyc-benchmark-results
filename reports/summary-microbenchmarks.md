# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.5, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 41.64x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 22.18x |  |
| [super_method](benchmarks/super_method.md) | 19.08x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 18.11x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 13.79x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 11.72x | +350.5% |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 11.52x | +909.9% |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 10.91x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 10.25x |  |
| [str_call](benchmarks/str_call.md) | 8.82x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 8.66x |  |
| [int_list](benchmarks/int_list.md) | 7.49x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 6.82x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.02x |  |
| [sieve](benchmarks/sieve.md) | 5.86x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 5.77x |  |
| [dict_clear](benchmarks/dict_clear.md) | 4.97x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.55x |  |
| [str_format](benchmarks/str_format.md) | 4.21x | +214.7% |
| [method_object](benchmarks/method_object.md) | 4.04x |  |
| [list_insert](benchmarks/list_insert.md) | 4.02x |  |
| [list_append_small](benchmarks/list_append_small.md) | 3.97x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 3.95x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.84x | +164.0% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.63x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.34x |  |
| [str_slicing](benchmarks/str_slicing.md) | 3.31x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 3.14x | +110.5% |
| [dict_set_default](benchmarks/dict_set_default.md) | 2.98x |  |
| [nested_func](benchmarks/nested_func.md) | 2.91x |  |
| [in_tuple](benchmarks/in_tuple.md) | 2.90x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 2.89x |  |
| [in_list](benchmarks/in_list.md) | 2.88x |  |
| [float_abs](benchmarks/float_abs.md) | 2.87x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.62x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.61x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.45x |  |
| [str_methods](benchmarks/str_methods.md) | 2.35x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 2.31x |  |
| [list_index](benchmarks/list_index.md) | 2.19x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.18x |  |
| [generators](benchmarks/generators.md) | 2.14x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.03x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.02x | +24.9% |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.00x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.98x | +41.1% |
| [list_remove](benchmarks/list_remove.md) | 1.93x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.93x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.92x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.91x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.83x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.80x | +15.7% |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.80x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.77x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.71x |  |
| [list_copy](benchmarks/list_copy.md) | 1.65x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.64x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.63x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.60x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.59x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.56x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.51x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.47x |  |
| [readline](benchmarks/readline.md) | 1.46x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.46x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.43x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.40x |  |
| [str_searching](benchmarks/str_searching.md) | 1.39x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.30x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.23x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.21x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.20x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.20x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.18x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.15x |  |
| [list_equality](benchmarks/list_equality.md) | 1.14x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.12x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.10x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [read_write_close](benchmarks/read_write_close.md) | 1.00x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.98x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.98x | -17.0% |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.94x |  |
| [dict_copy](benchmarks/dict_copy.md) | 0.91x | -52.6% |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.90x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.68x |  |
