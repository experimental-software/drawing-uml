# Drawing UML

> custom shape libraries for draw.io that help with the creation of UML diagrams

## Context

The [Unified Modeling Language (UML)](https://en.wikipedia.org/wiki/Unified_Modeling_Language) has been created in the 1990s as unification of the [Booch method](https://en.wikipedia.org/wiki/Booch_method), the object-modeling technique (OMT), and object-oriented software engineering (OOSE). Later on, it was adopted by the Object Management Group (OMG) for standardization. UML diagrams can be used for sketching, creating blueprints, and as a programming language (see Fowler, p. 2). This project is focused on the sketching use case, as a tool to manage complexity in the context of reverse engineering, design, and discussion of complex software systems.

The [Diagrams.net](https://en.wikipedia.org/wiki/Diagrams.net) application (fka. draw.io) is a free general-purpose drawing tool that has a few shapes with which UML diagrams can be painted. This repository contains a collection of shape libraries with a customized set of UML shapes.

## Quickstart

The simplest way to use the custom shape libraries from this repository is to copy one of the links below this paragraph to the clipboard, then visit the website [app.diagrams.net](https://app.diagrams.net), click the "Decide later" button when being asked where to store the diagram, and import the library via the menu entry "File > Open Library from > URL...".

[Use Case Diagram](https://raw.githubusercontent.com/experimental-software/drawing-uml/main/lib/UML-UseCaseDiagram.xml) •
[Component Diagram](https://raw.githubusercontent.com/experimental-software/drawing-uml/main/lib/UML-ComponentDiagram.xml) •
[Deployment Diagram](https://raw.githubusercontent.com/experimental-software/drawing-uml/main/lib/UML-DeploymentDiagram.xml) • 
[State Machine Diagram](https://raw.githubusercontent.com/experimental-software/drawing-uml/main/lib/UML-StateMachineDiagram.xml)

https://user-images.githubusercontent.com/5235584/223810663-b40a00d9-c53f-432f-8ac1-eaccd9d1d9c2.mp4

## Advanced usage

The Diagrams.net app can also be downloaded and installed as a desktop app: [drawio-desktop](https://github.com/jgraph/drawio-desktop). In this case, it may be convenient to download the custom shapes and import them for the device as described below.

### (1) Download the custom shape libraries

The custom shape libraries can be downloaded by clicking on [this link](https://github.com/experimental-software/drawing-uml/archive/refs/heads/main.zip) or by executing either of these Shell commands in the terminal:

<details>
  <summary>Download with git clone via SSH</summary>
  
  ```bash
  git clone git@github.com:experimental-software/drawing-uml.git
  ```
</details>

<details>
  <summary>Download with git clone via HTTPS</summary>
  
  ```bash
  git clone https://github.com/experimental-software/drawing-uml.git
  ```
</details>

<details>
  <summary> Download ZIP archive with curl</summary>
  
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

**Draw.IO**

- [Work with custom shape libraries | drawio.freshdesk.com](https://drawio.freshdesk.com/support/solutions/articles/16000067790-work-with-custom-shape-libraries)
- [draw.io YouTube channel](https://www.youtube.com/@drawioapp)

**Books on UML**

- [UML Distilled | Martin Fowler](https://www.google.de/books/edition/UML_Distilled/nHZslSr1gJAC)
