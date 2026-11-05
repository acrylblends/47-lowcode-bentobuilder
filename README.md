# Bento Builder

A visual internal-tool builder for composing a small operations portal from reusable components bound to simple data sources.

An ACRYL Blends blueprint for the **Low-code / No-code** category (`acrylblends.bento-builder`, category 47 of 100).

Status: designed, being built. `design/spec.md` is the specification and `design/mockup.html` the mockup (open it in a browser). The app itself,
composed from Cordis plugins (one `plugins/<feature>/` folder and one `blend.yaml` row per feature), lands here when it passes review.

When it is ready you will start it with:

```sh
npm create acrylblends@latest my-app -- --from acrylblends.bento-builder
cd my-app && npm install && npm run dev
```

Listed on https://acrylblends.github.io/blends and https://acryl.dev/blends.
