# TrustMRR startup scraper


## What is the TrustMRR startup database?
[TurstMRR](https://trustmrr.com/) is a database of startups to promote the build in public movement. It is a project developed and maintained by [Marc Lou](https://www.linkedin.com/in/marclouvion/).


All startups listed on TrustMRR need to connect their Stripe billing. So, TrustMRR only displays real revenue numbers (no fake or inflated revenue claims).






## How to use the trustMRR scraper?
This scraper is designed to scrape any category listed on TrustMRR.


You can find a list of available categories [here](https://trustmrr.com/category).


### inputs
This scraper takes 3 inputs:
- TrustMRR category URL: you can list as many categories as you wish to scrape
- Scrape profile: toggle it if you want to get all the information from the startup profiles
- Max number of scroll: by default TrustMRR category display 30 results. Each scroll will display 30 more results. By default this scraper will perform 10 scrolls.




### outputs
This scraper returns 2 result files:
- Overview
- Profile List


Overview views as only 2 columns:
- Category URL: the trustMRR category URL you scrape
- startup URL: the trustMRR startup profile


Profile list views provide:
- TrustMRR profile: the trustMRR startup profile that you can match with "startup Url" property from the Overview tab
- Startup Name
- Tag lin
- total revenue
- MRR
- Founded: the founding year of the startup
- Location: the headquarters location of the startup
- last 4 weeks Revenue
- website


### scheduling
Apify allows you to schedule a scraper for recurrent launch. This is perfect if you want to monitor the performance of a specific startup category.


Check out [this tutorial](https://docs.apify.com/platform/schedules) for more information about scheduling options.


## Source code and licence
This scraper is open source. Given the spirit of openess behing TrustMRR platform I want to make this scraper fulling open source.


This scraper is also fully copyleft. You are free to use and edit the source code as you wish, even for commercial applications.


## Related Apify actor
If you are interested in Startup Database like TrustMRR you might enjoy a few other Apify actors:
-[Crunchbase scraper](https://apify.com/curious_coder/crunchbase-scraper)
-[Y combinator Scraper](https://apify.com/michael.g/y-combinator-scraper)
-[Peerlist scraper](https://apify.com/advantageous_subcontra/peerlist-launch-upvoters-extractor)
-[Product hunt scraper](https://apify.com/danpoletaev/product-hunt-scraper)