# RISC-V Memory Hierarchy Power Analysis

This project investigates the power-performance trade-offs in RISC-V memory hierarchies using the gem5 simulator. By simulating various cache configurations, it explores how parameters like cache size, associativity, and block size impact performance and power consumption. The workloads include AES encryption, a widely-used, NIST-standardized method critical for high-speed security in fields like finance, healthcare, and IoT, and matrix multiplication, a computational core of deep learning and transformer architectures.

The gem5 simulator is configured to model adjustable L1/L2 caches and DRAM, enabling flexible memory hierarchy experimentation. McPAT is integrated for accurate power estimation based on activity statistics. Through simulations, data such as cache hit/miss rates, simulation time, and power usage is collected to evaluate how hardware optimizations for AES can reduce encryption time and energy usage, and how efficient configurations can accelerate matrix multiplications at low energy costs.

The final analysis identifies optimal configurations for balancing power efficiency and performance across these critical workloads. This study provides valuable insights for designing hardware configurations that support high-throughput, energy-efficient applications in security and AI-driven domains.
