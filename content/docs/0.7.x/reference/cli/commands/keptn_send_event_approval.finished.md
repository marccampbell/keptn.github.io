---
date: "2020-10-12T14:26:31+02:00"
title: "keptn send event approval.finished"
slug: keptn_send_event_approval.finished
---
## keptn send event approval.finished

Sends an approval.finished event to Keptn in order to confirm an open approval with the specified ID in the provided project and stage

### Synopsis

Sends an approval.finished event to Keptn in order to confirm an open approval with the specified ID in the provided project and stage. 

* This command takes the project (*--project*) and stage (*--stage*). 
* It is optional to specify the ID (*--id*) of the corresponding approval.triggered event. If the ID is not provided, the command asks the user which open approval should be accepted or declined.
* The open approval.triggered events and their ID can be retrieved using the "keptn get event approval.triggered --project=<project> --stage=<stage>" command.


```
keptn send event approval.finished [flags]
```

### Examples

```
keptn send event approval.finished --project=sockshop --stage=hardening --id=1234-5678-9123
```

### Options

```
  -h, --help             help for approval.finished
      --id string        The ID of the approval.triggered event to be approved
      --project string   The project containing the service to be approved
      --service string   The service to be approved
      --stage string     The stage containing the service to be approved
```

### Options inherited from parent commands

```
      --mock                 Disables communication to a Keptn endpoint
  -q, --quiet                Suppresses debug and info messages
      --suppress-websocket   Disables WebSocket communication to suppress info messages from services running inside Keptn
  -v, --verbose              Enables verbose logging to print debug messages
```

### SEE ALSO

* [keptn send event](../keptn_send_event/)	 - Sends an event to Keptn

###### Auto generated by spf13/cobra on 12-Oct-2020
