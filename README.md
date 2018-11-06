# Granny Grid

This is a grid for support of old browsers 👵

## Usage


## Compile CSS

These are commands to compile `.scss` to `.css` and minify the file. At some point, we should set up Webpack.

```bash
npm install uglifycss -g
npm install sass -g
```

```bash
sass main.scss main.css --sourcemap=none
uglifycss main.css --output main.css
cd ...
```
