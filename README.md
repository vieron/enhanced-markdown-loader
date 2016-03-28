# enhanced-markdown-loader

A webpack markdown loader with YAML front-matter, syntax highlighting, and asset `require`ing (like `html-loader` does).
Note that files required with this loader return a JS object, not a HTML string. So you can't chain another loaders
like `html-loader` that expect an HTML string as input.

This loader works pretty well with the simple [static-webpack-plugin](https://github.com/mushishi78/static-webpack-plugin).



