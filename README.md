# City Sustainability Clustering

Clusters global cities by sustainability performance to help GreenCityWatch prioritize which cities need policy intervention and funding.

## Overview

**Data**: city-level indicators — carbon emissions, renewable energy %, green space %, waste recycled %, and more
**Method**: K-Means clustering (k=3, chosen via the elbow method) on standardized features
**Output**: each city labeled into one of three tiers — Critical Intervention Zone, Transitional Cities, or Sustainability Leaders

### Key Result

Cities in the Critical Intervention Zone show the clearest pattern: high emissions paired with low recycling and renewable energy adoption — the group GreenCityWatch should target first. A choropleth map visualizes cluster distribution globally, and scatter plots show the emissions-vs-renewables trade-off driving the split.

#### Tools
Python · Pandas · Scikit-learn · Seaborn · Plotly
