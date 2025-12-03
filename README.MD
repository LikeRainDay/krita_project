# Krita AI Project Repository

## About Krita

Krita is a powerful open-source digital painting software designed for artists and designers. It offers rich painting tools, brush engines, and layer systems, supporting various file formats, making it an ideal choice for digital art creation. Key features include:

- Professional digital painting toolset
- Powerful brush engine and customizable brushes
- Comprehensive layer management system
- Support for multiple color spaces and file formats
- Built-in animation tools
- Cross-platform support (Windows, macOS, Linux)
- Active community support and continuous updates

## Project Overview

This repository focuses on integrating artificial intelligence technology with Krita and other image editing software through ComfyUI workflows. The project provides custom workflow configurations and examples to enhance digital art creation experience.

### Main Contents
- **ComfyUI Workflows**: Custom workflow configurations for Krita and Photoshop integration
- **Documentation**: Guides and tutorials for using AI workflows in digital art creation
- **Examples**: Sample Krita project files demonstrating AI-assisted workflows

### Project Features
- ComfyUI workflow integration for Krita and Photoshop
- AI-assisted painting and image editing tools
- Custom workflow examples and templates
- Layer and selection management workflows

## Project Structure

```
├── docs/                    # Documentation and tutorials
├── workflow/                # ComfyUI workflow configurations
│   ├── krita/              # Krita-specific workflows
│   │   ├── Custom.Workflow.Example.json
│   │   └── README.md       # Krita workflow guide
│   └── photoshop/          # Photoshop-specific workflows
│       └── README.md       # Workflow overview
├── *.kra                    # Krita project files (examples)
└── LICENSE                  # CC0 1.0 Universal License
```

## Quick Start

### Prerequisites
1. **Krita**: Install the latest version of [Krita](https://krita.org/)
2. **ComfyUI**: Set up [ComfyUI](https://github.com/comfyanonymous/ComfyUI) environment
3. **Krita AI Plugin**: Install one of the following plugins:
   - [Krita AI Diffusion](https://github.com/Acly/krita-ai-diffusion) - Stable Diffusion integration
   - [ComfyUI Krita Plugin](https://github.com/JasonS09/comfy_sd_krita_plugin) - Official ComfyUI plugin

### Setup Steps
1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd krita
   ```

2. Start your ComfyUI server

3. Configure the AI plugin in Krita to connect to your ComfyUI instance

4. Import workflow files from `workflow/krita/` directory into ComfyUI

5. Execute workflows directly from Krita interface

### For Photoshop Users
If you're using Photoshop, check the `workflow/photoshop/` directory for Photoshop-specific workflows. You'll need:
- [Auto-Photoshop-StableDiffusion-Plugin](https://github.com/AbdullahAlfaraj/Auto-Photoshop-StableDiffusion-Plugin) or
- [ComfyUI Photoshop Plugin](https://github.com/NimaNzrii/ComfyUI-Photoshop-Plugin)

## Workflow Documentation

- **[Krita Workflows Guide](workflow/krita/README.md)**: Detailed guide on using Krita-specific workflows, including node descriptions and usage examples
- **[Workflow Overview](workflow/README.md)**: General information about ComfyUI workflows and related plugins

## Contributing

Welcome to participate in the project through:
- Submit issues for problems or suggestions
- Submit pull requests to contribute workflows or improvements
- Share your experience and artwork
- Improve project documentation

## License

This project is licensed under the [CC0 1.0 Universal License](LICENSE) (Creative Commons Public Domain Dedication).
