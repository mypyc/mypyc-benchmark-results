# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.5, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 38.55x | +25.4% |
| [super_method_alt](benchmarks/super_method_alt.md) | 22.07x |  |
| [super_method](benchmarks/super_method.md) | 19.77x | +15.1% |
| [dataclass_method](benchmarks/dataclass_method.md) | 19.18x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 12.88x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 10.66x | +19.9% |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 10.43x | +16.9% |
| [str_call](benchmarks/str_call.md) | 9.15x | +44.9% |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 8.28x | +19.2% |
| [int_list](benchmarks/int_list.md) | 8.09x | +37.1% |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 6.66x | +35.8% |
| [list_comprehension](benchmarks/list_comprehension.md) | 6.05x |  |
| [sieve](benchmarks/sieve.md) | 5.88x | +17.1% |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 5.64x | +17.2% |
| [dict_clear](benchmarks/dict_clear.md) | 5.00x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.45x | +24.8% |
| [list_append_small](benchmarks/list_append_small.md) | 4.09x | +15.0% |
| [method_object](benchmarks/method_object.md) | 4.05x | +15.8% |
| [dict_to_list](benchmarks/dict_to_list.md) | 3.99x | +17.2% |
| [list_insert](benchmarks/list_insert.md) | 3.99x | +21.7% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.67x | +20.3% |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.36x | +42.5% |
| [str_slicing](benchmarks/str_slicing.md) | 3.32x | +40.8% |
| [dict_set_default](benchmarks/dict_set_default.md) | 3.08x | +73.6% |
| [float_abs](benchmarks/float_abs.md) | 2.91x |  |
| [nested_func](benchmarks/nested_func.md) | 2.91x | +22.5% |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 2.87x |  |
| [in_tuple](benchmarks/in_tuple.md) | 2.86x | +36.7% |
| [in_list](benchmarks/in_list.md) | 2.86x | +24.5% |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.66x | +31.8% |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.65x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.64x | +21.7% |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.60x |  |
| [list_index](benchmarks/list_index.md) | 2.36x | +36.2% |
| [str_methods](benchmarks/str_methods.md) | 2.27x | +28.0% |
| [list_slicing](benchmarks/list_slicing.md) | 2.26x | +23.8% |
| [tuple_equality](benchmarks/tuple_equality.md) | 2.25x | +40.8% |
| [generators](benchmarks/generators.md) | 2.12x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.06x | +25.9% |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.01x | +28.8% |
| [list_remove](benchmarks/list_remove.md) | 1.95x | +28.8% |
| [split_and_join](benchmarks/split_and_join.md) | 1.91x | +23.4% |
| [str_to_float](benchmarks/str_to_float.md) | 1.90x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.89x | +60.3% |
| [map_builtin](benchmarks/map_builtin.md) | 1.87x | +20.4% |
| [bytes_concat](benchmarks/bytes_concat.md) | 1.83x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.82x | +48.1% |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.81x |  |
| [str_format](benchmarks/str_format.md) | 1.78x | +40.5% |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.77x | +33.6% |
| [bytes_format](benchmarks/bytes_format.md) | 1.67x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.65x | +25.2% |
| [int_divmod](benchmarks/int_divmod.md) | 1.65x | +19.7% |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.65x | +25.6% |
| [list_copy](benchmarks/list_copy.md) | 1.64x | +17.2% |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.61x | +41.4% |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.60x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.58x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.52x |  |
| [readline](benchmarks/readline.md) | 1.49x | +23.5% |
| [bytes_call](benchmarks/bytes_call.md) | 1.46x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.45x | +24.4% |
| [str_searching](benchmarks/str_searching.md) | 1.43x | +31.8% |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.43x | +28.0% |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.40x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.38x | +18.3% |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.28x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.26x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.24x | +40.6% |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.23x | +19.5% |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.22x | +24.0% |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.21x | +20.4% |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.21x | +42.9% |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.18x | +71.1% |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.12x |  |
| [list_equality](benchmarks/list_equality.md) | 1.12x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 1.10x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.09x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.08x | -16.0% |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x | +19.7% |
| [read_write_close](benchmarks/read_write_close.md) | 1.00x | +104.6% |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.98x | +15.1% |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.96x | +16.9% |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.92x | +23.4% |
| [dict_copy](benchmarks/dict_copy.md) | 0.90x | -36.8% |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.69x | +24.1% |
