# Wall Layout Simulator

English | [日本語](README.ja.md)

Wall Layout Simulator is a standalone browser-based web application for designing and previewing room layouts, wall art placement, furniture arrangements, doors, and window frames.

It is implemented as a single `index.html` file and can run directly in a browser without a build step or server.

## Features

- 3D room layout preview
- Front, back, left, and right 2D wall views
- Top view, 3D view, and camera reset
- Room size customization
- Wall and floor color customization
- Wall art placement
  - Framed pictures
  - Posters
  - Fabric and tapestry items
  - Mirrors
- Preset paper and merchandise sizes
  - A-series and B-series sizes
  - Shikishi
  - Long tapestry
  - Dakimakura cover
  - Square format
  - Custom size
- Furniture placement
  - Sofa
  - Table
  - Shelf
  - Cabinet
  - Bed
- Door and window-frame objects
- Object selection, duplication, deletion, locking, hiding, and showing
- Alignment and distribution tools for wall-mounted objects
- Local image loading for wall art
- Image loading from URL
- Scene export and import as JSON
- PNG export
- Japanese and English UI switching
- Guided tour
- Demo scenes
  - Living room demo
  - Gallery wall demo

### Minimal file structure

```text
.
├── index.html
├── README.md
├── README.ja.md
└── LICENSE
```


## Usage

## Basic Workflow

1. Set the room width, depth, and height.
2. Select the active wall.
3. Add wall art, furniture, doors, or window frames.
4. Move, align, duplicate, or delete objects.
5. Export the result as PNG or JSON as needed.
6. Import a saved JSON scene to continue editing later.

## Keyboard Shortcuts

| Key | Action |
|---|---|
| `G` | Grab / move selected object |
| `R` | Rotate selected object |
| `S` | Box select |
| `V` | Clear selection |
| `Delete` / `Backspace` | Delete selected object |
| `Shift + D` | Duplicate selected object |
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |
| `1` | Front wall 2D view |
| `7` | Top view |
| `5` | Toggle projection mode |
| `M` | Show / hide side panels |
| `?` | Start guided tour |
| `F` | Reset zoom and pan |
| `Esc` | Cancel the current operation |

## JSON Data

Scenes can be exported and imported as JSON files.

The JSON data mainly includes:

- Room size and colors
- Object list
- Object positions and sizes
- Active wall
- Camera state
- Layer and display settings

## Notes on Image Loading

Local images can be attached to wall art through the file picker.

Images loaded from external URLs may be affected by browser CORS restrictions. If PNG export fails after loading an external image, try using a local image instead.

## Browser Compatibility

This application uses standard HTML, CSS, JavaScript, and Canvas APIs. A recent version of the following browsers is recommended:

- Microsoft Edge
- Google Chrome
- Mozilla Firefox
- Safari

## AI Assistance

This project was created with the assistance of GPT-5.5.

## License

This project is licensed under the GNU General Public License v3.0.

See [LICENSE](LICENSE) for details.
