# Query-1
```
{
  artists {
      firstName
      lastName
      email
      createdAt
      updatedAt
  }
    
}

```

# Query-2
```
{
  items {
    id
    title
    description
    artist {
      firstName
      lastName
      email
      createdAt
      updatedAt
    }
    createdAt
    updatedAt
  }
}
```