---
tags:
  - command
---

# /autocamp

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/autocamp [save|load|on|off|abort|status] | [setting] [on|off]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Turns autocamp on and off, saves and loads, and adjusts settings such as starting a macro after a rez
<!--cmd-desc-end-->

## Options

| Option | Description |
|--------|-------------|
| `on|off` | Toggles camping to desktop when dead. Default is OFF |
| `save|load` | Loads the ini / Saves settings to ini. Changes DO NOT auto save. |
| `endmac [whendead] {on|off}` | Toggles /endmac before camping. Default is OFF.<br><br>**whendead**: Toggles /endmac as soon as dead. Default is OFF |
| `startmac [on|off|clear] | set <"macroname param...">` | Toggles /mac macroname after rez. Default is OFF<br><br>If your macro has parameters, use quotes |
| `abort` | Aborts processing the currently detected death |
| `wait <#>` | Number of minutes to wait before camping to desktop. Default is 15. |
| `status` | Shows the current status |