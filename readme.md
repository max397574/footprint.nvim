# footprints.nvim

this is a lua version of
[footprints](https://github.com/axlebedev/footprints)

✨Features
--------
* Highlights lines where you changed text.
* Darker highlight based on how old changes are.

📦Installation
------------
Use your favourite package manager and call setup function.
```vim
" Vimscript with vim-plug
Plug 'max397574/footprints.nvim'
```

```
-- lua with packer.nvim
use {"max397574/footprints.nvim"}
```

✅Usage
-----
Just type and see your changes.

⚙️Customization
-------------
```lua
-- lua, default settings
require("footprints_nvim").setup {
    settings.highlight_color_1 = "#000000" --for the oldest change
    settings.highlight_color_2 = "#2E2E2E"
    settings.highlight_color_3 = "#616161"
    settings.highlight_color_4 = "#969696"
    settings.highlight_color_5 = "#A1A1A1" -- for the newest change
    settings.change_step_size = 1 -- how much time until a change goes to the next category
}
```

🚫Limitations/Issues
--------------------
Write issues in the issues tab

💡Future Plans/Ideas
------------------
Smarter highlight colors

👀Demo
------

https://user-images.githubusercontent.com/81827001/133138785-4d8d550a-5762-4223-b24d-97d3aa4f1bf4.mp4
