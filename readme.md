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
-   `cmd+k` goes one line down
-   `cmd+j` goes one word part left
-   `cmd+l` goes one word part right

-   `cmd+9` goes one character left
-   `cmd+0` goes one character right

-   `cmd+backspace` deletes one word part left
-   `cmd+delete/cmd+fn+backspace` deletes one word part right

#### Fast movement

-   `cmd+alt+i` goes five lines up
-   `cmd+alt+k` goes five lines down
-   `cmd+alt+j` goes one word left
-   `cmd+alt+l` goes one word right

-   `cmd+alt+backspace` deletes one word left
-   `cmd+alt+delete/cmd+alt+fn+backspace` deletes one word right

#### Very fast Movement

-   `cmd+ctrl+i` goes a page up
-   `cmd+ctrl+k` goes a page down
-   `cmd+ctrl+j` goes to the start of the line
-   `cmd+ctrl+l` goes to the end of the line

(note: since vscode didn't like `cmd+ctrl+alt+[i j k l]`, this just uses `ctrl+alt+[i j k l]` for selection)

### Manipulation

#### Line manipulation

-   `cmd+y` moves the line up
-   `cmd+h` moves the line down
-   `cmd+u` outdents the line left
-   `cmd+o` indents the line right

#### File explorer manipulation (in the side panel)

-   `cmd+n` creates a new file
-   `cmd+shift+n` creates a new folder
-   `cmd+enter` opens a file

### Editor Navigation

#### Next/Previous Location

-   `ctrl+u` moves to the previous location in the code
-   `ctrl+o` moves to the next location in the code

#### Change tab

-   `ctrl+i` moves to the editor group above
-   `ctrl+k` moves to the editor group below
-   `ctrl+j` moves to the tab on the left
-   `ctrl+l` moves to the tab on the right

#### Move tab

-   `ctrl+shift+y` moves the current tab to the editor group above
-   `ctrl+shift+h` moves the current tab to the editor group below
-   `ctrl+shift+u` moves the current tab left one
-   `ctrl+shift+o` moves the current tab right one

#### Panel Focus

-   `cmd+1` focuses the terminal
-   `cmd+2` focuses the current editor (and cycles between editor groups)
-   `cmd+3` focuses on the file browser
-   `cmd+4` focuses on source control
-   `cmd+shift+f` focuses on search panel
