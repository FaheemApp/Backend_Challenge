# Laravel News API

### Description
For this assignment you have to implement an application fetches news from [**News API**](https://newsapi.org/ "News API"). and return it back to client
### Functions
The two functionalities that need to be implemented are "list" and "search".

This is an example request for a generic GET request which should fulfill the "list".

```
> Request
GET /news   HTTP/1.1
Authorization: Basic QWxhZGRpbjpvcGVuIHNlc2FtZQ
Accept: application/json

> Response
[
  {
    "headline": "Human organs can be stored for three times as long in major breakthrough for transplants",  // Headline of the article
    "link": "https://www.telegraph.co.uk/science/2019/09/09/human-organs-can-stored-three-times-long-major-breakthrough/",  // Link of the article
  },
  {
    "headline": "Depth of Field: The Shared Memory of One World Trade Center",
    "link": "https://www.wired.com/story/one-world-trade-center-history-future/",
  },
]
```

You should also implement a feature that allows someone to "search" through the news.

```
> Request
GET /news?query=bitcoin   HTTP/1.1
Authorization: Basic QWxhZGRpbjpvcGVuIHNlc2FtZQ
Accept: application/json

> Response
[
  {
    "headline": "IRS goes after cryptocurrency owners for unpaid taxes",
    "link": "https://www.cbsnews.com/news/own-bitcoin-irs-pursues-cryptocurrency-owners-for-unpaid-taxes/",
  },
  {
    "headline": "Skirting US sanctions, Cubans flock to cryptocurrency to shop online, send funds",
    "link": "https://www.channelnewsasia.com/news/business/skirting-us-sanctions--cubans-flock-to-cryptocurrency-to-shop-online--send-funds-11901148",
  },
]
```


### Constraints
There are some constraints that you should be aware of. Not completing any of the following constraints will stop your candidacy from moving forward:
- You must use **Laravel framework**.
- You must return the two fields that are in the sample requests above in JSON format. You can add more fields if you'd like.

### Assessment
Primarily, we will be assessing good **design decisions**.

In addition, we will be assessing the following points:
- PHP Proficiency
- Ability to understand and use 3rd party APIs
- Ability to parse different forms of data
- Ability to write unit tests
- Ability to write documentation
- Ability to follow SOLID principles
- Generally professional code that follows standards in matter of commits and security

### Submission
You should upload your code to a Github repository (private or public) and share it with us. Your repository should have a README.md that explains how to run the code and if you’ve done anything extra. **If you fail to produce this repository within the time period mentioned in the email you received your application will be rejected.**
Best of luck!

