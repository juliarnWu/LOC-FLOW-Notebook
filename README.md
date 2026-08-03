# LOC-FLOW Notebook

LOC-FLOW Notebook is a Jupyter Notebook-based workflow framework for automated earthquake catalog construction from continuous waveform data.

It reorganizes the original LOC-FLOW processing pipeline into an interactive and modular environment while preserving the original earthquake detection and location algorithms. The workflow is presented through explicit processing steps, while repetitive data-processing procedures are encapsulated into independent Python modules to simplify implementation and maintain workflow transparency.

Unlike the original command-line workflow, LOC-FLOW Notebook allows users to inspect intermediate results, adjust parameters interactively, and execute individual processing stages when required. The modular design also provides a flexible framework for further customization and extension for specific research applications.

LOC-FLOW Notebook is fully compatible with the original command-line implementation and operates independently without affecting existing LOC-FLOW workflows.

---

## Versions

LOC-FLOW Notebook provides two editions for different dataset scales.

### LOC-FLOW Notebook Lite

Designed for small- to medium-scale datasets and workflow testing.

Features:

- Simplified workflow interface
- Complete processing demonstration
- Standardized data input and output
- Suitable for routine earthquake catalog construction

A small continuous waveform dataset from the original LOC-FLOW example is included for installation and execution testing.

The complete workflow can typically be completed within approximately 10 minutes.

---

### LOC-FLOW Notebook LScale

Designed for large-scale earthquake sequence processing.

Features:

- Large-scale waveform batch processing
- Optimized data organization
- Support for large numbers of phase observations and earthquake events

A three-day Kumamoto earthquake sequence dataset (>6000 detected events, 54 stations) is included for large-scale workflow testing.

The complete workflow can typically be completed within approximately 30 minutes.

---

## Compatibility

LOC-FLOW Notebook preserves the original LOC-FLOW processing framework and algorithms.

The Notebook version and the original command-line implementation can be used independently according to user requirements.

---

## Availability

The complete release of LOC-FLOW Notebook will be publicly available after publication.
