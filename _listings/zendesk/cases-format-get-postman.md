{
  "info": {
    "name": "Sales Force Desk API Get Cases",
    "_postman_id": "31bb7119-d708-44fc-911e-340023cc2082",
    "description": "Get cases.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Cases",
      "item": [
        {
          "id": "df4fbe43-af8b-49dd-8571-ea9d913f1ec6",
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
              "id": "d9eb80b2-6f77-43dc-95cb-e26f3a95d929"
            }
          ]
        }
      ]
    }
  ]
}