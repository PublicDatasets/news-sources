# News Outlets and RSS Feeds

A shared repo of news sources and their RSS feeds.

## Submission process

To add or update a news feed, [create an issue](https://help.github.com/articles/creating-an-issue/) and add your feed info with this structure

```
https://techcrunch.com,https://techcrunch.com/feed/
```

Which corresponds to DOMAIN,RSS

If a news website has multiple feeds, use quotations:
```
https://reuters.com,"http://feeds.reuters.com/news/artsculture, http://feeds.reuters.com/reuters/businessNews, http://feeds.reuters.com/reuters/companyNews"
```

## Removal process

Create an issue with the following structure:

```
Criteria failed: List the failed criteria
Proof: Explain why it failed the criteria 
Data (this is the newsfeed you want to remove): https://badsite.com,https://badsite.com/rss
```

Example:


```
Criteria failed: Does not try to mislead users, Properly discloses sponsored or promoted posts
Proof: The name of the site misleads users to think it's about baseball but it is actually used to distribute paid financial press releases, which are not properly disclosed. Example: https://www.baseballdailydigest.com/2018/11/29/einsteinium-price-reaches-0-0956-on-exchanges-emc2.html
Data (this is the newsfeed you want to remove): https://baseballdailydigest.com,https://www.baseballdailydigest.com/feed
```


## Criteria
A news source must follow these guidelines to be included on the list: 
1. Has SSL certificate (HTTPS)
2. Does not publish sexually explicit, graphically violent, hateful, dangerous and illegal content
3. Does not share or link to spam, malware, viruses or other harmful software
4. Does not copy content from other news sites
5. Does not try to mislead users
6. Properly discloses sponsored or promoted posts


We want to make this a community resource and welcome all suggestions. Open an issue to discuss if you have an idea for a new criteria. 
