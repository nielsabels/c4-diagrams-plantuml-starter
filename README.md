# Introduction

This repository is meant to be a starting point for people that want to create C4 diagrams using the PlantUML markup language and need an integrated, working sample.

# The C4 modelling language

C4 diagrams are part of the C4 modelling language, created by Simon Brown.

> The C4 model was created as a way to help software development teams describe and communicate software architecture, both during up-front design sessions and when retrospectively documenting an existing codebase. It's a way to create maps of your code, at various levels of detail, in the same way you would use something like Google Maps to zoom in and out of an area you are interested in.  
— [infoq.com](https://www.infoq.com/articles/C4-architecture-model/)

# Requirements

## Visual Studio Code

[Visual Studio Code](https://code.visualstudio.com/) is used as a source-code editor for the PlantUML markup. VSCode supports previewing the diagram as you are writing it, as well as exporting the diagram upon save.

## Docker

Docker is required to host a PlantUML server. This server will be used to translate the PlantUML markup to images (`.png`). Click here to read how to install it on [Windows](https://docs.docker.com/docker-for-windows/install/) or [Mac](https://docs.docker.com/docker-for-mac/install/).

## Visual Studio Code Extensions

- [qjebbs/vscode-plantuml](https://github.com/qjebbs/vscode-plantuml) is used to preview diagrams in the editor.
- [Gruntfuggly/triggertaskonsave](https://github.com/Gruntfuggly/triggertaskonsave) is used to trigger diagram creation upon save.

# Further Credits

- [RicardoNiepel/C4-PlantUML](https://github.com/RicardoNiepel/C4-PlantUML/) for bringing C4 support to PlantUML.

# Further Reading

- [An Introduction to the C4 Modelling Language](https://lnfabels.wordpress.com/2020/01/02/the-c4-modelling-language/)
