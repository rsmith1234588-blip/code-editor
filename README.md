# Snapcode → JS

A block-based code editor that turns blocks into real JavaScript as you build.
Snap blocks together on the left; the generated JavaScript appears on the right
and runs live in a preview.

## Features

- **Page blocks**: headings, text, buttons, input boxes, links, emoji, bullet lists, dividers, popups,
  page title, refresh, fonts, text size, alignment, colours and styling (a mini website builder)
- **Draw blocks**: circles, boxes, lines, emoji and text on a canvas
- **Sound blocks**: notes that play in order (write tunes!), rests, game sound effects, and speech
- **Event blocks**: keys (arrows, space, enter, WASD), mouse moves/clicks, repeating and delayed timers
- **Sensing blocks**: mouse position and button, current time and date, a timer, input box values
- **Standard blocks**: logic, loops, math, text, lists, variables, functions
- **Live preview** with a console, the current tab title, and protection against forever loops
- **Export**: copy the JavaScript, or copy a complete `.html` page that works on its own in any browser
- **Examples**: click counter, tip calculator, confetti art, rocket countdown, arrow-key dot game,
  paint, music box, live clock
- Your blocks are saved automatically in your browser

## Run it

Serve the folder with any static web server (the `media/` icons load by relative path):

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

Built with [Blockly](https://developers.google.com/blockly) and [highlight.js](https://highlightjs.org/).
