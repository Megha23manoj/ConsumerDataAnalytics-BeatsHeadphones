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

### Data Cleaning

- Handling missing values
- Dropping the duplicate rows if any
- Converting categorical columns to numerical variables if necessary

### Conclusions after Exploratory Data Analysis and Sentiment Analysis

- Most reviews are concentrated around the higher end of the scale, indicating that the majority of customers are generally satisfied with the products.
- Ratings below 3 were identified as outliers. Though these reviews are comparitively less in number. I did not let go of them so that these can be investigated further to understand the reasons behind the low ratings.
- Majority of reviews are classified as positive, followed by negative and neutral sentiments. Positive reviews often highlight aspects such as product quality, ease of use, and value for money.
- Speaking brand specific, Beats has significant competition from all the selected competitor brands - but analying number positive rated reviews and review text sentiment - Bose and Sony are the biggest competitor
  
### Potential Implications

- Since the overall sentiment for Beats is positive, its a good news for the brand
- Few negative/poor reviews should be analysed separate to extract words that depict the negative sentiment, investigate the problem and work on it to improve more in product quality and in sales.
- Some reviews can also be due to poor customer service. Such can be noted to improve the service more
- The positive words from the positive reviews can be taken into account so that the USP of Beats can be highlighted to develop even better marketing strategies

### SWOT Analysis based on Insights

**Strengths**

Well-known among younger audiences, thanks to its stylish design and celebrity endorsements.
Strong customer satisfaction with a high number of positive reviews.
Benefits from being part of the Apple ecosystem, offering seamless compatibility.
Appeals as a fashion and lifestyle brand, not just audio equipment.

**Weaknesses**

Seen as expensive compared to competitors with similar or better sound quality.
The bass-heavy sound may not appeal to audiophiles who prefer a balanced sound.

**Opportunities**

Potential to expand product lines with varied sound profiles and features.
Use Apple’s distribution and marketing to reach new markets.
Expanding demand for wireless devices offers innovation opportunities.
Adopting eco-friendly practices could attract new customers.

**Threats**

Competitors like Sony, Bose, and Sennheiser are strong and innovative.
Consumers are increasingly seeking value for money and sound quality.
Premium pricing might be a disadvantage in economic downturns.
Any negative perception or quality issues could harm the brand's image.

### Conclusion

**Key Findings**

Beats by Dre enjoys strong customer satisfaction, similar to competitors like Sony and Bose.
Some consumers find Beats overpriced and criticize the bass-heavy sound profile.
There's potential to attract more audiophiles and environmentally conscious consumers through product diversification and sustainable practices.

**Implications**

Beats can leverage its strong brand and positive sentiment to expand its market by enhancing product features and addressing perceived weaknesses.
Marketing strategies focusing on customer service, sound quality, sustainability, and diverse consumer needs could further strengthen its position.

**Overall Reflection:** The project provides valuable insights into consumer sentiment for Beats by Dre, highlighting both strengths and areas for improvement. It contributes to a better understanding of market dynamics and informs strategic decisions to enhance brand perception and customer satisfaction. The detailed report is provided in the code file uploaded.
