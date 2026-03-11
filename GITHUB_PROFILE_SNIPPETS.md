# Add this Snake game to your GitHub profile

Follow these steps to put the game on GitHub and show it on your profile.

---

## Step 1: Push the game to GitHub

1. Create a new repository on GitHub (e.g. `snake-game`).
2. In your project folder, run:

```bash
cd "c:\Users\Production\Documents\Project\snake-game"
git init
git add .
git commit -m "Add Snake game"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/snake-game.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

---

## Step 2: Enable GitHub Pages (so others can play it)

1. Open your repo: `https://github.com/YOUR_USERNAME/snake-game`
2. Go to **Settings** → **Pages** (left sidebar).
3. Under **Source**, choose **Deploy from a branch**.
4. Under **Branch**, select `main` and folder **/ (root)**.
5. Click **Save**. After a minute or two, the game will be live at:

   **https://YOUR_USERNAME.github.io/snake-game/**

---

## Step 3: Add it to your profile README

Your profile README is in a repo named exactly like your username (e.g. `github.com/yourname/yourname`).

### Option A: Simple link

```markdown
## 🎮 Projects

- [🐍 Snake Game](https://YOUR_USERNAME.github.io/snake-game/) – Classic Snake in the browser
```

### Option B: Section with description

```markdown
## 🎮 Things I built

| Project | Description |
|--------|-------------|
| [🐍 Snake Game](https://YOUR_USERNAME.github.io/snake-game/) | Classic Snake with Easy/Normal/Hard and obstacles |
```

### Option C: Card-style with badge

```markdown
## Projects

[![Snake Game](https://img.shields.io/badge/🐍_Play_Snake_Game-00ff88?style=for-the-badge)](https://YOUR_USERNAME.github.io/snake-game/)
```

### Option D: Pinned repo (no README edit)

1. Go to your profile: `https://github.com/YOUR_USERNAME`
2. Click **Customize your pins** (or **Add** in the projects section).
3. Select **snake-game** so it appears in your pinned repositories.

---

Replace `YOUR_USERNAME` in every link with your real GitHub username. After saving the README or pinning the repo, the Snake game will show up on your profile.
