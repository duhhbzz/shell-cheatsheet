# Shell Cheat Sheet

#### Summary

My cheat sheet from BeyondCode Boot Camp's Shell Workshop. Quick hints, tips, & environment set up.

## REMEMBER

#### TREL - Try, Read, Evaluate, Loop.

Do or do not, there is no try. It is proven that you learn by doing. Projects are an essential
part of the learning process. There are two modes your mind may go into when learning:

#### **Focus Mode** & **Diffuse Mode**

-   Focus Mode - focus mode occurs when you're consciously focused on you task, whether it is
    reading, watching videos, or working on a project. Often people will may fall into a Robot mode
    of mimicking without comprehending the task they did. It's almost like auto pilot. To gain the best
    benefits from Focus Mode, I personally have to do the task on my own. Break it, fix it, all of it.

-   Diffuse Mode - diffuse mode occurs at the subconcious level, this is where apiphanies often occur.
    Times when you are not actively learning or studying, like doing the dishes or cooking for example.

## Bash Shell Command Cheat Sheet

| **Input Command**                       | **Command Results**                |
| --------------------------------------- | ---------------------------------- |
| **How to Reset**                        |                                    |
| <kbd>Ctrl ⌃</kbd> + <kbd>C</kbd>        | Cancel job                         |
| `reset`                                 | fix jank [resets terminal          |
| <kbd>Cmd ⌘</kbd> + <kbd>K</kbd>         | **K**lear the **K**onsole          |
| **or** <kbd>Ctrl ⌃</kbd> + <kbd>L</kbd> | c**L**ear the conso**L**e          |
| <kbd>Ctrl ⌃</kbd> + <kbd>D</kbd>        | **D**one (en**D** of file)         |
| **Navigate & Manipulate files**         |                                    |
| `pwd`                                   | print working directory            |
| `cd`                                    | change directory                   |
| `mkdir`                                 | makes directory                    |
| `ls`                                    | prints list of files & directories |
| `rm` **&** `rm -r`                      | deletes files & directories        |
| `cp` **&** `cp -r`                      | copies files & directories         |
| `touch`                                 | creates new file                   |
| **Git Commands**                        |                                    |

## Notes

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

    webi aliasman bat curlie \
      fd fzf jq keypairs lsd \
      rg sd serviceman

    aliasman cat 'bat --style=plain --pager=none'
    aliasman ll 'lsd -lAhF'
    aliasman curl 'curlie'

    ```

3. Learn
````
