# Better Keybindings

VSCode has some great keybinding support, but the default settings are utter nonsense, with no real justification behind them.

Some people prefer to use vim keybindings, however I have found these to be quite difficult to learn intuitively, and also not quite have the flexibility I was looking for. Instead, I made this.

Since I was focused on ergonomics over ease-of-learning, it does not strictly follow the defaults in a few places where it probably could, but I believe it is still very quick to pick up.

## How to use

### Navigation

The core idea of this is to use `cmd+[i j k l]` as your basic movement.

`alt` is added for selection.

#### Normal movement

-   `cmd+i` goes one line up
-   `cmd+j` goes one character left
-   `cmd+l` goes one character right
-   `cmd+k` goes one line down

#### Fast movement

-   `cmd+shift+i` goes five lines up
-   `cmd+shift+j` goes one word left
-   `cmd+shift+l` goes one word right
-   `cmd+shift+k` goes five lines down

#### Very fast Movement

-   `cmd+ctrl+i` goes a page up
-   `cmd+ctrl+j` goes to the start of the line
-   `cmd+ctrl+l` goes to the end of the line
-   `cmd+ctrl+k` goes a page down

(note: since vscode didn't like `cmd+ctrl+alt+[i j k l]`, this just uses `ctrl+alt+[i j k l]` for selection)

### Manipulation

#### Line manipulation

-   `ctrl+i` moves the line up
-   `ctrl+j` outdents the line left
-   `ctrl+l` indents the line right
-   `ctrl+k` moves the line down

#### File explorer manipulation (in the side panel)

-   `cmd+n` creates a new file
-   `cmd+shift+n` creates a new folder
-   `cmd+enter` opens a file

### Editor Navigation

#### Change tab

-   `cmd+y` moves to the editor group up
-   `cmd+u` moves to the tab on the left
-   `cmd+o` moves to the tab on the right
-   `cmd+h` moves to the editor group below

#### Move tab

-   `cmd+shift+y` moves the current tab to the editor group above
-   `cmd+shift+u` moves the current tab left one
-   `cmd+shift+o` moves the current tab right one
-   `cmd+shift+h` moves the current tab to the editor group below

#### Panel Focus

-   `cmd+1` focuses the terminal
-   `cmd+2` focuses the current editor (and cycles between editor groups)
-   `cmd+3` focuses on the file browser
-   `cmd+4` focuses on source control
-   `cmd+shift+f` focuses on search panel
