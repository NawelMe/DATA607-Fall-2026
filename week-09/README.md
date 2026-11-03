# DATA 607, Week 9 — Noelle Messaoudi

**Published report:** [NYT Hardcover Fiction Best Sellers: A Year Apart](https://rpubs.com/NoelleMe/1473089)

Start with [START_HERE.md](START_HERE.md) for the remaining account and submission steps.

- [nyt_books_api.qmd](nyt_books_api.qmd): NYT Books API report. Store the private Books API key in `NYT_API_KEY`; the first run saves two dated JSON responses in `data/`. Later renders reuse them by default. The two JSON responses used for this report are saved in `data/`.
- [vignettes/noelle_m_tidyr_complete.qmd](vignettes/noelle_m_tidyr_complete.qmd): revised Tidyverse CREATE source. Submit this `.qmd` through **your own fork** of `acatlin/FALL2026TIDYVERSE`, not from this Week 9 repository.

## Validation and status

- The revised Tidyverse source rendered successfully with Quarto and the built-in `fish_encounters` data.
- The NYT report rendered successfully using the saved responses for November 8, 2026 and November 9, 2025. Earlier checks confirmed cached renders avoid API calls even with a key, and missing credentials and malformed responses fail clearly.
- The NYT report is published on RPubs at the link above. The saved JSON responses allow the report to be rendered without an API key.
- No class fork or class pull request has been created. Noelle/Nawel was missing from the Fall roster when checked; resolve the roster entry before editing the README. No other student block has been changed.
- CREATE is due November 15, 2026; EXTEND is due December 6, 2026, according to the Fall repository README. EXTEND requires a merged classmate vignette; none was available when checked.

Review the source, rendered output, and assistance disclosure before submitting. Record your own explanation if a video is required.
