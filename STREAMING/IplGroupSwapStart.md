---
ns: STREAMING
aliases: ["0x95A7DABDDBB78AE7"]
---
## IPL_GROUP_SWAP_START

```c
// 0x95A7DABDDBB78AE7 0x9EF0A9CF
void IPL_GROUP_SWAP_START(char* iplName1, char* iplName2);
```

```
Starts pre-streaming for a seamless swap from first IPL group to second. Once ready finish with IPL_GROUP_SWAP_FINISH. Once started it must be cancelled or finished to release streaming resources. Old hash 0x25CF3B0410CD653C.
```

## Parameters
* **iplName1**: Currently enabled IPL group, the before state.
* **iplName2**: Desired end state IPL group to pre-stream.

