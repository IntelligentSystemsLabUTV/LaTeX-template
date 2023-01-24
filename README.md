# LaTeX-template

LaTeX project template repository. Pulls and builds to a fully-equipped, VS Code-compatible Docker container, based on the [`LaTeX Workshop`](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshops) extension.

Builds on top of the Docker images provided in [`LaTeX-env`](https://github.com/IntelligentSystemsLabUTV/LaTeX-env).

## Scope

This framework is aimed at supporting the writing of scientific papers, books, and publications in general, in the English and Italian languages. It is designed to work offline and support `git`.

## Requirements

- Docker
- Docker Compose
- Visual Studio Code
- Extensions to add Docker containers support to VS Code

## Usage

This is intended to be the starting configuration of any LaTeX project. It can be used to set up the workspace/repository of a new LaTeX project, or added to an existing one, by just copying the contents of this repository to the root workspace/repository folder.

Then, use the VS Code command "Open Folder in Container" selecting the workspace/repository folder.

The rest of the job can be managed using the functionalities offered by [`LaTeX Workshop`](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshops).

## Configuration

By default, build files and output will be located in the `build` folder.

All [`LaTeX Workshop`](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshops) options can be configured in the `.devcontainer/devcontainer.json` file.
