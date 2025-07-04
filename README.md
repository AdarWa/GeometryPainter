
# Geometry Painter

**Geometry Painter** is a web-based tool for drawing and exporting simple geometric shapes.

![screenshot](https://github.com/AdarWa/GeometryPainter/blob/main/image.png?raw=true)

## Features

- **Draw polygonal shapes** by clicking to place vertices
- **Auto-labeling** of points and sides using alphabetic identifiers
- **Interactive canvas** powered by [Konva.js](https://konvajs.org/)
- **Export to JSON** format with structured shape data

## Getting Started

1. Clone or download this repository.
2. Start a simple web server on your machine.
3. Access the web server using any modern web browser.

```bash
git clone https://github.com/AdarWa/GeometryPainter
cd GeometryPainter
python3 -m http.server
# Open http://localhost:8000 in any modern web browser
```

## Usage

-   Click the **"Draw"** button to enter drawing mode.
    
-   Click anywhere on the canvas to place vertices.
    
-   Vertices will be connected to form a polygon.

-   Click **"Download"** to export the geometry as a `.json` file.

##  License

This project is licensed under the MIT License. See `LICENSE` for more details.
