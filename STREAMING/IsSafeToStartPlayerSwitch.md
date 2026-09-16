---
ns: STREAMING
aliases: ["0x71E7B2E657449AAD"]
---
## IS_SAFE_TO_START_PLAYER_SWITCH

```c
// 0x71E7B2E657449AAD 0xEAA51103
cs_type(Any) BOOL IS_SAFE_TO_START_PLAYER_SWITCH();
```

```
Returns true if OK to start a player switch, false if in the middle of death or arrest etc. Old hash 0x3510BF4043201732.
```

## Return value
True if safe to start player switch, else false.
