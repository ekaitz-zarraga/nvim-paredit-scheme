# Scheme extension for nvim-paredit

> **This extension has been DEPRECATED because `nvim-paredit` deprecated the
> API and now supports scheme directly. This is not needed anymore.**
> Thanks to Julien Vincent for his work! I don't need to maintain this anymore
> :)

This is a Scheme extension for [`nvim-paredit`][paredit].

[paredit]: https://github.com/julienvincent/nvim-paredit

Install it with any plugin manager you like and then:

``` lua
local paredit = require "nvim-paredit"
local scheme  = require "nvim-paredit-scheme"

scheme.setup(paredit)
```
