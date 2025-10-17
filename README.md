# Insights-from-Amazon-Beauty-Reviews-via-LLM
A data analysis project to identify top themes and what delights customers about beauty products. Use Amazon beauty review data and use ChatGPT API to generate insights and provide recommendations.

## **Executive Summary**

The project uses the Amazon Beauty Review Dataset to inform companies to inform companies of customer sentiments and insights derived from customer reviews.

The data cleaning phase involved merging the reviews and metadata databases and dropping irrelevant columns. Key highlights included dropping all NA prices which was a substantial part of the dataset but any analysis without prices is incomplete. Additionally, the extensive categorization of the data was completed in this section, it did not come with the dataset.

After some EDA we focused on the reviews doing a sentiment analysis and discovering that people tend to be much more expressive when they rate something highly. It allowed us to focus on **4+ star products**, employing an LLM we used it analyze the reviews and group the data around **key themes** and **things people like**. We also analyzed products bought together and discovered people purchase more in similar categories leading to the conclusion that companies should bundle products in similar catergories. Based on the extensive analysis we propose the following recommendations for companies designing products especially in the hair, creams/lotions and eye/eyemakeup space.



*   Key satisfaction drivers: fragrance, hydration, and ease of use.

*  Repurchase & co-purchase: Nail Products, Cream/Lotion, and Perfume are most rebought

*   People purchases products in the same category together, creating space for bundles

Contributors:
Mahesh Wadhokar
Hanchao Tang
Andy Chen
Yu Husn Ku
