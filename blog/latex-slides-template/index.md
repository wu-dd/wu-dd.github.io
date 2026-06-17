---
layout: blog
title: "Keynote LaTeX Presentation Template"
date: 2025-10-11
author: Sakura
tags:
  [LaTeX, Beamer, Presentations, Academic, Templates, Open Source]
description: A modern, clean LaTeX Beamer presentation template with a sleek design inspired by keynote presentations.
---

<div style="text-align: center; margin: 2em 0;">
  <h1 style="font-size: 2.5em; margin-bottom: 0.3em; line-height: 1.2; color: #222;">Keynote LaTeX Presentation Template</h1>
  <p style="color: #666; font-size: 1.1em; margin-bottom: 1em;">A modern, clean Beamer template for professional presentations</p>
  <p style="color: #666; font-size: 0.95em;">
    <i class="fas fa-calendar"></i> Last Updated: October 11, 2025
  </p>
</div>

<div style="display: flex; gap: 1em; justify-content: center; margin: 2em 0; flex-wrap: wrap;">
  <a href="https://github.com/Bili-Sakura/Latex-Slides-Template-GenAI" style="display: inline-flex; align-items: center; gap: 0.5em; padding: 0.8em 1.5em; background: #4a90e2; color: white; text-decoration: none; border-radius: 6px; font-weight: 500; transition: all 0.2s;">
    <i class="fab fa-github"></i> View on GitHub
  </a>
  <a href="https://github.com/Bili-Sakura/Latex-Slides-Template-GenAI/archive/refs/heads/master.zip" style="display: inline-flex; align-items: center; gap: 0.5em; padding: 0.8em 1.5em; background: #f5f5f5; color: #333; text-decoration: none; border-radius: 6px; font-weight: 500; border: 1px solid #ddd; transition: all 0.2s;">
    <i class="fas fa-download"></i> Download ZIP
  </a>
</div>

## About This Template

The Keynote LaTeX Presentation Template is a modern, clean Beamer theme designed for academic and professional presentations. It features a progress bar, flexible citation management, and support for advanced features like multi-page PDF figures.

This template is production-ready and has been used in real presentations for conferences, research talks, and academic seminars.

## Quick Start

After cloning this repository, follow these simple steps:

### 1. Update Metadata

```latex
\title{Your Presentation Title}
\author{Your Name}
\institute{Your Institution}
\date{\today}
```

### 2. Add Your Content

```latex
% Edit slides.tex
\begin{frame}{Slide Title}
  Your content here
\end{frame}
```

### 3. Compile

```bash
pdflatex keynote.tex
biber keynote
pdflatex keynote.tex
pdflatex keynote.tex
```

## Key Features

- ✨ **Modern design** with progress bar and slide numbers
- 📚 **Advanced citation management** with per-slide references  
- 🖼️ **Multi-page PDF support** with cropping
- 🎨 **Rich content support** (colored boxes, tables, math)

### Advanced Citation Management

One of the standout features is the sophisticated citation system built on top of BibLaTeX:

<div style="background: #f8f9fa; border-left: 4px solid #4a90e2; padding: 1em; margin: 1em 0; border-radius: 4px;">
  <strong>🔬 Research-Focused:</strong> Per-slide references displayed at bottom-left using <code>\bottomleftrefs</code> command, perfect for academic presentations where citing sources on each slide is crucial.
</div>

### Multi-page PDF Support

Academic presentations often need to include specific pages from papers or multi-page figures:

```latex
% Include specific page from a multi-page PDF
\includegraphics[width=0.7\linewidth, page=3]{multipage.pdf}

% Crop specific regions from PDF pages
\adjustbox{width=0.8\linewidth, trim=0 {0.2\height} 0 {0.3\height}, clip}{
  \includegraphics[page=2]{multipage.pdf}
}
```

## Preview

<div style="text-align: center; margin: 2em 0;">
  <div style="border: 2px solid #e8e8e8; border-radius: 6px; overflow: hidden; background: #f9f9f9;">
    <embed src="/assets/blog/latex-slides-template/template-preview.pdf" type="application/pdf" width="100%" height="500px" style="display: block;">
  </div>
  <div style="margin-top: 1em;">
    <a href="/assets/blog/latex-slides-template/template-preview.pdf" download style="display: inline-flex; align-items: center; gap: 0.5em; padding: 0.8em 1.5em; background: linear-gradient(135deg, #dc3545 0%, #c82333 100%); color: white; text-decoration: none; border-radius: 6px; font-weight: 600; transition: all 0.3s;">
      <i class="fas fa-file-pdf"></i> Download Example PDF
    </a>
  </div>
</div>

## Template Structure

The template is thoughtfully structured for easy customization:

```
Latex-Slides-Template-GenAI/
├── keynote.tex              # Main document file
├── slides.tex               # Slide content (edit this)
├── references.bib           # Bibliography database
├── beamerthemeKeynote.sty   # Custom beamer theme
├── keynote.bbx              # Custom bibliography style
├── keynote.cbx              # Custom citation style
├── assets/                  # Images and figures
├── demo/                    # Production examples
└── docs/                    # Comprehensive guide
```

## Documentation

For detailed usage instructions, customization options, troubleshooting, and advanced features, please refer to the [comprehensive guide](https://github.com/Bili-Sakura/Latex-Slides-Template-GenAI/blob/master/docs/GUIDE.md).

The guide includes:
- Complete feature documentation
- Code examples for all template features
- Customization instructions
- Compilation methods and troubleshooting
- Best practices and tips

## Citation

<div style="margin: 1.5em 0; padding: 1em 1.5em; background: #f9f9f9; border-left: 4px solid #4a90e2; color: #555;">
  <p>If you use this template in your work, please cite:</p>
  <pre style="background: #f4f4f4; padding: 1em; border-radius: 4px; overflow-x: auto; margin: 1em 0; font-size: 0.85em;">@misc{sakura2025keynote,
  author = {Sakura},
  title = {Keynote LaTeX Presentation Template},
  year = {2025},
  url = {https://github.com/Bili-Sakura/Latex-Slides-Template-GenAI}
}</pre>
</div>

## Real-World Usage

This template has been used for several production presentations, including academic conference talks, research seminars, and thesis defenses. Check out the `demo/world_models.pdf` example to see advanced features in action.

---

<div style="background-color: #f8f9fa; padding: 1.5em; border-radius: 8px; border-left: 4px solid #4a90e2; margin: 2em 0;">
  <h3 style="margin-top: 0; color: #4a90e2;">🚀 Get Started Today</h3>
  <p><strong>Repository:</strong> <a href="https://github.com/Bili-Sakura/Latex-Slides-Template-GenAI" target="_blank">github.com/Bili-Sakura/Latex-Slides-Template-GenAI</a></p>
  <p><strong>License:</strong> MIT (free for academic and commercial use)</p>
  <p><strong>Requirements:</strong> LaTeX distribution with Beamer, BibLaTeX, and standard packages</p>
</div>

---

<div style="text-align: center; margin: 2em 0; padding: 1em; background: #f5f5f5; border-radius: 4px;">
  <p><em>Happy presenting! 🎤</em></p>
  <p><em>Contact: <a href="mailto:bili_sakura@zju.edu.cn">bili_sakura@zju.edu.cn</a></em></p>
  <p style="font-size: 0.9em; color: #666; margin-top: 0.5em;">© 2025 Sakura</p>
</div>
