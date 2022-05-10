[![Build LaTeX document](https://github.com/finnge/latex-paper/actions/workflows/latex.yaml/badge.svg)](https://github.com/finnge/latex-paper/actions/workflows/latex.yaml)

# latex acm style paper

Uses a ACM based LaTeX Project for Term Papers.

## features
- Generate LaTeX with VSCode
- Generate LaTeX with GitHub Actions per commit
- Automatic inserted PDF into GitHub Release


## vscode docker

To edit and generate PDFs out of the LaTeX project with vscode, this repo uses the remote container plugin with the setup done by [`qdm12/latexdevcontainer`](https://github.com/qdm12/latexdevcontainer). You need following things:

- [Docker](https://www.docker.com/products/docker-desktop) installed and running
    - If you don't use Linux, share the directories `~/.ssh` and the directory of your project with Docker Desktop
- [Docker Compose](https://docs.docker.com/compose/install/) installed
- [VS code](https://code.visualstudio.com/download) installed
- [VS code remote containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) installed


To start:

- Open the command palette in Visual Studio Code (CTRL+SHIFT+P) and select `Remote-Containers: Rebuild and Reopen in Container...`. ⚠️ this will erase your container shell history and custom latex packages you added on top of the base image.
