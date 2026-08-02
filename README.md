# LOC-FLOW Notebook

LOC-FLOW Notebook is a Jupyter Notebook-based workflow framework for automated earthquake catalog construction from continuous waveform data.

It reorganizes the original LOC-FLOW processing pipeline into an interactive and modular environment while maintaining the original earthquake detection and location algorithms. LOC-FLOW Notebook is fully compatible with the original command-line implementation of LOC-FLOW and operates independently without affecting existing workflows.

## User Version

The User Version is designed for routine earthquake catalog construction and includes two editions for different dataset scales.

### LOC-FLOW Notebook Lite

Designed for small- to medium-scale datasets and rapid workflow testing.

**Features:**
- Simplified interface
- Encapsulated Python modules
- Standardized input/output management

A small continuous waveform dataset from the original LOC-FLOW example is included for installation and execution testing, which can typically be completed within approximately 10 minutes.

### LOC-FLOW Notebook LScale

Designed for large-scale earthquake sequence processing and high-volume seismic datasets.

**Features:**
- Large-scale batch processing
- Optimized data organization
- Support for large numbers of events and phase observations

A three-day Kumamoto phase-picking dataset (>6000 events, 54 stations) is included for large-scale workflow testing, which can typically be completed within approximately 30 minutes.

## Research Version

### LOC-FLOW Notebook Lite-Research

The Lite-Research version preserves the original Notebook-based implementation developed during the construction of LOC-FLOW Notebook.

Unlike the User Version, functions and classes are directly implemented within the Notebook without Python module encapsulation. Therefore, some parameters, function structures, and processing procedures differ from the User Version.

It is provided for workflow inspection and further customization.

## Documentation

Detailed installation instructions, workflow descriptions, and parameter explanations will be provided in the LOC-FLOW Notebook User Guide.

## Availability

The complete release of LOC-FLOW Notebook will be publicly available after publication.
