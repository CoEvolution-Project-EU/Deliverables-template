# Instructions for Deliverable Setup

Use the following macros to provide the required information in the deliverable (located in the `deliverable.tex` file):

- `\ProjectAcronym{}`: Project acronym.
- `\ProjectFullTitle{}`: Full project title.
- `\ProjectRefNo{}`: Project reference number.
- `\delivWP{}`: The deliverable WP.
- `\delivWPName{}`: The deliverable WP name, as it appears in the DoA.
- `\delivNumber{}`: The deliverable number, Dx.y.
- `\delivName{}`: Deliverable's title, as it appears in the DoA.
- `\delivShortTitle{}`: Short title of the deliverable.
- `\delivResponsible{}`: Responsible partner (participant short name).
- `\delivVersion{}`: Version as vn.n.
- `\ContractualDate{}`: Due date.
- `\ActualDate{}`: Date of submission.
- `\delivDissLevel{}`: Dissemination level (PU or SEN).
- `\delivType{}`: Type of deliverable: Report, Data Management Plan, Demonstrator, or Other.
- `\delivAuthor{}`: Name(s) of the Deliverable Leader(s) (participant short name(s)).
- `\delivFPAuthor{}`: Names of co-authors (participants short names).
- `\delivReviewers{}`: Names of reviewers (participants short names).
- `\delivStatus{}`: Status: (d)raft, (f)inal, or (s)ubmitted.
- `\delivKeywords{}`: List of free keywords relevant to the deliverable.
- `\istChange{}{}{}{}`: For setting deliverable revisions. Arguments: date, version number, author's name, and summary of changes.

### Steps to Follow

1. **Deliverable Setup**  
   The deliverable setup starts from the `deliverable.tex` file. In this file, you have to set the above macros to provide the required information.

2. **Sections of the Deliverable**  
   Inside the `sections` folder, there are various sections of the deliverable. Start with the introduction (`introduction.tex`), then move on to the executive summary (`summary.tex`) and abbreviations (`abbreviations.tex`). Afterward, write the main text in the `mainbodyofthedeliverable.tex` file.

3. **Conclusion and Appendices**  
   Use `conclusion.tex` for the conclusions. For appendices, use `appendix-a.tex` and `appendix-b.tex`.

4. **Note**  
   If you want to exclude a section (e.g., the appendices), comment out the corresponding loader in the `deliverables.tex` file.  
   **Example**: Comment the `\input{sections/appendix-a}` line in the `deliverables.tex` file, and Appendix-A will disappear from the PDF.


## Important!

### Overleaf settings:
- Compiler: pdfLaTex
- TeX Live version: 2020 (Legacy)
