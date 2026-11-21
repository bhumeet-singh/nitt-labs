# Nitt Labs — Dataset Documentation

## Dataset 01: Shabad OS Database

### Source Information

- Provider: Shabad OS
- Version: 4.8.7
- Release Date: October 15, 2022
- Acquisition Date: November 21, 2026
- Format: SQLite
- File Size: Approximately 151 MB
- Local Path: data/raw/database.sqlite

### References

- Documentation: https://www.shabados.com/docs/database/
- Repository: https://github.com/ShabadOS/Database
- Release: https://github.com/shabados/database/releases/tag/4.8.7

### Intended Research Use

- Gurbani vocabulary frequency analysis
- Gurmukhi character frequency analysis
- Vocabulary coverage across Banis
- Corpus-informed educational curriculum
- Guided Gurbani learning
- Future natural language processing research

### Initial Verification

- Successfully connected using Python's sqlite3 library.
- Established a read-only database connection.
- Retrieved 14 database tables.
- Verified that the database is excluded from Git tracking.

### Data Handling Principles

- Preserve the original database without modification.
- Conduct analysis on separate extracted datasets.
- Maintain source references and attribution.
- Verify applicable licenses before redistribution.
- Document all preprocessing decisions.
- Respect the original context of Gurbani.

### Status

Dataset acquired and connection verified.

Detailed schema exploration and exploratory data analysis
will begin in Phase 3.