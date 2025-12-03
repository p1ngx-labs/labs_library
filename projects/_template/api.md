# 🔌 API Dokumentation

## Übersicht

*Beschreibe die API und ihre Hauptfunktionen.*

## Base URL

```
https://api.example.com/v1
```

## Authentifizierung

*Beschreibe die Authentifizierungsmethode.*

## Endpoints

### GET /resource

Beschreibung des Endpoints.

**Parameter:**

| Name | Typ | Beschreibung |
|------|-----|--------------|
| id | string | Resource ID |

**Response:**

```json
{
  "id": "123",
  "name": "Example"
}
```

### POST /resource

Beschreibung des Endpoints.

**Body:**

```json
{
  "name": "Neuer Eintrag"
}
```

**Response:**

```json
{
  "id": "124",
  "name": "Neuer Eintrag",
  "created": "2024-01-01T00:00:00Z"
}
```

## Fehlercodes

| Code | Beschreibung |
|------|--------------|
| 400 | Bad Request |
| 401 | Unauthorized |
| 404 | Not Found |
| 500 | Internal Server Error |
