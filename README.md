# alymatar.github.io

The live copy of my portfolio: **https://alymatar.github.io/**

These files are a static build of [alymatar/portfolio](https://github.com/alymatar/portfolio), a FastAPI + Jinja2 app. Don't edit them by hand: change the app, run `python scripts/export_static.py`, and copy the contents of `dist/` here.

The site's JSON API is served as files: [`/api/health.json`](https://alymatar.github.io/api/health.json), [`/api/projects.json`](https://alymatar.github.io/api/projects.json) and `/api/projects/<slug>.json`, with docs at [`/api/docs/`](https://alymatar.github.io/api/docs/).
