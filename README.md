# 91546s2015_Richard_Hennigan_pa1

The JavaScript for this project was compiled from source written in CoffeeScript.

## Build instructions

### Installing CoffeeScript

If you need to install `coffee`, the CoffeeScript compiler, you can do so with `npm`:

```bash
npm install -g coffee-script
```

### Compiling to JavaScript

```bash
coffee -m -o . -c coffeescript/
```

## Explanation of "fractal mode"

In this mode, you draw a polyline and a polygon, and the algorithm recursively replaces line segments of the polygon with the supplied polyline. It does this by scaling, rotating, and translating copies of the polyline so that its endpoints are aligned with the endpoints of the line segment which it is replacing. The `sample` button will provide an input that generates a Kock snowflake, which starts with a triangle and replaces each line with the pointed polyline shown.