# Consumer Insights Data Analytics Externship of Luxury Head Phones of Beats by Dre and it's competitors

### Purpose

The project aimed to enhance the understanding of consumer sentiment and feedback to inform strategic brand-building efforts. The primary objective was to leverage data science techniques to analyze large datasets of consumer reviews, uncover patterns and trends, and extract meaningful insights.

### Key Objectives

- Apply EDA techniques to uncover underlying patterns and trends within the datasets, providing a deeper understanding of customer behavior and preferences.
- Use effective visualizations present relationships, correlations and insights, enabling stakeholders to make informed decisions
- Perform comprehensive sentiment analysis on consumer reviews, determining the overall sentiment and specific sentiments related to various aspects of the brand
- Utilize NLP tools, including Gemini AI, to interpret and summarize customer feedback, extracting key themes and sentiments that could guide brand strategy.

### Background
Beats by Dre is a prominent audio brand, co-founded by Dr. Dre and Jimmy Iovine in 2006. Known for its stylish design and powerful bass-heavy sound, the company has revolutionized the premium headphone market. In 2014, Beats by Dre was acquired by Apple Inc., further solidifying its place in the tech industry as a leader in audio technology and lifestyle products. Consumer sentiment analysis is crucial in the tech industry because it helps to:

- Improve Products: Understand customer feedback to enhance product features and user experience
- Monitor Brand Perception: Track how the brand is viewed and maintain a positive reputation
- Stay Competitive: Identify market trends and adapt quickly to consumer preferences
- Refine Marketing Strategies: Craft messages that resonate with customers based on their sentiments
- Manage Crises: Quickly respond to negative feedback to protect the brand’s image

### Dataset
I gathered reviews of products (here, headphones) from Amazon for ten different products (two from Beats, while the other eight from different brands and competitors, two from each brand). Headphone brands considered:

- Beats by Dre
- Sony
- Bose
- Sennheiser
- Audio Technica

**Data Selection:** Chose different models of headphones of Beats and their competitive brands and made sure to stick to similar price range in order to target similar market
**Web Scraping:** Used Oxylabs API to scrape the reviews into CSV files, combined them into a dataset of 1000 reviews
**Challenges Faced:** 
As per the structure of Oxylabs, I could not gather reviews from beyond the 10th page. Hence, the maximum possible reviews that could be obtained from a single request is 100. Thus, in order to build a large enough dataset of 1000 reviews, I took 10 different products into consideration contrary to the 5 that was initially decided. Many a times, only 10 reviews were collected from a single request due to technical issues. Ideally, it should have been 100 per request. Hence, I spent lot more of time and effort on building the dataset since I had to make multiple API requests to get the required number of reviews.
