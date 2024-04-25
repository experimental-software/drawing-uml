# Drawing UML

> custom shape libraries for draw.io

## Context

UML diagrams can help to design and discuss complex software systems. The [Diagrams.net](https://en.wikipedia.org/wiki/Diagrams.net) application (fka. draw.io) is a general-purpose drawing tool that has a few shapes with which UML diagrams can be painted. This repository contains a collection of custom shape libraries with a customized set of shapes.

## Quickstart

The simplest way to use the custom shape libraries from this repository is to copy one of the links below to the clipboard, then visit the website [app.diagrams.net](https://app.diagrams.net), click the "Decide later" button, and import the library via the menu entry "File > Open Library from > URL...".

[Component Diagram](https://github.com/experimental-software/drawing-uml/blob/main/lib/UML-ComponentDiagram.xml) |
[Deployment Diagram](https://github.com/experimental-software/drawing-uml/blob/main/lib/UML-DeploymentDiagram.xml) | 
[State Machine Diagram](https://github.com/experimental-software/drawing-uml/blob/main/lib/UML-StateMachineDiagram.xml) |
[Use Case Diagram](https://github.com/experimental-software/drawing-uml/blob/main/lib/UML-UseCaseDiagram.xml)

Those steps are shown in the video below:

https://user-images.githubusercontent.com/5235584/223810663-b40a00d9-c53f-432f-8ac1-eaccd9d1d9c2.mp4

## Usage

The Diagrams.net app can also be downloaded and installed as a desktop app: [drawio-desktop](https://github.com/jgraph/drawio-desktop). In this case, it may be convenient to download the custom shapes and import them for the device as described below.

### (1) Download the custom shape libraries

The custom shape libraries can be downloaded by clicking on [this link](https://github.com/experimental-software/drawing-uml/archive/refs/heads/main.zip) or by executing either of these Shell commands in the terminal:

<details open>
  <summary>Download with git clone via SSH</summary>
  ```bash
  git clone git@github.com:experimental-software/drawing-uml.git
  ```
</details>

<details open>
  <summary>Download with git clone via HTTPS</summary>
  
  ```bash
  git clone https://github.com/experimental-software/drawing-uml.git
  ```
</details>

<details open>
  <summary> Download ZIP archive via cURL</summary>
  
  ```bash
  curl https://codeload.github.com/experimental-software/drawing-uml/zip/refs/heads/main \
    --output drawing-uml.zip
  unzip drawing-uml.zip -d .
  ```
</details>

### (2) Open the app

The app can be opened directly in the browser at [app.diagrams.net](https://app.diagrams.net) or after downloading it from the [drawio-desktop GitHub releases](https://github.com/jgraph/drawio-desktop/releases/latest).

### (3) Create a new diagram

### (4) Import a library

The libraries from this repository can be imported via the menu entry "File > Open library from > Device".

## Alternative projects

- [PlantUML](https://plantuml.com/en/)
- [Visual Paradigm](https://www.visual-paradigm.com/)
- [Visio Stencil and Template for UML 2.5](http://softwarestencils.com/uml/index.html)

## References

- [UML Specification | omg.org](https://www.omg.org/spec/UML/)
- [Work with custom shape libraries | drawio.freshdesk.com](https://drawio.freshdesk.com/support/solutions/articles/16000067790-work-with-custom-shape-libraries)
- [draw.io YouTube channel](https://www.youtube.com/@drawioapp)
