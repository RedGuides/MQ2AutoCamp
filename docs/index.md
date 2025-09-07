---
tags:
  - plugin
resource_link: "https://www.redguides.com/community/resources/mq2autocamp.98/"
support_link: "https://www.redguides.com/community/threads/mq2autocamp.66804/"
repository: "https://github.com/RedGuides/MQ2AutoCamp"
config: "MQ2AutoCamp.ini"
authors: "Sym"
tagline: "Will camp your character to avoid the rez timer running out"
---

# MQ2AutoCamp
<!--desc-start-->
This plugin watches for a characters death (that is, have Revival Sickness) and it will camp your toon to the desktop to prevent your rez timer running out. If you get a rez, zone manually, or use /autocamp to abort MQ2AutoCamp cancels the current countdown. If you die again it'll start the countdown again. Every minute that passes during the countdown to camping it displays a popup warning for 30 seconds and lists the current countdown info to the chat window.
<!--desc-end-->

## Commands

<a href="cmd-autocamp/">
{% 
  include-markdown "projects/mq2autocamp/cmd-autocamp.md" 
  start="<!--cmd-syntax-start-->" 
  end="<!--cmd-syntax-end-->" 
%}
</a>
:    {% include-markdown "projects/mq2autocamp/cmd-autocamp.md" 
        start="<!--cmd-desc-start-->" 
        end="<!--cmd-desc-end-->" 
        trailing-newlines=false 
     %} {{ readMore('projects/mq2autocamp/cmd-autocamp.md') }}

## Settings

Example MQ2AutoCamp.ini,

```ini
[Voxvox_Settings]
Enabled=1
WaitMinutes=30
;default is 15
Endmac=1
;end the macro before camping
EndmacWhenDead=1
;end the macro upon dying
StartMacro=1
;start macro after a rez
StartMacroName=kissassist assist bobtank 98
;the macro to start after rez (exclude .mac)
```
