# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.13.1, Ubuntu 24.04.1 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 26.10x |  |
| [attrs_method](benchmarks/attrs_method.md) | 19.65x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 19.59x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 19.31x |  |
| [int_to_float](benchmarks/int_to_float.md) | 16.26x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 15.93x |  |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 15.79x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 15.53x | +83.6% |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 15.00x |  |
| [super_method](benchmarks/super_method.md) | 13.90x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 13.60x |  |
| [int_list](benchmarks/int_list.md) | 12.19x |  |
| [sieve](benchmarks/sieve.md) | 12.12x |  |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 11.57x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 11.15x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 8.24x |  |
| [enums](benchmarks/enums.md) | 7.59x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 6.55x | +26.2% |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 6.54x | +44.9% |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 5.93x |  |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 5.79x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 5.67x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 5.66x |  |
| [generators](benchmarks/generators.md) | 5.50x | +179.2% |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 5.45x |  |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 5.14x |  |
| [nested_func](benchmarks/nested_func.md) | 5.00x | +27.9% |
| [float_abs](benchmarks/float_abs.md) | 4.98x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 4.59x |  |
| [str_call](benchmarks/str_call.md) | 4.26x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 4.10x |  |
| [in_tuple](benchmarks/in_tuple.md) | 3.80x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 3.64x |  |
| [str_format](benchmarks/str_format.md) | 3.61x |  |
| [in_list](benchmarks/in_list.md) | 3.57x |  |
| [list_insert](benchmarks/list_insert.md) | 3.34x |  |
| [bytes_call](benchmarks/bytes_call.md) | 3.27x |  |
| [dict_clear](benchmarks/dict_clear.md) | 3.25x |  |
| [bytes_format](benchmarks/bytes_format.md) | 3.24x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 3.14x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 3.03x |  |
| [list_append_small](benchmarks/list_append_small.md) | 2.95x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 2.90x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 2.82x | +17.5% |
| [bytes_concat](benchmarks/bytes_concat.md) | 2.78x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 2.72x |  |
| [list_index](benchmarks/list_index.md) | 2.72x |  |
| [str_slicing](benchmarks/str_slicing.md) | 2.67x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 2.62x |  |
| [method_object](benchmarks/method_object.md) | 2.55x |  |
| [list_slicing](benchmarks/list_slicing.md) | 2.41x |  |
| [encode_decode](benchmarks/encode_decode.md) | 2.19x |  |
| [list_append_large](benchmarks/list_append_large.md) | 2.14x |  |
| [str_methods](benchmarks/str_methods.md) | 2.14x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 2.13x |  |
| [str_searching](benchmarks/str_searching.md) | 2.12x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 2.06x |  |
| [int_divmod](benchmarks/int_divmod.md) | 2.01x |  |
| [list_copy](benchmarks/list_copy.md) | 1.99x |  |
| [dict_copy](benchmarks/dict_copy.md) | 1.84x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 1.76x |  |
| [list_remove](benchmarks/list_remove.md) | 1.76x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 1.74x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 1.74x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 1.70x |  |
| [list_from_range](benchmarks/list_from_range.md) | 1.66x |  |
| [map_builtin](benchmarks/map_builtin.md) | 1.63x |  |
| [in_set](benchmarks/in_set.md) | 1.63x |  |
| [split_and_join](benchmarks/split_and_join.md) | 1.56x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 1.55x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 1.44x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 1.41x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 1.40x | +3.6% |
| [read_write_chars](benchmarks/read_write_chars.md) | 1.38x |  |
| [str_to_float](benchmarks/str_to_float.md) | 1.37x |  |
| [readline](benchmarks/readline.md) | 1.35x |  |
| [list_equality](benchmarks/list_equality.md) | 1.27x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 1.17x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 1.15x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 1.14x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 1.06x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 1.05x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 1.04x |  |
| [read_write_text](benchmarks/read_write_text.md) | 1.03x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 1.01x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 1.01x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 1.00x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 1.00x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.99x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 0.97x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 0.91x |  |
| [create_attrs](benchmarks/create_attrs.md) | 0.89x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.74x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 0.73x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.48x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.42x |  |
