# Structural Map — osn

**Generated**: 2026-10-18
**Source files scanned**: 0
**Approximate token count**: 0
**Parser**: regex

## Notation

```
[path/to/file.ext]
  fn function_name(params) -> return_type
    calls: fn1, fn2, fn3
    called_by: fn4, fn5
  struct StructName { field1, field2 }
  enum EnumName { VAL1, VAL2 }
```

- `calls:` lists functions this function directly invokes (project-internal only)
- `called_by:` lists functions that directly invoke this function
- Only PUBLIC / EXPORTED symbols listed unless internal symbols cross file boundaries
- Call graph edges are best-effort — static analysis only

## Map

```

```

## Cross-File Dependency Summary

```
(no cross-file dependencies detected)
```
