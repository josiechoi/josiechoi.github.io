---
layout: post
title:  "Web Scraping"
date:   2020-09-24 22:10:00 +0200
author: "Josephine Choi"
---


Finished DC's Websscraping course this week and just installed Scrapy to my personal desktop. Took a little longer than expected because of the permission so need to uninstall 3.7 Anaconda and install 3.8. Can't wait to give it a spin. 

DC's course is more about xpath and CSS notation. Scrapy should also work well with Beautiful Soup. Installed last week. 

Excited to see an article in Webscraping in the latest issue of Code4Lib J. When I have the time, definitely need to take a closer look at this. But the author uses Selenium, so that's something I don't have much background knowledge. 

Made a lot of progress in DC. Some of the courses (such police activities, HR analytics) finished quickly, while regex and webscraping were more challenging. I think I may go back and take some notes and then applies these new knowledge to some projects. I think HR analytics, which was about churn analysis, could be used to improve my capstone project (which was a binary classification problem). I thought it was interesting that it looked I could have just used weight='balanced' to solve imbalanced data problem. It was also nice to brush up my knowledge about sklearn, ROC curve etc. I did random forest for my capstone, but I might go back to use decision tree instead because it would be more intrepretable to produce the diagram.

I actually thought about asking internally to see if we can get some real data from our library so that we can analyze our circ activities. Will need a partner plus need to go through ethics board, of course. This will be a bit more challenging because then I will need to brush up my knowledge in time series data analysis, but real data will mean real insight. I wish the SFPL data was for per transaction and not for per patron, cuz aggregated data like this (with per patron) cannot be used analyzed use pattern.  

Web scraping course was interesting. And one day I really want to scrape the bookstore's website (if it is permissible?). I thought it would be useful to get a list of books being used for courses and it may be a way of getting it faster. 

Regex is so versatile. For one thing, I can go back improve my ezproxy project because I did use regex to extract data from URL (thanks to Collingwood's code, which made the whole process painless). I always wanted to improve it so that I could, for instance, extract which PQ database the traffic was from. 

Other than DC, this week I am doing some research re: modular programming. RUL is thinking about moving away from ezproxy, so that means maybe in a couple years or so my little pet project with ezproxy will be halted. It would be a pity if it would be lost just like that, I thought it was interesting, meaningful, and I spent quite a bit of time working on it. . If I turned this to a package, maybe another person can pick it up. I should probably try to publish some research results. It could be quite interesting now considering we now have mutliple years of data. Even if we just focus on one year of data, we can do some serious statistical analysis such as looking at the chi square of different faculty use. 

Some extra readings/videos to do: 

Hands-On Web Scraping with Python(Book) 
https://learning-oreilly-com.ezproxy.lib.ryerson.ca/library/view/hands-on-web-scraping/9781789533392/
Selenium WebDriver With Python 3.x - Novice To Ninja
(Video)  
https://learning-oreilly-com.ezproxy.lib.ryerson.ca/videos/selenium-webdriver-with/9781789131550/


This week, I also did some research re: how libraries have used Python 

-Frazer(2020), as mentioned above,use Selenium to output info from GOBI site (webscraping) (That's the article just published in {Code4Lib}
-Magnuson (2016) discussed a few projects. The first is to use BeautifulSoup to scrape library catalogue to generate an Excel file, which could be used to compare a xlsx sheet provided by a donor to decide whether the library will accept a donation or not. Second, is to create an inventory of research done by faculty and to identitify if the word "sustainability" keywords were used in the research spreadsheet's  title or abstract.  
https://acrl.ala.org/techconnect/post/do-library-stuff-faster-with-python/
- Maguson (2014) provided even more inspirations. It was about PyMARC, and provided case studies in which Python can be powerful. The first use case is to turn MARC into KBart list, and the second is to turn MARC to Dspace Upload. It was also interesting that there is a pymarc Google group. (Unforunately, right now I do not understand marc enough to make this beneficial, but it is a good learning opportunity in the future). 
https://acrl.ala.org/techconnect/post/hacking-in-python-with-pymarc/





