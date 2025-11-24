---
slug: github-tech-resume
id: github-tech-resume
title: my-resume
repo: justin-napolitano/tech-resume
githubUrl: https://github.com/justin-napolitano/tech-resume
generatedAt: '2025-11-24T21:36:38.791Z'
source: github-auto
summary: >-
  A LaTeX resume/CV template designed for customization and clarity. Inspired by
  AltaCV and AwesomeCV, this template runs on XeLaTeX and provides a flexible
  framework for creating professional resumes.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: project
entryLayout: project
showInProjects: true
showInNotes: false
showInWriting: false
showInLogs: false
---

A LaTeX resume/CV template designed for customization and clarity. Inspired by AltaCV and AwesomeCV, this template runs on XeLaTeX and provides a flexible framework for creating professional resumes.

---

## Features

- Custom LaTeX class (`my-resume.cls`) for resume formatting
- Options for single-sided or double-sided page layouts
- Highlight bar with configurable placement
- Support for header customization
- Multiple page styles and color options
- Compatible with XeLaTeX for font and graphics support
- Includes example PDFs demonstrating layout variations

## Tech Stack

- LaTeX (XeLaTeX engine)
- Python (build automation script)
- Makefile (build automation, assumed from `make` commands)

## Getting Started

### Prerequisites

- XeLaTeX installed
- Python 3
- `make` utility

### Installation

1. Clone the repository:

```bash
git clone https://github.com/justin-napolitano/tech-resume.git
cd tech-resume
```

2. Install Python dependencies:

```bash
pip install -r requirements.txt
```

### Build the Resume

Run the build script or use make commands:

```bash
make clean
make html
```

Alternatively, use the provided Python build script:

```bash
python python-build.py
```

### Compile Manually

Compile the LaTeX source with XeLaTeX:

```bash
xelatex resume.tex
```

## Project Structure

```
tech-resume/
├── deployz/                # (Assumed deployment scripts or assets)
├── sections/               # LaTeX sections for modular resume content
├── my-resume.cls           # Custom LaTeX class for resume
├── python-build.py         # Python script for build automation
├── resume.tex              # Main LaTeX resume source file
├── README.md               # This documentation
├── LICENSE                 # License file
├── resume.pdf              # Compiled resume example
├── resume-*.png            # Example output screenshots
├── *.log, *.aux, *.out     # LaTeX auxiliary files
└── picture.jpg, head_shot.jpeg  # Images used in the resume
```

## Future Work / Roadmap

- Update Overleaf template to sync with latest GitHub version
- Add more customization options for colors and fonts
- Improve build automation and error handling in Python script
- Add unit tests for build pipeline
- Expand documentation with usage examples and troubleshooting

---

For issues or contributions, please open a GitHub issue or pull request.

