## From Spreadsheets to Scripts: Modernizing IR/IE Workflows with R
### Presentation for NCAIR 2026
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
- Slides using NCAIR_Presentation.qmd and revealjs for HTML output.
- Real IE/IR Examples done in Excel for slide screenshots.
- Code examples of how to do the same things as in Excel in R
 
### Slides flow:
- Title/Introduction: Title and Intro of Presenter
- Is this you? Do you have a problem with Excel or Spreedsheets? Well do I have a solution for you!
- Session Overview: What will attendees leave with. What the session will be and what it won't be
    - It will be a great intro to the value of R and how simple it can be (not hiding that more complex stuff can be hard)
    - It will not be a coding workshop where I actually show people how to code, We are just showing example code and output, not letting them code or teaching them exactly what something does. (There will be code on the screen, we just won't go into great detail)
- The Reality of IR/IE Workflows in Excel: Explanation of how IR/IE professionals use Excel day to day. Getting them to relate to the potential struggles with using excel. Those include reproducibility, scalability, version control, etc.
- From Spreadsheets to Scripts: High level explanation of why R can change those workflows to fix struggles with excel. How switching can allow for you to have reproducible reports and data management tools at scale. How things like Quarto, Shiny, and other tools can expand the offerings of your data work.
- Live Examples: Excel -> R: Explaining a task, showing that task in excel and what challenges might arise, then showing that same task in R. I want to have 3-4 examples that include IR tasks such as IPEDS reporting and executive Team reports, as well as IE tasks like general education assessment reporting and reproducable data summaries for program review/unit review/self studies.
- Benefits *and* Tradeoffs: Explaining that there are great benefits while being realistic about the tradeoffs/challenges such as learning R, getting it adopted(issues with IT for example), etc.
- First Steps for your own transition: How to decide what can and should be migrated. How to approach migrating tasks. How to gain adoption of a new/different tool.
- Resources, Tools, and Community: Give links, Mention suggested tools (R, Rstudio/Positron, Quarto, Shiny, coding agents/ai assistants etc.), talk about ThIRsday's by David Eubanks at Furman University and the communities managed by Posit.
#### Slides Todo:

| Slide Name              | Created | Draft 1  | Notes and Review | Final |
|-------------------------|---------|----------|------------------|-------|
| Title Slide             | [ x ]   | [ x ]    |  [  ]            | [  ]  |
| Is this you?            | [ x ]   | [ x ]    |  [  ]            | [  ]  |
| Reality of Excel        | [ x ]   | [  ]     |  [  ]            | [  ]  |
| Spreedsheets to Scripts | [ x ]   | [  ]     |  [  ]            | [  ]  |
| Live Examples           | [ x ]   | [  ]     |  [  ]            | [  ]  |
| B&T                     | [ x ]   | [  ]     |  [  ]            | [  ]  |
| First Steps             | [ x ]   | [ x ]    |  [  ]            | [  ]  |
| Resources               | [ x ]   | [ x ]    |  [  ]            | [  ]  |
| Q&A                     | [ x ]   | [ x ]    |  [ x ]           | [ x ] |
| Contact                 | [ x ]   | [ x ]    |  [ x ]           | [ x ] |
 
### Examples:
#### Example 1: IPEDS Reporting
 
**Task Description:**  
Compile and summarize institutional data for IPEDS submission.
 
**Excel Workflow:**  
- Manual data entry and aggregation  
- Copy-paste between sheets  
- Risk of formula errors and inconsistent updates  
- Limited reproducibility
 
**R Workflow:**  
- Automated data import and cleaning  
- Scripted aggregation and summary  
- Reproducible output for each reporting cycle  
- Scalable for future years
 
**Data/Code Notes:**  
- Simulated student enrollment dataset  
- R script for summary tables  
- Placeholder: [Screenshot Excel] [Code Example R]
 
---
 
#### Example 2: Executive Team Reports
 
**Task Description:**  
Generate regular summary reports for leadership.
 
**Excel Workflow:**  
- Manual updates to charts and tables  
- Version control issues  
- Tedious formatting
 
**R Workflow:**  
- Dynamic report generation with Quarto  
- Automated chart creation  
- Consistent formatting and versioning
 
**Data/Code Notes:**  
- Simulated program enrollment and outcomes  
- Quarto template for report  
- Placeholder: [Screenshot Excel] [Code Example R]
 
---
 
#### Example 3: General Education Assessment
 
**Task Description:**  
Summarize assessment results for gen ed outcomes.
 
**Excel Workflow:**  
- Data entry from multiple sources  
- Manual calculation of summary statistics  
- Error-prone and hard to audit
 
**R Workflow:**  
- Data merging and cleaning  
- Automated summary statistics  
- Transparent, auditable workflow
 
**Data/Code Notes:**  
- Simulated assessment results  
- R script for summary and visualization  
- Placeholder: [Screenshot Excel] [Code Example R]
 
---
 
#### Example 4: Program Review Data Summaries
 
**Task Description:**  
Prepare reproducible data summaries for unit/program review.
 
**Excel Workflow:**  
- Multiple versions of files  
- Manual updates and risk of outdated data  
- Difficult to scale
 
**R Workflow:**  
- Centralized data source  
- Scripted summaries and visualizations  
- Easy updates and scalability
 
**Data/Code Notes:**  
- Simulated program review dataset  
- R script for summary tables and plots  
- Placeholder: [Screenshot Excel] [Code Example R]
 
---
 
#### Example Development Checklist
 
| Example                | Excel Screenshot | R Code Example | Simulated Data | Name of File in Data folder |
|------------------------|-----------------|---------------|---------------|-------------|
| IPEDS Reporting        | [ ]             | [ ]           | [ ]           | |
| Executive Team Reports | [ ]             | [ ]           | [ ]           | |
| Gen Ed Assessment      | [ ]             | [ ]           | [ ]           | |
| Random Picture Data    | [ ]             | [ ]           | [x]           | data_example_1.xlsx |
 
---
 
**Note:** Examples are linked to slide topics and learning outcomes. All data will be simulated for demonstration.
 
 