# web_scraper

## Building and running the project

Build:

```sh
go build -o crawler
```

Run:

```sh
./crawler BASE_URL maxConcurrency maxPages
```

Developer example:

```sh
go run . https://learnwebscraping.dev/practice/ecommerce/ 3 10
```
