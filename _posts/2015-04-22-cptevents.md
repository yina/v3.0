---
layout: page
title: "CPTEVENTS"
category: dat
date: 2015-04-22 22:45:09
order: 5
---

## ```CPTEVENTS``` table

The ```CPTEVENTS``` table is new to v3.0 of the MIMIC-II database.

Column name | Data type | New column | Remarks
--- | --- | --- | ---
```SUBJECT_ID``` | NUMBER(7)  | Y  | Foreign key.
```HADM_ID``` | NUMBER(7) | Y  | Foreign key.
```CPT_CD``` | VARCHAR2(8)  | Y  | ?
```CPTEVENTSDATAID``` | NUMBER  | Y  | Unique row identifier

