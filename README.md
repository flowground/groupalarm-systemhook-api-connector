# ![LOGO](logo.png) groupalarm Systemhook API **flow**ground Connector

## Description

A generated **flow**ground connector for the groupalarm Systemhook API API (version 1.15.0).

Generated from: https://app.groupalarm.com/api/v1<br/>
Generated at: 2019-07-26T13:59:36+03:00

## API Description

The systemhook service implements all systemhook functions for GroupAlarm<br/>
<br/>
# Authentication<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>

## Authorization

Supported authorization schemes:
- API Key
- API Key

## Actions

### CreateSystemhook
> Creates a new system hook<br/>

*Tags:* `systemhook`

### UpdateSystemhook
> Updates the existing system hook with the passed id<br/>

*Tags:* `systemhook`

#### Input Parameters
* `id` - _required_ - id of the systemhook<br/>

### DeleteSystemhook
> Deletes the system hook with the passed id<br/>

*Tags:* `systemhook`

#### Input Parameters
* `id` - _required_ - id of the systemhook<br/>

### GetSystemhooks
> Returns all system hooks for the passed organization id<br/>

*Tags:* `systemhook`

#### Input Parameters
* `organization` - _required_ - id of organization<br/>

### GetSystemhookServicePayloads
> Returns all payloads of the usable system hooks<br/>

*Tags:* `systemhook`

### TestSystemhook
> Tests a passed systemhook object against the given url with an example payload for the passed service<br/>

*Tags:* `systemhook`

## License

**flow**ground :- Telekom iPaaS / groupalarm-systemhook-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
