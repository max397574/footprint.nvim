# footprints.nvim

this is a lua version of
[footprints](https://github.com/axlebedev/footprints)

## WIP

✨Features
--------
* At the moment only highlight lines where you left insert mode

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
Just type and leave insert mode.

⚙️Customization
-------------
```lua
-- lua, default settings
require("footprints_nvim").setup {
    highlight_color = "#A1A1A1"
}
```

🚫Limitations/Issues
--------------------
* Can't change line in insert mode

💡Future Plans/Ideas
------------------
Feel free to suggest stuff in the issues

👀Demo
------

https://user-images.githubusercontent.com/81827001/133116866-d9acedc2-ffdc-4b67-a6f2-b128b071be38.mp4

