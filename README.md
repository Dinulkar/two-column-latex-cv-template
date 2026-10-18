# Two-Column LaTeX CV Template

A professional, customizable, two-page A4 CV/resume template created using LaTeX. The design features a clean two-column layout with a colored sidebar, circular profile picture, and structured sections for personal details, skills, work experience, education, and projects.

## Features

- **Two-column layout** — organized and easy-to-read CV design.
- **A4 page format** — suitable for professional applications.
- **Customizable sidebar** — includes contact details, languages, and skills.
- **Profile photo** — circular portrait image support.
- **Work experience** — highlight responsibilities and achievements.
- **Education** — showcase academic qualifications.
- **Projects** — present technical projects and accomplishments.
- **Clickable links** — add links to LinkedIn, GitHub, and your portfolio.
- **LaTeX-based** — easy to edit, maintain, and compile to PDF.

## Preview

Compile the LaTeX source to generate the CV PDF. Add your own profile image to preview the complete layout.

## Requirements

- A LaTeX distribution, such as TeX Live or MiKTeX, or an Overleaf account.
- A compatible compiler: pdfLaTeX, XeLaTeX, or LuaLaTeX.
- A profile image named `profile.png` in the project directory.

## Getting Started

1. Clone or download this repository.
2. Open `cv-template.tex` in Overleaf or your preferred LaTeX editor.
3. Add your profile image as `profile.png`.
4. Replace the example placeholders with your own information.
5. Customize the skills, experience, education, languages, and projects.
6. Compile the source to generate your PDF CV.

### Compile using the command line

```bash
pdflatex cv-template.tex
```

## Customization

You can personalize the template by editing:

- **Contact details:** Name, email, phone, and professional links.
- **Work experience:** Job titles, companies, dates, and achievements.
- **Education:** Degrees, institutions, and graduation dates.
- **Skills:** Technical tools, programming languages, and relevant competencies.
- **Projects:** Project descriptions, technologies, and outcomes.
- **Colors and styling:** Modify the color definitions, fonts, and spacing in the LaTeX source.
- **Profile photo:** Replace the image with your own portrait.

## Repository Structure

```text
two-column-latex-cv-template/
├── cv-template.tex
├── README.md
└── profile.png
```

The profile image is supplied by the user and does not need to be committed to a public repository.

## Important Notes

- Replace all placeholders before using the CV.
- Review the final PDF for page breaks and spacing after editing.
- Avoid publishing personal contact details or photographs unless you intend to make them public.
- The template is designed for two A4 pages; substantial content changes may require layout adjustments.

## License

A license has not been specified. Add a `LICENSE` file if you intend to grant others permission to reuse or modify the template.
