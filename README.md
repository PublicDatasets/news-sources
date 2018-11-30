# Reputable News Outlets and RSS Feeds

A shared repo of high quality news sources and their RSS feeds. We include an work-in-progress set of criteria to gauge publisher quality and weed out spam sites. Help us keep this list up to date and keep it a community resource.

## Submission process

To add or update a news feed, [create an issue](https://help.github.com/articles/creating-an-issue/) and add your feed info with this structure

```
site: https://techcrunch.com
rss: https://techcrunch.com/feed/
```

You can submit multiple rss feeds per site:
```
site: https://reuters.com
rss: http://feeds.reuters.com/news/artsculture, http://feeds.reuters.com/reuters/businessNews, http://feeds.reuters.com/reuters/companyNews
```

## Removal process

Create an issue with the following structure:

```
action: Update or Remove
criteria: List the relevant criteria
proof: Explain why it failed the criteria 
site (this is the newsfeed you want to remove): https://badsite.com, https://badsite.com/rss
```

Example:


```
action: Remove
criteria: (5) Does not try to mislead users, (6) Properly discloses sponsored or promoted posts
proof: The name of the site misleads users to think it's about baseball but it is actually used to distribute paid financial press releases, which are not properly disclosed. Example: https://www.baseballdailydigest.com/2018/11/29/einsteinium-price-reaches-0-0956-on-exchanges-emc2.html
site: https://baseballdailydigest.com, https://www.baseballdailydigest.com/feed
```


## Criteria
A news source must meet all of these guidelines to be included: 
1. Has SSL certificate (HTTPS)
2. Does not publish sexually explicit, graphically violent, hateful, dangerous and illegal content
3. Does not share or link to spam, malware, viruses or other harmful software
4. Does not copy content from other news sites
5. Does not try to mislead users
6. Properly discloses sponsored or promoted posts


We welcome all suggestions. Open an issue to discuss if you have an idea for a new criteria. 
