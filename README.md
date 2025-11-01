Python scrape to acquire the full list of store marquees, banners, and signs that mention "kratom" through search engine AllText.nyc. AllText is a search engine that allows users to look up a term and find all Google Street View images of New York City taken between 2007 and 2024 that include this term.
This project required an API scrape, which we haven't yet learned, so some lines of code are annotated *I used CHATGPT to help me do this* or *I used CHATGPT to explain this code*

This scrape produced a .csv of all mentions of kratom in Google Image results, which I can analyze further to map location trends and change over time.
Before further analysis for my capstone, I will speak with an OCR confidence expert to determine how to slice the .csv for accuracy of results, ie. confidence score. There are some search results with confidence of 1 that contain kratom, and some that don't, so I couldn't slice based on any empirical confidence score range.


For implementation in the larger project, I will repurpose my code for other common substances to draw conclusions about kratom addictiveness/popularity.
Other similarly classified legal substances include: lion's mane, kava, kanna, ashwaghanda, hemp. Plotting change over time in appearance of these substances compared to kratom can provide context for kratom's outsized popularity, growth trends, and addictive properties.
