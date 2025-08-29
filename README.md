# ABSA Analysis of Customer Reviews with Web Scraping + LLM in Python

This project applies Aspect-Based Sentiment Analysis (ABSA) to customer reviews of Lightyear, a European fintech investment app, using web scraping and AI language models.

ABSA identifies sentiments tied to specific product or service features, providing more granular insights than overall sentiment analysis.

The dataset includes 1441 reviews scraped from Trustpilot.

A fixed schema defines aspect categories such as Account Features, Mobile App Usability, Pricing, Support, and Overall Satisfaction.

OpenAI’s API processes each review to extract mentioned aspects, classify their sentiments as Positive, Negative, or Neutral, and return structured JSON outputs.

The output dataset is flattened with 3985 rows, where each row corresponds to one aspect and its sentiment from a specific review.

Columns include country, review date, rating, review ID, review text, aspect raw text, normalized aspect, category, aspect code, and sentiment.

This structured format supports detailed analysis and visualization of customer feedback by product features.

The project enables targeted understanding of strengths and weaknesses to guide service improvements.

Overall, it demonstrates how Python web scraping and LLMs can combine to deliver fine-grained sentiment insights from user reviews.
