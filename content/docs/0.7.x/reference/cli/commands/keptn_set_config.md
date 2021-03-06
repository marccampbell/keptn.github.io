---
date: "2020-10-12T14:26:31+02:00"
title: "keptn set config"
slug: keptn_set_config
---
## keptn set config

Sets flags of the CLI configuration

### Synopsis

Sets flags of the CLI configuration, which is stored in $HOME/.keptn/config.

*	This command takes a key and a new value as arguments. 


```
keptn set config [flags]
```

### Examples

```
keptn set config AutomaticVersionCheck false
```

### Options

```
  -h, --help   help for config
```

### Options inherited from parent commands

```
      --mock                 Disables communication to a Keptn endpoint
  -q, --quiet                Suppresses debug and info messages
      --suppress-websocket   Disables WebSocket communication to suppress info messages from services running inside Keptn
  -v, --verbose              Enables verbose logging to print debug messages
```

### SEE ALSO

* [keptn set](../keptn_set/)	 - Sets flags of the CLI configuration

###### Auto generated by spf13/cobra on 12-Oct-2020
