# CV

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![LaTeX](https://img.shields.io/badge/built%20with-LaTeX-ff69b4.svg)](https://www.latex-project.org/)

This repository contains the LaTeX source code and compiled PDF of my CV. The CV is designed to showcase my academic and professional accomplishments, skills, and experiences.

## Table of Contents

- [Content](#content)
- [Getting Started](#getting-started)
- [Building the CV](#building-the-cv)
- [Customization](#customization)
- [License](#license)


## Content

The CV is divided into sections that typically include:

- Contact Information
- Education
- Projects
- Skills

The template is flexible and can be customized to fit individual preferences and needs.

## Getting Started

To get started, you need to have a LaTeX distribution installed on your system. If you don't have one, you can download and install [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/).

Once you have a LaTeX distribution installed, you can clone this repository using the following command:

```
git clone https://github.com/dmhd6219/cv.git
```

## Building the CV

### For English Version:
1. Edit the `eng.tex` file using a text editor of your choice.
2. Customize the content in each section to match your personal information, education, experience, etc.
3. Save your changes.

In your terminal, navigate to the repository directory and run the following commands to compile the CV:

```bash
pdflatex eng.tex
```

This will generate a `eng.pdf` file in the same directory.

### For Russian Version:
1. Edit the `rus.tex` file using a text editor of your choice.
2. Customize the content in each section to match your personal information, education, experience, etc.
3. At `layout.tex` uncomment `5`, `8`, `10`, `11` lines.
4. At `macros.tex` uncomment `37` line.
5. At `macros.tex` comment `38` line.
6. Save your changes.

In your terminal, navigate to the repository directory and run the following commands to compile the CV:

```bash
pdflatex rus.tex
```

This will generate a `rus.pdf` file in the same directory.

## Customization

The template is designed to be highly customizable. You can adjust the styling, fonts, colors, and layout to your liking by modifying the LaTeX code in the `main.tex` file. Additionally, you can explore LaTeX documentation and tutorials to learn more about advanced customization.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to use, modify, and distribute this template to create your own CV. If you find any issues or improvements, contributions are welcome! Just fork the repository, make your changes, and create a pull request.
