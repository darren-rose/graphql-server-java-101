# graphql-server-java-101

#### endpoint

```
http://localhost:8080/graphql
```

#### query

```
{
  bookById(id: "book-1"){
    id
    name
    pageCount
    author {
      firstName
      lastName
    }
  }
}
```
