# Scraping AllText.nyc for mentions of "kratom"

### This website scrape project using Python code acquires the full list of store marquees, banners, and signs that mention "kratom" in New York City between 2007 and 2024. AllText.nyc allows users to search a term and recieve a list of images captured on GoogleStreetView between these years, including metadata like date captured, geolocation, and text found.

This scrape produced a .csv of all mentions of kratom in Google Image results, which I can analyze further to map location trends and change over time.
Before further analysis for my capstone, I will speak with an OCR confidence expert to determine how to slice the .csv for accuracy of results, ie. confidence score. There are some search results with confidence of 1 that contain kratom, and some that don't, so I couldn't slice based on any empirical confidence score range.</br>

For implementation in the larger project, I will repurpose my code for other common substances to draw conclusions about kratom addictiveness/popularity.
Other similarly classified legal substances include: lion's mane, kava, kanna, ashwaghanda, hemp. Plotting change over time in appearance of these substances compared to kratom can provide context for kratom's outsized popularity, growth trends, and addictive properties.</br>

**NOTE:**This project required an API/JSON scrape, so some lines of code are annotated *I used CHATGPT to help me do this* or *I used CHATGPT to explain this code* as we have not yet learned API scraping as of 11/3/2025.


