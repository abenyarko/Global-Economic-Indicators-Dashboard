# Data sources and dictionary

Sources described in the project README:
- World Bank Country API
- World Bank GDP indicator
- World Bank GDP per capita indicator
- World Bank Population indicator
- Country metadata CSV
- NASA global temperature dataset

## To document
Record indicator codes, source links, definitions, measurement units, date coverage, geographic coverage, data refresh date, and any licensing or attribution requirements.

| Field | Definition | Source | Unit / format | Notes |
|---|---|---|---|---|
| GDP | Economic output | World Bank | Confirm currency basis | Confirm current vs constant |
| GDP per capita | Economic output per person | World Bank | Confirm currency basis | Not additive |
| Population | Population estimate | World Bank | Persons | Specify year |
| Population density | Population per land area | Confirm source / derivation | Persons per sq. km | Verify denominator |
| Region | Geographic grouping | Country metadata | Category | Document mapping |
| Year | Reference period | Source indicators | Year | Check differing coverage |

This table is a documentation starter, not an audited data dictionary.
