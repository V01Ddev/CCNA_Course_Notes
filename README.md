# CCNA Course Notes

My notes from Jeremy's IT Lab [Complete Course for the CCNA 200-301](https://www.youtube.com/watch?v=H8W9oMNSuwo&list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ),
compiled into a single LaTeX report.

The finished document is **`main.pdf`**. The markdown notes it is built from
live in `Course_Notes/`; `main.tex`, `chapters/`, `images/` and `tools/` are
what turns them into that PDF.

Forked from [psaumur/CCNA_Course_Notes](https://github.com/psaumur/CCNA_Course_Notes).

## Building

```sh
python3 tools/fetch_images.py     # downloads the diagrams (once)
python3 tools/build_chapters.py   # markdown -> chapters/*.tex
latexmk -pdf main.tex
```
