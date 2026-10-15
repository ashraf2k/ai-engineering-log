# Week 2 — Pandas + data cleaning notes

## Pandas commands I'll use for the tickets
- `df.info()` — columns, types, non-null counts
- `df.isnull().sum()` — missing values per column
- `df.groupby('queue').size()` — tickets per team
- `df['col'].value_counts()` — how often each label appears
- `df.drop_duplicates(subset=[...])` — remove duplicate rows
- `df['col'].str.lower().str.strip()` — clean inconsistent text

## Missing values: drop or fill?
- Drop when: ...
- Fill when: ...

## One thing that surprised me
- ...