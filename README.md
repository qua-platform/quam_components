# QuAM Components

This repository, `quam_components`, provides a collection of tailored components for controlling popular qubit architectures. These components extend the functionality of QuAM, making it easier to design and execute quantum experiments.

QuAM (Quantum Abstract Machine) is an innovative software framework designed to provide an abstraction layer over the QUA programming language, facilitating a more intuitive interaction with quantum computing platforms. Aimed primarily at physicists and researchers, QuAM allows users to think and operate in terms of qubits and quantum operations rather than the underlying hardware specifics.

## Key Features

- **Abstraction Layer**: Simplifies quantum programming by providing higher-level abstractions for qubit operations.
- **Component-Based Structure**: Utilizes modular components like Mixers and IQChannels for flexible quantum circuit design in terms of e.g. FluxLines and Resonators.
- **Automated Configuration**: Generate QUA configurations from QuAM setups seamlessly.
- **Extensibility**: Extend QuAM with custom classes to handle complex quantum computing scenarios.
- **State Management**: Features robust tools for saving and loading your quantum states, promoting reproducibility and consistency.

## Installation

To install `quam_components`, first ensure you have Python ≥ 3.8 installed on your system.
Then run the following command:

### Requirements
```sh
pip install git+https://github.com/qua-platform/quam.git
pip install qualang-tools
```
### Installation
```sh
pip install git+https://github.com/qua-platform/quam_components.git
