---
ns: STREAMING
aliases: ["0xBEB2D9A1D9A8F55A"]
---
## SET_SRL_READAHEAD_TIMES

```c
// 0xBEB2D9A1D9A8F55A 0x62F02485
void SET_SRL_READAHEAD_TIMES(Any p0, Any p1, Any p2, Any p3);
```

```
Sets how far in advance an SRL streams. Call right after PREFETCH_SRL. Two values each for while prestreaming vs while playing back, and for loading assets vs loading maps. Default 3 seconds. Pass -1 to use default. Old hash unknown.
```

## Parameters
* **p0**: Prestream map readahead time.
* **p1**: Prestream assets readahead time.
* **p2**: Playback map readahead time.
* **p3**: Playback assets readahead time.

