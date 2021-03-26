# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.2, Ubuntu 20.04 LTS and Intel Core i7-2600K (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 35.64x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 21.16x | +15.6% |
| [super_method](benchmarks/super_method.md) | 17.98x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 17.30x | +22.8% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 14.42x | +22.3% |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 10.66x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 10.53x | +76.5% |
| [str_call](benchmarks/str_call.md) | 8.78x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 8.61x | +191.6% |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 7.46x |  |
| [int_list](benchmarks/int_list.md) | 6.85x | +18.0% |
| [sieve](benchmarks/sieve.md) | 6.35x | +11.5% |
| [list_comprehension](benchmarks/list_comprehension.md) | 5.13x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.77x |  |
| [list_insert](benchmarks/list_insert.md) | 4.75x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 4.68x | +77.2% |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.55x |  |
| [dict_clear](benchmarks/dict_clear.md) | 4.37x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.92x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 3.89x | +41.7% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.85x |  |
| [list_append_small](benchmarks/list_append_small.md) | 3.77x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.21x |  |
| [nested_func](benchmarks/nested_func.md) | 3.21x | +119.8% |
| [float_abs](benchmarks/float_abs.md) | 3.01x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.91x |  |
| [str_slicing](benchmarks/str_slicing.md) | 2.90x |  |
| [method_object](benchmarks/method_object.md) | 2.82x | +84.2% |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.80x |  |
| [in_list](benchmarks/in_list.md) | 2.71x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 2.67x | +59.2% |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.59x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.48x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.41x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.40x |  |
| [dict_copy](benchmarks/dict_copy.md) | 2.39x | +46.2% |
| [list_index](benchmarks/list_index.md) | 2.38x | +66.5% |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.28x |  |
| [str_methods](benchmarks/str_methods.md) | 2.27x | +15.2% |
| [generators](benchmarks/generators.md) | 2.11x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.96x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.94x |  |
| [list_remove](benchmarks/list_remove.md) | 1.92x | +39.2% |
| [list_copy](benchmarks/list_copy.md) | 1.87x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.85x | +53.2% |
| [bytes_concat](benchmarks/bytes_concat.md) | 1.84x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.83x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.79x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.76x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.75x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.73x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.71x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.69x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.62x | +133.7% |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.59x | +158.5% |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.54x |  |
| [int_divmod](benchmarks/int_divmod.md) | 1.51x | +27.6% |
| [bytes_call](benchmarks/bytes_call.md) | 1.47x | +16.7% |
| [readline](benchmarks/readline.md) | 1.38x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.36x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.35x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.35x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.33x | +74.5% |
| [str_searching](benchmarks/str_searching.md) | 1.30x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.30x |  |
| [list_equality](benchmarks/list_equality.md) | 1.28x |  |
| [str_format](benchmarks/str_format.md) | 1.27x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.25x | +23.9% |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.23x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.22x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.22x | -3.0% |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.19x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.19x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.19x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.18x | +295.0% |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.15x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.11x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.10x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.00x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.99x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.98x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.98x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.97x | +17.2% |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.81x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.71x |  |
