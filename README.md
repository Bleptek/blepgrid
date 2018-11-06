# Granny Grid

This is a grid for support of old browsers 👵🏻

## Usage

```html
<section class="granny">
    <div class="col-xs-1-2 col-sm-1-4">
        <div class="module"></div>
    </div>
    <div class="col-xs-1-2 col-sm-1-4">
        <div class="module"></div>
    </div>
    <div class="col-xs-1-2 col-sm-1-4">
        <div class="module"></div>
    </div>
    <div class="col-xs-1-2 col-sm-1-4">
        <div class="module"></div>
    </div>
</section>
```

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
