# Frontend build snapshots

This repository publishes two generated static application snapshots with GitHub Pages:

- [Mesto snapshot](https://goldlexx.github.io/frontend/build-mesto/)
- [Movies Explorer snapshot](https://goldlexx.github.io/frontend/build-movies/)

These are archived build artifacts. The editable source is maintained in separate repositories: [Mesto React](https://github.com/goldlexx/mesto-react), [Mesto Full-stack](https://github.com/goldlexx/react-mesto-api-full), and [Movies Explorer frontend](https://github.com/goldlexx/movies-explorer-frontend). The snapshots may not include later fixes from those source repositories.

The GitHub Actions workflow copies these folders to the Pages artifact and generates the landing page. This repository does not contain the original source, dependency manifests, or a reproducible build command. To change either application, update its source repository and generate a new snapshot deliberately.
