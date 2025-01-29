# SoundStage Selector: Intelligent Artist Recommendation for Concerts

Overview

Selecting the right performers for an event is crucial in creating an engaging and memorable experience for the audience. This project utilizes data from YouTube and Spotify to assess artist characteristics, audience engagement patterns, and collaboration networks, enabling concert organizers to make informed lineup decisions.

# Objectives

Identify artists that align with event themes and audience preferences.

Analyze streaming and social engagement metrics to assess artist popularity.

Examine collaboration networks to evaluate artist influence and cross-promotional potential.

Provide an interactive tool for concert planners to generate tailored artist recommendations.

# Data Sources

The dataset for this project is curated from publicly available platforms, primarily:

Spotify: Track-related metadata, genre classification, and streaming attributes such as danceability, energy, and acousticness.

YouTube: Viewer engagement insights, including likes, comments, views, and official video indicators.

Collaboration Data: Information on past collaborations between top artists.

# Key Attributes Analyzed

Artist Metrics: Genre, collaboration history, track count, country of origin.

Engagement Indicators: Weighted score incorporating YouTube and Spotify interaction data.

Collaboration Influence: Ratio of collaborative tracks to total unique collaborators.

Music Features: Tempo, energy, loudness, and duration analysis across genres.

# Data Processing & Feature Engineering

Removed redundant attributes such as URLs and metadata not contributing to artist selection.

Aggregated artist engagement scores using weighted metrics.

Categorized diverse genres into broader classifications for better interpretability.

Utilized network analysis algorithms to visualize collaboration structures.

Applied correlation analysis to study relationships between artist influence and engagement levels.

# Data Loading & Preprocessing

Read datasets from Spotify, YouTube, and artist collaboration sources.

Dropped unnecessary columns such as URLs and metadata.

Renamed and structured columns for consistency.

Handled missing values by filling or dropping based on context.

# Feature Engineering

Created an engagement score as a weighted sum of likes, comments, and views.

Calculated collaboration impact as the ratio of collaboration songs to unique collaborators.

Normalized engagement and collaboration impact using Min-Max scaling.

Categorized and mapped genres into broader categories.

# Network Analysis & Correlation Study

Constructed a collaboration network to visualize artist connections.

Used Fruchterman-Reingold layout for network positioning.

Analyzed correlations between artist engagement, concert fees, and collaboration impact.

# Visualization & Dashboard Development

Generated insights into artist recommendations based on popularity and audience resonance.

Plotted regional trends in genre distribution and collaboration influence.

Developed a dashboard for concert planners to filter and explore artists based on key metrics.



# Visualization & Insights

An interactive dashboard was developed to showcase:

Artist recommendations based on popularity and audience resonance.

Genre trends across global regions.

Collaboration impact on engagement levels.

Distribution of track duration by genre.

# Key Findings

Influence of Collaborations: High collaboration artists often exhibit stronger audience interactions.

Duration Preferences: Tracks between 3–5 minutes achieve the highest listener engagement.

Regional Music Trends: Rock leads in North America, while Reggaeton dominates South America.

Gender Disparities: Male artists significantly outnumber female artists and bands in the dataset.
