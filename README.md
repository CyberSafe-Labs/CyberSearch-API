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
Deployment Prerequisites:
Please make sure that all the dependencies are installed on the machine hosting Puppeteer
The list of Dependencies can be found <a href="https://github.com/puppeteer/puppeteer/blob/master/docs/troubleshooting.md#chrome-headless-doesnt-launch-on-unix">here</a>.
