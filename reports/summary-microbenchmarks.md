# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.13.1, Ubuntu 24.04.1 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [sieve_packed](benchmarks/sieve_packed.md) | 68.71x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 45.02x |  |
| [attrs_method](benchmarks/attrs_method.md) | 19.65x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 19.58x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 19.34x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 15.81x |  |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 15.79x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 15.57x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 15.00x |  |
| [int_to_float](benchmarks/int_to_float.md) | 13.92x |  |
| [super_method](benchmarks/super_method.md) | 13.88x |  |
| [sieve](benchmarks/sieve.md) | 13.18x | -3.9% |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 12.54x |  |
| [int_list](benchmarks/int_list.md) | 12.35x |  |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 11.52x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 11.33x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 8.23x |  |
| [enums](benchmarks/enums.md) | 7.59x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 7.03x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 6.61x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 6.22x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 6.00x |  |
| [bytes_normalize](benchmarks/bytes_normalize.md) | 5.91x |  |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 5.90x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 5.83x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 5.74x |  |
| [generators](benchmarks/generators.md) | 5.58x |  |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 5.30x |  |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 5.02x |  |
| [float_abs](benchmarks/float_abs.md) | 4.97x |  |
| [nested_func](benchmarks/nested_func.md) | 4.70x |  |
| [rot13](benchmarks/rot13.md) | 4.70x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 4.35x |  |
| [str_call](benchmarks/str_call.md) | 4.26x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.24x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.76x |  |
| [str_format](benchmarks/str_format.md) | 3.64x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 3.62x |  |
| [in_list](benchmarks/in_list.md) | 3.55x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 3.32x |  |
| [list_insert](benchmarks/list_insert.md) | 3.24x |  |
| [bytes_format](benchmarks/bytes_format.md) | 3.21x |  |
| [dict_clear](benchmarks/dict_clear.md) | 3.21x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.13x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 3.04x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 3.01x |  |
| [list_append_small](benchmarks/list_append_small.md) | 2.91x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 2.88x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.79x |  |
| [encode_decode](benchmarks/encode_decode.md) | 2.70x |  |
| [str_slicing](benchmarks/str_slicing.md) | 2.69x |  |
| [list_index](benchmarks/list_index.md) | 2.69x |  |
| [method_object](benchmarks/method_object.md) | 2.58x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.55x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 2.44x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.44x |  |
| [str_methods](benchmarks/str_methods.md) | 2.43x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.15x |  |
| [str_searching](benchmarks/str_searching.md) | 2.15x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 2.12x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 2.10x |  |
| [int_divmod](benchmarks/int_divmod.md) | 2.07x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.04x |  |
| [list_copy](benchmarks/list_copy.md) | 1.96x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.86x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.79x |  |
| [list_remove](benchmarks/list_remove.md) | 1.78x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.75x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.75x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.68x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.64x |  |
| [in_set](benchmarks/in_set.md) | 1.63x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.56x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.54x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.54x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.49x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.40x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.37x |  |
| [readline](benchmarks/readline.md) | 1.33x |  |
| [list_equality](benchmarks/list_equality.md) | 1.27x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.20x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.13x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.12x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.05x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.05x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.05x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.05x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.00x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 0.99x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 0.98x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 0.97x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.97x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 0.90x |  |
| [create_attrs](benchmarks/create_attrs.md) | 0.90x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.74x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 0.74x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.48x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.41x |  |
