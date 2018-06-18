{
  "info": {
    "name": "Sales Force Desk API Get Case",
    "_postman_id": "41ae67cd-e093-44bc-a3c1-cc5591a31d53",
    "description": "Get case.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Cases",
      "item": [
        {
          "id": "e0517d37-0f37-4210-afef-766ac7e69e4e",
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
              "id": "6b6fd5e0-3d71-41c2-b0f9-e7c4bf321f00"
            }
          ]
        },
        {
          "id": "e5991312-df3c-4340-9544-52c403b5ae5a",
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
              "id": "4e83da1d-e987-4344-b8d4-6c45161dd00f"
            }
          ]
        }
      ]
    }
  ]
}