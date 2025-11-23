# PCB Rogowski Coil

![license - CC BY 4.0](https://img.shields.io/badge/license-CC--BY-green)
![type - Hardware](https://img.shields.io/badge/type-Hardware-blue)
![category - power electronics](https://img.shields.io/badge/category-power%20electronics-lightgrey)
![status - archived](https://img.shields.io/badge/status-archived-red)

A collection of PCB-based Rogowski coil designs for current sensing applications. This repository contains multiple coil configurations optimized for different measurement requirements.

## Overview

Rogowski coils are toroidal coils used for measuring alternating current (AC) or high-speed current pulses. Unlike traditional current transformers, Rogowski coils are flexible and can be wrapped around conductors of any size, making them ideal for non-invasive current measurements.

This project provides five different PCB Rogowski coil designs, each optimized for specific applications and measurement ranges.

## Features

- **Five Different Coil Types**: Multiple configurations to suit various measurement needs
- **PCB-Based Design**: Manufacturable using standard PCB processes
- **High-Frequency Response**: Suitable for AC and fast transient current measurements
- **Non-Invasive**: Can be placed around conductors without physical contact
- **Open Source**: Licensed under CC BY 4.0

## Coil Types

### Type 1 (RogT1)

<img src="images/RogT1_t.png" alt="RogT1 Top View" width="300"/>
*Top view of Rogowski Coil Type 1*

<img src="images/RogT1_b.png" alt="RogT1 Bottom View" width="300"/>
*Bottom view of Rogowski Coil Type 1*

<img src="images/RogT1_d.png" alt="RogT1 Design" width="300"/>
*Design view of Rogowski Coil Type 1*

### Type 2 (RogT2)

<img src="images/RogT2_t.png" alt="RogT2 Top View" width="300"/>
*Top view of Rogowski Coil Type 2*

<img src="images/RogT2_b.png" alt="RogT2 Bottom View" width="300"/>
*Bottom view of Rogowski Coil Type 2*

<img src="images/RogT2_d.png" alt="RogT2 Design" width="300"/>
*Design view of Rogowski Coil Type 2*

### Type 3 (RogT3)

<img src="images/RogT3_t.png" alt="RogT3 Top View" width="300"/>
*Top view of Rogowski Coil Type 3*

<img src="images/RogT3_b.png" alt="RogT3 Bottom View" width="300"/>
*Bottom view of Rogowski Coil Type 3*

<img src="images/RogT3_d.png" alt="RogT3 Design" width="300"/>
*Design view of Rogowski Coil Type 3*

### Type 4 (RogT4)

<img src="images/RogT4_t.png" alt="RogT4 Top View" width="300"/>
*Top view of Rogowski Coil Type 4*

<img src="images/RogT4_b.png" alt="RogT4 Bottom View" width="300"/>
*Bottom view of Rogowski Coil Type 4*

<img src="images/RogT4_d.png" alt="RogT4 Design" width="300"/>
*Design view of Rogowski Coil Type 4*

### Type 5 (RogT5)

<img src="images/RogT5_t.png" alt="RogT5 Top View" width="300"/>
*Top view of Rogowski Coil Type 5*

<img src="images/RogT5_b.png" alt="RogT5 Bottom View" width="300"/>
*Bottom view of Rogowski Coil Type 5*

<img src="images/RogT5_d.png" alt="RogT5 Design" width="300"/>
*Design view of Rogowski Coil Type 5*

## Design Files

Detailed design files are available in PDF format for each coil type:

- [Type 1 Design (PDF)](images/Rogcoil_type1.pdf)
- [Type 2 Design (PDF)](images/Rogcoil_type2.pdf)
- [Type 3 Design (PDF)](images/Rogcoil_type3.pdf)
- [Type 4 Design (PDF)](images/Rogcoil_type4.pdf)
- [Type 5 Design (PDF)](images/Rogcoil_type5.pdf)

## Applications

Rogowski coils are commonly used in:

- Power quality monitoring
- Motor current measurement
- Circuit breaker testing
- High-frequency current sensing
- Power electronics development
- Energy monitoring systems

## Usage

1. Select the appropriate coil type based on your measurement requirements
2. Review the design files (PDF) for detailed specifications
3. Manufacture the PCB using standard PCB fabrication processes
4. Integrate with appropriate signal conditioning circuitry
5. Calibrate the coil for your specific application

## Technical Considerations

When using these designs, consider:

- **Sensitivity**: Depends on the number of turns and coil geometry
- **Frequency Response**: Rogowski coils have excellent high-frequency characteristics
- **Output Voltage**: Proportional to the rate of change of current (di/dt)
- **Integration**: May require an integrator circuit depending on your application
- **Shielding**: Consider electromagnetic interference in your application environment


## Author

**[Fulong Li](https://fulongli.github.io/)**


## Related Papers 
-

## License

This project is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). See [LICENSE.md](LICENSE.md) for details.

You are free to:
- **Share**: Copy and redistribute the material in any medium or format
- **Adapt**: Remix, transform, and build upon the material for any purpose

Under the following terms:
- **Attribution**: You must give appropriate credit, provide a link to the license, and indicate if changes were made

---

**Note**: These designs are provided as-is. Please verify all specifications and test thoroughly before use in critical applications.
