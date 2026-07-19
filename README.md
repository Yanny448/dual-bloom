# The Beauty of Contradiction — Amy Lessard

**The Beauty of Contradiction** — portfolio site of painter **Amy Lessard**
(House of Duality series) — contemporary symbolic painting exploring the duality
of the human experience.

A single self-contained page (`index.html`): no build step, no dependencies.
Open it in a browser, or drop the whole folder on any static host
(Netlify, Vercel, GitHub Pages…).

## Photographs

The three canvases live in `images/` (web-optimised, ~1800px):

| File | Painting |
|---|---|
| `images/painting-01.jpg` | *Mercy* — orange figure on cobalt blue |
| `images/painting-02.jpg` | *Hunger* — pink & black Porsche wing |
| `images/painting-03.jpg` | *Blues* — blue torso on flame red |

Full-resolution originals are kept in `originals/`.

## Customising

- **Contact email**: search for `mailto:` in `index.html`.
- **Colours**: all tokens live in the `:root` block at the top of the CSS.
- **Titles & texts**: each work is a self-contained `<article>` block.
