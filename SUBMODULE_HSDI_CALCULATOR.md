# HSDI calculator submodule (optional mirror)

The calculator lives in its own repo so it can be indexed at its own GitHub Pages URL:

**https://hari-krishnan.github.io/hsdi-frame-rate-calculator/**

**Zenodo (v0.0.1):** [10.5281/zenodo.19120795](https://doi.org/10.5281/zenodo.19120795) · [record](https://zenodo.org/records/19120795)

**Latest source:** [GitHub `main`](https://github.com/hari-krishnan/hsdi-frame-rate-calculator/tree/main)

To mirror the calculator under this site (repo must have **GitHub Pages** enabled on `main`):

```bash
cd /path/to/profile
git submodule add https://github.com/hari-krishnan/hsdi-frame-rate-calculator.git projects/hsdi-frame-rate-calculator
git commit -m "Add hsdi-frame-rate-calculator submodule"
git push
```

Enable **GitHub Pages** on the `hsdi-frame-rate-calculator` repo (branch `main`, root).

Old link `.../projects/content/frame_rate_calculator.html` redirects to the new canonical URL.
