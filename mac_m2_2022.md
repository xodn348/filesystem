+--------+  +--------+  +--------+  +--------+
|  CPU   |  | Fabric |  |  GPU   |  | DRAM   |
|  8c    |  |        |  |  10c   |  | 8/24GB |
+---+----+  +----+---+  +----+---+  +----+---+
    |            |           |           |
    |            |           |           |
+---+----+       |      +----+---+  +----+---+
|  Cache |       |      | Neural |  | DRAM   |
|        |       |      | Engine |  | 8/24GB |
|        |       |      |  16c   |  |        |
+---+----+       |      +----+---+  +----+---+
    |            |           |           |
    +------------+-----------+-----------+

+----------------------------+
| Unified memory architecture |
| - High bandwidth, low latency|
| - Apple-designed package    |
| - Accessible to entire SoC  |
| - Neural Engine: 15.8 TOPS  |
+----------------------------+