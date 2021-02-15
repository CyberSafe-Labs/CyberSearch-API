# CyberSearch API

Search Engine API with Node/Express and Puppeteer using Google Search

The API scrapes Top Search Results from Google Search

To get started, make sure to run `npm install` to install all dependencies
```
npm install
```

To start the server:
```
npm start
```

You can send a `GET` request with your search query:
```
http://localhost:3000/search?searchquery=cats
```

For Optimising and Deployment guide please refer to this <a href="https://dev.to/waqasabbasi/optimizing-and-deploying-puppeteer-web-scraper-1nll">link.</a>

Example Response
```
[
  {
    title: 'Cats Are Funny',
    description: 'Watch funny videos about cats`,
    url: 'catsarefunny.com'
  },
  {
      title: 'Cats Are Cute',
      description: 'Watch cute videos about cats`,
      url: 'catsarecute.com'
    },
]
```
