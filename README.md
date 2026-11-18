# NSW Emergency Department | Performance Intelligence

Interactive Power BI dashboard analysing quarterly emergency department
performance across NSW hospitals, [2010-2026].

![Dashboard](Page1.png)

▶ [Watch the 60-second demo](YOUR_VIDEO_LINK)

## The question
How is ED demand changing, and are hospitals keeping up on waiting and
transfer times?

## What the dashboard shows
- KPI cards: attendances, % leaving within 4 hours, median time to leave,
  ambulance transfer within 30 minutes, each with change vs last quarter
- Trend of attendances, this year vs last year
- 4-hour performance by peer group
- Top 10 busiest hospitals
- Insight sentences that update with the filters

## How it's built
- **Data model:** star schema with Calendar, Dim Entity and Dim Measure
  dimensions and a long-format fact table (measure_name / measure_value)
- **DAX:** explicit measures per KPI, time intelligence (DATEADD,
  SAMEPERIODLASTYEAR), conditional colours, dynamic text measures
- **Design:** one-page layout, single-select slicers, consistent palette,
  red/green used only for changes

## Key findings (2024 Q4)
- [Fill in from your cards]
- [Fill in from your charts]

## Data
[Source name and link], publicly available NSW Health data. This is an
independent analysis and isn't affiliated with NSW Health.

## Files
- `.pbix`: the full report (open in Power BI Desktop)
- `NSW_ED_Dashboard.pdf`: static copy
