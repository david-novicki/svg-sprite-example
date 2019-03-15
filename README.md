## SVG Sprite Examples

This shows a small proof of concept of SVG sprites.

Reference: https://github.com/jesstelford/color-svg-sprite

## Pros

- Simple syntax
- Single source of truth for base icons
- Cache-able
- No Javascript

## Cons

- No ability to change the viewBox
- Webpack loaders to handle sprite.svg in our application
- Cannot currently apply our global class as a hover

## Recommendation

This is a fair and solid way to move forward. Icons can be removed from sprite.svg when their use case needs become greater than sprite SVG implementation can handle.
