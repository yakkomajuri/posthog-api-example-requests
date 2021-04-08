# /api/organizations

## Request

```
GET /api/organizations
```

## Response

```
HTTP 200 OK
Content-Type: application/json

{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "id": "01761e21-7eab-0000-48b4-7389137b2cb2",
            "name": "Demo",
            "created_at": "2020-12-01T11:48:00.300134Z",
            "updated_at": "2020-12-01T11:48:00.300164Z",
            "membership_level": 15,
            "personalization": {},
            "setup": {
                "is_active": false,
                "current_section": null
            },
            "plugins_access_level": 9,
            "teams": [
                {
                    "id": 17,
                    "uuid": "0177ee7a-dc4b-0000-1a1f-61d5ba802f48",
                    "organization": "01761e21-7eab-0000-48b4-7605937b2cb2",
                    "api_token": "hBg7iNHOEy80Y0bQTgAzdy2IhNk3vKCWRL4QFxCBWDA",
                    "name": "HogFlix Demo App",
                    "completed_snippet_onboarding": true,
                    "ingested_event": true,
                    "is_demo": true,
                    "timezone": "UTC"
                },
                {
                    "id": 2,
                    "uuid": "01761e21-cf82-0000-f4bb-5166582039ff",
                    "organization": "01761e21-7eab-0000-48b4-7212937b2cb2",
                    "api_token": "V4d5f0478d158d3ebdbf6-abc55c4b8e56e4180fe0",
                    "name": "HogFlix Movies",
                    "completed_snippet_onboarding": true,
                    "ingested_event": true,
                    "is_demo": false,
                    "timezone": "UTC"
                }
            ],
            "available_features": []
        }
    ]
}
```
