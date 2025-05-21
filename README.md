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

- Normal Mode

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

## Refrences

[![Cheat Sheet VIM](https://img.shields.io/badge/Vim_Cheat_Sheet-VIM)](https://vim.rtorr.com/)

[![Video Reference](https://img.shields.io/badge/Video%20Reference-8A2BE2)](https://youtu.be/qPyv6_iRsWc)

[![More Tricks](https://img.shields.io/badge/More%20Tricks-FF2222)](https://youtu.be/RdyfT2dbt78)
