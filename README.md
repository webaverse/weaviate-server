# weaviate-server

- https://console.semi.technology/

```
https://weaviate.webaverse.com/
```

## Query

### TV Tropes

```
{
  Get {
    Example (nearText: {
      concepts: ["male"]
    }) {
      title,
      content,
      quotes
    }
  }
}
```

```
{
  Get {
    Trope (nearText: {
      concepts: ["male"]
    }) {
      title,
      quotes,
      content,
    }
  }
}
```

### Aesthetics Wiki

```
{
  Get {
    Aesthetic (nearText: {
      concepts: ["male"]
    }) {
      title,
      content,
    }
  }
}
```

## Data Sources

- https://github.com/webaverse/wikipedia-scraper
- https://github.com/webaverse/tvtropes-scraper
- https://github.com/webaverse/aesthetics-wiki-scraper
