---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Find the best investment on the housing market in the East of England
---

In recent years, the allure of the countryside has increasingly drawn attention from potential homeowners seeking tranquility away from the urban hustle. This trend has been particularly notable in East England, where picturesque landscapes blend with historical richness to offer a unique living experience. This project aims to leverage extensive data analysis to better understand the housing market dynamics in this region, providing valuable insights for individuals considering a move to the countryside.

The analysis encompasses a comprehensive exploration of house price trends and sales volumes over the past two decades, spanning from 1996 to 2015. By examining datasets on both existing homes and newly built properties, this study aims to capture a full spectrum of the market, offering insights into how prices have evolved and how many homes have been sold over time. Such knowledge is crucial, not only for potential buyers to make informed decisions but also for policymakers and developers to assess the impact of their initiatives and plan future developments effectively.

Using techniques ranging from basic statistical analysis to advanced predictive modeling, this project seeks to uncover patterns and correlations that define the housing market in East England's countryside. The ultimate goal is to provide a predictive outlook on housing prices, enabling prospective homeowners to anticipate market trends and make strategic decisions about when and where to purchase a property.

By focusing on this geographic area and market segment, this study addresses a significant gap in the available research, offering a targeted analysis that can help individuals and families better understand what to expect when considering a move to the countryside. Furthermore, this project not only aids buyers but also contributes to the broader dialogue about rural development and economic sustainability in East England.

Here you can see a map of the areas we have been considering in the analysis:

<iframe src="{{site.baseurl}}/graphs/Map_East_England.html" width="1000" height="500" style="border:none;"></iframe>

<br>

# A clear trend during the years

<iframe src="{{site.baseurl}}/graphs/Heatmap_Primary_Price.html" width="1200" height="400" style="border:none;"></iframe>

<iframe src="{{site.baseurl}}/graphs/Heatmap_Resales_Price.html" width="1200" height="400" style="border:none;"></iframe>

The analysis includes two comprehensive heatmaps displaying the median prices for both resales and primary houses sold over the years across various areas in East England. The heatmaps are structured to reflect each geographic area as rows, with the columns representing time, segmented by year and quarter. The color gradient, ranging from light to dark green, visualizes the median prices—darker shades of green denote higher prices. By contrasting these two maps, we can observe the distinct behavior of prices in the resale market compared to the primary housing market. This distinction is crucial for understanding both the immediate and long-term trends that influence buying decisions in these segments.

<br>

# Price trends for all districts over the years

Below is an analysis of apartment prices on the primary and secondary markets for subsequent districts. In order to best compare prices and their changes between districts, charts were created for each district and then superimposed on one chart. Additionally, we used linear regression to check the average annual change for each district, which allowed us to predict the dynamics of changes in subsequent years.

<iframe src="{{site.baseurl}}/graphs/district_price_trends_primary_market.html" width="1200" height="500" style="border:none;"></iframe>

<iframe src="{{site.baseurl}}/graphs/district_price_trends_resale_market.html" width="1200" height="500" style="border:none;"></iframe>


The lines show a clear upward trend in prices over these two decades, indicating that houses in all districts have generally become more expensive over time. There is a clear decline in both markets around the crisis in 2008, but the overall trend is upwards. In the case of the secondary market, this growth is more stable, while in the primary market we have more sudden changes. It's clear that the Cambridge District has the highest median prices, but it's also the smallest area, which means the housing market there is very small.

<br>

# Do high prices scare buyers?

<iframe src="{{site.baseurl}}/graphs/correlation_2.html" width="1200" height="900" style="border:none;"></iframe>

Looking at existing houses there is a generally negative correlation throughout most of the period, suggesting that higher prices tend to be associated with fewer units sold. This might indicate price sensitivity in the existing homes market.
The correlation appears to become less negative over time, especially around 2008-2010, which could coincide with market adjustments or economic events like the financial crisis, potentially altering buying behavior.
After 2010, the correlation becomes more negative again before stabilizing towards the end, suggesting a return to the earlier trend.

When it comes to new houses the correlation also starts negative but shows significant variability over time.
Notably, there is a period where the correlation turns positive around 2004 to 2008, indicating that during this time, higher prices did not deter buyers of new build homes, possibly due to a booming real estate market or attractiveness of newer properties.
The correlation dips again into the negative after 2008, likely influenced by the broader economic downturn, which may have made new build homes less attractive or attainable.
A significant rise in positive correlation from around 2010 through 2015 suggests a strong recovery in the new build market where higher prices coincide with higher sales.

<br>

# A view in each district 

<iframe src="{{site.baseurl}}/graphs/correlation_3_units_and_prices.html" width="1200" height="700" style="border:none;"></iframe>

The correlations are mostly negative across both home types in most districts, reinforcing the general trend that higher prices might be limiting sales.
Some districts show a mix of negative and slightly positive correlations for new build homes, indicating localized variations in how price affects sales. These variations could be driven by factors like local economic conditions, availability of housing, and consumer preferences.
Notably, in West Suffolk, new build homes show a really negative correlation, suggesting that in this area, higher prices might correlate with decreased demand or a perception of lower value in new homes.
- Existing homes show consistent price sensitivity, with higher prices generally correlating with fewer sales. This could suggest a more established market where buyers are cautious about pricing.
- New build homes show more variability, indicating that this market may be influenced by different factors, including economic cycles, the appeal of new features, and potentially more aggressive marketing strategies.

<br>

# A more clear understanding considering the Volume of Sales

<iframe src="{{site.baseurl}}/graphs/Existing Homes Volume of Sales.html" width="500" height="200" style="border:none;"></iframe>
<iframe src="{{site.baseurl}}/graphs/New Build Homes Volume of Sales.html" width="500" height="200" style="border:none;"></iframe>

For existing homes, Cambridge shows a rising price-to-units ratio, suggesting robust demand and solid long-term investment potential. Fenland, with its moderate but consistent price-to-units ratio, represents a more affordable and stable option, attractive for sustainable growth without the volatility seen in urban centers. In contrast, new builds in Fenland demonstrate stable growth with reasonable sales volumes, making it a promising area for investors seeking value in new housing. Cambridge, however, with periodic spikes in the price-to-units ratio for new homes, continues to attract premium investments, particularly in new developments.


# Let's focus on Fenland and Cambridge

Our analysis highlighted the Fenland district for its exceptionally affordable housing on the primary market, where the median price of apartments was the lowest in all recorded years with modest growth rates. On the resale market, although Fenland no longer offers the lowest prices, its growth dynamics—analyzed through linear regression—surpass those in Peterborough, making it a viable option for buyers with limited budgets or those looking to be the first owners of their homes.

Simultaneously, Cambridge stands out as a sterling choice for premium investors and those seeking a dependable asset unlikely to depreciate. The consistent demand and robust market conditions in Cambridge ensure it remains a top choice for individuals aiming for long-term capital appreciation. Properties here represent a secure investment, with their value holding steady or increasing over time, making Cambridge ideal for those who prioritize stability and quality in their investments.

To determine the optimal timing for purchases in Fenland, we analyzed historical price trends and found that typically, the lowest prices occurred in the first quarter of each year, with the highest in the fourth quarter. This pattern suggests that early-year purchases might yield the best deals. However, given the overall upward trajectory of the market, the strategic move would be to buy at the earliest opportunity available, regardless of the quarter.

<iframe src="{{site.baseurl}}/graphs/fenland.html" width="1000" height="500" style="border:none;"></iframe>

In conclusion, while Fenland offers an entry point into the housing market with potential for appreciation, Cambridge presents a compelling option for those looking for premium investment opportunities in a market known for its resilience and long-term value retention. Whether you seek affordability and growth or stability and premium investment, these insights will guide you in making an informed decision tailored to your financial and lifestyle goals.


