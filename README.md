# dynamiclinenumbers.nvim

Toggle between relative and absolute line numbers based on mode.

# Installation

[Lazy.nvim](https://github.com/folke/lazy.nvim):

```lua
return {
  "iiixio/nvim-dynamiclinenumbers",
  name = "nvim-dynamiclinenumbers",
  config = function()
    require("nvim-dynamiclinenumbers").setup()
  end,
}
```
