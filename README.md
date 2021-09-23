# texlive-docker
A simple Docker Image that can be used to compile latex through the vscode extension latex-workshop.

[![Docker](https://github.com/lukasboettcher/texlive-docker/actions/workflows/docker-publish.yml/badge.svg?branch=main)](https://github.com/lukasboettcher/texlive-docker/actions/workflows/docker-publish.yml)

To use, add

    {
        "latex-workshop.docker.enabled": true,
        "latex-workshop.docker.image.latex": "ghcr.io/lukasboettcher/texlive-docker:main"
    }

to your global vscode config, or to the workspace config in .vscode/config.json.
