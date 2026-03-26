# From Spreadsheets to Scripts: Modernizing IR/IE Workflows with R

**Presented by Logan King [Haywood Community College](https://www.haywood.edu/)**  
**NCAIR 2026 · Technology, Analytics, and Visualization Track**

---

## About

Excel remains the dominant tool for many institutional research and effectiveness tasks, but manual workflows introduce copy-paste errors, version control issues, data size limitations, and tedious processes that consume valuable time. This session demonstrates how R and IDEs like RStudio and Positron can transform common IR/IE processes into reproducible, efficient, and scalable workflows.

Through practical examples, participants see how common IR/IE tasks done in Excel can be seamlessly transformed into an R script or Quarto report. This session provides an honest assessment of both advantages and challenges in transitioning to R, including learning curves, implementation time, and organizational considerations. No programming experience is required!

### Learning Outcomes

1. Evaluate the benefits and trade-offs of transitioning IR/IE workflows from Excel to R.
2. Identify 2–3 IR/IE tasks currently performed in Excel/Sheets that can be migrated to R scripts to improve efficiency and reproducibility.
3. Formulate next steps for beginning your transition from Excel to R.

---

## Slides

📄 **[View the slides (PDF)](NCAIR_2026_Slides.pdf)** — no software installation required.

If you'd like to view or modify the source, the slides are built from [`NCAIR_Spreadsheets_to_Scripts.qmd`](NCAIR_Spreadsheets_to_Scripts.qmd) using [Quarto](https://quarto.org/) and [reveal.js](https://revealjs.com/).

### Rendering the Slides Yourself

1. **Install R** — <https://www.r-project.org/>
2. **Install an IDE** — [RStudio](https://posit.co/products/open-source/rstudio/) or [Positron](https://github.com/posit-dev/positron)
3. **Install Quarto** — <https://quarto.org/docs/get-started/> *Should be installed natively but good to check*
4. **Install required R packages:**

   ```r
   install.packages(c("readxl", "dplyr", "gt", "ggplot2", "scales", "tidymodels", "probably"))
   ```

5. **Clone this repository and render:**

   ```pwsh or bash
   git clone https://github.com/hcc-rlking/ncair-presentation-excel-to-r.git
   cd ncair-presentation-excel-to-r
   quarto render NCAIR_Spreadsheets_to_Scripts.qmd
   ```

   The rendered HTML slides will appear in the project directory.

---

## Code Examples

The R code snippets shown in the slides are **illustrative examples only**. They demonstrate what an R-based workflow *looks like* for common IR/IE tasks, but are not a fully runnable project. The three scenarios covered are:

| Example | Packages Used | Description |
|---|---|---|
| **IPEDS Comparisons** | `readxl`, `dplyr`, `gt` | Read IPEDS enrollment data, compute peer-comparison metrics, and produce a formatted table |
| **SLO Assessment** | `readxl`, `dplyr`, `ggplot2` | Summarize student learning outcome rubric scores and visualize the percentage meeting thresholds |
| **Statistical Analysis** | `readxl`, `tidymodels`, `probably` | Fit a logistic regression model predicting student retention from demographic and academic variables |

> **Coming soon:** A gallery of fully working, self-contained examples is planned for a future update to this repository.

---

## Resources, Tools & Community

### Tools (Free & Open Source)

| Tool | Description |
|---|---|
| [R](https://www.r-project.org/) | Statistical programming language |
| [RStudio](https://posit.co/products/open-source/rstudio/) | Popular IDE for R |
| [Positron](https://github.com/posit-dev/positron) | Next-generation data science IDE by Posit |
| [Quarto](https://quarto.org/) | Open-source publishing system for reports, slides, websites, and more |
| [Shiny](https://shiny.posit.co/) | Framework for building interactive web applications with R |

### Learning

- [R for Data Science (2e)](https://r4ds.hadley.nz/) — free online textbook
- [Quarto Documentation](https://quarto.org/docs/guide/) — official guide

### Community

- [Posit Data Science Hangout](https://posit.co/data-science-hangout/) — weekly virtual meetup
- [ThIRsdays](https://www.reddit.com/r/ThIRsdays/) — community for institutional research professionals using R

---

## Contact

**Logan King**  
Haywood Community College  
📧 [rking3387@haywood.edu](mailto:rking3387@haywood.edu)  
🔗 [LinkedIn](https://www.linkedin.com/in/logan-king-91607b1ab)
