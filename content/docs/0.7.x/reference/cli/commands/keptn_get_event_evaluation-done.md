---
date: "2020-10-12T14:26:31+02:00"
title: "keptn get event evaluation-done"
slug: keptn_get_event_evaluation-done
---
## keptn get event evaluation-done

Returns the latest Keptn sh.keptn.events.evaluation-done event from a specific Keptn context

### Synopsis

Returns the latest Keptn sh.keptn.events.evaluation-done event from a specific Keptn context.

```
keptn get event evaluation-done [flags]
```

### Examples

```
keptn get event evaluation-done --keptn-context=1234-5678-90ab-cdef
```

### Options

```
  -h, --help                   help for evaluation-done
      --keptn-context string   The ID of a Keptn context from which to retrieve an evaluation-done event
```

### Options inherited from parent commands

```
      --mock                 Disables communication to a Keptn endpoint
  -q, --quiet                Suppresses debug and info messages
      --suppress-websocket   Disables WebSocket communication to suppress info messages from services running inside Keptn
  -v, --verbose              Enables verbose logging to print debug messages
```

### SEE ALSO

* [keptn get event](../keptn_get_event/)	 - Returns the latest Keptn event specified by event type

###### Auto generated by spf13/cobra on 12-Oct-2020
