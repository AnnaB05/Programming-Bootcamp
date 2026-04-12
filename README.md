# Programming-Bootcamp

Collaborative ASCII Art wall for UofL NSBE's Programming Bootcamp Event. Learn Git basics as you contribute your art to the wall!

---

## 🖼️ What is the Wall?

`wall.txt` is a shared text file where everyone adds their own ASCII art. Think of it as a collaborative canvas — the more people contribute, the cooler it gets!

---

## 🚀 How to Contribute (Step-by-Step for Beginners)

### Step 1 — Fork the Repository

1. Click the **Fork** button at the top-right of this page.
2. This creates your own personal copy of the repo under your GitHub account.

### Step 2 — Clone Your Fork

Open a terminal and run:

```bash
git clone https://github.com/<YOUR-USERNAME>/Programming-Bootcamp.git
```

Replace `<YOUR-USERNAME>` with your actual GitHub username.

Then navigate into the folder:

```bash
cd Programming-Bootcamp
```

### Step 3 — Create a New Branch

Always work on a new branch so your changes are separate:

```bash
git checkout -b add-my-art
```

You can replace `add-my-art` with any short descriptive name you like.

### Step 4 — Add Your ASCII Art to `wall.txt`

Open `wall.txt` in any text editor (Notepad, VS Code, nano, etc.).

Scroll to the bottom of the file and add a new section with your name and art, for example:

```
============================================================
  Your Name Here
============================================================

  [paste your ASCII art here]

```

Not sure what to draw? Try a simple smiley, your initials, an animal — anything goes! You can find ASCII art inspiration at https://www.asciiart.eu/.

### Step 5 — Stage and Commit Your Changes

Tell Git which file you changed:

```bash
git add wall.txt
```

Save your changes with a descriptive message:

```bash
git commit -m "Add ASCII art by <YOUR-NAME>"
```

### Step 6 — Push Your Branch to GitHub

```bash
git push origin add-my-art
```

### Step 7 — Open a Pull Request

1. Go to **your fork** on GitHub (`https://github.com/<YOUR-USERNAME>/Programming-Bootcamp`).
2. You should see a banner saying **"Compare & pull request"** — click it.
3. Add a short title and description, then click **"Create pull request"**.
4. Wait for a maintainer to review and merge your art into the main wall. 🎉

---

## 💡 Tips

- Keep your ASCII art between the `====` divider lines so the wall stays organized.
- If you get a **merge conflict**, don't panic! Ask a facilitator for help — resolving conflicts is a great Git skill to learn.
- You can update your fork at any time. First, add the original repo as a remote (you only need to do this once):
  ```bash
  git remote add upstream https://github.com/AnnaB05/Programming-Bootcamp.git
  ```
  Then pull in the latest changes:
  ```bash
  git fetch upstream
  git merge upstream/main
  ```

---

## 📄 License

This project is open for everyone. Have fun and happy coding! 🤖☕
