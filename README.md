# Power Grid Model - Reference Implementations

This repository hosts reference implementations and examples showcasing various use-cases of [Power Grid Model](https://github.com/PowerGridModel/power-grid-model), a high-performance library for steady-state distribution power system analysis.

## Overview

Power Grid Model Reference Implementations provides practical examples and reference implementations that demonstrate how to apply Power Grid Model to real-world power grid scenarios. These implementations cover various voltage levels and operational contexts, serving as a starting point for developers and grid operators.

## Use Cases

This repository will showcase implementations for the following use-cases:

### 🔌 Grid Connection
Reference implementations for analyzing and validating new grid connections, including capacity assessment and impact analysis on existing infrastructure.

### ⚡ Real-time Congestion Management
Examples demonstrating real-time monitoring and management of grid congestion, enabling operators to respond quickly to capacity constraints and maintain grid stability.

### 📊 48-Hour Ahead Congestion Management
Implementations for predictive congestion management, allowing grid operators to forecast and plan for congestion events within a 48-hour horizon.

### 🏗️ Grid Planning
Reference implementations for long-term grid planning scenarios, including infrastructure expansion, capacity planning, and network optimization.

## Voltage Levels

The reference implementations cover all voltage levels in the power distribution system:

- **Low Voltage (LV)**: Residential and small commercial applications (typically < 1 kV)
- **Medium Voltage (MV)**: Distribution networks serving larger areas (typically 1-35 kV)
- **High Voltage (HV)**: Transmission and sub-transmission networks (typically > 35 kV)

## Getting Started

> **Note**: This repository is currently under development. Reference implementations and examples will be added progressively.

### Prerequisites

- Python 3.8 or higher
- [Power Grid Model](https://github.com/PowerGridModel/power-grid-model) library

### Installation

```bash
# Clone the repository
git clone https://github.com/PowerGridModel/pgm-reference-implementations.git
cd pgm-reference-implementations

# Install dependencies (once examples are available)
pip install -r requirements.txt
```

## Repository Structure

```
pgm-reference-implementations/
├── grid-connection/          # Grid connection examples
├── real-time-congestion/     # Real-time congestion management
├── ahead-congestion/         # 48h ahead congestion management
├── grid-planning/            # Grid planning scenarios
├── common/                   # Shared utilities and helpers
└── docs/                     # Documentation and guides
```

## Contributing

We welcome contributions! Whether you're fixing bugs, adding new reference implementations, or improving documentation, your help is appreciated.

Please see our [contributing guidelines](CONTRIBUTING.md) (coming soon) for more information on how to get involved.

## License

This project is licensed under the Mozilla Public License Version 2.0 - see the [LICENSE](LICENSE) file for details.

## Related Projects

- [Power Grid Model](https://github.com/PowerGridModel/power-grid-model) - The core library for power system analysis
- [Power Grid Model IO](https://github.com/PowerGridModel/power-grid-model-io) - Input/output utilities for Power Grid Model

## Contact and Support

- **Issues**: Please report bugs and feature requests via [GitHub Issues](https://github.com/PowerGridModel/pgm-reference-implementations/issues)
- **Discussions**: Join the conversation in [GitHub Discussions](https://github.com/PowerGridModel/pgm-reference-implementations/discussions)
- **Documentation**: Visit the [Power Grid Model documentation](https://power-grid-model.readthedocs.io/)

## Acknowledgments

Power Grid Model is developed and maintained by contributors from Alliander and the open-source community.