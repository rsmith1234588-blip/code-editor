# Snapcode → JS

A block-based code editor that turns blocks into real JavaScript as you build.
Snap blocks together on the left; the generated JavaScript appears on the right
and runs live in a preview.

## Features

- **Page blocks**: headings, text, buttons with click actions, input boxes, colours (a mini website builder)
- **Draw blocks**: circles, boxes and text on a canvas
- **Event blocks**: repeat every N seconds, run after N seconds, arrow-key controls
- **Standard blocks**: logic, loops, math, text, lists, variables, functions
- **Live preview** with a console, plus protection against forever loops
- **Export**: copy the JavaScript, or copy a complete `.html` page that works on its own in any browser
- **Examples**: click counter, tip calculator, confetti art, rocket countdown, arrow-key dot game
- Your blocks are saved automatically in your browser

## Run it

Serve the folder with any static web server (the `media/` icons load by relative path):

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

Built with [Blockly](https://developers.google.com/blockly) and [highlight.js](https://highlightjs.org/).
