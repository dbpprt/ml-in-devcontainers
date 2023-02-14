# Immutable development environments for PyTorch powered by Visual Studio Code Dev Containers
This project provides a development environment for PyTorch using Visual Studio Code and Docker. It is based on the [Visual Studio Code Dev Container](https://github.com/Microsoft/vscode-remote-release) feature.
Being able to have immutable and reproducible development environments is a key part to successfully work with multiple projects.

## Features
- devcontainer.json: Configuration file for the Visual Studio Code Dev Container feature, using a Docker image, based on nvidia/cuda:11.8.0-base-ubuntu22.04
- Optionally: install AWS CLI V2 and reuse your AWS credentials from the host system
- Optionally: install Docker inside the container and reuse your Docker daemon from the host system (if you're training inside a container again)
- Sophisticated set of extensions for Python, Jupyter, etc.
- Sopthisticated set of settings for Python (Linter, Formatter, etc.)
- Sample MNIST training script (PyTorch Example)

## Getting Started
- (Prerequisite) Docker is installed on your system
- (Prerequisite) Visual Studio Code Dev Container extension is installed
- Clone this repository
- Open the folder in Visual Studio Code
- When prompted, click "Reopen in Container"