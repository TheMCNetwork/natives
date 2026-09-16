---
ns: STREAMING
aliases: ["0xEF39EE20C537E98C"]
---
## SET_SRL_POST_CUTSCENE_CAMERA

```c
// 0xEF39EE20C537E98C 0x814D0752
void SET_SRL_POST_CUTSCENE_CAMERA(Any p0, Any p1, Any p2, Any p3, Any p4, Any p5);
```

```
Sets where the camera will be after the cutscene ends so streaming has that scene in memory before cut to gameplay. Call before or during cutscene, ideally 5 seconds before end. Params hold camera position plus look direction. Old hash unknown.
```

## Parameters
* **p0**: Camera position X.
* **p1**: Camera position Y.
* **p2**: Camera position Z.
* **p3**: Camera direction X.
* **p4**: Camera direction Y.
* **p5**: Camera direction Z.

