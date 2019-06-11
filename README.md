# ![LOGO](logo.png) TrafficManagerManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the TrafficManagerManagementClient API (version 2017-09-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/trafficmanager-trafficmanageranalytics/2017-09-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:14:33+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Delete a subscription-level key used for Real User Metrics collection.

*Tags:* `RealUserMetrics`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Get the subscription-level key used for Real User Metrics collection.

*Tags:* `RealUserMetrics`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create or update a subscription-level key used for Real User Metrics collection.

*Tags:* `RealUserMetrics`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets latest heatmap for Traffic Manager profile.

*Tags:* `HeatMaps`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group containing the Traffic Manager endpoint.
* `profileName` - _required_ - The name of the Traffic Manager profile.
* `heatMapType` - _required_ - The type of HeatMap for the Traffic Manager profile.
    Possible values: default.
* `topLeft` - _optional_ - The top left latitude,longitude pair of the rectangular viewport to query for.
* `botRight` - _optional_ - The bottom right latitude,longitude pair of the rectangular viewport to query for.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-trafficmanager-trafficmanageranalytics-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
