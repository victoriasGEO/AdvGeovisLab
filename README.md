# Personal R Markdown Website Starter (No Gallery)

This starter has **About**, **Analyses**, and **Contact** pages—no gallery. Add photos directly to the About page (`img/` folder).

## Publish steps
1. In RStudio:
   ```r
   install.packages(c("rmarkdown","knitr","ggplot2"))
   rmarkdown::render_site()
   ```
2. Commit everything (including `docs/`) and push to GitHub.
3. Settings → Pages → Deploy from a branch → `main` + `/docs`.
