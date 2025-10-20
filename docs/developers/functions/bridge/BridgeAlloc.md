# BridgeAlloc

Allocate a memory buffer for use by MARENOL. The memory is freed by [BridgeFree](./BridgeFree.md).

```c++
void* BridgeAlloc(
    size_t size // memory size to allocate
    );
```

## Parameters

`size` Memory size (in bytes) to allocate.

## Return Value

Returns a pointer to the memory block allocated. If an error occurs allocating memory, then MARENOL is closed down.

## Example

```c++
auto ptr = (char*)BridgeAlloc(128);
//do something with ptr
BridgeFree(ptr);
```

## Related functions

- [BridgeFree](./BridgeFree.md)