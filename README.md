# LaTeX Coursework

Homework write-ups for university courses, typeset in LaTeX.

## Structure

- [`MATH309/`](MATH309/) — Math 309 (Introduction to Mathematical Proofs) homework assignments
- [`CSCE235/`](CSCE235/) — CSCE 235 (Introduction to Discrete Structures) homework assignments

Each `.tex` file is a standalone homework assignment; compiled PDFs are kept alongside their source. Build artifacts (`build/`) are gitignored.

## Building

Each course directory has its own `.latexmkrc` that sends auxiliary files to `build/` and keeps the compiled PDF in the course directory alongside the source. Requires `latexmk` and a `TeX distribution` on your `PATH`.