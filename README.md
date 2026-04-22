# Renliang Sun — Academic Personal Website

This repository contains the content files for your academic personal website, based on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template.

## Quick Start (5 minutes)

### Step 1: Fork the template
1. Go to [academicpages.github.io](https://github.com/academicpages/academicpages.github.io)
2. Click **"Use this template"** → **"Create a new repository"**
3. Name it `<your-github-username>.github.io`

### Step 2: Replace content files
Copy the files from this package into your forked repository, replacing the existing ones:

```
_config.yml              → replace the root _config.yml
_data/navigation.yml     → replace _data/navigation.yml
_pages/about.md          → replace _pages/about.md
_pages/publications.md   → replace _pages/publications.md
_pages/experience.md     → add to _pages/
_pages/cv.md             → replace _pages/cv.md
_publications/*.md       → replace all files in _publications/
```

### Step 3: Customize (search for TODO)
Open `_config.yml` and update the fields marked with `TODO`:
- [ ] `url` — your actual GitHub Pages URL
- [ ] `repository` — your actual repo path
- [ ] `author.avatar` — add your profile photo as `images/profile.png`
- [ ] `author.googlescholar` — your Google Scholar profile URL
- [ ] `author.github` — your GitHub username
- [ ] `author.linkedin` — your LinkedIn username (optional)
- [ ] `author.orcid` — your ORCID (optional)

### Step 4: Add your profile photo
Upload a square photo to `images/profile.png` in your repository.

### Step 5: Deploy
Your site will be live at `https://<your-github-username>.github.io` within a few minutes!

## File Structure

```
├── _config.yml                  # Site-wide configuration
├── _data/
│   └── navigation.yml           # Top navigation bar
├── _pages/
│   ├── about.md                 # Homepage / About
│   ├── publications.md          # Publications listing
│   ├── experience.md            # Research & work experience
│   └── cv.md                    # CV page
├── _publications/               # 23 individual publication pages
│   ├── 2026-05-01-refrain-adaptive-early-stopping.md
│   ├── 2026-05-02-agentic-rl-survey.md
│   ├── ...
│   └── 2019-02-01-incomplete-frame-discernment.md
├── images/                      # Put your profile photo here
└── files/                       # Put your CV PDF here
```

## Updating Content

- **Add a new publication**: Create a new `.md` file in `_publications/` following the existing format
- **Update your bio**: Edit `_pages/about.md`
- **Add news**: Edit the News section in `_pages/about.md`
- **Change navigation**: Edit `_data/navigation.yml`

## Questions?

Refer to the [Academic Pages documentation](https://academicpages.github.io/) for more details.
