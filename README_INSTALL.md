# Installation notes

Copy these files into the root of the GitHub Pages repository `julianschroeter.github.io`.

Recommended steps:

```bash
git clone https://github.com/julianschroeter/julianschroeter.github.io.git
cd julianschroeter.github.io
cp -R /path/to/julian_website_update/* .
```

Then open `_config.yml` and copy the relevant values from `_config_patch.yml` into the existing Chirpy configuration. Do not replace the full `_config.yml` blindly, because Chirpy contains many theme settings.

Commit and push:

```bash
git add .
git commit -m "Add academic website content"
git push
```

GitHub Pages will rebuild the website automatically.
