# Textflow
![Text morphing animation](assets/text_anim.gif)

Textflow is a tool for creating natural-looking text morphing animations. It transforms one string into another by representing them as point sets and matching them with a linear assignment that minimizes total point distances.

## Usage
 Run `main.ipynb`. The following parameters are configurable:
 - `from_text`: The text to start from.
 - `to_text`: The text to morph into.
 - `font_url`: The URL of the font file to use.
 - `base_fig_width`: The base width of the figure.
 - Animation properties (frame rate, easing, hold time, etc.).