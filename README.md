# mac-like-sublime-hotkey-for-windows
Sublime hot key config for windows so that it behaviors like which of mac.
```javascript
[
  { "keys": ["ctrl+e"], "command": "move_to", "args": {"to": "eol", "extend": false} },
  { "keys": ["ctrl+a"], "command": "move_to", "args": {"to": "bol", "extend": false} },
  { "keys": ["ctrl+k"], "command": "run_macro_file", "args": {"file": "res://Packages/Default/Delete to Hard EOL.sublime-macro"} },
  { "keys": ["ctrl+backspace"], "command": "run_macro_file", "args": {"file": "res://Packages/Default/Delete to Hard BOL.sublime-macro"} },
  { "keys": ["alt+a"], "command": "select_all" },
]
```
