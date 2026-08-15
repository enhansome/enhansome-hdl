# Awesome Hardware Description Languages with stars

A curated list of amazingly awesome hardware description language projects.

# Hardware development

## HDL doc

* Verilog [IEEE Std 1364-2001](https://inst.eecs.berkeley.edu/~cs150/fa06/Labs/verilog-ieee.pdf), [Quick Ref Guide](http://sutherland-hdl.com/pdfs/verilog_2001_ref_guide.pdf), [SystemVerilog 3.1a](http://www.ece.uah.edu/~gaede/cpe526/SystemVerilog_3.1a.pdf), [Synthesizing SystemVerilog Busting the Myth that SystemVerilog is only for Verification](http://sutherland-hdl.com/papers/2013-SNUG-SV_Synthesizable-SystemVerilog_paper.pdf)
* VHDL standards [IEEE Std 1076-2000](http://edg.uchicago.edu/~tang/VHDLref.pdf)
* SystemC standards [IEEE Std 1666-2011](http://paginas.fe.up.pt/~ee07166/lib/exe/fetch.php?media=1666-2011.pdf)

## HDL simulators and compilers

* Verilog
  * [Verilator](https://www.veripool.org/wiki/verilator) Verilog to C++ transpiler
  * [Icarus Verilog](http://iverilog.icarus.com/) - simulator
  * [Yosys](http://www.clifford.at/yosys/) - RTL synthesis
* VHDL
  * [GHDL](https://github.com/ghdl/ghdl) ⭐ 2,864 | 🐛 371 | 🌐 VHDL | 📅 2026-08-13 - VHDL compiler and simulator, IEEE 1076-2002, written in ADA
  * [nvc](https://github.com/nickg/nvc) ⭐ 872 | 🐛 107 | 🌐 C | 📅 2026-08-12 - GPLv3 VHDL compiler and simulator, IEEE 1076-2002, written in C
* chisel/firrtl
  * [essent](https://github.com/ucsc-vama/essent) ⭐ 195 | 🐛 0 | 🌐 Scala | 📅 2026-08-04 - firrtl to optimized C++ transpiler
  * [treadle](https://github.com/chipsalliance/treadle) ⚠️ Archived - firrtl simulator written in Scala
* [Lola-2](https://inf.ethz.ch/personal/wirth/Lola/Lola2.pdf)
  * [Oberon-2013](https://inf.ethz.ch/personal/wirth/Lola/) - Project Oberon, 2013 Edition, written in [Oberon-07](http://www-oldurls.inf.ethz.ch/personal/wirth/Oberon/) [License](https://inf.ethz.ch/personal/wirth/ProjectOberon/license.txt)
* CIRCT
  * [ksim](https://github.com/pku-liang/ksim) ⭐ 52 | 🐛 2 | 🌐 C++ | 📅 2025-01-16 - CIRCT IR to optimized C++ transpiler
  * [arcilator](https://github.com/circt/arc-tests) ⭐ 39 | 🐛 0 | 🌐 C | 📅 2026-01-26 - Fast and cycle-accurate hardware simulation in CIRCT

## HDL Libraries

* VHDL
  * [Open Logic](https://github.com/open-logic/open-logic) ⭐ 998 | 🐛 15 | 🌐 VHDL | 📅 2026-07-31 - VHDL Standard Library (FIFOs, CDCs, fixed-point math, etc.)
* System Verilog
  * [Taxi Transport Library](https://github.com/fpganinja/taxi) ⭐ 890 | 🐛 25 | 🌐 SystemVerilog | 📅 2026-08-12 - System Verilog standard library

## Meta HDL and Transpilers

* C++
  * [SystemC](https://www.doulos.com/knowhow/systemc/) - an IEEE standard meta-HDL
  * [VisualHDL](http://sysprogs.com/legacy/visualhdl/) - an integrated development environment (IDE) rapid design for FPGAs

* Dart
  * [ROHD](https://github.com/intel/rohd) ⭐ 489 | 🐛 137 | 🌐 Dart | 📅 2026-08-10 - A framework for hardware description and verification, 2021+

* Haskell
  * [CλaSH](https://github.com/clash-lang/clash-compiler) ⭐ 1,606 | 🐛 409 | 🌐 Haskell | 📅 2026-08-15 - A functional hardware description language
  * [Bluespec](https://github.com/B-Lang-org/bsc) ⭐ 1,137 | 🐛 320 | 🌐 Haskell | 📅 2026-08-03 - Compiler, simulator, and tools for the Bluespec Hardware Description Language.
  * [sv2v](https://github.com/zachjs/sv2v) ⭐ 748 | 🐛 37 | 🌐 Haskell | 📅 2026-03-28 - SystemVerilog to Verilog conversion
  * [concat](https://github.com/conal/concat) ⭐ 460 | 🐛 38 | 🌐 Haskell | 📅 2024-02-28 Haskell to hardware, 2016+
  * <https://github.com/conal/talk-2015-haskell-to-hardware> ⭐ 58 | 🐛 0 | 🌐 TeX | 📅 2016-06-22
  * [pipelineDSL](https://github.com/p12nGH/pipelineDSL) ⭐ 1 | 🐛 0 | 🌐 Haskell | 📅 2021-06-20 - A Haskell DSL for describing hardware pipelines

* Java
  * [jhdl](http://www.jhdl.org/) ..2006
  * [PSHDL](http://pshdl.org/)

* JavaScript
  * [hdl-js](https://github.com/DmitrySoshnikov/hdl-js) ⭐ 91 | 🐛 6 | 🌐 JavaScript | 📅 2018-10-09 - Hardware description language (HDL) parser, and Hardware simulator.
  * [reqack](https://github.com/drom/reqack) ⭐ 33 | 🐛 24 | 🌐 JavaScript | 📅 2026-07-20 -  elastic circuit toolchain
  * [shdl](https://github.com/jcbuisson/shdl) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-10 - Simple Hardware Description Language
  * [irtl](https://github.com/drom/irtl) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-09 - a small intermediate representation (IR) builder for RTL. emits FIRRTL or Verilog

* Julia
  * [Julia-Verilog](https://github.com/interplanetary-robot/Verilog.jl) ⭐ 51 | 🐛 2 | 🌐 Julia | 📅 2017-04-18 - a Verilog-generation DSL for Julia., 2017

* OCaml
  * [Hardcaml](https://github.com/janestreet/hardcaml/blob/master/docs/index.mdx) ⭐ 1,110 | 🐛 7 | 🌐 OCaml | 📅 2026-07-10 An OCaml library for designing hardware, complete with testing and simulation tools.

* Kotlin
  * [Verik](https://github.com/frwang96/verik) ⭐ 47 | 🐛 0 | 🌐 Kotlin | 📅 2022-12-24 HDL for design and verification. generates SV. UVM.

* Python
  * [Amaranth](https://github.com/amaranth-lang/amaranth) ⭐ 2,067 | 🐛 132 | 🌐 Python | 📅 2026-08-12 (previously nMigen) - A refreshed Python toolbox for building complex digital hardware, 2018+
  * [migen](https://github.com/m-labs/migen) ⚠️ Archived - Meta HDL, 2011+
  * [MyHDL](https://github.com/myhdl/myhdl) ⭐ 1,125 | 🐛 131 | 🌐 Python | 📅 2025-04-10 - Process based HDL, verification framework included, 2004+
  * [veriloggen](https://github.com/PyHDI/veriloggen) ⭐ 327 | 🐛 26 | 🌐 Python | 📅 2026-03-08 - Python, Verilog centric meta HDL with HLS like features, 2015-?
  * [PyRTL](https://github.com/UCSBarchlab/PyRTL) ⭐ 303 | 🐛 19 | 🌐 Python | 📅 2026-08-13 - Meta HDL, simulator suitable for research.
  * [magma](https://github.com/phanrahan/magma/) ⭐ 265 | 🐛 195 | 🌐 Python | 📅 2024-10-19 - Meta HDL, 2017+
  * [PyMTL](https://github.com/cornell-brg/pymtl) ⭐ 246 | 🐛 81 | 🌐 Python | 📅 2019-10-27 - Process based HDL, verification framework included, 2014+
  * [HWT](https://github.com/Nic30/hwt) ⭐ 226 | 🐛 11 | 🌐 Python | 📅 2026-07-23 Meta HDL, verification env. IP-core generator, analysis tools, HDL glue
  * [garnet](https://github.com/StanfordAHA/garnet) ⭐ 119 | 🐛 79 | 🌐 Python | 📅 2026-07-16 Coarse-Grained Reconfigurable Architecture generator based on magma, 2018+
  * [Hdl21](https://github.com/dan-fritchman/Hdl21) ⭐ 96 | 🐛 48 | 🌐 Python | 📅 2026-02-17 - Analog HDL in Python
  * [PyHGL](https://github.com/PyHGL/pyhgl) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2023-05-26 - Meta HDL, three-state event-driven simulation, 2022+
  * [PyXHDL](https://github.com/davidel/pyxhdl) ⭐ 30 | 🐛 0 | 🌐 VHDL | 📅 2026-05-18 - Python Frontend For VHDL And Verilog, 2023+
  * [GateForge](https://github.com/vagran/GateForge) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-04-06 - Meta HDL, 2025+
  * [Pyrope](https://masc.soe.ucsc.edu/pyrope.html) - Python-like language supporting "fluid pipelines" and "live flow", 2017+

* Ruby
  * [RHDL](https://github.com/philtomson/RHDL) ⭐ 15 | 🐛 0 | 🌐 Ruby | 📅 2013-03-13

* Rust
  * [calyx](https://github.com/cucapra/calyx) ⭐ 610 | 🐛 173 | 🌐 Rust | 📅 2026-08-14 - Intermediate Language (IL) for Hardware Accelerator Generators, 2020+
  * [kaze](https://github.com/yupferris/kaze) ⚠️ Archived - Meta HDL, 2019+
  * [hoodlum](https://github.com/tcr/hoodlum) ⭐ 98 | 🐛 16 | 🌐 Rust | 📅 2017-04-08 - Meta HDL, 2016+
  * [Cement](https://github.com/pku-liang/Cement) ⭐ 40 | 🐛 0 | 🌐 Rust | 📅 2025-01-16 - A rule-based Meta HDL inspired by Bluespec, 2024+
  * [Filament](https://filamentHDL.com) - Fearless Hardware Design
  * [Spade](https://gitlab.com/spade-lang/spade) - A hardware description language inspired by modern software languages like Rust.

* Scala
  * [chisel](https://github.com/freechipsproject/chisel3) ⭐ 4,759 | 🐛 512 | 🌐 Scala | 📅 2026-08-14 - Meta HDL, 2012+
  * [SpinalHDL](https://github.com/SpinalHDL/SpinalHDL) ⭐ 2,027 | 🐛 168 | 🌐 Scala | 📅 2026-08-12 - Meta HDL 2012+
  * [DFHDL](https://dfianthdl.github.io/) - Multi-abstraction Meta HDL, 2021+

* C#
  * [Quokka](https://github.com/EvgenyMuryshkin/qusoc) ⭐ 24 | 🐛 0 | 🌐 Verilog | 📅 2026-03-04 - C# to low-level RTL translator (Verilog, VHDL) and simulation toolkit examples (gates, components, RISC-V, SoC)

* Veryl
  * [Veryl](https://github.com/dalance/veryl) ⭐ 1,015 | 🐛 137 | 🌐 Rust | 📅 2026-08-14 - An original HDL based on SystemVerilog / Rust syntax, and transplier to SystemVerilog

## HLS

* [Vitis](https://github.com/Xilinx/HLS) ⭐ 414 | 🐛 10 | 📅 2026-08-04 - LLVM based, made by Xilinx. [user manual](https://www.xilinx.com/support/documentation/sw_manuals/xilinx2020_2/ug1399-vitis-hls.pdf)
* [ahaHLS](https://github.com/dillonhuff/ahaHLS) ⭐ 130 | 🐛 3 | 🌐 C++ | 📅 2024-06-11 - 2019, An open source high level synthesis (HLS) tool using LLVM
* [Shang](https://github.com/etherzhhb/Shang) ⭐ 120 | 🐛 4 | 🌐 C++ | 📅 2014-05-29 - 2012-2014, LLVM based, c->verilog
* [polyphony](https://github.com/ktok07b6/polyphony) ⭐ 110 | 🐛 2 | 🌐 Python | 📅 2026-04-14 - 2015-2017, simple python to hdl
* [combinatorylogic/soc](https://github.com/combinatorylogic/soc) ⭐ 59 | 🐛 0 | 🌐 Verilog | 📅 2020-01-02 - 2019, An experimental System-on-Chip with a custom compiler toolchain.
* [hector](https://github.com/pku-liang/Hector) ⭐ 45 | 🐛 0 | 🌐 C++ | 📅 2025-01-10 - 2022, An open-source hardware synthesis framework using MLIR
* [Quokka](https://github.com/EvgenyMuryshkin/QuokkaEvaluation) ⭐ 37 | 🐛 17 | 🌐 Verilog | 📅 2026-03-04 - C# to HL RTL translator
* [Holoso](https://github.com/Zubax/holoso) ⭐ 32 | 🐛 9 | 🌐 Python | 📅 2026-08-15 - 2026+, high-level synthesis of portable Verilog from idiomatic Python for numerical/DSP applications
* [Potholes](https://github.com/SamuelBayliss/Potholes) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2014-05-13 - 2012-2014 - polyhedral model preprocessor, Uses Vivado HLS, PET
* [hls\_recurse](https://github.com/m8pple/hls_recurse) ⭐ 6 | 🐛 1 | 🌐 C++ | 📅 2016-08-30 - 2015-2016 - conversion of recursive fn. for stackless architectures
* [hg\_lvl\_syn](https://github.com/funningboy/hg_lvl_syn) ⭐ 1 | 🐛 0 | 🌐 Perl | 📅 2010-12-21 - 2010, ILP, Force Directed scheduler
* [xronos](https://github.com/endrix/xronos) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2012-12-12 - 2012, java, simple HLS
* [hlslibs](https://github.com/hlslibs) - ac\_math, ac\_dsp, ac\_types
* [legup](http://legup.eecg.utoronto.ca/) - 2011-2015, LLVM based c->verilog
* [bambu](http://panda.dei.polimi.it/?page_id=31) - 2003-?, GCC based c->verilog
* [augh](http://tima.imag.fr/sls/research-projects/augh/) - c->verilog, DSP support
* <https://github.com/utwente-fmt> - abstract hls, verification libraries
* [abc](https://people.eecs.berkeley.edu/~alanmi/abc/) <2008-?, A System for Sequential Synthesis and Verification
* [DelayGraph](https://github.com/ni/DelayGraph) - 2016, C#, register assignment algorithms
* [XLS](https://google.github.io/xls/) - 2020, HLS toolchain from Google

## Other HDL languages

* [Silice](https://github.com/sylefeb/Silice) ⭐ 1,430 | 🐛 70 | 🌐 C++ | 📅 2026-06-18 - A language for hardcoding algorithms into FPGA hardware
* [act](https://github.com/asyncvlsi/act) ⭐ 130 | 🐛 1 | 🌐 C++ | 📅 2026-08-11 - asynchronous circuit/compiler tools
* [ORD](https://github.com/tub-msc/ordec) ⭐ 113 | 🐛 6 | 🌐 Python | 📅 2026-08-14 - Python-superset HDL for analog and mixed-signal IC design entry, part of the open-source ORDeC design platform
* [autopiper](https://github.com/google/autopiper) ⚠️ Archived
* [AnvilHDL](https://github.com/kisp-nus/anvil) ⭐ 30 | 🐛 28 | 🌐 OCaml | 📅 2026-08-05 - 2025+, An HDL designed to help avoid common bugs while allowing low-level control through a Rust-like type system
* [TL-Verilog](https://makerchip.com) - 2015+, Supports "timing-abstract" and "transaction-level design" methodologies; supported by proprietary and open-source tools

## Hardware Intermediate Representations

* [firrtl](https://github.com/freechipsproject/firrtl) ⚠️ Archived - 2016-?, Flexible Intermediate Representation for RTL
* [LLHD](https://github.com/fabianschuiki/llhd) ⭐ 436 | 🐛 39 | 🌐 Rust | 📅 2022-04-20 - Low Level Hardware Description — A foundation for building hardware design tools
* [lgraph](https://github.com/masc-ucsc/lgraph) ⭐ 239 | 🐛 3 | 🌐 C++ | 📅 2026-08-15 - 2017-?, A Multi-Language Synthesis and Simulation IR for Hardware Design
* [coreir](https://github.com/rdaly525/coreir) ⭐ 106 | 🐛 156 | 🌐 C++ | 📅 2022-06-27 - 2016-?, LLVM HW compiler## License
* [VLSIR](https://github.com/Vlsir/Vlsir) ⭐ 39 | 🐛 29 | 🌐 TypeScript | 📅 2026-02-15 - IC Interchange Formats, defined in Google Protobuf SDL
* [CIRCT](https://circt.llvm.org) - 2020+, LLVM / MLIR framework "Circuit IR Compilers and Tools"
* [SpyDrNet](https://byuccl.github.io/spydrnet/) - 2019+, Framework for parsing and manipulating structural netlists in Python

## Synthesis tools

* [yosys](https://github.com/YosysHQ/yosys) ⭐ 4,672 | 🐛 563 | 🌐 C++ | 📅 2026-08-14 - RTL synthesis framework
* [vtr-verilog-to-routing](https://github.com/verilog-to-routing/vtr-verilog-to-routing) ⭐ 1,257 | 🐛 126 | 🌐 C++ | 📅 2026-08-14

## Visualization and Documentation generators

* [wavedrom](https://github.com/drom/wavedrom) ⭐ 3,463 | 🐛 204 | 🌐 JavaScript | 📅 2026-07-08 - Javascript wave graph visualizer for documentations and sim.
* [netlistsvg](https://github.com/nturley/netlistsvg) ⭐ 813 | 🐛 55 | 🌐 JavaScript | 📅 2024-01-25 - Javascript schematic visualizer
* [bitfield](https://github.com/drom/bitfield) ⭐ 394 | 🐛 19 | 🌐 JavaScript | 📅 2024-02-22 - Javascript bit field diagram renderer
* [d3-hwschematic](https://github.com/Nic30/d3-hwschematic) ⭐ 122 | 🐛 20 | 🌐 JavaScript | 📅 2026-05-13 - Javascript hierarchical schematic visualizer for HDLs
* [d3-wave](https://github.com/Nic30/d3-wave) ⭐ 68 | 🐛 6 | 🌐 TypeScript | 📅 2026-06-09 - Javascript wave graph visualizer for RTL simulations
* [sphinx-hwt](https://github.com/Nic30/sphinx-hwt) ⭐ 12 | 🐛 5 | 🌐 Python | 📅 2025-11-12 - Plugin for sphinx documentation generator which adds schematic into html documentation.
* [Visual Debug](https://redwoodeda.com/viz) - Custom simulation visualization framework, available within the [Makerchip.com](https://makerchip.com) IDE.

## HDL parsers

* [slang](https://github.com/MikePopoloski/slang) ⭐ 1,115 | 🐛 22 | 🌐 C++ | 📅 2026-08-12 - SystemVerilog compiler and language service.
* [pyverilog](https://github.com/PyHDI/Pyverilog) ⭐ 799 | 🐛 82 | 🌐 Python | 📅 2024-06-15 - Python-based Hardware Design Processing Toolkit for Verilog HDL
* [rust\_hdl](https://github.com/kraigher/rust_hdl) ⭐ 504 | 🐛 87 | 🌐 Rust | 📅 2026-08-15 - VHDL parser and language server written in Rust
* [sv-parser](https://github.com/dalance/sv-parser) ⭐ 481 | 🐛 40 | 🌐 Rust | 📅 2026-06-10 -  IEEE 1800-2017 System Verilog Parser written in Rust
* [Surelog](https://github.com/chipsalliance/Surelog) ⭐ 472 | 🐛 47 | 🌐 C++ | 📅 2026-08-14 - SystemVerilog 2017 Pre-processor, Parser, Elaborator, UHDM Compiler. Provides IEEE Design/TB C/C++ VPI and Python AST API.
* [hdlConvertor](https://github.com/Nic30/hdlConvertor) ⭐ 331 | 🐛 32 | 🌐 C++ | 📅 2025-06-30 - Fast (System) Verilog/VHDL parser written as C++ extension for Python
* [pyVHDLParser](https://github.com/Paebbels/pyVHDLParser) ⭐ 86 | 🐛 17 | 🌐 Python | 📅 2024-07-15 - VHDL parser written in Python
* [verible](https://chipsalliance.github.io/verible/) - Verible provides a SystemVerilog parser, style-linter, and formatter.

## Other Simulation tools

* [cocotb](https://github.com/potentialventures/cocotb) ⭐ 2,471 | 🐛 414 | 🌐 Python | 📅 2026-08-14 - A coroutine based co-simulation library for writing VHDL and Verilog testbenches in Python
* [midas](https://github.com/ucb-bar/midas) ⭐ 103 | 🐛 8 | 🌐 Scala | 📅 2019-11-22 - FPGA-Accelerated Simulation Framework Automatically Transforming Arbitrary RTL
* [osvvm](https://github.com/OSVVM/OsvvmLibraries) ⭐ 86 | 🐛 5 | 📅 2026-07-30 -  A VHDL verification framework, verification utility library, verification component library, and a simulator independent scripting flow
* [uvvm](https://github.com/OSVVM/OsvvmLibraries) ⭐ 86 | 🐛 5 | 📅 2026-07-30 - A free and Open Source Methodology and Library for VHDL verification of FPGA and ASIC.
* [crave](https://github.com/antmicro/crave) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2023-11-30 - Constrained random stimuli generation for C++ and SystemC (AntMicro's fork of [crave](https://github.com/agra-uni-bremen/crave) ⭐ 53 | 🐛 11 | 🌐 C++ | 📅 2023-11-29)

## Other Design Automation tools

* [fusesoc](https://github.com/olofk/fusesoc) ⭐ 1,450 | 🐛 153 | 🌐 Python | 📅 2026-08-11 -  Package manager and a set of build tools for HDL.
* [RgGen](https://github.com/rggen/rggen) ⭐ 466 | 🐛 24 | 🌐 Ruby | 📅 2026-07-16 - Code generator tool to generate RTL, UVM RAL models and Wiki documents from CSR specifications
* [svlint](https://github.com/dalance/svlint) ⭐ 388 | 🐛 24 | 🌐 Rust | 📅 2025-11-06 - SystemVerilog linter compliant with IEEE1800-2017. Written in Rust, based on [sv-parser](https://github.com/dalance/sv-parser) ⭐ 481 | 🐛 40 | 🌐 Rust | 📅 2026-06-10.
* [bender](https://github.com/pulp-platform/bender) ⭐ 384 | 🐛 47 | 🌐 Rust | 📅 2026-08-13 -  Dependency management tool for hardware design projects.
* [peakrdl](https://github.com/SystemRDL/PeakRDL) ⭐ 208 | 🐛 6 | 🌐 Python | 📅 2026-07-14 - CSR toolchain to generate RTL, UVM RAL models, document(html and markdown), IPXACT, c header from SystemRDL or IPXACT.
* [HDLGen](https://github.com/WilsonChen003/HDLGen) ⭐ 114 | 🐛 0 | 🌐 Verilog | 📅 2023-10-31 - Tool for processing of embedded Perl or Python scripts in Verilog source code.
* [tbengy](https://github.com/prasadp4009/tbengy) ⭐ 56 | 🐛 2 | 🌐 Python | 📅 2024-05-19 - Code generator tool to generate SV/UVM RTL and Testbech as well scripts with support for bitstream generation for Digilent FPGAs
* [hbs](https://github.com/m-kru/hbs) ⭐ 12 | 🐛 1 | 🌐 Tcl | 📅 2026-07-26 - A lean dependency management and build system for hardware description projects.
* [sv-tests](https://symbiflow.github.io/sv-tests) - Test suite designed to check compliance with the SystemVerilog standard

## PSS : Portable test and Stimulus Standard

* [Accellera](https://www.accellera.org/downloads/standards/portable-stimulus) - specification to create a single representation of stimulus and test scenarios
* [PSS 2.1 LRM](https://www.accellera.org/images/downloads/standards/pss/Portable_Test_Stimulus_Standard_v2.1.pdf) - PDF Spec
* [PSSTools Org](https://github.com/PSSTools) - PSS releated tools on GitHub. Parsers, editor plugins.
* [Matthew Ballance](https://github.com/mballance) PSS Blog posts:
  * [Automating Bare-Metal Tests with PSS](https://bitsbytesgates.com/pss/2023/02/25/AutomatingBareMetalTestsWithPSS.html)
  * [PSS Fundamentals: Actions, Components, and Test Generation](https://bitsbytesgates.com/pss/2023/03/03/ActionsComponents_and_TestGeneration.html)
  * [Declarative Programming and Multi-Core Tests](https://bitsbytesgates.com/pss/2023/03/11/DeclarativeMultiCoreTests.html)
  * [Relating Actions with Dataflow](https://bitsbytesgates.com/pss/2023/03/18/RelatingActionsWithDataflow.html)
  * [Modeling DMA Test Scenarios with PSS](https://bitsbytesgates.com/pss/2023/03/25/ModelingTestScenariosForDMA.html)
  * [PSS Memory Management Fundamentals](https://bitsbytesgates.com/pss/2023/04/02/ManagingMemoryInPSS.html)
  * [PSS Concurrency and Resources](https://bitsbytesgates.com/pss/2023/04/09/PSSConcurrencyAndResources.html)
  * [Interacting with Devices via PSS Registers](https://bitsbytesgates.com/pss/2023/04/18/InteractingWithDevicesViaRegisters.html)
  * [Relating Actions with Dataflow Part2 -- Parallelism](https://bitsbytesgates.com/pss/2023/05/07/RelatingActionsWithDataflowPart2.html)
* [PSS CookBook](https://github.com/LeeKaiXuan/PSS_Cookbook) ⭐ 3 | 🐛 0 | 🌐 Dockerfile | 📅 2025-12-24 - Documentation for introducing the usage of PSS language

## License

[![CC0](cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Aliaksei Chapyzhenka](http://drom.io) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-15._
