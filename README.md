# Scheme extension for nvim-paredit

This is a Scheme extension for [`nvim-paredit`][paredit].

[paredit]: https://github.com/julienvincent/nvim-paredit

Install it with any plugin manager you like and then:

``` lua
local paredit = require "nvim-paredit"
local scheme  = require "nvim-paredit-scheme"

scheme.setup(paredit)
```
