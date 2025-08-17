# GraphQL Episode Queries

This project contains GraphQL queries to fetch specific episodes from the Rick and Morty API.

## Endpoint
https://rickandmortyapi.com/graphql

## Queries
We use the `episode(id: ID!)` field to fetch:
- `id`
- `name`
- `air_date`
- `episode`

## Files
- `episode-id-1.graphql` → Query for Episode 1
- `episode-id-1-output.json` → Response for Episode 1
- `episode-id-2.graphql` → Query for Episode 2
- `episode-id-2-output.json` → Response for Episode 2
- `episode-id-3.graphql` → Query for Episode 3
- `episode-id-3-output.json` → Response for Episode 3
- `episode-id-4.graphql` → Query for Episode 4
- `episode-id-4-output.json` → Response for Episode 4

## Example Query
```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
