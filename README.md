# Interlinear

## Overview

**Interlinear** is a LaTeX package designed to facilitate the typesetting of interlinear glossed text, commonly used in linguistic examples. This package provides customizable formatting for interlinear text, allows for the specification of multiple lines with different formatting, and includes options for managing the presentation of context and language information.

The package also supports predefined styles for common use cases, such as glossing text in italics or setting up non-interlinear modes, making it versatile for a variety of linguistic documentation needs.

## Installation

To install this package, follow these steps:

1. **Manual Installation:**
   - Download the package files.
   - Place the `interlinear.sty` file in your LaTeX working directory or a directory that is part of your LaTeX path.

2. **Required Packages:** 
    - marginnote : for marginnotes 
    - xifthen 
    - xkeyval : For key=val options
    - xparse
    - etoolbox
    - enumitem

3. **Using a LaTeX Distribution:**
   - If the package is included in a LaTeX distribution like TeX Live or MikTeX, you can install it using the distribution's package manager.
   - Example (for TeX Live users on Linux):
     ```bash
     sudo tlmgr install interlinear
     ```
   - Example (for MikTeX users on Windows):
     ```bash
     miktex-console
     ```

## Usage

After installation, you can use **Interlinear** in your LaTeX documents by adding the following line in the preamble of your document:

```latex
\usepackage{interlinear}
```

## Basic Example

Here’s a basic usage example:

```latex
\documentclass{article}
\usepackage{interlinear}

\begin{document}

\begin{interlinear}[linesnumber=3,linefourformat=\itshape]
% Interlinear content here
\end{interlinear}

\end{document}
```

## License

This work (this version and later ones) may be distributed and/or modified under the conditions of the LaTeX Project Public License (LPPL), version 1.3c or later.

The latest version of this license is available at: [LaTeX Project Public License](https://www.latex-project.org/lppl/)

This package is maintained (as per LPPL maintenance status) by **Kouamé Josué Akpoué**.

## Contributing

If you would like to contribute to the development of this package, you can do so by:

- Reporting bugs or suggesting features via the issue tracker.
- Submitting pull requests with improvements or bug fixes.

## Contact Information

For any inquiries or support requests, please contact:

**Kouamé Josué Akpoué**  
**Email:** [josueakpoue@gmail.com](mailto: josueakpoue@gmail.com)  
**GitHub:** [https://github.com/dbjoshua](https://github.com/dbjoshua)

## Changelog

### Version 1.0.0 (2024-08-22)

- Initial release.
- Key features include customizable formatting for interlinear text, predefined styles, and margin note customization.
