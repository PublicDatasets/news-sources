# News Outlets and RSS Feeds

A shared repo of news sources and their RSS feeds. Submit an issue to add a new RSS feeds or update existing record on newsfeeds.csv.

## Submission process

To submit a news feed, add an issue with the following structure:  

```
{
  site: https://techcrunch.com,
  url: https://techcrunch.com/feed/
}
```

If a news website has multiple feeds, submit a request to add them all:
```
{
  site: https://reuters.com,
  url: [http://feeds.reuters.com/news/artsculture, http://feeds.reuters.com/reuters/businessNews, http://feeds.reuters.com/reuters/companyNews...] 
}
```

## Criteria
A news source must follow these guidelines to be included on the list: 
1. Has SSL certificate (HTTPS)
2. Does not publish sexually explicit, graphically violent, hateful, dangerous and illegal content
3. Does not share or link to spam, malware, viruses or other harmful software
4. Publishes original content
5. Does not copy content from other news sites
6. Properly discloses sponsored or promoted posts


If you have any suggestions on the criteria or to disagree about a token submission, open an issue to chat. 
