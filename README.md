# FH_EVI_2026

## Project overview:

tbd

## What's in this repo

| Folder | What's inside |
|---|---|
| [`week01_structure_based_design/`](week01_structure_based_design/) | Week 1 reading + discussion questions (de novo protein design review) |
| [`week02-03_protein_language_models/`](week02-03_protein_language_models/) | Weeks 2-3 reading + discussion questions (ESMC and EVO2) |
| [`learn_python/`](learn_python/) | Python lessons and notebooks (run them in Google Colab) |
| [`sai/`](sai/) | Sai's project folder |
| [`sonia/`](sonia/) | Sonia's project folder |

Each week's folder has a `README.md` with the instructions and questions for that week. GitHub shows it automatically below the file list when you open the folder.

---

## GitHub basics

GitHub is a website for storing and sharing files (mostly code) with a full history of every change. A few terms:

- **Repository ("repo")**: a project folder on GitHub, like this one.
- **Commit**: a saved snapshot of a change, with a short message describing it. Every upload or edit you make on GitHub becomes a commit.
- **README.md**: a file GitHub displays automatically when you open a folder. The `.md` means it's written in **Markdown**, a simple text format where `# Heading` makes a heading, `**bold**` makes **bold**, and `- item` makes a bullet list.

### Getting set up (one time)

**1. Create a free GitHub account**

1. Go to [github.com/signup](https://github.com/signup) (works in Chrome on a Chromebook).
2. Enter an email address you check regularly. A personal email is best, since school accounts sometimes block outside emails.
3. Create a password and pick a **username**. Other people will see it, so keep it simple and appropriate (e.g. `firstname-lastname` or `firstnamebio`).
4. Complete the puzzle check, then enter the code GitHub emails you to verify your address.
5. If GitHub asks you to choose a plan, pick **Free**. You can skip any personalization questions.

**2. Email me your account info**

Send me an email with:

- your GitHub **username**
- the **email address** you signed up with

I'll use these to add you as a collaborator on this repo.

**3. Accept the invitation**

Check your email (or the notifications bell on github.com) for the invitation to this repo and click **Accept invitation**. You can't upload files until you've accepted. The invitation expires after 7 days, so let me know if you miss it and I'll resend it.

### Getting around the repo in your browser

- Click a folder name to open it. Click a file to view it.
- Click **FH_EVI_2026** at the top of the page (in the breadcrumb path) to get back to the main page.
- PDFs open in the browser. If one won't preview, click the **Download raw file** button (down-arrow icon) at the top right of the file.
- To see what's changed recently, click the **Commits** link (clock icon) near the top of the file list.

Everything here works in a web browser, **including on a Chromebook**. You don't need to install git or anything else.

---

## Saving your Google Docs as Markdown and uploading them

Write your notes and answers in Google Docs, then save a Markdown copy into **your own folder** (`sai/` or `sonia/`). These steps work in Chrome on a laptop or a Chromebook.

### Step 1: Download the doc as a Markdown file

1. Open your Google Doc.
2. Click **File → Download → Markdown (.md)**.
3. The file saves to your **Downloads** folder. (On a Chromebook, open the **Files** app and look under **Downloads**.)
4. Optional: rename it to something descriptive with no spaces, e.g. `week1_answers.md`.

### Step 2: Upload it to your folder on GitHub

1. Go to [github.com/dustin-mullaney/FH_EVI_2026](https://github.com/dustin-mullaney/FH_EVI_2026) and make sure you're signed in.
2. Click your folder: **`sai`** or **`sonia`**.
3. Click the **Add file** button (top right of the file list) → **Upload files**.
4. Drag your `.md` file onto the page, or click **choose your files** and pick it from Downloads.
5. Under **Commit changes**, type a short message like `add week 1 answers`.
6. Leave **Commit directly to the `main` branch** selected and click **Commit changes**.

Click your file to check that it shows up formatted correctly.

**Updating a file later:** upload a new version with the **same file name** and GitHub replaces it. The old version stays in the history. You can also click the file, then the pencil icon (**Edit this file**), make changes, and click **Commit changes...**.

### Option: copy and paste instead of downloading

This is handy if downloading is awkward:

1. In Google Docs, turn on Markdown once: **Tools → Preferences → check "Enable Markdown"**.
2. Select everything in your doc (Ctrl+A), then **Edit → Copy as Markdown**.
3. On GitHub, open your folder → **Add file → Create new file**.
4. Type a file name ending in `.md` (e.g. `week1_answers.md`), paste into the big text box (Ctrl+V), and click **Commit changes...** → **Commit changes**.

> Make sure you're inside **your own** folder before uploading. The path above the file box should read `FH_EVI_2026 / sai /` or `FH_EVI_2026 / sonia /`.

---

## Opening the Learn Python notebooks in Google Colab

The [`learn_python/`](learn_python/) notebooks (`.ipynb` files) can run for free in your browser with [Google Colab](https://colab.research.google.com). You just need a Google account. This works on a Chromebook.

### Option A: click a badge (easiest)

Open [`learn_python/README.md`](learn_python/) and click the **Open in Colab** badge next to any notebook.

### Option B: open from Colab directly

1. Go to [colab.research.google.com](https://colab.research.google.com).
2. **File → Open notebook → GitHub** tab.
3. Paste `https://github.com/dustin-mullaney/FH_EVI_2026` and press Enter.
4. Pick a notebook from the list (e.g. `learn_python/04_python_programming/01_why_python.ipynb`).

### Running a notebook

- Click a code cell and press **Shift+Enter** (or the ▶ button) to run it.
- The first time you run a cell, Colab may warn that the notebook is from GitHub. Click **Run anyway**.

### Notebooks that use data files

Some notebooks (especially in `05_python_data_analysis` and `06_data_vis_python`) read files like `data/microbiome.csv`. Colab doesn't download those automatically, so add a new code cell at the very top (**+ Code**), paste the following, and run it first. Change the folder name on the last line to match the notebook you're in:

```python
!git clone -q https://github.com/dustin-mullaney/FH_EVI_2026.git
%cd FH_EVI_2026/learn_python/05_python_data_analysis
```

### Saving your work

Changes you make in Colab are **not** saved back to GitHub. To keep your edited copy, use **File → Save a copy in Drive**. It goes into a `Colab Notebooks` folder in your Google Drive.
