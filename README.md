# Automated Web Scraper for Product & Price Data from an E-commerce Website.

## Summary
This project involved building an automated web scraper to collect smartphone price data from an e-commerce website every 30 minutes during the Republic Day Sale. The collected data was analysed to understand pricing strategies across brands and price segments.

## Key Details
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;•	**Data Collection:** Automated web scraping using BeautifulSoup & Requests to extract smartphone prices and product details.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;•	**Data Analysis:** Cleaning and exploration using Pandas, Matplotlib and Plotly to identify pricing trends.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;•**	Dataset Size:** 12,673 rows.

## Tech Stack
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Python (BeautifulSoup, Requests, Pandas, Matplotlib & Plotly)

## Analysis & Results
### Brand-wise Pricing Strategy:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;•  Contrary to expectations, peak discounts were observed after the sale period, in February, likely due to excess inventory.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• Only Samsung and Infinix showed significant price reductions during the Republic Day.

### Price Segment-wise Pricing Strategy
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;•  Budget Models (< ₹10,000): Highest discounts on 5th and 7th February, followed by 26th–28th January.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;•  Mid-range & Upper Mid-range Models (₹10,000 – ₹30,000): Discounts peaked in February, followed by January.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;•  Premium Models (> ₹30,000): Significant price reductions only at the end of January, with minimal discounts in February.
**Insight:** Higher-priced smartphones tend to have shorter and less frequent discount periods, whereas low-end models see higher discounts post-sale.

### Impact:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• For Brands: Smartphone companies can adjust their pricing strategies based on competitor trends to maximize profits.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• For Retailers: They can optimize marketing strategies by aligning with brand discount patterns to maximize revenue. Additionally, they can manage inventory more efficiently to avoid overstocking or shortages.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;• For Consumers: Buyers can make informed purchase decisions by knowing when to expect the highest price reductions.

