ChromePhp wrap for PHP
================

## Summary
Forked from unknownuser88/consolewrap.
Replacing the functionality for ChromePhp.

This plugin places your selected variable in ChromePhp as ChromePhp::log('variable' , variable); PHP only.
THIS IS NOT A SNIPPET.

## Install

#### Git Clone
Clone this repository in to the Sublime Text "Packages" directory, which is located where ever the
"Preferences" -> "Browse Packages" option in sublime takes you.

## Key Binding

The default key binding is "ctrl+shift+a".

## Key Binding Conflicts

Unfortunately there are other plugins that use "ctrl+shift+a", this is a hard problem to solve. If ChromePhp Wrap doesn't work, then you have two options:

1. Add ```{"keys": ["ctrl+shift+a"],  "command": "chromephpwrap"}``` to your user keybindings file. This will override anything specified by a plugin.
2. Find the offending plugin, and change the shortcut in its sublime-keymap file (will revert on updates).


## Usage

First you need to select a variable and press "ctrl+shift+a". The ChromePhp::log line will appear on the next line. 

You can Also remove all ChromePhp::log from your selsection or from all document 

---
