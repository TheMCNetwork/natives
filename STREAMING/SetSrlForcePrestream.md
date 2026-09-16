---
ns: STREAMING
aliases: ["0xF8155A7F03DDFC8E"]
---
## SET_SRL_FORCE_PRESTREAM

```c
// 0xF8155A7F03DDFC8E 0xF8F515E4
void SET_SRL_FORCE_PRESTREAM(Any p0);
```

```
Enables or disables forced prestreaming for cutscenes. Call right after PREFETCH_SRL. Modes: 0 default, 1 force on, 2 force off, 3 force completely off. Only force on when camera position plus first cutscene frame stay close and scenes hold few entities, else pool overflow risk.
```

## Parameters
* **p0**: Prestream mode, 0 to 3.

