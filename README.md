# nvim-spider-utf8

This repo provides an extra rockspec to easily enable
[`nvim-spider`]'s [UTF-8 support][enable-utf8] in [`lazy.nvim`].

You will need `lazy.nvim` v11+ to use this rockspec.

## Getting Started

Add the following to your `lazy.nvim` config:

```lua
{
  "chrisgrieser/nvim-spider",
  dependencies = {
    { "rami3l/nvim-spider-utf8", build = "rockspec" },
  },
}
```

[enable-utf8]: https://github.com/chrisgrieser/nvim-spider?tab=readme-ov-file#utf-8-support
[`nvim-spider`]: https://github.com/chrisgrieser/nvim-spider
[`lazy.nvim`]: https://github.com/folke/lazy.nvim
