+--------+  +--------+  +--------+  +--------+
|  CPU   |  | Fabric |  |  GPU   |  | DRAM   |
| 10c    |  |        |  | 10c    |  |16/32GB |
+---+----+  +----+---+  +----+---+  +----+---+
    |            |           |           |
    |            |           |           |
+---+----+       |      +----+---+  +----+---+
|  Cache |       |      | Neural |  | DRAM   |
|        |       |      | Engine |  |16/32GB |
|        |       |      |  16c   |  |        |
+---+----+       |      +----+---+  +----+---+
    |            |           |           |
    +------------+-----------+-----------+

+----------------------------+
| Unified memory architecture |
| - High bandwidth, low latency|
| - Apple-designed package    |
| - Accessible to entire SoC  |
| - Neural Engine: 38 TOPS    |
| - 2nd-gen 3nm process      |
+----------------------------+