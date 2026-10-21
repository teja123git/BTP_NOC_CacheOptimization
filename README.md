# Adaptive NoC-Based Memory Prefetching

This project explores adaptive memory prefetching techniques for multicore systems using the Network-on-Chip (NoC). It investigates the use of underutilized router buffers to improve the placement and delivery of prefetched cache blocks, with the goal of reducing memory access latency and improving overall system performance.

The project is developed using [gem5](https://www.gem5.org/), focusing on the Ruby memory system, cache coherence protocols, hardware prefetching, and NoC integration.

## Objectives

- Investigate hardware prefetching techniques for multicore architectures.
- Explore the use of underutilized NoC router buffers for managing prefetched data.
- Develop mechanisms for tracking, placing, and retrieving prefetched cache blocks.
- Evaluate the impact on memory latency, cache performance, network traffic, and resource utilization.

## Technologies

- [gem5](https://www.gem5.org/)
- Ruby memory system and cache coherence
- MOESI-based cache coherence protocol
- Hardware stride prefetching
- Garnet Network-on-Chip

## License and Attribution

This project builds upon the [gem5 simulator](https://github.com/gem5/gem5). The original gem5 license and applicable attribution notices are retained.
