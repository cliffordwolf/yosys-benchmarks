# PICORV32 - a size-optimized RISC-V core

Source: https://github.com/cliffordwolf/picorv32/tree/v1.0

There are three cores: small, regular and large.

- **PicoRV32 (small):** The `picorv32` module without counter instructions,
  without two-stage shifts, with externally latched `mem_rdata`, and without
  catching of misaligned memory accesses and illegal instructions.

- **PicoRV32 (regular):** The `picorv32` module in its default configuration.

- **PicoRV32 (large):** The `picorv32` module with enabled PCPI, IRQ, MUL,
  DIV, BARREL_SHIFTER, and COMPRESSED_ISA features.

- **PicoSoC:** The `picosoc` module with `picorv32`, flash, UART, and SRAM
  IP on a simple System-on-Chip.
