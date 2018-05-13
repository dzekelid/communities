{
  "info": {
    "name": "Azure Virtual Network API Bgp Service Communities List",
    "_postman_id": "83252340-503d-48e1-8858-d74322762585",
    "description": "Gets all the available bgp service communities.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "bgp service communities",
      "item": [
        {
          "id": "1f6d6756-3801-4add-9731-f1842663a047",
          "name": "BgpServiceCommunities_List",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/providers/Microsoft.Network/bgpServiceCommunities"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets all the available bgp service communities"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc07043a-9094-4bf2-ba69-b1b7696ccc9d"
            }
          ]
        }
      ]
    }
  ]
}