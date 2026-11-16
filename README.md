# FPGA In-System Verification Project

FPGA course project focusing on in-system verification and debugging using on-chip logic analyzers (ILA / Signal Tap) and virtual I/O (VIO / ISSP).

## Target Boards & Tools

- **ZedBoard (Zynq-7000)**
  - Toolchain: Xilinx Vivado
  - Debug Cores: ILA, VIO
  - Clock: 100 MHz

- **DE10-Standard (Cyclone V)**
  - Toolchain: Intel Quartus Prime
  - Debug Cores: Signal Tap, In-System Sources and Probes (ISSP)
  - Clock: 50 MHz

*Note: RTL code in `Design/` is parameterized to support both 100 MHz and 50 MHz clock frequencies.*

## Directory Structure

```text
├── Design/          # Target-independent RTL source files
├── Vivado/
│   ├── ILA/         # Vivado project with ILA (ZedBoard)
│   └── VIO/         # Vivado project with VIO (ZedBoard)
├── Quartus/
│   ├── ILA/         # Quartus project with Signal Tap (DE10-Standard)
│   └── VIO/         # Quartus project with ISSP (DE10-Standard)
└── User Manuals/    # Board documentation
```

## Design Specification

*(To be determined)*

## Team

- Hazem Yasser ([hazem-yasser](https://github.com/hazem-yasser))
- Member 2
- Member 3
- Member 4
