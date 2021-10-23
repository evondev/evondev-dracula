# Dracula High Contrast Theme for Visual Studio Code

[![Version](https://vsmarketplacebadge.apphb.com/version/evondev.dracula-high-contrast.svg)](https://marketplace.visualstudio.com/items?itemName=evondev.dracula-high-contrast)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/evondev.dracula-high-contrast.svg)](https://marketplace.visualstudio.com/items?itemName=evondev.dracula-high-contrast)
[![Downloads](https://vsmarketplacebadge.apphb.com/downloads/evondev.dracula-high-contrast.svg)](https://marketplace.visualstudio.com/items?itemName=evondev.dracula-high-contrast)

> This Theme based on [dracula-official](https://github.com/dracula/dracula-theme)

![Preview](https://raw.githubusercontent.com/evondev/evondev-dracula/master/preview.png)

## Installation

1. Open Extensions sidebar panel in VS Code. **View → Extensions**
2. Search for **Evondev Dracula**
3. Click **Install** to install it.
4. Click **Reload** to reload the editor.
5. File > Preferences > Color Theme > Dracula High Contrast

## Scheme color

- Dracula normal contrast
- Dracula high contrast
- Dracula darker contrast

## Enable Gradient scheme

- Install Custom CSS and JS Loader Extension
- Download file `gradient.css` by [`click here`](https://github.com/evondev/evondev-dracula/blob/master/gradient.css)
- Copy `gradient.css` to a location on your machine, such as your user folder. Copy the file path and add it to your VS code `settings.json`.
- On Mac it might look something like the snippet below:

```
"vscode_custom_css.imports": [
    "file:///Users/MyUserName/Documents/gradient.css"
  ],
```

- On Window it might look something like the snippet below:

```
"vscode_custom_css.imports": [
    "file:///C:/Users/MyUserName/Documents/gradient.css"
  ],
```

- If you don't know how to add custom CSS path above, please watch this video: (https://www.youtube.com/watch?v=h6undBvNB8s)

## My settings.json

- If you want to know my settings.json, please check here: (https://github.com/evondev/evondev-dracula/blob/master/evondev-settings.json)

## My other extensions

- [Evondev Snippets](https://marketplace.visualstudio.com/items?itemName=evondev.evondev-snippets&ssr=false)
- [Evondev - HTML to CSS Class](https://marketplace.visualstudio.com/items?itemName=evondev.generate-css-classs&ssr=false)

## Font I'm using

I use [SF Mono Ligatures](https://github.com/kube/sf-mono-ligaturized).
