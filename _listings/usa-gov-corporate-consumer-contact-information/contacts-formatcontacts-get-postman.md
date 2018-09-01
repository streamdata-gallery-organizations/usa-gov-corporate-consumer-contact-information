{
  "info": {
    "name": "USA.Gov Corporate Consumer Contact API Get Contacts",
    "_postman_id": "32d60787-2690-4860-bced-3e25b9261fac",
    "description": "Contacts is a general purpose call that, by default, will return all of the corporate directory records. However, you can pass parameters into the contacts call that allow you to filter the records returned by the API in powerful ways.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "contacts",
      "item": [
        {
          "id": "ed8be0f9-e245-4b56-bee9-7c028b592404",
          "name": "getContacts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.usa.gov",
              "path": [
                "api",
                "USAGovAPI",
                "contacts.:format/contacts"
              ],
              "query": [
                {
                  "key": "query_filter",
                  "value": "query_filter",
                  "disabled": false
                },
                {
                  "key": "result_filter",
                  "value": "result_filter",
                  "disabled": false
                },
                {
                  "key": "sort",
                  "value": "sort",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "format",
                  "value": "format",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "X-Range",
                "value": "X-Range",
                "description": "You can limit the results returned by the API by including an X-Range HTTP header in your GET request, with a value of items=x to y, where x is the lower limit and y is the upper limit of the results to be returned",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Contacts is a general purpose call that, by default, will return all of the corporate directory records"
          },
          "response": [
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "[\r\n  {\r\n    \"Id\": \"Id\",\r\n    \"Name\": \"Name\",\r\n    \"Description\": \"Description\",\r\n    \"Subdivision\": \"Subdivision\",\r\n    \"Street1\": \"Street1\",\r\n    \"Street2\": \"Street2\",\r\n    \"City\": \"City\",\r\n    \"StateTer\": \"StateTer\",\r\n    \"Zip\": \"Zip\",\r\n    \"Email\": \"Email\"\r\n  }\r\n]",
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "2860e759-62d9-461f-b4cc-e76a7a471cde"
            }
          ]
        }
      ]
    }
  ]
}