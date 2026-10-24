# Build a Large Language Model (From Scratch)

My follow-along Quarto notebooks (plus experiments) for Sebastian Raschka's book.

## Data

`data/raw/the_verdict.txt` — short story used as the training text in Ch. 2. Never modify.

## How to run

Notebooks live in `notebooks/` as `.qmd` (one per chapter) and run from that folder, so data paths are `../data/raw/...`.
Open in Positron/VS Code and run cells, or render:

```bash
uv run quarto render notebooks/ch02_working_with_text_data.qmd
```

## Notes

- Rendered `.html` and `*_files/` are git-ignored; regenerate as needed.
- Figures go in `notebooks/images/`.
- Progress: Ch. 2 done, Ch. 3 in progress (through 3.4).
