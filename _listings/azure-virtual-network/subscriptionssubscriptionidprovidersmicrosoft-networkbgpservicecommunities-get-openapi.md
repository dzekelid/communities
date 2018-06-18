---
swagger: "2.0"
x-collection-name: Azure Virtual Network
x-complete: 0
info:
  title: Azure Virtual Network API Bgp Service Communities List
  description: Gets all the available bgp service communities.
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---