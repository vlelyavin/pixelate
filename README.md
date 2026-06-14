# pixelate

interactive pixel art effect for any image. drop an image, move your mouse, watch it react.

**[try it live](https://vlelyavin.github.io/pixelate/)**

## what it does

- turns any image into a particle grid
- particles repel from cursor with spring physics
- color shifts on displacement
- auto-switches to ImageData renderer at 50k+ particles for performance

## controls

- **mouse** - repel particles
- **radius slider** - cursor area of effect (30-300px)
- **force slider** - repulsion strength
- **pixel size slider** - particle density (2-16px)
- **spring slider** - how fast particles snap back
- **space** - reset

## tech

single html file, zero dependencies. canvas 2D + typed arrays for performance.

## license

MIT
