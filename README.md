# Programming-Bootcamp

Collaborative ASCII Art wall for UofL NSBE's Programming Bootcamp Event. Learn Git basics as you contribute your art to the wall!

---

## Our Collaborative Art Wall

You can find our art wall in the `wall.txt` file. 
---

## Instructions

### Fork the Repository

 Click the **Fork** button at the top-right of this page.
 This makes a copy of the repo under your GitHub account.

### Clone Forked Repo

Open gitbash (Windows) or Terminal (Mac/Linux) and run:

 
```bash
git clone https://github.com/<YOUR-USERNAME>/Programming-Bootcamp.git
```

Replace `<YOUR-USERNAME>` with your GitHub username.

navigate into the repo's folder:

```bash
cd Programming-Bootcamp
```

### Create a New Branch

working on a new branch keeps your changes separate from the main branch, making it easier to catch problems. This also keeps your main branch safe from large changes breaking something important.

use git checkout to create a new branch

```bash
git checkout -b yourname-art
```

replace `yourname` with your name or github user

### Add Your ASCII Art to `wall.txt`

Open `wall.txt` in a GitHub codespace.

Scroll to the bottom of the file and add a new section with your name and art, for example:

```
============================================================
  Your Name Here
============================================================

  [this is where you can post your art]

```

If you don't know what to make you can find ASCII art inspiration at https://www.asciiart.eu/.

### Stage and Commit Your Changes

Tell Git which file you changed:

```bash
git add wall.txt
```

commit your changes with a short message:

```bash
git commit -m "Added my art - <username>"
```

### Push Your Branch to GitHub

```bash
git push origin add-my-art
```

### Open a Pull Request

 Go to **your fork** on GitHub (`https://github.com/<username>/Programming-Bootcamp`).
 You should see a banner saying **"Compare & pull request"** — click it.
 Add a short title and description, then click **"Create pull request"**.
 Wait for a maintainer to review and merge your art into the main wall. 🎉

---

## 💡 Tips 

- Keep your ASCII art between the `====` divider lines so our Board stays organized.
  
- If you get a **merge conflict**, ask us for help — merge conflicts are to be expected when collaborating with others in github. Learning how to resolve them is important!
  
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

 Have fun!
