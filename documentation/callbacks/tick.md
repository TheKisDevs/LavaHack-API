---
description: TickEvent.ClientTickEvent
---

# Tick

```lua
-- Simple step
this:registerCallback("tick", function(tick)
    mc.player.stepHeight = 2
end)
```

or

```lua
-- Simple step
this:registerCallback("events", function(event)
    if(event:getName() == "tick") then
        mc.player.stepHeight = 2
    end
end)
```
