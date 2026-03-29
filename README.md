# toast-frontend

Frontend application for the Toast platform.

## Quick Start

### Example API Calls

Get all items:
```bash
curl http://localhost:8000/api/items
```

Get a specific item:
```bash
curl http://localhost:8000/api/items/1
```

Create a new item:
```bash
curl -X POST http://localhost:8000/api/items \
  -H "Content-Type: application/json" \
  -d '{"name": "example"}'
```

Update an item:
```bash
curl -X PUT http://localhost:8000/api/items/1 \
  -H "Content-Type: application/json" \
  -d '{"name": "updated"}'
```

Delete an item:
```bash
curl -X DELETE http://localhost:8000/api/items/1
```
