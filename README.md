# Peri, marketing site

A single static page. No framework, no build step, no dependencies.
Deploys as-is to GitHub Pages, Vercel, Netlify, or Cloudflare Pages.

## Editing

Three placeholders live in one `<script id="peri-config">` block at the
top of `index.html`. Change them there and every link on the page updates.

- `APP_STORE_URL`
- `PRIVACY_URL`
- `SUPPORT_EMAIL`

## Screenshots

`assets/screen-1.png` through `screen-6.png`, in the order of the six
feature blocks on the page:

1. A gentle read on your day
2. Notice what's shifting
3. It learns what helps you
4. It notices, so you don't have to
5. Someone to talk to, at 3am
6. See what your body is doing

These are resized to 640px wide. The full-resolution originals sit in
`assets/originals/`, which is gitignored so it stays off the host.

`screen-1.png` doubles as the Open Graph share image.

## Preview locally

    python3 -m http.server 4321
