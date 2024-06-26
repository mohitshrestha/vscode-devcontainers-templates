# Development Container Templates

<table style="width: 100%; border-style: none;"><tr>
<td style="width: 140px; text-align: center;"><a href="https://github.com/devcontainers"><img width="128px" src="https://raw.githubusercontent.com/microsoft/fluentui-system-icons/78c9587b995299d5bfc007a0077773556ecb0994/assets/Cube/SVG/ic_fluent_cube_32_filled.svg" alt="devcontainers organization logo"/></a></td>
<td>
<strong>Development Container Templates</strong><br />
A simple set of dev container 'templates' to help get you up and running with a containerized environment.
</td>
</tr></table>


A **development container** is a running [Docker](https://www.docker.com) container with a well-defined tool/runtime stack and its prerequisites. It allows you to use a container as a full-featured development environment which can be used to run an application, to separate tools, libraries, or runtimes needed for working with a codebase, and to aid in continuous integration and testing.

This repository contains a set of **Dev Container Templates** which are source files packaged together that encode configuration for a complete development environment. A Template can be used in a new or existing project, and a [supporting tool](https://containers.dev/supporting) will use the configuration from the template to build a development container.

## Contents

-   [`src`](src) - A collection of subfolders, each declaring a template. Each subfolder contains at least a
    `devcontainer-template.json` and a [devcontainer.json](https://containers.dev/implementors/json_reference/).

# For the Base Container Use Image: Alpine (alpine)

Simple Alpine container with Git installed.

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| imageVariant | Alpine version: | string | 3.20 |

This template references an image that was [pre-built](https://containers.dev/implementors/reference/#prebuilding) to automatically include needed devcontainer.json metadata.

* **Image**: mcr.microsoft.com/devcontainers/base:alpine ([source](https://github.com/devcontainers/images/tree/main/src/base-alpine))
* **Applies devcontainer.json contents from image**: Yes ([source](https://github.com/devcontainers/images/blob/main/src/base-alpine/.devcontainer/devcontainer.json))


---

_Note: This file was auto-generated from the [devcontainer-template.json](https://github.com/devcontainers/templates/blob/main/src/alpine/devcontainer-template.json).  Add additional notes to a `NOTES.md`._
