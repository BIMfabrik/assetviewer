# BIMfabrik Asset Viewer

A lightweight GitHub Pages viewer for GLB development assets.

## Default repositories

- `BIMfabrik/game_Buggy`
- `BIMfabrik/scargada`

The viewer recursively scans `assets/**/*.glb`, renders assets in interactive 3D cards, and provides stable deep links plus copyable AI-development prompts containing the exact repository, branch, path and Git blob SHA.

## Private repositories

The source game repositories are private. The viewer therefore asks for a GitHub token with read-only Contents access to those repositories. The token is kept only in browser `sessionStorage`; it is never written to URLs or the repository.

For public repositories no token is required.

## GitHub Pages

This repository is designed to publish directly from the `main` branch root.
