# Split Notebooks

These focused notebooks were split from `../PersonaMatch.ipynb` without re-running any cells. Existing outputs, execution counts, and notebook metadata were preserved from the original Databricks run.

Recommended review order:

1. `01_ingest.ipynb` - setup, GloVe loading, and raw city data loading.
2. `02_external_eda.ipynb` - external review and rating analysis.
3. `03_etl_pipeline.ipynb` - external and internal data cleaning, parsing, and preparation.
4. `04_persona_lexicon.ipynb` - persona dictionaries and phrase-based word clouds.
5. `05_scoring_model.ipynb` - vectorization, spatial joins, persona scoring, and internal-only scoring.
6. `06_visual_insights.ipynb` - score impact analysis, persona distributions, heatmaps, zones, KDE plots, and interactive maps.

The root `PersonaMatch.ipynb` remains the preserved original and can be deleted later only after the split notebooks are reviewed.
