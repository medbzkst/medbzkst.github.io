PhD Student at KAUST (King Abdullah University of Science and Technology)

mohamed dot bouaziz at kaust.edu.sa | [LinkedIn](https://www.linkedin.com/in/mohamed-bouaziz/) | [GitHub](https://github.com/medbzkst) | [Resume](./docs/resume.pdf)

Mohamed Bouaziz is a PhD student in the Accelerated Connected Computing Lab at KAUST, working on hardware acceleration on reconfigurable spatial dataflow architectures.

Mohamed is open to internship opportunities in the industry focused on building compilers and custom spatial dataflow architectures for HPC/AI applications.

# Skills
Programming Languages:
- C/C++ (preferred, advanced)
- Python (advanced)
- Verilog/SystemVerilog (proficient)
- MLIR (proficient)

Frameworks:
- High-Level Synthesis (HLS)
- MLIR compiler infrastructure
- AMD AIE API
- CUDA
- OpenMP
- OpenMPI
- Numpy, Cupy

Tools:
- Vivado/Vitis
- Vitis Analyzer
- Polygeist/Clang
- Gprof
- GitHub

# Publications

__[ISC'25] A Dataflow Overlay for Monte Carlo Multi-Asset Option Pricing on AMD Versal AI Engines__ \
[PDF](./papers/pdf/isc25mc.pdf) | [Slides](./papers/slides/isc25mc.pdf) | [Poster in SNSL](./posters/snsl25mc.pdf) \
__M. Bouaziz__, M. Samet, and S. A. Fahmy \
Proposes a dataflow design to run Monte Carlo simulations on AMD AI Engines for a financial application.

__[IPDPSW'25] PRNGine: Massively Parallel Pseudo-Random Number Generation and Probability Distribution Approximations on AMD AI Engines__ \
[PDF](./papers/pdf/ipdpsw25prng.pdf) | [Slides](./papers/slides/ipdpsw25prng.pdf) \
__M. Bouaziz__, and S. A. Fahmy \
Shows how PRNGs can be implemented on AMD AI Engines by combining supported operations and how to deploy the design in a dataflow model.

__[IPDPSW'25] Benchmarking Floating Point Performance of Massively Parallel Dataflow Overlays on AMD Versal Compute Primitives__ \
[PDF](./papers/pdf/ipdpsw25fp.pdf) | [Slides](./papers/slides/ipdpsw25fp.pdf) | [Poster in DATE'25, OSSMPIC workshop](./posters/date25fp.pdf) \
__M. Bouaziz__, and S. A. Fahmy \
Compares the performance and the energy efficiency of floating-point units on AMD Versal (AI Engines v.s. DSP58 blocks) and highlights the challenges for implementing massive designs of FP32 operations on the same architecture.

__[IEEE Access'23] Parallel FPGA routers with lagrange relaxation__ \
[Link (Open Access)](https://doi.org/10.1109/ACCESS.2023.3328769) \
R. Agrawal, K. Ahuja, D. Maheshwari, M. U. Shaikh, __M. Bouaziz__, and A. Kumar \
Implements parallel FPGA routing based on VTR/VPR 7 and leveraging Lagrangian Relaxation numerical method for routability.

__[ASAP'24 (PhD Forum Paper)] Leveraging MLIR for Efficient Irregular-Shaped CGRA Overlay Design__ \
[PDF](./papers/pdf/asap24cgraoverlay.pdf) | [Poster](./posters/asap24cgraoverlay.pdf) \
__M. Bouaziz__, and S. A. Fahmy \
Proposes leveraging MLIR compiler infrastructure to analyze irregularities in HPC/AI workloads and optimise the CGRA/dataflow architectures accordingly (performance & energy).

# Teaching
- Official Teaching Assistant:
  - __[Spring'25] CS356 (PhD level): Hardware Accelerator Architectures__ \
    Designing a High-Level Synthesis (HLS) tutorial from scratch. Giving tutorial sessions on HLS. Grading the course project.
  - __[Fall'23,24,25] CS256 (MS level): Digital Design and Computer Architecture__ \
    Giving tutorials on Vivado, providing help sessions for the course project (arcade game design in SystemVerilog), grading homework and the course project.
  - __[Fall'23] CS280 (MS level): System Architecture and Performance__ \
    Grading homework and the course project, and providing assistance to students.
- Unofficial Teaching/Workshop:
  - __[Summer'25] High-Level Synthesis and AMD NPU programming__ \
    Gave sessions on HLS design and AMD NPU programming to a group of enthusiastic students from [Ecole Polytechnique de Tunisie](https://ept.tn/) (where I did my MEng.). The course was sponsored by AMD, which generously provided access to FPGA boards and an AMD NPU-equipped machine to run practical sessions.
  - __[Spring'23] Digital Design and Computer Architecture__ \
    Gave lectures about digital design, FPGA architecture, RISC-V architecture, and Verilog coding to a group of enthusiastic students from [Ecole Polytechnique de Tunisie](https://ept.tn/) (where I did my MEng.).

# Mentoring
- Official Mentoring:
  - [Summer'24] SSI (Saudi Summer Intership: BS/MS students in top USA universities funded by the Saudi government) summer intership mentoring for students from Purdue University.
  - [Summer'22,23] KGSP (KAUST Gifted Student Program: BS students in top USA universities funded by KAUST) summer internships mentoring for students from the University of Washington and University of Illinois Urbana-Champaign.
  - Actively mentoring new joiners and students undergoing their MS thesis in our research lab.

# GitHub Projects
- [accl-kaust/mc-option-pricing-aie](https://github.com/accl-kaust/mc-option-pricing-aie) (owner)\
  A Monte Carlo simulator for multi-asset option pricing (financial application) on AMD AI Engines.
-  [accl-kaust/prngine](https://github.com/accl-kaust/prngine) (owner)\
  Paper artifact, where SFMT, XORSHIFT, and XOROSHIRO PRNGs are implemented on AMD AI Engines in a dataflow model and in a standalone accelerator model.
-  [accl-kaust/p-versal-bench](https://github.com/accl-kaust/fp-versal-bench) (owner)\
  Paper artifact, where massive dataflow designs of FP32 multipliers are implemented on AMD AI Engines and on AMD PL (using DSP58 blocks).
- [gitlab.inria.fr/bramas/autovesk (mlir-extension branch)](https://gitlab.inria.fr/bramas/autovesk/tree/mlir-extension) (contributor)\
  Upgraded the code generator to spit out MLIR kernels and added automatic compilation for the target architectures (AVX512, AVX2, SVE2 extensions). Note: this still requires transforming the code gen process into a proper MLIR pass.
