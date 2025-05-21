
# VsVim - Setup Guide

This post will guide you how to Setup Vim emulation for Visual Studio and VS Code for Windows/Mac and some guide about the keybinds.
## Installation

Getting started with the Installation of Vim Emulation for your IDE

```bash
  -> VS - Code
  Go to Extensions
  Search Vim 
  Download the extension by vscodevim
```

```bash
  -> Visual Studio (Windows)
  Go to Extensions from Toolbar
  Search VsVim
  Download the extension
  Repo Link - (https://github.com/VsVim/VsVim)

  -> Visual Studio (MAC)
  The process remains same as for Windows.
  If you face some issues reguarding Installation try to
  install the one in here. (https://github.com/VsVim/VsVim/issues/2988)
```
## KeyBinds

As you have already completed with the installation we will go through some basic KeyBinds for usage 

# Commands are case sensitive. 

- Modes in VIM

  Normal Mode (Esc)
  
  Insert Mode (Esc)

  Visual Mode (v or Shift + V for Selection in line)

  Command Mode (first toggle Normal Mode then type ":" with command.)

  Replace Mode (r for single letter or Shift + R for continuous replacement)

  We can switch between Normal/Insert Mode by pressing Esc or "<C-[>".

- # Normal Mode 
  
    By default, IDE starts in “normal” mode. In Normal mode key presses don’t work as one would expect. The KeyStrokes here dont get inserted into the document as text but are keys to move cursor.
    
    - Move The Cursor
        
        h [Moves one character left]

        j [Moves one row down]

        k [Moves one row up]

        l [Moves one character right]

        The commands can also be paired with a number to multiply the input several times i.e Numkey and KeyStroke (3k , 5l , 2j , 4h)
    - Basic Word Movement

        w [Move to beginning of next word]

        b [Move to beginning of previous word]

        e [Move to end of the next word]

        W [Move to beginning of next word after a whitespace]

        B [Move to beginning of previous word after a whitespace]

        E [Move to end of the next word after a whitespace]

    - Line Movements

        0 [Move to beginning of line]
        
        $ [Move to end of line]

- # Insert Mode
    
    This is the second most used mode in VIM and is familiar to most of the users. In insert mode you can use IDE like regular text editor to code.

    - Insert Mode Commands

        i [For entering Insert Mode]
        
        a [Moves the cursor to next character and enters Insert Mode]

        o [Inserts a new line below the current line and enters Insert Mode]

        I [Moves the cursor to beginning of the line and enters Insert Mode]

        A [Moves the cursor to end of the line and enters Insert Mode]

        O [Inserts a new line above the current line and enters Insert Mode]

- # Visual Mode

    Visual Mode is used to make selections of text, similar to how clicking and selecting it with mouse.

    - Visual Mode Commands

        v [Selects current character and enters into Visual Mode]
        
        V [Selects whole line and enters into Visual Mode]

        Ctrl + v [For entering Visual Mode blockwise]

- # Command Mode

    Command Mode has a variety of commands and can do things that Normal Mode can't do easily.

    - Commands

        Type the command with ":" as prefix it should appear at the bottom of window. Ex - ":%s/foo/bar/g" to replace all 'foo' with 'bar'

        : [Enters the Command Mode]

        % [Means across all lines]

        s [Means substitute]

        /foo [is a regex to find things to replace]

        /bar/ [is a regex to replace things with]

        /g [means global, otherwise it would only execute per line]

        :h / :help [Read docs for help]

- # Replace Mode

    Replace Mode allows to replace existing text by directly typing over it. Before entering this Mode we get into Normal Mode and put your cursor on the top of first character that you want to replace. 

    - Replace Commands

        r [For single letter]
        
        R [For continuous replacement]
## References

[![Cheat Sheet VIM](https://img.shields.io/badge/Vim_Cheat_Sheet-VIM)](https://vim.rtorr.com/)

[![Video Reference](https://img.shields.io/badge/Video%20Reference-8A2BE2)](https://youtu.be/qPyv6_iRsWc)

[![FreeCodeCamp](https://img.shields.io/badge/FreeCodeCamp-2222DF)](https://www.freecodecamp.org/news/tag/vim/)

[![More Tricks](https://img.shields.io/badge/More%20Tricks-DF2222)](https://youtu.be/RdyfT2dbt78)
