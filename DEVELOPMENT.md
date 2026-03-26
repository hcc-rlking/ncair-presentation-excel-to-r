## From Spreadsheets to Scripts: Modernizing IR/IE Workflows with R
### Presentation Progress Tracker for NCAIR 2026
#### Proposal
- Lead Presenter: Logan King
- Email: rking3387@haywood.edu
- Professional Affiliation: Haywood Community College
- Title: From Spreadsheets to Scripts: Modernizing IR/IE Workflows with R
- Track: Technology, Analytics, and Visualization
- Presentation Format: Speaker Presentation
- 2-3 Learning Outcomes
    1. Following this presentation, participants will be able to evaluate the benefits and trade-offs of transitioning IR/IE workflows from Excel to R.
    2. Following this presentation, participants will be able to identify 2-3 IR/IE tasks currently performed in Excel/Sheets that can be migrated to R scripts to improve efficiency and reproducibility.
    3. Following this presentation, participants will be able to formulate next steps for beginning their transition from Excel to R.
- Abstract:
Excel remains the dominant tool for many institutional research and effectiveness tasks, but manual workflows introduce copy-paste errors, version control issues, data size limitations, and tedious processes that consume valuable time. This session will demonstrate how R and IDE's like RStudio and Positron can transform common IR/IE processes into reproducible, efficient, and scalable workflows. Through practical examples, participants will see how common IR/IE tasks done in Excel can be seamlessly transformed into an R script or Quarto report. Attendees will learn to identify which of their own workflows could be migrated based on factors like repetition frequency, data volume, and error risk. This session provides an honest assessment of both advantages and challenges in transitioning to R, including learning curves, implementation time, and organizational considerations. No programming experience is required! Participants will leave with resources and actionable first steps to begin their Excel-to-R transition.
 
### Expected Output:
- Slides using NCAIR_Spreadsheets_to_Scripts.qmd and revealjs for HTML output.
- Real IE/IR Examples done in Excel for slide screenshots.
- Code examples of how to do the same things as in Excel in R


### Slides Overview

| # | Slide Title | Purpose |
|---|---|---|
| 1 | A little about Haywood CC | Introduces the presenter's institution with key stats |
| 2 | Is This You? | Opening hook — audience relates to common Excel frustrations |
| 3 | Session Overview | Sets expectations with three learning outcomes |
| 4 | A Quick Note on What This Session is NOT | Clarifies this is not a coding workshop; focus is on concepts and next steps |
| 5 | The Reality of IR/IE Workflows in Excel | Names specific pain points (reproducibility, version control, errors, scalability, etc.) |
| 6 | What's the Fix? | Transition slide signals the shift from problems to solutions |
| 7 | From Spreadsheets to Scripts | Side-by-side table mapping each Excel challenge to its R solution |
| 8 | The Core Toolkit | Introduces R, RStudio/Positron, Quarto, and Shiny |
| 9 | Live Examples: Excel → R | Section divider for the demo portion |
| 10 | Example 1: IPEDS Comparisons | Excel vs. R workflow comparison — readxl + dplyr + gt |
| 11 | Example 1: Potential Output | Screenshot of formatted IPEDS comparison table |
| 12 | Example 2: SLO Assessment | Excel vs. R workflow comparison — readxl + dplyr + ggplot2 |
| 13 | Example 2: Potential Output | Screenshot of SLO assessment chart |
| 14 | Example 3: Statistical Analysis | Excel vs. R workflow comparison — readxl + tidymodels + probably |
| 15 | Example 3: Potential Outcome | Screenshot of Shiny dashboard output |
| 16 | Benefits *and* Tradeoffs | Honest two-column comparison of advantages and challenges |
| 17 | First Steps for Your Own Transition | Practical migration strategy and organizational buy-in tips |
| 18 | Resources, Tools, and Community | Links to tools, learning resources, communities, and AI assistants |
| 19 | Q&A | Open floor for questions |
| 20 | Thank You! | Contact info (LinkedIn, email) |

---

### Tracking

#### Slide Content
- [x] About Haywood CC
- [x] Opening hook (Is This You?)
- [x] Session Overview / Learning Outcomes
- [x] "Not a coding workshop" disclaimer
- [x] Excel pain points slide
- [x] Transition slide (What's the Fix?)
- [x] Excel → R solutions table
- [x] Core toolkit slide (R, RStudio, Positron, Quarto, Shiny)
- [x] Example 1: IPEDS Comparisons
- [x] Example 1: Potential Output
- [x] Example 2: SLO Assessment
- [x] Example 2: Potential Output
- [x] Example 3: Statistical Analysis
- [x] Example 3: Potential Outcome
- [x] Benefits and Tradeoffs
- [x] First Steps for Your Own Transition
- [x] Resources, Tools, and Community
- [x] Q&A slide
- [x] Thank You / Contact slide

#### Screenshots & Assets
- [x] Gemini-generated opening image (`Gemini_Generated_Image_mnzcyumnzcyumnzc.png`)
- [x] Reddit R code image (`r_code_1.png`)
- [x] HCC campus photo (`niceHCCpic.jpeg`)
- [x] Broken Excel image (`brokenexcel.png`)
- [x] HCC hex logo (`HCC_Hex.png`)
- [x] Toolkit logos (R, RStudio, Positron, Quarto, Shiny)
- [x] Excel-to-R transition image (`excel_to_r.jpg`)
- [x] Example 1 output screenshot (`example1_ipeds_table.png`)
- [x] Example 2 output screenshot (`example2_slo_chart.png`)
- [x] Example 3 output screenshot (`example3_shiny_dashboard.png`)

#### Code Examples
- [x] IPEDS Comparisons R snippet (readxl + dplyr + gt)
- [x] SLO Assessment R snippet (readxl + dplyr + ggplot2)
- [x] Statistical Analysis R snippet (readxl + tidymodels + probably)

#### Final Checks
- [x] Speaker notes for all slides
- [x] `_brand.yml` theming
- [x] Dry run / timing check
- [x] Final render and review


---

### Future Work: Examples Gallery

- [ ] Create a self-contained `examples/` directory with runnable R scripts and sample data for each scenario
- [ ] IPEDS Comparisons — full pipeline from raw Excel to formatted `gt` table
- [ ] SLO Assessment — rubric data intake through `ggplot2` visualization
- [ ] Statistical Analysis — retention modeling with `tidymodels` and a Shiny dashboard
- [ ] Other community sourced IR/IE in R examples!
- [ ] Add a README inside `examples/` with instructions for running each example independently