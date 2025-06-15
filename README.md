## Ergol coffee style

This is a personal project to modify slightly the style of the [Ergol Layout](https://ergol.org/), a Colemak-style keyboard layout optimized for French, English and coding.

## Why fork the ergol layout?

The Ergol layout is a great layout, I really like it for my everday use. However, I found issues with all tiling shortcuts for sway, emacs, and aerospace ()

## How to use it?

This project is using [Kalamine](https://github.com/OneDeadKey/kalamine), a text-based, cross-platform Keyboard Layout Maker (just like the official Ergol Layout). You can use it to generate the layout for your system.


## Install the layout

To install the layout, you need to have the `kalamine` tool installed and then run the following command in the root of this project:

```bash
kalamine build ergol.toml
```

This will generate the layout files in the `dist` directory.

## Developing the layout

To develop or test the layout, you can use the `watch` command to automatically expose a web application that will show you the layout in real-time as you modify it :
```bash
kalamine watch ergol.toml
```
You can then open your browser to `http://localhost:8000` to see the layout.



