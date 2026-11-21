# Nitt Labs — Research & Development Log

## Project Information

**Project:** Nitt (ਨਿੱਤ)

**Researcher:** Bhumeet Singh Bhatia

**Institution:** University of Massachusetts Amherst

**Start Date:** November 21, 2026

**Research Areas:** Data Science, Machine Learning, Natural
Language Processing, Educational Technology

## Research Objectives

1. Conduct computational analysis of Gurbani vocabulary.
2. Develop a corpus-informed Gurmukhi learning curriculum.
3. Investigate predictive models for vocabulary recall.
4. Develop an experimental adaptive learning system.
5. Integrate research findings into an accessible Sikh
   educational platform.

---

## Entry 001 — November 21, 2026

### Objective

Establish the project identity, research direction,
development roadmap, and technical environment.

### Work Completed

- Audited the existing Nitnem Tracker application.
- Selected Nitt as the working brand name.
- Defined the January beta scope.
- Identified potential research datasets.
- Established preliminary research questions.
- Created the Nitt Labs GitHub repository.
- Created the research directory structure.
- Configured Python 3.14.6 and a virtual environment.
- Installed data science and machine learning libraries.
- Successfully tested the Jupyter Notebook environment.
- Created the project README.

### Key Decisions

- Prioritize computational Gurbani analysis and adaptive
  Gurmukhi learning for the initial beta.
- Use Python for data processing and machine learning.
- Preserve the existing application architecture where practical.
- Prioritize privacy, accessibility, and verified Gurbani sources.
- Defer Sangat circles and journaling until after the initial beta.
- Schedule development around academic commitments.

### Results

The initial development environment is operational.

No dataset analysis or machine learning experiments have
been conducted yet.

### Challenges and Limitations

- Limited development time before the January 19 deadline.
- Upcoming examinations and academic commitments.
- Dataset licensing and provenance require verification.
- Educational content requires knowledgeable review.
- External learning models may not generalize to Gurbani learners.

### Next Steps

- Verify and acquire the initial Gurbani dataset.
- Inspect its structure and available variables.
- Establish a reproducible data processing workflow.
- Begin exploratory data analysis.

---

## Entry 002 — November 21, 2026

### Objective

Acquire and verify the first Gurbani dataset for Nitt Labs.

### Work Completed

- Downloaded Shabad OS Database version 4.8.7.
- Stored the original SQLite database in data/raw/.
- Updated .gitignore to exclude local datasets.
- Established a read-only SQLite connection using Python.
- Successfully retrieved 14 database tables.
- Created the initial Gurbani exploration notebook.
- Documented dataset provenance in dataset_sources.md.

### Results

The Gurbani database is accessible through Python and Jupyter.
The database contains tables for Gurbani lines, Banis,
translations, transliterations, writers, and source metadata.

### Next Steps

- Explore the database schema.
- Examine individual tables and their relationships.
- Extract Gurbani text for computational analysis.
- Evaluate data quality and preprocessing requirements.
- Begin exploratory data analysis in Phase 3.

---D