# Cache-Controller-Simulator 
# Direct-Mapped Cache Simulator (C)

## Overview
As part of Computer System Architecture Module, with heavy focus on ARMv8 architecture to understand key concepts such as memory hierarchy, cache design, and CPU performance. Applying these principles i developed a direct-mapped cache controller simulator in C. Calculating memory accesses, cache hits/misses, and memory read/write statistics from trace files.

## Features
- Configurable cache size and block size
- Supports multiple memory trace files
- Reports CPU cache hits/misses and memory accesses
- ANSI C17 compliant

## Tech Stack
- Language: C
- Tools: GCC / Visual Studio Code
- Platform: Windows 

## How to Run
```bash
gcc src/*.c -o cache_sim
./cache_sim traces/memory_trace1.txt
```

## Results
Example of cache statistics output:

```
CPU Reads: 100
CPU Writes: 50
Cache Hits: 75
Cache Misses: 25
Memory Reads: 25
Memory Writes: 50
```

## Future Improvements
- Add fully associative and set-associative cache simulation
- Visualize cache statistics in a GUI
