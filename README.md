# Dual Bloom — Artist Portfolio

Portfolio site for the **Dual Bloom** body of work — contemporary symbolic
painting exploring the duality of the human experience.

A single self-contained page (`index.html`): no build step, no dependencies.
Open it in a browser, or drop the whole folder on any static host
(Netlify, Vercel, GitHub Pages…).

## Adding the photographs

Put the three photos in `images/`:

| File | Painting |
|---|---|
| `images/painting-01.jpg` | *Eat the Soul (11:11)* — orange figure on cobalt blue |
| `images/painting-02.jpg` | *999* — pink & black Porsche wing |
| `images/painting-03.jpg` | *He:ll (555)* — blue torso on flame red |

The page detects the files automatically and swaps them in place of the
painted SVG studies — nothing else to change.

## Customising

- **Contact email**: search for `mailto:` in `index.html`.
- **Colours**: all tokens live in the `:root` block at the top of the CSS.
- **Titles & texts**: each work is a self-contained `<article>` block.
