{
  "info": {
    "name": "Google Cloud SQL API Get Flags",
    "_postman_id": "aa912bc0-a76c-4bb7-ba57-4452e02ee4ed",
    "description": "List all available database flags for Google Cloud SQL instances.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Flags",
      "item": [
        {
          "id": "6c429cd8-de02-4527-9d53-dfb638bdd17c",
          "name": "sql.flags.list",
          "request": {
            "url": "http://www.googleapis.com/sql/v1beta4/flags?databaseVersion=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all available database flags for Google Cloud SQL instances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "887c8254-268d-43ae-9136-398254eb9d94"
            }
          ]
        }
      ]
    }
  ]
}