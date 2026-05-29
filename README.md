<div align="center">

![PersonaMatch Banner](https://capsule-render.vercel.app/api?type=waving&color=0:00C2FF,50:7C3AED,100:FF4D6D&height=170&section=header&text=PersonaMatch&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Persona-aware%20urban%20context%20scoring%20for%20Airbnb%20listings&descSize=16&descAlignY=60)

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Open%20App-00C853?style=for-the-badge)](https://persona-match-6b33514a.base44.app)
![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-Data%20Pipeline-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-External%20Storage-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

</div>

## Overview

PersonaMatch is a data-driven scoring system that evaluates Airbnb listings through the needs of different user personas. It combines internal listing data with external urban signals such as Google Maps reviews, neighborhood context, and semantic text analysis.

The goal is simple: instead of ranking listings only by generic quality, PersonaMatch estimates how relevant a location is for specific types of travelers.

## Personas

| Persona | What The Pipeline Looks For |
| --- | --- |
| Singles | Urban access, nightlife, local activity, flexible short-stay signals |
| Couples | Experience quality, nearby attractions, comfort, and review sentiment |
| Families | Safety, practical amenities, neighborhood suitability, family-oriented context |
| Remote Workers | Work-friendly signals, convenience, quietness, and long-stay compatibility |

## What Makes It Interesting

- Combines structured Airbnb data with external urban context.
- Uses semantic text features to interpret reviews and neighborhood descriptions.
- Separates user expectations from listing reality.
- Produces persona-specific relevance scores instead of a single generic ranking.
- Keeps credentials and datasets out of the public repository.

## Methodology

```text
External and internal data
        |
        v
Secure Databricks / Azure loading
        |
        v
Text processing and GloVe-based semantic features
        |
        v
Persona-specific lexical and contextual matching
        |
        v
Spatial and semantic aggregation
        |
        v
PersonaMatch score per listing
```

## Repository Contents

```text
PersonaMatch.ipynb   Main Databricks notebook
README.md            Project documentation
```

## Data And Security

The public repository intentionally does not include:

- Private datasets.
- Azure SAS tokens.
- API credentials.
- Raw external review exports.

The notebook is published as code only, with sensitive configuration removed or expected to be supplied locally.

## How To Run

1. Upload `PersonaMatch.ipynb` to Databricks.
2. Configure the required Azure / Databricks storage access.
3. Run the notebook cells in order.
4. Open the live demo to inspect the product-facing concept.

## Portfolio Summary

Built a persona-aware Airbnb scoring system that combines listing data, external urban context, Google Maps review signals, and semantic text features to produce personalized location scores for different traveler types.

<div align="center">

[![Open Live Demo](https://img.shields.io/badge/Open%20PersonaMatch-Live%20Demo-7C3AED?style=for-the-badge)](https://persona-match-6b33514a.base44.app)

</div>
