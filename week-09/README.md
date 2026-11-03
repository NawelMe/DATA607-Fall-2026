# DATA 607, Week 9 — Noelle Messaoudi

Start with [START_HERE.md](START_HERE.md) for the remaining account and submission steps.

- [nyt_books_api.qmd](nyt_books_api.qmd): NYT Books API report. Store the private Books API key in `NYT_API_KEY`; the first run saves two dated JSON responses in `data/`. Later renders reuse them by default. Commit those JSON files after the first live run.
- [vignettes/noelle_m_tidyr_complete.qmd](vignettes/noelle_m_tidyr_complete.qmd): revised Tidyverse CREATE source. Submit this `.qmd` through **your own fork** of `acatlin/FALL2026TIDYVERSE`, not from this Week 9 repository.

## Validation and status

- The revised Tidyverse source rendered successfully with Quarto and the built-in `fish_encounters` data.
- The NYT source rendered successfully in a separate temporary directory with synthetic test responses. Checks confirmed cached renders avoid API calls even with a key, and missing credentials and malformed responses fail clearly. **Test data are not included in this repository or presented as NYT findings.**
- Live NYT authentication and data retrieval still require the student API key. RPubs publication is outstanding.
- No class fork or class pull request has been created. Noelle/Nawel was missing from the Fall roster when checked; resolve the roster entry before editing the README. No other student block has been changed.
- CREATE is due November 15, 2026; EXTEND is due December 6, 2026, according to the Fall repository README. EXTEND requires a merged classmate vignette; none was available when checked.

Review the source, rendered output, and assistance disclosure before submitting. Record your own explanation if a video is required.
