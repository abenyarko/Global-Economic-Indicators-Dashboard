# Technical implementation

## Architecture
The project README describes World Bank REST API endpoints (country metadata, GDP, GDP per capita, population), a country metadata CSV, and a NASA global temperature dataset. Data are prepared using Power Query, modeled in Power BI, and presented through interactive reports.

```text
World Bank APIs ───────┐
Country metadata CSV ──┼──> Power Query (ingest / transform) ──> Power BI semantic model ──> DAX / report visuals
NASA temperature data ─┘
```

This is an architectural summary based on the published project description, not a claim that source queries or a model file are published here.

## Reproducibility checklist
- [ ] Record the exact source URLs, indicator codes, query parameters, and access dates.
- [ ] Export and document the Power Query M transformations, including join keys and type conversions.
- [ ] Document country identifiers, region mapping, calendar table, relationships, and filter direction.
- [ ] Export actual DAX measures and describe filter context and units.
- [ ] Document refresh settings, missing values, and how aggregates are excluded from country-level comparisons.
- [ ] Describe the NASA temperature dataset's role in the model, if used in published visuals.
- [ ] Add a sanitized PBIX/PBIT or other reproducible artifact if redistribution is permitted.
- [ ] Validate headline figures against the corresponding source-year values.

## Quality considerations
World Bank indicators can have different reporting years, missing country observations, revisions, and regional aggregate entries. GDP and GDP per capita must not be summed or averaged indiscriminately across time. Country comparisons should make the currency basis and reference year explicit. Population-weighted and unweighted per-capita comparisons answer different questions.

## Evidence status
The repository currently provides the project narrative and dashboard screenshots. Query source code, model definitions, and actual DAX expressions should be added from the working Power BI project; this document does not invent them.
