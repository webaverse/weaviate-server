# weaviate-server

- https://console.semi.technology/
- https://www.graphqlbin.com/v2/new

## TV Tropes

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

## Aesthetics Wiki

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

## Wikipedia

```
{
  Get {
    Paragraph (nearText: {
      concepts: ["male"]
    }) {
      title,
      content,
    }
  }
}
```
