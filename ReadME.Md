# GraphQuest: Exploring and Implementing GraphQL

## Task 0: Write a Query to Get a Specific Character by ID

### Objective

Write a GraphQL query to retrieve a specific character’s information using their ID from the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql).

### Instructions

- Use the `character(id: ID!)` field to fetch character details.
- Query for characters with IDs: **1, 2, 3, 4**.
- Include the following fields in your query:
  - `id`
  - `name`
  - `status`
  - `species`
  - `type`
  - `gender`

### Example Query

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
```

### Directory Structure

```
character/
├── README.md
├── character-id-1.graphql
├── character-id-1-output.json
├── character-id-2.graphql
├── character-id-2-output.json
├── character-id-3.graphql
├── character-id-3-output.json
├── character-id-4.graphql
└── character-id-4-output.json
```

- Each `.graphql` file contains the query for a specific character.
- ## Each `.json` file contains the output of the query.
