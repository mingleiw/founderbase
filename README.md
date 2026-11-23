# founderbase

Promotional landing page for **Founder Base 创业者基地**, a startup space in San Francisco: desks and offices, an event venue, warehouse space, food on site and a network.

## What's here

- `index.html`: the whole site in one static file (HTML, CSS and a few lines of JS). English by default, with a 中文 toggle in the header. Light and dark themes follow the visitor's system setting.

No build step. Open `index.html` in a browser to preview it.

## Deploy

- **GitHub Pages:** Settings → Pages → Deploy from a branch → `main`, folder `/ (root)`.
- **Vercel or Netlify:** import the repo as a static site with no build command and the root as the output folder.

## Before going live

The page marks facts that still need filling in with a dashed yellow box. Search `index.html` for `class="ph"`:

- Address or neighborhood (hero and footer)
- Contact email (contact section)
- Event venue pricing, capacity and A/V details (event hosts section)
- Short bios for Will, Carrie and Minglei (partners section)
- Form backend: the interest form shows a "not connected" note and sends nothing until one is wired up
- Confirm the office amenities listed (internet, printing, meeting rooms) and the venue's sound and projection

Design pass guided by [unslop](https://github.com/heydamir/unslop) by Damir Sokolovsky (CC BY 4.0).
