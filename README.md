# DPFTranslator_CPython_CPP

This project focuses on **automating the bidirectional translation** of workflows between Python-based PyDPF scripts (CPython) and C++ DPF workflows. The goal of this repo is to present concepts that simplify and automate the transition between these two environments, enabling developers to work with DPF workflows across both Python and C++.

## Key Concepts

- **Automated Bidirectional Translation**: Provides an automated process to translate PyDPF scripts into C++ workflows and vice versa.
- **Open Source**: The translation leverages **open-source PyDPF APIs** and available **DPF Operators** to handle data and workflows.
- **Minimal Dependency on `dpf-core`**: Since `dpf-core` is not open source, this project minimizes reliance on it. Instead, it focuses on using PyDPF's open-source APIs, ensuring flexibility and accessibility within the open-source ecosystem.

## Goals

1. To develop a fully automated tool that converts PyDPF workflows into C++ workflows and back.

   - **Open Source Examples of Workflows in C++ and PyDPF**: [Link to Examples](https://dpf.docs.pyansys.com/version/0.8/operator_reference_load_apis.html) > APIs > Workflow examples.

2. To showcase the flexibility of PyDPF and its operators within the open-source DPF framework.

## License

This project uses an open-source license, but the underlying code is currently private.
