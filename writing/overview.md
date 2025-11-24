---
slug: github-tech-resume-writing-overview
id: github-tech-resume-writing-overview
title: Crafting a Professional Resume with tech-resume
repo: justin-napolitano/tech-resume
githubUrl: https://github.com/justin-napolitano/tech-resume
generatedAt: '2025-11-24T18:07:52.267Z'
source: github-auto
summary: >-
  I’ve always felt that your resume should reflect not just where you’ve been
  but also where you want to go. That's where my GitHub repo,
  [tech-resume](https://github.com/justin-napolitano/tech-resume), comes into
  play. It’s a LaTeX resume template designed to give you a leg up in the job
  market, with customization and clarity at its core.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: writing
entryLayout: writing
showInProjects: false
showInNotes: false
showInWriting: true
showInLogs: false
---

I’ve always felt that your resume should reflect not just where you’ve been but also where you want to go. That's where my GitHub repo, [tech-resume](https://github.com/justin-napolitano/tech-resume), comes into play. It’s a LaTeX resume template designed to give you a leg up in the job market, with customization and clarity at its core.

## Why This Repo Exists

I was tired of the typical “cookie-cutter” resumes that look bland and don’t showcase individual personality. I wanted something fresh and flexible, hence the birth of tech-resume. Drawing inspiration from well-known templates like AltaCV and AwesomeCV, I aimed to create a framework that makes crafting a standout resume easy and efficient.

## Key Design Decisions

Building this template wasn't just about making it look good. I wanted it to work effectively across various user needs, so I made several pivotal choices:

- **Custom Class**: I developed a custom LaTeX class (`my-resume.cls`). This underpinning allows for effective formatting without getting mired in LaTeX intricacies.
  
- **Flexible Layout Options**: Users can choose between single-sided or double-sided layouts. It’s about providing choices that match individual styles.
  
- **Highlight Features**: With a configurable highlight bar, you can draw attention to what you find important. It’s all about emphasizing your most vital skills or experiences.
  
- **Modular Sections**: The resume is broken into sections. This allows for easy customization, enabling you to focus on what truly matters.

- **Cross-Compatibility**: Built on XeLaTeX, the template supports a wide range of fonts and graphics. You aren’t just limited to basic aesthetics here.

## Tech Stack

Here’s a rundown of the stack I'm using:

- **LaTeX** - The core of the project, specifically the XeLaTeX engine for better font handling and graphics support.
- **Python** - For a build automation script that guides the generation of the final document.
- **Makefile** - It streamlines the process, allowing users to run simple commands to build their resumes.

These choices are intentional, designed to integrate seamlessly and make life easier for the end-user.

## Getting Started

If you're ready to dive in, here’s how to get started with tech-resume:

### Prerequisites

You’ll need a few things installed first:

- **XeLaTeX**: Make sure this is set up on your machine.
- **Python 3**: The script runs on Python 3, so don’t forget that.
- **Make utility**: It's handy for executing commands.

### Installation Steps

1. **Clone the Repo**
   ```bash
   git clone https://github.com/justin-napolitano/tech-resume.git
   cd tech-resume
   ```

2. **Install Python Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

### Build Your Resume

Once you’re set up, building your resume is straightforward. You can either run the build script directly or use the provided Makefile:

```bash
make clean
make html
```

Or, simply run:

```bash
python python-build.py
```

### Manual Compilation

If you prefer to compile manually with XeLaTeX, just use:

```bash
xelatex resume.tex
```

## Project Structure

The organization of the repo is intuitive. Here’s a snapshot:

```
tech-resume/
├── deployz/                # Deployment scripts or assets
├── sections/               # Modular LaTeX sections for content
├── my-resume.cls           # Custom LaTeX class for resume
├── python-build.py         # Build automation script
├── resume.tex              # Main LaTeX source
├── README.md               # Documentation
├── LICENSE                 # License file
├── resume.pdf              # Compiled resume example
├── resume-*.png            # Output screenshots
├── *.log, *.aux, *.out     # Auxiliary files
└── picture.jpg, head_shot.jpeg  # Images for the resume
```

## Tradeoffs and Challenges

Every project has its tradeoffs. For tech-resume, the balance between simplicity and customization was a constant theme. I wanted it to be user-friendly but also offer enough flexibility for those who want to tweak things. 

The reliance on LaTeX might intimidate some, but I truly believe the output outweighs that initial hurdle. The quality and control over formatting, combined with elegant design options, provide a level of professionalism that is hard to beat.

## What’s Next?

Looking forward, there’s a lot on my plate. Here’s what I’d like to tackle:

- **Overleaf Template Updates**: I plan to keep the Overleaf version synchronized with the GitHub code to ensure everyone has the latest features.
  
- **Customization Options**: I want to add even more customization options for colors and fonts. Individual branding matters.
  
- **Build Automation Improvements**: Enhancing error handling in the Python build script would smooth the user experience.
  
- **Unit Tests**: Adding tests for the build pipeline feels like a necessity to ensure everything works seamlessly.
  
- **Expanded Documentation**: I’ll be enhancing the docs with more usage examples and troubleshooting tips to make it easier for everyone.

Feel free to check back regularly; I’m always tinkering with it.

## Stay Updated

If you're interested in following along as I make updates or want to chime in with feedback, catch me on social media—I'm active on Mastodon, Bluesky, and Twitter/X. I share tidbits, updates, and insights that go beyond just this repo.

In the end, tech-resume isn’t just a resume template; it’s a tool to help you tell your story. Let’s build something great together.
