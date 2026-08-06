# Celestial Goods

A static website for Celestial Goods, an organic and artisanal delicacies storefront.

## Preview the site locally

1. Open a terminal in the repository root.
2. Run:
   ```bash
   cd dist
   python3 -m http.server 8000
   ```
3. Open this URL in your browser:
   ```
   http://localhost:8000
   ```

## About the build

- The preview site is served from the `dist/` folder.
- `dist/index.html` loads the built JavaScript and CSS from `dist/assets/`.

## Notes

- The project currently contains the built static output. If you want to work from source, add the app source files alongside this repository.

