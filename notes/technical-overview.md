---
slug: github-tech-resume-note-technical-overview
id: github-tech-resume-note-technical-overview
title: Tech Resume Overview
repo: justin-napolitano/tech-resume
githubUrl: https://github.com/justin-napolitano/tech-resume
generatedAt: '2025-11-24T18:48:31.656Z'
source: github-auto
summary: >-
  This repo provides a LaTeX resume template focused on clarity and ease of
  customization. It runs on XeLaTeX, making it flexible for professional use.
  Key components include:
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: note
entryLayout: note
showInProjects: false
showInNotes: true
showInWriting: false
showInLogs: false
---

This repo provides a LaTeX resume template focused on clarity and ease of customization. It runs on XeLaTeX, making it flexible for professional use. Key components include:

- Custom class file (`my-resume.cls`) for formatting
- Options for single or double-sided layouts
- Configurable header and highlight bar
- Multiple styles and color choices

### Quick Start

1. **Prerequisites**: Ensure you have XeLaTeX, Python 3, and the `make` utility installed.
2. **Clone the Repo**:
    ```bash
    git clone https://github.com/justin-napolitano/tech-resume.git
    cd tech-resume
    ```
3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
4. **Build the Resume**:
    Use:
    ```bash
    make clean
    make html
    ```
   Or run the Python script:
    ```bash
    python python-build.py
    ```

### Gotcha

To compile it manually, remember to use XeLaTeX:
```bash
xelatex resume.tex
```
