# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.2, Ubuntu 20.04 LTS and Intel Core i7-2600K (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [enums](benchmarks/enums.md) | 37.40x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 21.36x | +15.3% |
| [super_method](benchmarks/super_method.md) | 18.36x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 17.47x | +27.7% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 14.44x | +21.0% |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 10.82x | +17.5% |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 10.73x | +71.0% |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 8.67x |  |
| [str_call](benchmarks/str_call.md) | 8.64x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 8.27x |  |
| [int_list](benchmarks/int_list.md) | 6.85x | +21.9% |
| [sieve](benchmarks/sieve.md) | 6.21x | +10.4% |
| [list_comprehension](benchmarks/list_comprehension.md) | 5.19x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 4.99x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 4.85x |  |
| [list_insert](benchmarks/list_insert.md) | 4.44x |  |
| [dict_clear](benchmarks/dict_clear.md) | 4.37x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 4.32x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 3.89x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 3.78x | +39.5% |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 3.75x |  |
| [list_append_small](benchmarks/list_append_small.md) | 3.74x | +21.3% |
| [str_slicing](benchmarks/str_slicing.md) | 3.74x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.23x |  |
| [nested_func](benchmarks/nested_func.md) | 3.11x | +112.4% |
| [float_abs](benchmarks/float_abs.md) | 3.01x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.95x |  |
| [in_list](benchmarks/in_list.md) | 2.67x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 2.64x | +63.5% |
| [method_object](benchmarks/method_object.md) | 2.63x | +76.8% |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.58x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 2.58x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.52x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.38x |  |
| [list_index](benchmarks/list_index.md) | 2.36x | +66.9% |
| [list_slicing](benchmarks/list_slicing.md) | 2.33x |  |
| [dict_copy](benchmarks/dict_copy.md) | 2.22x | +42.5% |
| [str_methods](benchmarks/str_methods.md) | 2.19x | +10.1% |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.14x |  |
| [generators](benchmarks/generators.md) | 2.11x | +19.1% |
| [str_to_float](benchmarks/str_to_float.md) | 2.03x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 1.96x |  |
| [list_remove](benchmarks/list_remove.md) | 1.92x | +40.8% |
| [bytes_concat](benchmarks/bytes_concat.md) | 1.88x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.88x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 1.87x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 1.84x |  |
| [list_copy](benchmarks/list_copy.md) | 1.83x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.82x | +56.1% |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.73x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.73x |  |
| [bytes_format](benchmarks/bytes_format.md) | 1.71x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.64x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.62x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.61x | +131.6% |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.55x | +150.1% |
| [int_divmod](benchmarks/int_divmod.md) | 1.54x | +30.6% |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.48x |  |
| [bytes_call](benchmarks/bytes_call.md) | 1.46x | +15.9% |
| [readline](benchmarks/readline.md) | 1.38x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.33x |  |
| [str_searching](benchmarks/str_searching.md) | 1.32x |  |
| [str_format](benchmarks/str_format.md) | 1.32x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.31x | +74.9% |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.31x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.31x |  |
| [list_equality](benchmarks/list_equality.md) | 1.27x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.26x |  |
| [int_to_float](benchmarks/int_to_float.md) | 1.23x | +21.7% |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.22x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 1.22x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.20x | +308.0% |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.20x |  |
| [encode_decode](benchmarks/encode_decode.md) | 1.19x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.18x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 1.17x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.13x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.12x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 1.01x | +18.8% |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.00x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.98x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.98x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.98x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.81x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.70x |  |
