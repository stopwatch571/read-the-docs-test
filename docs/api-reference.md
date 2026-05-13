# API Reference

## Example Endpoint

### `GET /api/items/{item_id}`

Retrieve a single item by its ID.

**Path Parameters**

| Parameter | Type    | Description          |
|-----------|---------|----------------------|
| `item_id` | integer | The unique item ID   |

**Query Parameters**

| Parameter | Type   | Required | Description         |
|-----------|--------|----------|---------------------|
| `format`  | string | No       | Response format     |

**Response**

```json
{
  "id": 1,
  "name": "Example Item",
  "created_at": "2026-05-13T10:00:00Z"
}
```

**Status Codes**

| Code | Description           |
|------|-----------------------|
| 200  | Success               |
| 404  | Item not found        |
| 500  | Internal server error |
