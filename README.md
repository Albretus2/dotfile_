


#   My Dotfile

![App Screenshot](https://github.com/Albretus2/dotfile_/blob/main/Screen%20Shot%202024-06-14%20at%2013.39.41.png)

kumpulan configurasi file file dan shorcut atau keymaps

## 🐳 Fish shell (oh my fish)

install lewat brew
```bash
  brew install fish
```
copy folder fish, kemudian paste ke dalam `~/.config`


## ✦ wezterm

copy folder wezterm, kemudian paste ke dalam `~/.config`

#### **🚧 shorcut/keymaps**
`leader` == `ctrl + a`

| Keymaps            | deskripsi                                                              |
| ----------------- | ------------------------------------------------------------------ |
| `leader + s`  | split layar secara horizontal |
| `leader + v` | split layar secara vertical|
| `leader + h`| memindahkan fokus kursor ke atas |
| `leader + l`| memindahkan fokus kursor ke bawah |
| `leader + j`| memindahkan fokus kursor ke kiri |
| `leader + k`| memindahkan fokus kursor ke kanan |
| `leader + q`| menutup split layar |
| `cmd + t`| menambahkan tab baru|
| `cmd + w`| menutup tab|


## ✪ Neo Vim

copy folder nvim, kemudian paste ke dalam `~/.config`

struktur folder:

```bash
├── init.lua
├── lazy-lock.json
└── lua
    └── alber
        ├── core
        │   ├── init.lua
        │   ├── keymaps.lua
        │   └── options.lua
        ├── lazy.lua
        └── plugins
            ├── alpha.lua
            ├── auto-session.lua
            ├── autopairs.lua
            ├── bufferline.lua
            ├── colorscheme.lua
            ├── comment.lua
            ├── dressing.lua
            ├── formatting.lua
            ├── gitsign.lua
            ├── indent-blankline.lua
            ├── init.lua
            ├── lazygit.lua
            ├── linting.lua
            ├── lsp
            │   ├── lspconfig.lua
            │   └── mason.lua
            ├── lualine.lua
            ├── nvim-cmp.lua
            ├── nvim-tree.lua
            ├── substitution.lua
            ├── surround.lua
            ├── telescope.lua
            ├── todo-comments.lua
            ├── treesitter.lua
            ├── trouble.lua
            ├── vim-maximizer.lua
            └── which-key.lua

```

#### **🚧 shorcut/keymaps**
`leader` == `spasi` \
`command` == `shift + :` \

#### ⎇ Core

| Keymaps            | deskripsi                                                              |
| ----------------- | ------------------------------------------------------------------ |
| `i`  | masuke mode insert |
| `u`  | undo |
| `dl`  | delete |
| `jk`  | keluar mode insert |
| `command + q`  | keluar nvim |
| `command + w`  | save file |
| `command + wqa`  | keluar nvim dan save file |
| `leader + sh`  | split layar nvim secara horizontal |
| `leader + sv` | split layar nvim secara vertical|
| `leader + sx`| menutup split layar |
| `leader + to`| membuka tab baru |
| `leader + tx`| menutup tab |
| `leader + tp`| membuka tab sebelumya |
| `leader + tn`| membuka tab selanjutnya|
| `leader + tf`| membuka tab baru yang sama dengan tab sebelumnya|


**⎇ keymaps plugins** \
⌱ neo-tree (sidebar untuk nvim)
| Keymaps            | deskripsi                                                              |
| ----------------- | ------------------------------------------------------------------ |
| `leader + ee`  | membuka sidebar  |
| `leader + ef` | menutup sidebar|
| `leader + ec`| menutup semua folder yang ada di sidebar |
| `leader + er`| refresh sidebar/neotree |


\

----- 
\

⌱ telescope (mesin pencarian untuk nvim)
| Keymaps            | deskripsi                                                              |
| ----------------- | ------------------------------------------------------------------ |
| `leader + ff`  | membuka pencarian berdasarkan file |
| `leader + fr` | membuka pencarian berdasarkan file recent|
| `leader + fs`| membukan pencarian berdasarkan string atau text |
| `command + c`| menutup pencarian |

untuk lebih lanjut baca di `nvim / alber / plugins / telescope.lua`

\

----- 
\

⌱ command (shorct untuk membuat komentar)
| Keymaps            | deskripsi                                                              |
| ----------------- | ------------------------------------------------------------------ |
| `gcc`  | mengkomentari sebaris |

baca dokumentasi berikut untuk lebih lanjut https://github.com/numToStr/Comment.nvim


\

----- 
\

⌱ auto-session (untuk menyimpan file sebelumnya dan bisa di pulihkan)
| Keymaps            | deskripsi                                                              |
| ----------------- | ------------------------------------------------------------------ |
| `leader + ws`  | untuk menyimpan session |
| `leader + wr`  | untuk mengembalikan session |

\

----- 
\

⌱ lazygit (git yang ada di nvim)
| Keymaps            | deskripsi                                                              |
| ----------------- | ------------------------------------------------------------------ |
| `leader + lg`  | mengkomentari sebaris |

#### ⎇ lazyvim

| Keymaps            | deskripsi                                                              |
| ----------------- | ------------------------------------------------------------------ |
| `command + Lazy`  | membuka interface lazy |
