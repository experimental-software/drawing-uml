# Drawing UML

This repository contains custom shape libraries for the creation of [UML diagrams](https://www.uml-diagrams.org) with [Diagrams.net](https://en.wikipedia.org/wiki/Diagrams.net).

## Usage

### (1) Download the custom shape libraries

```bash
# (a) Download with git clone via SSH
git clone git@github.com:experimental-software/drawing-uml.git

# (b) Download with git clone via HTTPS
git clone https://github.com/experimental-software/drawing-uml.git

# (c) Download ZIP archive via cURL
curl https://codeload.github.com/experimental-software/drawing-uml/zip/refs/heads/main \
  --output drawing-uml.zip
unzip drawing-uml.zip -d .
```

### (2) Open the app

The app can be opened directly in the browser at [app.diagrams.net](https://app.diagrams.net) or after downloading it from the [drawio-desktop GitHub releases](https://github.com/jgraph/drawio-desktop/releases/latest).

### (3) Create new diagram

### (4) Import a library

The libraries from this repository can be imported via the menu entry "File > Open library from > Device".

## Libraries

### State Machine Diagram

[![Custom library URL](https://img.shields.io/badge/stm-library_url-blueviolet.svg)][stm-library]
[![UML diagram syntax](https://img.shields.io/badge/stm-syntax-lightgrey.svg)][stm-syntax]

[stm-library]: https://raw.githubusercontent.com/experimental-software/drawing-uml/main/UML%20-%20State%20Machines.xml
[stm-syntax]: https://www.uml-diagrams.org/state-machine-diagrams.html

![diagram: state-machines-reference.drawio](./docs/state-machines-reference.drawio.png)

### Object Diagram

[![Custom library URL](https://img.shields.io/badge/object_diagram-library_url-blueviolet.svg)][object_diagram-library]
[![UML diagram syntax](https://img.shields.io/badge/object_diagram-syntax-lightgrey.svg)][object_diagram-syntax]

[object_diagram-library]: https://raw.githubusercontent.com/experimental-software/drawing-uml/main/UML%20-%20Object%20Diagram.xml
[object_diagram-syntax]: https://www.uml-diagrams.org/class-diagrams-overview.html#object-diagram

![diagram: object diagram overview](./docs/object-diagram-overview.png)

## References

- [UML Specification | omg.org](https://www.omg.org/spec/UML/)
- [Work with custom shape libraries | drawio.freshdesk.com](https://drawio.freshdesk.com/support/solutions/articles/16000067790-work-with-custom-shape-libraries)
- [draw.io YouTube channel](https://www.youtube.com/@drawioapp)
