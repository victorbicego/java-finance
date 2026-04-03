Stack vs Heap 

Escape analysis (JIT optimization)

Scalar replacement

Object allocation (TLAB)

Object layout (headers, padding, alignment)

Compressed OOPs

Happens-before

Memory visibility

Instruction reordering (CPU + compiler)

Memory barriers (store/load fences)

volatile (guarantees, limitations, use cases)

synchronized (monitor internals, lock states)

Biased locking (legacy, removal impact)

Lock elision

Safepoints

CPU cache (L1, L2, L3)

Cache coherence (MESI protocol)

Cache lines (false sharing detection)

False sharing mitigation (padding, @Contended)

NUMA architecture (local vs remote memory access)

Race conditions

Thread contention

CAS (Compare-And-Swap internals)

Atomic classes (AtomicInteger, LongAdder, Striped64)

Lock-free programming

Wait-free vs lock-free

Busy waiting vs blocking

Spin locks

Backoff strategies

Context switching cost

System calls cost

User-space vs kernel-space

Heap generations (Young / Old)

Allocation rate & object lifetime

GC roots

Stop-the-world pauses (STW)

Serial GC

Parallel GC

G1 GC (regions, mixed GC)

ZGC (colored pointers, concurrent phases)

Shenandoah

Throughput vs latency trade-off

GC tuning (-XX flags, pause goals)

Allocation profiling

Object pooling (trade-offs)

Off-heap memory

Direct ByteBuffers

Memory-mapped files (mmap)

Pre-allocation strategies

Garbage-free programming

Disruptor pattern (ring buffer)

Mechanical sympathy

CPU pipelines

Branch prediction

Memory bandwidth vs latency

Latency vs throughput

Tail latency (p99, p999, p9999)

Latency jitter

Warmup (JIT effects)

Coordinated omission

GC logs analysis

JFR (Java Flight Recorder)

Async Profiler

perf (Linux profiling)

JMH benchmarking pitfalls