# Karpathy's AI Job Exposure Data — Archived

On March 15, 2026, Andrej Karpathy published an analysis scoring 342 US occupations for AI exposure using Bureau of Labor Statistics data and Gemini Flash. He deleted the GitHub repository within hours. This archive preserves the complete dataset.

## What's Here

| File | Description |
|------|-------------|
| `data.json` | Full dataset — 342 occupations with scores, employment, pay, education, outlook, and AI scoring rationale |
| `data.csv` | Same data in CSV format for easy analysis |

## Data Schema

Each occupation includes:

| Field | Description |
|-------|-------------|
| `title` | Occupation name |
| `category` | BLS category (25 categories) |
| `exposure` | AI exposure score (0–10) |
| `exposure_rationale` | Gemini Flash's reasoning for the score |
| `jobs` | Total US employment |
| `pay` | Median annual wage (USD) |
| `education` | Typical entry-level education |
| `outlook` | Job outlook score |
| `outlook_desc` | Outlook description (e.g., "Faster than average") |

## Summary Statistics

- **342 occupations** covering **143 million US jobs**
- **Weighted average AI exposure: 4.9 / 10**
- **130 occupations** (49M workers, $3.67T in wages) score 7+
- **Only perfect 10:** Medical Transcriptionists
- **Lowest scores (1):** Roofers, Janitors, Construction Laborers, Grounds Workers, Athletes

## Exposure Distribution

| Score | Occupations | Workers |
|-------|------------|---------|
| 1 | 9 | 6.2M |
| 2 | 36 | 23.7M |
| 3 | 47 | 23.5M |
| 4 | 42 | 18.7M |
| 5 | 43 | 11.0M |
| 6 | 35 | 10.9M |
| 7 | 70 | 23.8M |
| 8 | 29 | 10.8M |
| 9 | 30 | 14.3M |
| 10 | 1 | 44K |

## Source & Credit

- **Original author:** Andrej Karpathy
- **Original URL:** https://karpathy.ai/jobs/ (may no longer be available)
- **Wayback Machine snapshot:** https://web.archive.org/web/20260315050821/https://karpathy.ai/jobs/
- **Data source:** [Bureau of Labor Statistics Occupational Outlook Handbook](https://www.bls.gov/ooh/)
- **Scoring model:** Gemini Flash

## Context

This data was archived for research and discussion purposes. The scores represent an LLM's assessment of AI automation potential, not peer-reviewed labor economics. Exposure ≠ displacement. See our [full analysis](https://x.com/ScatterAI) for caveats and interpretation.

## License

The original data is from the US Bureau of Labor Statistics (public domain). The AI-generated exposure scores and rationales were published by Andrej Karpathy. This archive is provided for research and educational purposes.

---

Archived by [ScatterAI](https://scatterai.com)
