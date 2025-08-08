This project analyzes English-language news articles from North American news outlets to understand how media portrays Donald Trump during the 2024 U.S. presidential election period.

**Project Overview**
When Donald Trump launched his 2024 presidential campaign, media attention surged. This analysis examines the tone, topics, and trends in recent news coverage of Trump, revealing how different facets of his public persona are reported across the political spectrum.
We focus on articles mentioning Trump published from mid-October to mid-November 2024 across the United States and Canada, drawing insights useful for media companies, political teams, and researchers interested in political media trends.

**Dataset**
Total articles: 507 news articles

Sources: 41 distinct North American news outlets (left-leaning, right-leaning, centrist, entertainment/tech)

Data fields include:
- Title
- Description (subtitle or first sentence)
- Source
- Category (manually annotated, e.g., Election, Legal Issues, Economy)
- Sentiment (Positive / Negative / Neutral, manually annotated)

**Data Collection**
Data collected using NewsAPI under free-tier constraints:

- Multiple 30-day window requests to cover the 2-month period.
- Capping max 20 articles per source to reduce bias.
- Manual removal of irrelevant or duplicate articles.
- Careful source selection to ensure diversity and representativeness.

**Methodology**
Open Coding & Typology Development: Created 6 major article categories after iterative manual annotation.
Sentiment Analysis: Classified articles as Positive, Negative, or Neutral based on coverage tone.
TF-IDF Analysis: Extracted distinctive terms per category after stop word removal and exclusion of common words like "Donald" and "Trump."
Visualization: Used matplotlib and Excel to generate bar plots and pie charts for frequency and sentiment distributions.

**Key Findings**
Media coverage is predominantly neutral or negative, with positive articles being a minority (~11%).
The Election and Cultural Impact categories account for ~70% of articles, reflecting the election cycle's importance.
Legal issues related to Trump show high neutral coverage (~60%) given the seriousness of the topics.
Economic articles focus on tariffs, cryptocurrency, markets, and stocks.
Cultural impact articles show the highest negative coverage (~44%), reflecting public and media polarization.
Polling articles have relatively higher positive coverage (~22%), focusing on electoral forecasts.
