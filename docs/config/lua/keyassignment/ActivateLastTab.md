# ActivateLastTab

*Since: nightly builds only*

Activate the last active tab. If there is none, it will do nothing.

```lua
return {
  leader = { key="a", mods="CTRL" },
  keys = {
    -- CTRL-a, followed by CTRL-o will switch back to the last active tab
    {key="o", mods="LEADER|CTRL", action="ActivateLastTab"},
  }
}
```


