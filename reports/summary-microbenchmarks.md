# Mypyc benchmark summary (microbenchmarks)

**Note:** Microbenchmarks don't reflect real-world performance and can be noisy.
           They are mostly used for identifying bottlenecks, and detecting major performance
           improvements or regressions.

Performance is relative to interpreted Python.

Environment: CPython 3.8.10, Ubuntu 20.04.2 LTS and Intel Core i5-1145G7 (64-bit).

| Benchmark | Current perf | Change in 3 months |
| --- | :---: | :---: |
| [alloc_long_lived_linked](benchmarks/alloc_long_lived_linked.md) | 0.00x |  |
| [list_insert](benchmarks/list_insert.md) | 0.00x |  |
| [encode_decode](benchmarks/encode_decode.md) | 0.00x |  |
| [super_method_alt](benchmarks/super_method_alt.md) | 0.00x |  |
| [create_namedtuple](benchmarks/create_namedtuple.md) | 0.00x |  |
| [min_max_sequence](benchmarks/min_max_sequence.md) | 0.00x |  |
| [tuple_from_iterable](benchmarks/tuple_from_iterable.md) | 0.00x |  |
| [attrs_as_dict_key](benchmarks/attrs_as_dict_key.md) | 0.00x |  |
| [call_method_from_interpreted](benchmarks/call_method_from_interpreted.md) | 0.00x |  |
| [sieve](benchmarks/sieve.md) | 0.00x |  |
| [attrs_method](benchmarks/attrs_method.md) | 0.00x |  |
| [call_type_from_interpreted](benchmarks/call_type_from_interpreted.md) | 0.00x |  |
| [unpack_namedtuple](benchmarks/unpack_namedtuple.md) | 0.00x |  |
| [str_searching](benchmarks/str_searching.md) | 0.00x |  |
| [int_bitwise_ops](benchmarks/int_bitwise_ops.md) | 0.00x |  |
| [list_comprehension](benchmarks/list_comprehension.md) | 0.00x |  |
| [bytes_slicing](benchmarks/bytes_slicing.md) | 0.00x |  |
| [int_divmod](benchmarks/int_divmod.md) | 0.00x |  |
| [int_to_float](benchmarks/int_to_float.md) | 0.00x |  |
| [str_slicing](benchmarks/str_slicing.md) | 0.00x |  |
| [in_set](benchmarks/in_set.md) | 0.00x |  |
| [dict_call_keywords](benchmarks/dict_call_keywords.md) | 0.00x |  |
| [bytes_concat](benchmarks/bytes_concat.md) | 0.00x |  |
| [get_namedtuple_item](benchmarks/get_namedtuple_item.md) | 0.00x |  |
| [sorted_with_key](benchmarks/sorted_with_key.md) | 0.00x |  |
| [float_abs](benchmarks/float_abs.md) | 0.00x |  |
| [bytes_searching](benchmarks/bytes_searching.md) | 0.00x |  |
| [catch_exceptions](benchmarks/catch_exceptions.md) | 0.00x |  |
| [keyword_args_from_interpreted](benchmarks/keyword_args_from_interpreted.md) | 0.00x |  |
| [list_concatenate](benchmarks/list_concatenate.md) | 0.00x |  |
| [bytes_format](benchmarks/bytes_format.md) | 0.00x |  |
| [attrs_attr_access](benchmarks/attrs_attr_access.md) | 0.00x |  |
| [method_object](benchmarks/method_object.md) | 0.00x |  |
| [map_builtin](benchmarks/map_builtin.md) | 0.00x |  |
| [access_attr_from_interpreted](benchmarks/access_attr_from_interpreted.md) | 0.00x |  |
| [bytes_call](benchmarks/bytes_call.md) | 0.00x |  |
| [alloc_short_lived_simple](benchmarks/alloc_short_lived_simple.md) | 0.00x |  |
| [dict_del_item](benchmarks/dict_del_item.md) | 0.00x |  |
| [generators](benchmarks/generators.md) | 0.00x |  |
| [set_literal_iteration](benchmarks/set_literal_iteration.md) | 0.00x |  |
| [list_equality](benchmarks/list_equality.md) | 0.00x |  |
| [read_write_chars](benchmarks/read_write_chars.md) | 0.00x |  |
| [list_remove](benchmarks/list_remove.md) | 0.00x |  |
| [create_dataclass](benchmarks/create_dataclass.md) | 0.00x |  |
| [list_append_large](benchmarks/list_append_large.md) | 0.00x |  |
| [list_slicing](benchmarks/list_slicing.md) | 0.00x |  |
| [min_max_pair](benchmarks/min_max_pair.md) | 0.00x |  |
| [enums](benchmarks/enums.md) | 0.00x |  |
| [list_append_small](benchmarks/list_append_small.md) | 0.00x |  |
| [super_method](benchmarks/super_method.md) | 0.00x |  |
| [dict_call_generator](benchmarks/dict_call_generator.md) | 0.00x |  |
| [list_copy](benchmarks/list_copy.md) | 0.00x |  |
| [dict_to_list](benchmarks/dict_to_list.md) | 0.00x |  |
| [matrix_multiply](benchmarks/matrix_multiply.md) | 0.00x |  |
| [sum_tree_singledispatch](benchmarks/sum_tree_singledispatch.md) | 0.00x |  |
| [str_format](benchmarks/str_format.md) | 0.00x |  |
| [alloc_short_lived_linked](benchmarks/alloc_short_lived_linked.md) | 0.00x |  |
| [str_methods_2](benchmarks/str_methods_2.md) | 0.00x |  |
| [in_list](benchmarks/in_list.md) | 0.00x |  |
| [read_write_binary](benchmarks/read_write_binary.md) | 0.00x |  |
| [list_from_range](benchmarks/list_from_range.md) | 0.00x |  |
| [ord_builtin](benchmarks/ord_builtin.md) | 0.00x |  |
| [multiple_assignment](benchmarks/multiple_assignment.md) | 0.00x |  |
| [dict_set_default](benchmarks/dict_set_default.md) | 0.00x |  |
| [bytes_split_and_join](benchmarks/bytes_split_and_join.md) | 0.00x |  |
| [dict_iteration](benchmarks/dict_iteration.md) | 0.00x |  |
| [str_call](benchmarks/str_call.md) | 0.00x |  |
| [str_to_float](benchmarks/str_to_float.md) | 0.00x |  |
| [dict_clear](benchmarks/dict_clear.md) | 0.00x |  |
| [list_add_in_place](benchmarks/list_add_in_place.md) | 0.00x |  |
| [tuple_slicing](benchmarks/tuple_slicing.md) | 0.00x |  |
| [positional_args_from_interpreted](benchmarks/positional_args_from_interpreted.md) | 0.00x |  |
| [list_index](benchmarks/list_index.md) | 0.00x |  |
| [nested_func](benchmarks/nested_func.md) | 0.00x |  |
| [readline](benchmarks/readline.md) | 0.00x |  |
| [read_write_small_files](benchmarks/read_write_small_files.md) | 0.00x |  |
| [split_and_join](benchmarks/split_and_join.md) | 0.00x |  |
| [str_methods](benchmarks/str_methods.md) | 0.00x |  |
| [dict_copy](benchmarks/dict_copy.md) | 0.00x |  |
| [create_attrs](benchmarks/create_attrs.md) | 0.00x |  |
| [bytes_methods](benchmarks/bytes_methods.md) | 0.00x |  |
| [dataclass_as_dict_key](benchmarks/dataclass_as_dict_key.md) | 0.00x |  |
| [alloc_long_lived_simple](benchmarks/alloc_long_lived_simple.md) | 0.00x |  |
| [list_for_reversed](benchmarks/list_for_reversed.md) | 0.00x |  |
| [bytes_indexing](benchmarks/bytes_indexing.md) | 0.00x |  |
| [tuple_equality](benchmarks/tuple_equality.md) | 0.00x |  |
| [read_write_close](benchmarks/read_write_close.md) | 0.00x |  |
| [dataclass_method](benchmarks/dataclass_method.md) | 0.00x |  |
| [in_tuple](benchmarks/in_tuple.md) | 0.00x |  |
| [read_write_text](benchmarks/read_write_text.md) | 0.00x |  |
| [int_long_bitwise_ops](benchmarks/int_long_bitwise_ops.md) | 0.00x |  |
| [list_from_tuple](benchmarks/list_from_tuple.md) | 0.00x |  |
| [nested_func_escape](benchmarks/nested_func_escape.md) | 0.00x |  |
| [dataclass_attr_access](benchmarks/dataclass_attr_access.md) | 0.00x |  |
| [int_list](benchmarks/int_list.md) | 0.00x |  |
| [read_write_binary_chunks](benchmarks/read_write_binary_chunks.md) | 0.00x |  |
