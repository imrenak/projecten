# Paper Weekly

Persoonlijke website/portfolio showcasing "Imre's voetbalreis". Contains images and a background video. 

## Project structure

- `index.html` - Main HTML file
- `css/` - Stylesheet(s)
- `img/` - Images
- `video/` - Background video file

## Notes

- If your video files are large, consider using Git Large File Storage (Git LFS) or storing videos in a separate hosting provider (e.g., YouTube, Vimeo, or cloud storage).
- To publish this on GitHub Pages, create a repository and enable GitHub Pages in repository settings (optional).

## How to initialize and push to GitHub

1. Create a new repository on GitHub (https://github.com/new).
2. On your local machine in the project root, run:

```powershell
git init
git add .
git commit -m "Initial commit: Paper Weekly site"
# Replace the URL below with the repo URL from GitHub
git remote add origin https://github.com/USERNAME/REPO_NAME.git
git branch -M main
git push -u origin main
```

Or, if you use GitHub CLI (`gh`):

```powershell
gh repo create USERNAME/REPO_NAME --public --source=. --remote=origin --push
```

## License

This project is provided under the MIT License (see `LICENSE`).
