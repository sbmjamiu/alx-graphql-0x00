# 📁 GraphQuest: Exploring and Implementing GraphQL

This directory contains GraphQL queries and output results for fetching character information from the **Rick and Morty GraphQL API**.

---

## 📄 Query: Get a Specific Character by ID

Write GraphQL queries using the `character(id: ID!)` field to retrieve specific details about characters with the following IDs:

- 1
- 2
- 3
- 4

Each query retrieves the following fields:

- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

---

## 📂 File Structure

Each character query and its response are saved in separate files:

| Filename                     | Description                           |
| ---------------------------- | ------------------------------------- |
| `character-id-1.graphql`     | GraphQL query for character with ID 1 |
| `character-id-1-output.json` | JSON result for character with ID 1   |
| `character-id-2.graphql`     | GraphQL query for character with ID 2 |
| `character-id-2-output.json` | JSON result for character with ID 2   |
| `character-id-3.graphql`     | GraphQL query for character with ID 3 |
| `character-id-3-output.json` | JSON result for character with ID 3   |
| `character-id-4.graphql`     | GraphQL query for character with ID 4 |
| `character-id-4-output.json` | JSON result for character with ID 4   |

---

---

## 📄 Query: List All Characters (Paginated)

This section includes GraphQL queries to retrieve a paginated list of characters from the Rick and Morty API using the `characters(page: Int)` field.

### 🔍 Selected Fields

- `id`
- `name`
- `status`
- `image`

### 📂 Files

| Filename                        | Description                         |
| ------------------------------- | ----------------------------------- |
| `characters-page-1.graphql`     | GraphQL query for characters page 1 |
| `characters-page-1-output.json` | JSON output for characters page 1   |
| `characters-page-2.graphql`     | GraphQL query for characters page 2 |
| `characters-page-2-output.json` | JSON output for characters page 2   |
| `characters-page-3.graphql`     | GraphQL query for characters page 3 |
| `characters-page-3-output.json` | JSON output for characters page 3   |
| `characters-page-4.graphql`     | GraphQL query for characters page 4 |
| `characters-page-4-output.json` | JSON output for characters page 4   |

### 🧪 How to Test

1. Go to [https://rickandmortyapi.com/graphql](https://rickandmortyapi.com/graphql)
2. Paste any of the `.graphql` queries.
3. Run the query and copy the result.
4. Save the output to the matching `.json` file.
