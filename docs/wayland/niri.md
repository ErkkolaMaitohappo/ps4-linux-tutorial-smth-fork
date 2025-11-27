# Niri Optimizations

| Niri tweaks                                                  | Description                                                                                  |
|--------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| `decorations { border { enable no } shadow { enable no } rounded-corners 0 }` | Disables borders, drop-shadows and rounded corners                          |
| blur { enable no }                                           | Disables blur (biggest single performance win on PS4 Pro)                                    |
| animate no                                                   | Disables all animations (instant window movement, no slowdown)                               |
| AQ_NO_MODIFIERS=1                                            | Disables DRM modifiers – fixes DDB limit errors and stuttering on GCN 2.0                    |
| RADV_PERFTEST=nggc,rt,sco                                    | Enables Next Generation Geometry Culling, Rasterizer Toggle and Shader Cache Optimizations   |