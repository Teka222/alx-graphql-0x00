# Character Queries with GraphQL

This project contains GraphQL queries to fetch specific character information using the Rick and Morty API.

## Endpoint
https://rickandmortyapi.com/graphql

## Queries
We use the `character(id: ID!)` field to fetch the following data:
- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

## Files
- `character-id-1.graphql` → Query for character with ID 1
- `character-id-1-output.json` → Response for character ID 1
- `character-id-2.graphql` → Query for character with ID 2
- `character-id-2-output.json` → Response for character ID 2
- `character-id-3.graphql` → Query for character with ID 3
- `character-id-3-output.json` → Response for character ID 3
- `character-id-4.graphql` → Query for character with ID 4
- `character-id-4-output.json` → Response for character ID 4

## Example Query
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
