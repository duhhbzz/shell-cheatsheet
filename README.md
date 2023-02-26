# Shell Cheat Sheet

Just one Beyonder's Shell Cheat Sheet...

## How to Reset

| What to do                              | What it does               |
| --------------------------------------- | -------------------------- |
| <kbd>Ctrl ⌃</kbd> + <kbd>C</kbd>        | Cancel job                 |
| `reset`                                 | fix jank                   |
| <kbd>Cmd ⌘</kbd> + <kbd>K</kbd>         | **K**lear the **K**onsole  |
| **or** <kbd>Ctrl ⌃</kbd> + <kbd>L</kbd> | c**L**ear the conso**L**e  |
| <kbd>Ctrl ⌃</kbd> + <kbd>D</kbd>        | **D**one (en**D** of file) |

## Notes Format

````mkdn
# Goal: Install dev tools

The tools make the man, so install not just the necessary tools, but the best tools:

|                                What to do | What it does | Comment |
| ----------------------------------------: | :----------: | :------ |
|                                         x |      y       | z       |
| <kbd>Shift ⇧</kbd> + <kbd>Alt ⌥</kbd> + ' |  Prints "Æ"  | wow     |

1. Install Core Dev Tools:
    - Mac
        ```sh
        # install xcode command line tools
        xselect --install
        ```
    - Linux
        ```sh
        # install linux dev tools
        sudo apt install -y fish git vim curl
        ```
2. Install Extra Dev Tools:

    ```sh
    curl https://webi.sh/ | sh
    source ~/.config/envman/PATH.env

    webi fish
    webi vim-essentials
    ```

3. Learn
````
