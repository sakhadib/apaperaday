# Paper-a-Day — Minimal Static Site

This is a tiny static two-page site demonstrating a searchable & sortable list of posts and a dynamic post page driven by `data.js`.

Files

- `index.html` — Home page (list, search, sort)
- `post.html` — Post detail page (dynamic via ?id=)
- `data.js` — Posts data (array `posts`)

How to run

Open `index.html` in a browser. For full linking to `post.html?id=1` you can serve the folder with a simple static server.

On Windows PowerShell you can run:

```powershell
# Python 3
python -m http.server 8000
# then open http://localhost:8000/index.html
```

Notes

- Built with Tailwind CDN for quick styling.
- `data.js` contains sample data; edit or extend it to add more posts.
- Post pages are accessed like `post.html?id=1`.

Possible improvements

- Add pagination, tag filters, or client-side routing.
- Use a minimal build step to pre-render pages if scaling.

Enjoy!