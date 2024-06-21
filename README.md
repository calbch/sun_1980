<div align="center">
  <img src="/doc/manual.jpeg" alt="Your Image Description">
</div>


1980s Sun
===

Inspired by [this tweet](https://x.com/usgraphics/status/1803481619090776557) from [United States Graphics Company](https://x.com/usgraphics).

Build with: http://git.io/lush.nvim

Feel free to contribute.

# Lazy Setup

`dir` is wherever you saved this repo. I know you can [build](https://github.com/rktjmp/lush.nvim/blob/main/BUILD.md)
 it. But it's nowhere near finished.

```lua
  {
    dir = "~/Code/1980_sun",
    lazy = false,
    priority = 1000,

    init = function()
      vim.cmd.colorscheme("1980_sun")
    end,
  },

```
