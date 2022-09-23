# weaviate-server

- https://console.semi.technology/
- https://www.graphqlbin.com/v2/new

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
