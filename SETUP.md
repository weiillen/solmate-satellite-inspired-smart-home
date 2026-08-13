# GitHub Setup

The original PowerPoint contains embedded videos and is larger than GitHub's normal 100 MB single-file limit. This repository therefore tracks `.pptx` files with **Git LFS**.

On macOS:

```bash
brew install git-lfs
git lfs install
```

Then, from the repository folder:

```bash
git init
git add .
git commit -m "Add SOLMATE project portfolio"
git branch -M main
git remote add origin https://github.com/weiillen/solmate-satellite-inspired-smart-home.git
git push -u origin main
```

You can confirm that the deck is tracked by LFS with:

```bash
git lfs ls-files
```

Expected LFS file:

```text
docs/solmate-project-presentation.pptx
```
