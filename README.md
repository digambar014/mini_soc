# Mini SoC

A small System-on-Chip integration in Verilog, combining several sub-modules into a single top-level design.

## Overview

A top-level module integrates an ALU, a counter and a multiplexer into a compact SoC-style datapath, verified with a testbench and synthesizable to a gate-level netlist.

## Files

| File | Role |
|------|------|
| `mini_soc.v` | Top-level integration |
| `alu.v` | Arithmetic logic unit |
| `counter.v` | Counter |
| `mux2x1.v` | 2:1 multiplexer |
| `mini_soc_tb.v` | Testbench |
| `mini_soc_netlist.v` | Synthesized netlist |

`mini_soc.png` shows the design.

## Simulation

Compile and run `mini_soc_tb.v` with a Verilog simulator.

## License

MIT - see [LICENSE](LICENSE).
