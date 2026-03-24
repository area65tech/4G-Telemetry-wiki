# Read the Docs - 4G Telemetry Documentation

This folder contains the source files for the Read the Docs documentation of the AREA65 4G Telemetry system.

## Folder Structure

```
docs/rtd/
├── index.rst              # Main navigation page
├── getting-started.rst    # Getting Started guide
├── api-reference.rst      # API Reference documentation
├── arduino-library.rst    # Arduino Library documentation
├── hardware-integration.rst # Hardware Integration guide
├── troubleshooting.rst    # Troubleshooting guide
├── hardware_interfaces.webp # Hardware interface diagram
└── README.md              # This file
```

## How to Use

1. Copy all files from this folder to your Read the Docs repository
2. Ensure you have a `conf.py` file in your repository root
3. Build the documentation using Sphinx

## Example conf.py

```python
project = '4G Telemetry'
copyright = '2026, AREA65'
author = 'AREA65'
release = '1.0.0'

extensions = [
    'sphinx_rtd_theme',
]

html_theme = 'sphinx_rtd_theme'
html_static_path = ['_static']
```

## Documentation Contents

- **Getting Started** - Package contents, initial setup, and next steps
- **API Reference** - Data protocol, cloud platform API, and interface configuration
- **Arduino Library** - Library installation, usage examples, and technical specifications
- **Hardware Integration** - Interface options, power requirements, and mechanical dimensions
- **Troubleshooting** - Common issues, debug checklist, and support resources

## Links

- [Read the Docs](https://readthedocs.org/)
- [Sphinx Documentation](https://www.sphinx-doc.org/)
- [AREA65 Product Website](https://area65tech.com/4g-telemetry/)
