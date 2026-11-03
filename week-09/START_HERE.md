# Week 9: remaining submission steps

Prepared for Noelle Messaoudi. GitHub username: `NawelMe`.

## 1. NY Times API

The source is `nyt_books_api.qmd`. The author is filled in. It compares the latest saved Hardcover Fiction list with the list 52 weeks earlier.

1. Create an account at <https://developer.nytimes.com/>, create an app, and enable the Books API.
2. In RStudio, run this once to install the needed packages:

   ```r
   install.packages(c("dplyr", "tidyr", "readr", "stringr", "ggplot2",
                      "httr", "jsonlite", "knitr", "usethis"))
   usethis::edit_r_environ()
   ```

3. In the file that opens, add `NYT_API_KEY=your_actual_key`. Save and restart R. Do not send the key in chat or commit that file.
4. Open the repository as your RStudio project, open `nyt_books_api.qmd`, and click **Render**. The first render needs the key; later renders use the saved JSON files.
5. Read the resulting tables and conclusions. Commit the `.qmd` and both generated `data/nyt_hardcover-fiction_YYYY-MM-DD.json` files.
6. Submit the `.qmd` as required by the assignment. Your collaborator also asked for RPubs: publish the rendered report using the publishing option available in your RStudio setup. If RPubs is not offered for Quarto HTML, run `rsconnect::rpubsUpload("NYT Hardcover Fiction comparison", "nyt_books_api.html")` after installing `rsconnect`, then finish in the browser. Check the published page before submitting its URL.

The first API run and live numerical conclusions still require your key. No NYT data have been invented or substituted.

## 2. Tidyverse CREATE — due November 15, 2026

The ready source is `vignettes/noelle_m_tidyr_complete.qmd`.

1. Open <https://github.com/acatlin/FALL2026TIDYVERSE/fork> and create the fork under `NawelMe`.
2. On your fork, upload **only** `vignettes/noelle_m_tidyr_complete.qmd` into a `vignettes` folder. Do not upload an HTML file or data files.
3. Your name is missing from the roster. Ask the professor to add your block or identify the correct entry. Do not edit another student block or add a block without resolving this.
4. Once your block exists, change only its Initial line to:

   ```markdown
   Initial Description and Link: Demonstrating `tidyr::complete()` with fish detections and preserving existing missing values — [noelle_m_tidyr_complete.qmd](vignettes/noelle_m_tidyr_complete.qmd)
   ```

5. Sync your fork before opening the PR. Use the title **Initial: Noelle M** and target `acatlin/FALL2026TIDYVERSE`, branch `main`. The PR should contain only the vignette and the change to your README line.
6. Submit your GitHub handle `NawelMe` in the course submission area if requested there.

Do not merge the class pull request yourself.

## 3. Tidyverse EXTEND — due December 6, 2026

This is a separate assignment. After a classmate vignette is merged, choose one that has not already been revised. Edit that existing `.qmd` in place, add annotated code, and update only your own Revision/Addition line. Open a PR titled `Revision: Noelle M edits Firstname L`, then add its PR URL to your own Revision/Addition line.

At the time of this review, the class repository contained no student vignettes to extend.

## Before submitting

Read the code and assistance disclosure. Keep the disclosure consistent with the help actually received and the course policy. The video should be your own explanation. You can explain the NYT report as: request authenticated JSON, validate it, cache it, select and clean fields, then compare two dated snapshots. You can explain the vignette as: missing fish-station rows distort the denominator, `complete()` restores the full grid, and zero means nondetection rather than proven absence.

The supplied DOCX links to Spring 2026. The current Fall repository README is the source for the Fall CREATE/EXTEND workflow.
