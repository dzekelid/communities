---
swagger: "2.0"
x-collection-name: Azure Virtual Network
x-complete: 1
info:
  title: NetworkManagementClient
  description: the-microsoft-azure-network-management-api-provides-a-restful-set-of-web-services-that-interact-with-microsoft-azure-networks-service-to-manage-your-network-resources--the-api-has-entities-that-capture-the-relationship-between-an-end-user-and-the-microsoft-azure-networks-service-
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/providers/Microsoft.Network/bgpServiceCommunities:
    get:
      summary: Bgp Service Communities List
      description: Gets all the available bgp service communities.
      operationId: BgpServiceCommunities_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-networkbgpservicecommunities-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Bgp Service Communities
---