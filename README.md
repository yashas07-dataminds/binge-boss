# binge-boss
Amazon Prime Video Data Analysis Dashboard
A comprehensive, interactive data visualization dashboard analyzing Amazon Prime Video's content library. This project extracts actionable insights from a dataset of over 9,600 titles, exploring content distribution, geographical trends, rating classifications, and historical release patterns.

📊 Dashboard Highlights & Key Metrics
Based on the core dataset (amazon_prime_titles.csv), the dashboard uncovers the following insights:

Total Content Library: 9,655 unique titles spanning across 519 diverse genres.

Creative Talent: Content driven by 5,771 unique directors.

Historical Depth: Covers a rich historical release window spanning from 1920 to 2021.

Content Split: Heavily weighted toward Movies (80.82% / 7.81K) compared to TV Shows (19.18% / 1.85K).

Top Genre: Drama takes the leading spot with 986 titles, closely followed by Comedy.

Primary Maturity Rating: 13+ is the most frequent rating classification with 2,117 total shows.

Project Overview

The streaming landscape is fiercely competitive, and understanding catalog architecture is key to recognizing platform strategy. This project was developed to dissect and visualize the foundational content structure of Amazon Prime Video using amazon_prime_titles.csv. By transforming raw metadata into structured, visual intelligence, this dashboard maps out how the platform balances its library across time, global regions, genres, and audience demographics.

Deep-Dive Analysis & Observations

The Movie vs. TV Show Asymmetry:One of the most striking architectural insights from the dashboard is the massive dominance of Movies over TV Shows ($80.82\%$ vs $19.18\%$). While competitor platforms often focus heavily on episodic TV content to drive weekly user retention, Amazon Prime Video's library boasts a staggering 7.81K movies, positioning it as a massive digital archive for feature films.

The Exponential Streaming Boom:The Total Shows by Release Year timeline visualizes a historical curve starting all the way back in 1920. However, the trajectory experiences an exponential, vertical spike post-2010. This perfectly mirrors the "Streaming Wars" era, highlighting massive content acquisition frameworks and aggressive catalog expansion to meet global broadband adoption.

Demographic Targeting via Ratings:The maturity rating distribution reveals that Amazon Prime Video acts as a highly versatile, mainstream platform. The dominant 13+ classification (2,117 titles) indicates a deliberate focus on broad-appeal, four-quadrant family content, while robust numbers in the 16+ and 18+ brackets ensure deep engagement for mature audiences.

Global Footprint & Genre Diversification:Through geospatial mapping, the project highlights how content production centers aggregate heavily across North America and Europe, while simultaneously expanding tracking for emerging international media hubs. Genre-wise, the heavy volume of Drama (986) and Comedy (536) indicates a reliance on high-sentiment, universally relatable genres to anchor their global viewership.

🛠️ Features
Geographical Content Mapping: Interactive world map showcasing total shows distributed by country of origin.

Historical Timeline Analysis: An interactive area/line chart tracking the explosive growth of both Movies and TV Shows by release year, emphasizing the streaming boom post-2000.

Maturity Rating Breakdown: A detailed horizontal bar chart tracking content distribution across 25 distinct rating classifications (e.g., 13+, 16+, ALL, 18+).

Genre Deep-Dive: Clean visualization of top-performing content categories including Drama, Comedy, Documentaries, and Animation.

💾 Dataset Reference
The underlying analysis is powered by the amazon_prime_titles.csv file, which contains metadata for all movies and TV shows available on Amazon Prime Video.

Key attributes analyzed include:

type (Movie vs. TV Show)

title, director, and cast

country of production

release_year and maturity rating

listed_in (Genres)
