# Human Sensory Atlas

Welcome to the **Human Sensory Atlas** by [@MrBang21](https://x.com/MrBang21).

This project is a highly-reactive, vanilla Javascript 2D physics engine and interactive visualization dashboard for exploring the human body's sensory, anatomical, and neurological connections.

## Features

- **Force-Directed Graph**: Uses a custom-built 2D physics engine supporting simulated annealing to naturally layout complex networks. It precisely respects multi-parent connections (pulling nodes to proper geometric centers) while intelligently repelling non-connected overlapping nodes.
- **Multiple Layout Modes**: Smoothly transition between:
  - **Petal Layout**: A radial burst view.
  - **Physics Layout**: A lively Hooke's Law elastic spring simulation.
  - **Stacked Layout**: A hierarchical flow layout for reading structure trees.
- **Deep Biological Trait Filtering**: Toggle connections and biological classifications by male, female, or shared traits natively in the interactive UI.
- **Connection Categorizations**: Nodes and edges are categorized deeply to help explore the human form from multiple perspectives:
  - Default Anatomy
  - Neuronal / Nerve
  - Sexual / Erogenous
  - Excised / Removed
  - Adverse Consequence
  - Claimed Benefit
  - Direct Harm
  - Energetic

## Live Demo
Check out the fully interactive project hosted live at: [https://mrbang21.github.io/human/](https://mrbang21.github.io/human/)

## Tech Stack
Pure Native Web Technologies. No heavy frameworks or excessive canvas dependencies required.
- **Vanilla JS**: No React, Vue, or D3.js. High-performance direct DOM and SVG manipulation.
- **SVG lines & HTML Elements**: Seamlessly animates DOM elements over scalable vector graphics.
- **Local Data**: Driven entirely by the `human.json` file.

## Usage
Simply launch a local web server in this directory and open `index.html`!
```
python -m http.server 
```
Then navigate to `http://localhost:8000/`.

## Author
Built by [@MrBang21](https://x.com/MrBang21).
Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) - share freely with attribution.
