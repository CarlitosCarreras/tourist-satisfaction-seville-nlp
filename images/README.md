# Results

This folder contains the main visual outputs generated during the analysis of tourist satisfaction in Seville using online reviews collected from TripAdvisor and Civitatis.

The visualizations summarize overall tourist satisfaction, differences across visitor profiles, sentiment patterns, and the most frequently discussed attractions and experiences.

---

## Included Visualizations

### 1. Overall Tourist Satisfaction

**File:** `overall-tourist-satisfaction.png`

Presents the overall sentiment distribution estimated using the roBERTuito sentiment analysis model.

Main finding:

- 80.5% of reviews were classified as positive.
- 12.9% were classified as negative.
- 6.6% were classified as neutral.

---

### 2. Tourist Satisfaction by Type of Trip

**File:** `tourist-satisfaction-by-type-of-trip.png`

Compares satisfaction levels across different travel types, including solo travelers, couples, families, and groups of friends.

Main finding:

- Satisfaction remains consistently high across all travel profiles.
- Families travelling with children showed the highest proportion of positive reviews.

---

### 3. Tourist Satisfaction by Visitor Origin

**File:** `residents-and-foreigners-tourist-satisfaction.png`

Compares sentiment between domestic and international visitors.

Main finding:

- Residents reported higher satisfaction levels than foreign visitors.
- International tourists exhibited slightly higher levels of negative sentiment.

---

### 4. Tourist Satisfaction by Attraction

**File:** `tourist-satisfaction-of-most-commented-attractions.png`

Shows sentiment distributions for the most frequently reviewed attractions and tourist experiences in Seville.

Main finding:

- Guided tours generally received the highest satisfaction levels.
- The Real Alcázar and the Cathedral of Seville accumulated the largest shares of negative reviews among the most commented attractions.

---

### 5. Most Commented Attractions

**File:** `most-commented-attractions.png`

Displays the ten attractions, tours, and tourist experiences receiving the largest number of reviews.

Main finding:

- Free tours and guided cultural tours generated the highest volume of visitor engagement.

---

### 6. Positive Reviews Word Cloud

**File:** `positive-comments-word-cloud.png`

Word cloud generated from reviews classified as positive.

Main finding:

- Positive experiences were associated with terms such as:
  - Sevilla
  - Guía
  - Visita
  - Historia
  - Interesante
  - Recomendable

---

### 7. Negative Reviews Word Cloud

**File:** `negative-comments-word-cloud.png`

Word cloud generated from reviews classified as negative.

Main finding:

- Negative experiences were associated with:
  - Entrada
  - Hora
  - Cola
  - Tiempo
  - Visita
  - Catedral

These terms suggest that dissatisfaction was often related to organization, waiting times, ticket access, and visitor management issues.

---

## Data Source

The figures were generated from an anonymized dataset of 3,937 tourist reviews collected from TripAdvisor and Civitatis.

## Methodology

- Web Scraping
- Data Cleaning
- Natural Language Processing (NLP)
- Transformer-based Sentiment Analysis (roBERTuito)
- Descriptive Statistics
- Data Visualization

