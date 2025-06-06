# CV Project Index

## Project Overview
This is a comprehensive LaTeX-based curriculum vitae (CV) for Jorge J. Ortiz, Associate Professor at Rutgers University. The project uses multiple bibliography files to organize different types of publications and achievements.

## File Structure

### Main Document Files
- **`main.tex`** (11KB, 242 lines)
  - Primary CV document with complete formatting and structure
  - Contains personal information, education, appointments, experience, honors, grants, students, and publications
  - Uses custom styling with blue color scheme and professional formatting
  - Includes comprehensive sections for academic career

- **`_main.tex`** (2.7KB, 55 lines)
  - Alternative/simplified main file
  - Focuses on publications and synergistic activities
  - Contains different publication categorization (most related vs. other significant)
  - Includes detailed synergistic activities section

- **`00_cv.tex`** (5.4KB, 147 lines)
  - Standalone CV document
  - Organizes publications by type with detailed enumeration
  - Includes acceptance rates and award notifications
  - Covers: Under Submission, Conferences/Journals, Workshops/Posters, Theses, Patents

- **`pubs.tex`** (6.0KB, 143 lines)
  - Publications input file (referenced by main.tex)
  - Contains formatted publication listings

### Bibliography Files
- **`publications.bib`** (21KB, 516 lines)
  - Main bibliography database
  - Contains complete publication entries

- **`10_workshops.bib`** (51KB, 605 lines)
  - Workshop presentations, posters, and technical reports
  - Largest bibliography file with extensive workshop participation

- **`11_conf-journ.bib`** (30KB, 387 lines)
  - Conference and journal publications
  - Peer-reviewed academic publications

- **`12_publications.bib`** (642B, 20 lines)
  - Minimal publication entries
  - Possibly a subset or specific category

- **`20_under-submission.bib`** (9.6KB, 85 lines)
  - Manuscripts currently under review
  - Work in progress publications

- **`30_patents.bib`** (4.9KB, 160 lines)
  - Patent applications and granted patents
  - Intellectual property documentation

## Content Organization

### Academic Profile
- **Education**: UC Berkeley (PhD, MS Computer Science), MIT (BS Computer Science)
- **Current Position**: Associate Professor, Rutgers University (2025-present)
- **Previous Roles**: Assistant Professor, AI Lead at NY Yankees, IBM Research

### Key Achievements
- Multiple Best Paper Awards and Finalist recognitions
- NSF and NIH grant funding (multi-million dollar projects)
- Extensive invited speaking engagements
- Ph.D. student supervision and mentorship
- Significant patent portfolio (12+ patents)

### Publication Categories
1. **Under Submission** (4 papers)
2. **Conferences and Journals** (15+ papers with acceptance rates)
3. **Workshops and Posters** (25+ presentations)
4. **Theses** (PhD and Masters)
5. **Patents** (12 issued patents)

### Technical Features
- **Bibliography Management**: Uses `bibentry` and `natbib` packages
- **Formatting**: Custom styling with `titlesec`, `geometry`, and `hyperref`
- **Color Scheme**: Professional blue (`mBlue` RGB: 51, 77, 167)
- **Layout**: Single-spaced, 12pt font, professional margins
- **Hyperlinks**: Functional email and web links

## Usage Instructions

### Compilation Order
1. Run LaTeX to generate `.aux` file
2. Run BibTeX to generate `.bbl` file
3. Run LaTeX again to incorporate bibliography

### File Dependencies
- Main documents reference bibliography files
- `pubs.tex` is input by `main.tex`
- All `.bib` files are referenced by bibliography commands

## Maintenance Notes
- Update bibliography files when new publications are added
- Modify `main.tex` for structural changes
- Use `00_cv.tex` for publication-focused versions
- Maintain consistent formatting across all files

## Key Research Areas
Based on publication titles and content:
- Multimodal Learning and AI
- Human-Computer Interaction
- IoT and Smart Environments
- Computer Vision and Sensing
- Machine Learning Applications

## Contact Information
- **Email**: jortiz@alum.mit.edu
- **Website**: http://jorgeortizphd.info
- **Phone**: 617-784-6550
- **Institution**: Rutgers University, Electrical and Computer Engineering 