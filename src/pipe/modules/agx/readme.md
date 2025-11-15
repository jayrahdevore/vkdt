# agx: transform linear scene to visual display

## connectors

- `input`
- `output`

## parameters

- `sat` saturation value
- `offset` slope offset
- `slope_r` red channel slope
- `slope_g` green channel slope
- `slope_b` blue channel slope
- `power`

---

Still figuring this stuff out, this is pretty much copy pasta from
[this bare-bones implementation](https://iolite-engine.com/blog_posts/minimal_agx_implementation).
TODO: replace the approximate curve with a parametrized one, ideally similar to
darktable's implementation.

This module should probably be placed after the colour module.
