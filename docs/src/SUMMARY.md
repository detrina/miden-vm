# Summary

- [Introduction](./intro/main.md)
  - [Overview](./intro/overview.md)
  - [Usage](./intro/usage.md)
  - [Performance](./intro/performance.md)
- [User Documentation](./user_docs/main.md)
  - [Miden Assembly](./user_docs/assembly/main.md)
    - [Code Organization](./user_docs/assembly/code_organization.md)
    - [Flow Control](./user_docs/assembly/flow_control.md)
    - [Field Operations](./user_docs/assembly/field_operations.md)
    - [u32 Operations](./user_docs/assembly/u32_operations.md)
    - [Stack manipulation](./user_docs/assembly/stack_manipulation.md)
    - [Input / Output Operations](./user_docs/assembly/io_operations.md)
    - [Cryptographic Operations](./user_docs/assembly/cryptographic_operations.md)
  - [Miden Standard Library](./user_docs/stdlib/main.md)
    - [std::crypto::hashes](./user_docs/stdlib/crypto/hashes.md)
    - [std::math::u64](./user_docs/stdlib/math/u64.md)
    - [std:sys](./user_docs/stdlib/sys.md)
- [Design](./design/main.md)
  - [Programs](./design/programs.md)
  - [Program decoder](./design/decoder/main.md)
    - [Decoder constraints](./design/decoder/constraints.md)
  - [Operand stack](./design/stack/main.md)
    - [Operation constraints](./design/stack/op_constraints.md)
    - [System operations](./design/stack/system_ops.md)
    - [Field operations](./design/stack/field_ops.md)
    - [u32 operations](./design/stack/u32_ops.md)
    - [Stack manipulation](./design/stack/stack_ops.md)
    - [Input / output operations](./design/stack/io_ops.md)
    - [Cryptographic operations](./design/stack/crypto_ops.md)
  - [Range Checker](./design/range.md)
  - [Chiplets](./design/chiplets/main.md)
    - [Hash Chiplet](./design/chiplets/hasher.md)
    - [Bitwise Chiplet](./design/chiplets/bitwise.md)
    - [Memory Chiplet](./design/chiplets/memory.md)
  - [Multiset checks](./design/multiset.md)
- [Background Material](./background.md)