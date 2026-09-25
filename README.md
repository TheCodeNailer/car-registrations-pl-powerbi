Designed and built an end-to-end Power BI report analyzing 5 years of Polish vehicle registration data (2021-2025, 53,151 rows across 60 source files), covering data engineering, dimensional modeling, DAX and interactive report design.

Highlights:

• Wrote a Python (pandas) script to clean and standardize 60 monthly open-data files — encoding fixes, Polish diacritics normalization, brand-name consolidation — then loaded and shaped the results in Power Query.
• Designed a star-schema data model: 2 fact tables (registrations, population) and 4 dimension tables, plus a 16-measure DAX layer covering YoY / MoM time intelligence and population-normalized KPIs.
• Implemented advanced Power BI features: a field parameter (dynamic month/quarter switch), 2 custom report-page tooltips, conditional formatting (icon sets and a colour-scale choropleth map), and slicers synchronized across pages.
• Ran a self-review pass after initial delivery and fixed 3 measure/visual defects found during QA: a misleading yearly total, a false previous-year comparison, and an uncoloured map.
