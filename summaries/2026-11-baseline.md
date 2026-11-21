# AI doom forecast tracking — baseline (21 Nov 2026)

## Calendar events (primary Google Calendar)

| Date | Event | Anchor |
|---|---|---|
| 1 Jan 2028 | AI 2027 scenario: superintelligence median | AI Futures Project scenario model, 80% CI 2026–2033. Kokotajlo p(catastrophe) ~70% |
| 1 Jan 2033 | Metaculus median: first general AI system | Metaculus community (1,800+ forecasters); 25% by 2029; compressed from ~2060 (2019) |
| 1 Jan 2047 | ESPAI researcher survey median: machines outperform humans at every task | n=1,580 AI researchers; same survey: median 10%, mean 18% extinction/severe disempowerment |
| 27 Dec 2054 | Hinton's AI extinction window closes | Stated Dec 2024: 10–20% chance AI causes extinction within three decades |

## Scheduled tasks

- Monthly sweep: 1st of each month, 04:00 Europe/Helsinki. Checks Metaculus median, AI Futures Project model, latest ESPAI survey, composite P(Doom) index, new credible dated estimates. Updates the four event descriptions with changelog lines; moves event dates only if the underlying forecast materially changed. Writes its summary to this repo at summaries/YYYY-MM.md.
- Quarterly digest: 2 Jan / 2 Apr / 2 Jul / 2 Oct, 04:30 Europe/Helsinki. Reads the quarter's three monthly summary files and writes summaries/YYYY-QN.md with trends, notable changes, and a frequency recommendation.

## Headline numbers at setup

- ESPAI 2024 survey (n=1,580): median 10%, mean 18% extinction/permanent disempowerment probability.
- Superforecasters (XPT): ~0.4% extinction by 2100; domain experts ~3%.
- Composite P(Doom) Index: ~10% AI-caused catastrophe (≥10% of humanity or civilizational collapse) by 2100.
- Hinton: 10–20% within 30 years. Amodei: 25% things go really badly.

The credible content of all forecasts is probability, not dates. Expect most monthly summaries to report "nothing new".