{
  "info": {
    "name": "Sales Force Desk API Update Case",
    "_postman_id": "c8a113c5-8cf7-4a13-bfd2-242792cfaf98",
    "description": "Update case.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Cases",
      "item": [
        {
          "id": "d0edc5bc-64c5-491b-bac2-1a34fa202ecf",
          "name": "get-cases",
          "request": {
            "url": "http://yoursite.desk.com/api/v2/cases.json?format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get cases."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "944a09e1-a800-40ba-b1d0-4c17131da725"
            }
          ]
        },
        {
          "id": "9d9e30d9-7aff-4010-8ead-be3e745dfe8c",
          "name": "get-case",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "cases/:id.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get case."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "35092e26-029e-4cc3-befc-a9adeef9f86d"
            }
          ]
        },
        {
          "id": "905ac09a-9c6d-410f-9407-6be969b96de4",
          "name": "update-case",
          "request": {
            "url": {
              "protocol": "http",
              "host": "yoursite.desk.com",
              "path": [
                "api",
                "v2",
                "cases/:id.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update case."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c88b35cf-a7d3-467b-b2ab-aa8289eb4a1a"
            }
          ]
        }
      ]
    }
  ]
}