# CCG Brochure — Image Guide

Drop your render files into the `images/` folder using these exact filenames:

| File | Section | Notes |
|---|---|---|
| `hero-tile-1.jpg` | Hero grid — top left | Exterior aerial or hero shot. Landscape. |
| `hero-tile-2.jpg` | Hero grid — top right | Masterplan or aerial. Landscape. |
| `hero-tile-3.jpg` | Hero grid — bottom left | Interior or detail shot. Landscape. |
| `hero-tile-4.jpg` | Hero grid — bottom right | Animation frame or VR screenshot. Landscape. |
| `about.jpg` | About section | Portrait orientation. Interior or atmospheric. |
| `project-1.jpg` | Projects — full-width hero | Bali Beachfront Masterplan. Best/widest image. Min 1600×900px. |
| `project-2.jpg` | Projects — card | Hong Kong Hotel. Min 1000×630px. |
| `project-3.jpg` | Projects — card | LA Prime Residence. Min 1000×630px. |
| `project-4.jpg` | Projects — card | Bali Prime Villa. Min 1000×630px. |
| `project-5.jpg` | Projects — card | California Residential. Min 1000×630px. |

JPG or PNG both work. If an image is missing, the dark gradient placeholder shows instead — nothing breaks.

## To update copy or stats

Open `index.html` in any text editor and search for:
- `100+` — update project count
- `8+` — update countries count
- Project names, locations or output badges — find by the project location text

## To deploy to Vercel

1. Go to vercel.com → Add New Project
2. Import from GitHub, or drag this folder to vercel.com/new
3. No build settings needed — it's a static site
4. Done. You'll get a URL like `ccg-brochure.vercel.app`

To use a custom domain, add it under Project Settings → Domains in Vercel.
