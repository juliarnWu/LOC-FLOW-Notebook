# LOC-FLOW Notebook

LOC-FLOW Notebook is a Jupyter Notebook-based workflow framework for automated earthquake catalog construction from continuous waveform data.

This project reorganizes the original LOC-FLOW processing pipeline into an interactive and modular Jupyter Notebook environment while maintaining the original earthquake detection and location algorithms. It provides a more accessible workflow for seismic data processing, parameter adjustment, intermediate result inspection, and reproducible earthquake catalog construction.

---

## Versions

LOC-FLOW Notebook provides two versions according to different usage requirements:

- **User Version**: designed for routine applications with encapsulated modules and standardized interfaces.
- **Research Version**: preserves the original Notebook-based implementation for workflow exploration and further modification.

---

# User Version

The User Version provides a simplified interface for routine earthquake catalog construction. Core functions and classes are encapsulated into independent Python modules, reducing implementation complexity and allowing users to focus on workflow execution, parameter configuration, and result analysis.

The User Version contains two editions designed for different dataset scales.

---

## LOC-FLOW Notebook Lite

LOC-FLOW Notebook Lite is designed for small- to medium-scale earthquake datasets and routine research applications.

### Features

- Interactive Jupyter Notebook workflow
- Simplified user interface
- Encapsulated Python modules with standardized interfaces
- Unified input and output management
- Suitable for rapid testing and routine earthquake catalog construction

### Test Dataset

A small continuous waveform dataset from the original LOC-FLOW example is provided with the Lite edition.

This dataset allows users to quickly verify whether the installation and execution environment are configured correctly. The complete workflow test can typically be completed within approximately **10 minutes**.

---

## LOC-FLOW Notebook LScale

LOC-FLOW Notebook LScale is designed for large-scale earthquake sequence processing and high-volume seismic datasets.

### Features

- Batch processing strategy for large earthquake catalogs
- Optimized data organization and task management
- Support for large numbers of seismic events and phase observations
- Consistent interface with the Lite edition
- Designed for large-scale research applications

### Test Dataset

A three-day phase-picking dataset from the 2016 Kumamoto earthquake sequence is provided with the LScale edition.

The dataset contains more than **6000 earthquake events** recorded by **54 seismic stations**. It represents a reduced dataset extracted from the dataset used in the manuscript and is designed to test the performance of large-scale processing workflows.

The complete LScale workflow test can typically be completed within approximately **30 minutes**.

---

# Research Version

## LOC-FLOW Notebook Lite-Research

LOC-FLOW Notebook Lite-Research preserves the original Notebook-based implementation developed during the construction of LOC-FLOW Notebook.

Unlike the User Version, this implementation directly presents the workflow logic within the Notebook environment without encapsulating functions and classes into independent Python modules. Therefore, some parameter definitions, function structures, and processing procedures may differ from those in the User Version.

### Features

- Transparent step-by-step workflow implementation
- Direct access to intermediate processing procedures
- Original development structure of the workflow
- Additional experimental functions developed during workflow construction
- Suitable for users interested in understanding, modifying, or extending the workflow

The Research Version is mainly provided for workflow inspection, methodological exploration, and further customization.

---

# Availability

The complete release of LOC-FLOW Notebook, including the User Version and Research Version, will be publicly available after publication.
