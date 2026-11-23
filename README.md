# How Do Hawker Food Prices Differ Across Food Categories and Regions in Singapore?

**Important:** This is entirely synthetic data. The hawker centre names are based on real locations, but the prices, ratings and portion sizes are artificially generated. Do not interpret the results as actual Singapore hawker market statistics.

<img width="1600" height="901" alt="hawker centre" src="https://github.com/user-attachments/assets/5cfc8156-3dd1-4bde-ab35-51deb749d2a0" />


## Introduction 
Hawker centres are an essential part of Singapore's food culture, offering a wide variety of affordable local dishes to residents and visitors. However, food prices may vary depending on factors such as food category, location, portion size and customer preferences. Understanding these price differences can provide useful insights into the affordability and pricing patterns of hawker food across Singapore. This project aims to analyse a synthetic dataset of 500 hawker food records to explore price variations across different food categories and regions. Using descriptive statistics and data visualisation techniques, such as bar charts, pie charts, histograms and scatterplots, the analysis will identify pricing patterns, compare average food prices and examine the relationship between portion size and price. The findings aim to provide a clearer understanding of hawker food pricing in Singapore.

## Analysis Questions
### 1. Which food category has the highest average price?

<img width="989" height="494" alt="BQ1" src="https://github.com/user-attachments/assets/0d8749f3-fdf6-44ba-8d82-cf2760ac577c" />

Meat & Seafood averages about 6.5 SGD, which is more than double the average price of Drinks at roughly 2.6 SGD and noticeably higher than Malay Food or Rice & Noodles at around 4.8 SGD. This means businesses can use affordable rice, noodles, and drinks to attract daily budget-conscious customers, while relying on premium meat and seafood dishes—or drink add-ons—to boost overall revenue and profit margins.

### 2. Which hawker dishes are the most and least expensive?

<img width="1051" height="495" alt="BQ2" src="https://github.com/user-attachments/assets/202cf1b5-1a1b-4428-8403-ff3c1560b05a" />

Satay Set is the highest-priced item at 7.0 SGD, which is 3.5 times more expensive than Kopi at about 2.0 SGD, while everyday main meals like Chicken Rice and Wanton Mee sit in the middle at roughly 4.6 SGD. This means hawker stalls can rely on mid-priced main meals for steady daily sales volume, while bundling high-margin items like Satay Sets with low-cost drinks like Kopi or Teh to boost average customer spending.

### 3. What is the most common food category in the dataset?

<img width="989" height="494" alt="BQ3" src="https://github.com/user-attachments/assets/f616ad5d-d326-4d07-86c8-5ea00a3aaac7" />

Rice & Noodles leads the market with 150 samples, which is roughly 2.6 times higher than Meat & Seafood (58 samples) and Malay Food (57 samples), and noticeably ahead of Snacks & Desserts (89 samples). This means businesses should ensure strong supply chains and high stall capacity for staple rice and noodle dishes to capture the largest customer demand, while using less common categories like Malay Food or Meat & Seafood to stand out from heavy competition.

### 4. What is the distribution of hawker food prices?

<img width="1103" height="495" alt="BQ4" src="https://github.com/user-attachments/assets/e656ed8e-3a8b-4b94-89ce-7ea42c30474a" />

Hawker food prices peak sharply at around 4.7 SGD (47 samples), compared to very few items priced above 7.0 SGD (only 2 to 3 samples per price bracket) or below 2.0 SGD (9 to 12 samples). This means businesses should price core menu items between 4.0 and 5.5 SGD to match mainstream customer expectations, while keeping prices under 7.0 SGD unless offering premium dishes to avoid losing price-sensitive diners.

### 5. Is there a relationship between portion size and food price?

<img width="989" height="495" alt="BQ5" src="https://github.com/user-attachments/assets/a772d20d-5f94-4b7e-baf0-ee1bb56bdedd" />

Portion size has only a weak positive link to price ($r = 0.35$), as dishes with a similar portion index around 1.0 vary widely from roughly 1.2 SGD to over 8.0 SGD compared to smaller portions below 0.5 that mostly stay under 5.0 SGD. This means hawker stalls do not need to serve oversized portions to charge higher prices, and can instead boost profits by focusing on premium ingredients, dish quality, or popular recipes rather than simply increasing food quantity.

### 6. Which Singapore region has the highest average hawker food prices?

<img width="989" height="495" alt="BQ6" src="https://github.com/user-attachments/assets/76a261a6-9028-41dd-b428-8560f9eca05e" />

Average hawker food prices stay very consistent across Singapore, with the Central region being the highest at roughly 4.5 SGD—only about 0.3 SGD more expensive than the cheapest region, the East, at roughly 4.2 SGD. This means hawker operators can apply a nearly uniform pricing strategy island-wide, while slightly raising menu prices in the Central region to offset higher commercial rents without losing price-sensitive customers.

## Google Dashboard 

<img width="1515" height="786" alt="google dashboard" src="https://github.com/user-attachments/assets/9511cb7d-a38b-42b4-bcc2-32dc97782d0e" />

Here is the link to visit the Google Dashboard: https://datastudio.google.com/reporting/f65edf71-f360-4931-9b1a-360a1b823b3b 


## Conclusion
Overall, Singapore’s hawker food market is heavily driven by affordable, everyday staples rather than portion size or location. Rice & Noodles is the most common category at 150 samples, and most dishes cluster between 4.0 and 5.5 SGD, peaking at 4.7 SGD. While Meat & Seafood averages the highest at 6.5 SGD—led by Satay Set at 7.0 SGD—portion size has only a weak impact on price ($r = 0.35$). Furthermore, average prices stay nearly identical across all regions, ranging only from about 4.2 SGD in the East to 4.5 SGD in the Central region. To maximize profits, hawker operators should maintain a consistent island-wide pricing strategy anchored around 4.5 SGD, rely on high-demand rice and noodle staples for steady volume, and boost margins through quality ingredients and drink add-ons rather than oversized portions.

## Tools
1. Python
2. Google Data Studio

## References
