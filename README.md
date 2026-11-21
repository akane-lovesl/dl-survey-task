# Deep Learning Frontier Research Survey — Task Brief

## 1. Task Description

- **Task Content**: Choose a cutting-edge research topic in **Deep Learning** and independently write a literature survey report (**at least 5 pages** of main body text, excluding references) in the style of an academic paper. The report should cover a structured review of the field, a critical evaluation and analysis of existing research, and your thoughts on future research directions.
- **Goal**: Practice reading and critically analyzing academic papers, keep up with frontier developments in deep learning, and present technical viewpoints clearly and coherently.
- **Format Requirements**:
  - **Typesetting**: Typeset in **LaTeX** using the provided template in [`Survey_Template/`](./Survey_Template/), and compile with **XeLaTeX**.
  - **Length**: At least **5 pages** of main body text (excluding references).
  - **References**: Cite at least **15** high-quality academic papers, of which at least **10** must be peer-reviewed (non-preprints). Format the bibliography using the template's `bibliography` setup (`natbib` + `apalike`). *(Tip: When both a published version and a preprint version exist for a paper, cite the published version in principle.)*
  - **Language**: Written in **English**, with accurate grammar and clear academic expression.

---

## 2. Evaluation Rubric (100 Points — Quality Self-Check Guide)

### 1. Writing Quality (30 pts)
- **27–30 pts**: Well-structured with clear hierarchy, coherent organization, and sharp arguments. Fluent, academic prose with few grammar or spelling errors. Figures and tables are informative, visually clean, and self-created.
- **23–26 pts**: Mostly complete structure with minor abrupt transitions between paragraphs. Reasonably organized with fairly clear arguments and occasional grammar/spelling errors. Figures and tables are informative and neat, though a notable portion are not self-created. *(Tip: Formal academic papers generally do not directly reuse figures from other papers; since this is a technical survey exercise, existing figures may be used sparingly with proper citation to manage workload, though heavy reuse will reduce the score.)*
- **19–22 pts**: Basic structure exists, but suffers from stacked paragraphs or over-fragmentation. Expression lacks clarity though remains understandable. Very few or poorly organized figures/tables.
- **≤ 18 pts**: Missing structure, unclear expression, or missing figures/tables.

### 2. Content Depth (30 pts)
- **27–30 pts**: Comprehensive understanding and deep analysis of the state of the art in the chosen topic. Clear judgment on the strengths and limitations of existing methods, offering original insights and a thoughtful outlook on future directions.
- **23–26 pts**: Broad understanding and solid analysis of current research. Fairly clear assessment of existing strengths and limitations, with some outlook on future directions.
- **19–22 pts**: General/surface-level understanding of current research; lacks clear judgment on existing work and offers no future outlook.
- **≤ 18 pts**: Largely meaningless compilation lacking depth, or significantly shorter than the required length.

### 3. Reference Quality & Citations (15 pts)
- **13–15 pts**: Most references come from reputable journals or conferences, are timely and relevant, and use accurate citation formatting.
- **10–12 pts**: Many references come from non-authoritative venues or are preprints; moderate timeliness and relevance; occasional citation formatting errors.
- **7–9 pts**: Fewer references than required, or frequent citation formatting errors.
- **≤ 6 pts**: Significantly fewer references than required, or cites non-existent / unverifiable fabricated references.

### 4. LaTeX Typesetting Proficiency (15 pts)
- **13–15 pts**: Uses the provided template properly with standard formatting for equations, figures, tables, and references. Demonstrates strong command of LaTeX with a comfortable, compact layout and effective use of LaTeX techniques beyond the template defaults.
- **10–12 pts**: Uses the provided template with mostly standard formatting for equations, figures, tables, and references. Shows reasonable familiarity with LaTeX and comfortable layout overall, though content is somewhat loose and uses no extra LaTeX techniques beyond the template.
- **7–9 pts**: Did not use the provided template (with no other obvious issues), or used the provided template with messy content/layout.
- **≤ 6 pts**: Neither used the provided template nor kept the layout orderly.

### 5. Originality & Independent Thinking (10 pts)
- **9–10 pts**: Offers original insights on the research topic and demonstrates independent critical thinking throughout the survey.
- **7–8 pts**: Understands the topic correctly, but lacks depth or personal insights.
- **≤ 6 pts**: Misunderstands the topic, or remains overly generic/superficial.

---

## 3. Output Format & Academic Practice

- **Output Format**: Compile into a **PDF** Survey document (e.g., `Survey.pdf`) using [`Survey_Template/`](./Survey_Template/) via **XeLaTeX**.
- **Academic Practice**: Focus on digesting and synthesizing original papers in your own words; always cite sources accurately when referencing others' ideas, figures, or results, and ensure all cited literature is real and verifiable.

---

## 4. Quick Start (Compiling the Template)

### Local Compilation (TeX Live / MiKTeX)
```bash
cd Survey_Template
xelatex main.tex
bibtex main
xelatex main.tex
xelatex main.tex
```

### Overleaf
1. Upload the contents of [`Survey_Template/`](./Survey_Template/) to a new Overleaf project.
2. Open **Menu → Compiler** and set it to **XeLaTeX**.
3. Edit the title variables at the top of `main.tex` and replace the example sections and `Paper_summaries.bib` entries with your survey content.
