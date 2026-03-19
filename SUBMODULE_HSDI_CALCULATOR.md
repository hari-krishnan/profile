# HSDI calculator submodule (optional mirror)

The calculator lives in its own repo so it can be indexed at its own GitHub Pages URL:

**https://hari-krishnan.github.io/hsdi-frame-rate-calculator/**

**Zenodo (v0.0.1):** [10.5281/zenodo.19120795](https://doi.org/10.5281/zenodo.19120795) · [record](https://zenodo.org/records/19120795)

After [`hsdi-frame-rate-calculator`](https://github.com/hari-krishnan/hsdi-frame-rate-calculator) exists on GitHub with **GitHub Pages** enabled, add it as a submodule so it also appears under this site:

```bash
cd /path/to/profile
git submodule add https://github.com/hari-krishnan/hsdi-frame-rate-calculator.git projects/hsdi-frame-rate-calculator
git commit -m "Add hsdi-frame-rate-calculator submodule"
git push
```

Enable **GitHub Pages** on the `hsdi-frame-rate-calculator` repo (branch `main`, root).

Old link `.../projects/content/frame_rate_calculator.html` redirects to the new canonical URL.
