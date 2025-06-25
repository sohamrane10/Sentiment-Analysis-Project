# Sentiment-Analysis-Project
# 🐦 Twitter Sentiment Analysis & Word Cloud Visualization in R

This R project performs sentiment analysis and text mining on Twitter data. The result includes interactive and static word clouds and sentiment score visualizations.

## 📌 Features

- Read and process tweets from CSV files
- Text cleaning using `tm` and regex
- Word frequency analysis via Term-Document Matrix
- Visualizations: Word Clouds (static & interactive), Bar Charts
- Sentiment analysis using NRC lexicon via `syuzhet` package

## 📂 Files

- `apple_tweets1.csv` & `apple_tweets2.csv` – Input datasets
- `code.R` – Complete R script
- `output/` – Contains word cloud and bar plot images
- `README.md` – Project documentation

## 📊 Libraries Used

```r
tm, wordcloud, wordcloud2, syuzhet, ggplot2, reshape2, scales, dplyr, lubridate
🧠 Sentiment Analysis Process
Used get_nrc_sentiment() to extract emotions (joy, anger, etc.)

Aggregated results and visualized using bar plots

Compared multiple datasets to track consistency

☁️ Word Cloud Visualization
Static Word Cloud
Created using wordcloud package with filtering (e.g., min.freq = 5, Dark2 palette).

Interactive Word Cloud
Used wordcloud2 with:

Shape = 'triangle'

Letter cloud with the word apple

## 📈 Output Preview

🧪 Challenges Faced
UTF-8 encoding errors handled using iconv()

Manual package installation (wordcloud2, syuzhet, etc.)

Proper cleaning of URLs, symbols, and repeated stopwords

## 🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/sohamrane10/twitter-sentiment-analysis.git
Open R or RStudio

Install required packages:

r
Copy
Edit
install.packages(c("tm", "wordcloud", "wordcloud2", "syuzhet", "ggplot2", "lubridate", "scales", "reshape2", "dplyr"))
Run code.R step-by-step.

## 🙌 Author
Soham Rane
📧 LinkedIn | 📁 GitHub

“Turning tweets into insights — one word cloud at a time.” 🌐📊
