# ComfyUI Workflows

This repository contains a collection of **ComfyUI workflows**. These workflows are designed to streamline tasks in the ComfyUI interface, making them easier and more efficient to execute.

## Available Workflows

### 1. **Text-2-Image-Flux.json**

This is a basic workflow for generating images from text using Flux. The workflow allows users to input a text prompt and convert it into an image with the help of various settings and nodes, including:

- **Prompt**: Describe the scene or image you want to generate.
- **Width** and **Height**: Ignored if **Aspect Ratio** is not set to "Custom."
- **Aspect Ratio**: Choose a preset ratio or select "Custom" to manually set dimensions.
- **Amount**: Defines how many images to generate.

Before the first run, you need to expand the **FluxMagic** node and set the following parameters:

- **AE**
- **T5**
- **CLIP**
- **UNet Name**

Press **Ctrl + Enter** or click **Queue** to start the process.

[Download Text-2-Image-Flux.json](./Text-2-Image-Flux.json)

![Flux Text-to-Image Workflow](static/flux-t2i.png)
