# Restaurant Data Analysis — Cognifyz Technologies Internship

Exploratory data analysis on a global restaurant dataset (~9,500 restaurants across 15 countries) completed as part of the Cognifyz Technologies Data Analysis Internship Program.

**Tools used:** Python · pandas · matplotlib · seaborn · Google Colab

---

## Project Structure

| File | Contents |
|---|---|
| `Data_Analysis_Level_1&2.ipynb` | Level 1 + Level 2 — all 8 tasks |
| `Data_Analysis_Level_3.ipynb` | Level 3 — all 3 tasks |
| `Data Analysis.csv` | Source dataset (restaurant records) |

---

## Level 1 — Exploratory Analysis

**Task 1 — Top Cuisines**
- North Indian (41.5%), Chinese (28.6%), and Fast Food (20.8%) dominate the dataset
- Cuisines column was split and exploded to count individual cuisine occurrences

**Task 2 — City Analysis**
- New Delhi has the highest restaurant count (5,473 out of 9,551)
- Inner City has the highest average rating (4.90) among rated restaurants

**Task 3 — Price Range Distribution**
- 46.5% of restaurants fall in Price Range 1 (budget)
- Price Range 4 (premium) has the highest average aggregate rating

**Task 4 — Online Delivery**
- Only 25.66% of restaurants offer online delivery
- Restaurants with online delivery have a higher average rating (3.25) vs those without (2.47)

---

## Level 2 — Intermediate Analysis

**Task 1 — Restaurant Ratings**
- Most common rating range (excluding unrated): 3.0–3.5
- Average votes per restaurant: 156.91
- 2,148 restaurants (22.5%) are unrated (rating = 0.0)

**Task 2 — Cuisine Combinations**
- "North Indian" alone is the most common single-cuisine listing (936 restaurants)
- "North Indian, Chinese" is the most common combination (511 restaurants)

**Task 3 — Geographic Analysis**
- Strong geographic cluster in North India (Delhi/NCR region)
- Scattered international presence across Philippines, UAE, and other markets

**Task 4 — Restaurant Chains**
- 734 unique chain brands identified
- Top chains: Cafe Coffee Day (83 outlets), Domino's Pizza (79), Subway (63)
- Chain average ratings are moderate (2.9–3.5) — independent restaurants tend to have higher ceiling ratings

---

## Level 3 — Advanced Analysis

**Task 1 — Rating Text Analysis**
- "Average" is the most common rating label (39.1% of restaurants)
- "Excellent" category restaurants receive significantly higher average votes
- Dataset has no free-text reviews; analysis performed on categorical Rating text column

**Task 2 — Votes Analysis**
- Toit (Bangalore) has the highest votes: 10,934 with a 4.8 rating
- Correlation between votes and rating: 0.31 (weak-to-moderate positive)
- Highly rated restaurants attract more engagement, but votes alone don't determine quality

**Task 3 — Price Range vs Services**
- Table booking availability increases sharply with price: 0% (Range 1) → 46.8% (Range 4)
- Online delivery peaks at Price Range 2 (41.3%) then declines — premium restaurants avoid delivery platforms
- Correlation: Price vs Table Booking = 0.50 (moderate positive); Price vs Online Delivery = 0.08 (negligible)

---

## Key Insights

- Premium restaurants favour table booking over delivery; budget restaurants are the opposite
- New Delhi dominates the dataset geographically, which may skew national-level findings
- A significant portion of the dataset (22.5%) is unrated — filtered out for all rating calculations to avoid bias
- Online delivery correlates with better ratings, likely because delivery-enabled restaurants invest more in operations and customer experience

---

## How to Run

1. Open either notebook in [Google Colab](https://colab.research.google.com)
2. Upload `Dataset.csv` to the Colab session
3. Update the file path in Cell 1 if needed
4. Runtime → Run All

---

## Author

**Ranjith B** — Data Analyst  
[LinkedIn](https://linkedin.com/in/ranjith-b-thycrypsych) · ranjith04nb@gmail.com
