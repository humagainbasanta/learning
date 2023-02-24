# Making VSCODE easier
**Search  for the  to _keybindings.json_ using ```ctrl+shift+p``` shortcut**

1. This will create the new file without system popup
```Json
  {
        "key": "ctrl+n",
        "command": "explorer.newFile"
    }
```
2. Some more JSON for the vscode :

```JSON
// Place your key bindings in this file to override the defaults
//this will create the browser functionlaty in the vs code  for the contrl + number key actions
[
    { "key": "ctrl+1", "command": "workbench.action.openEditorAtIndex1" },
    { "key": "ctrl+2", "command": "workbench.action.openEditorAtIndex2" },
    { "key": "ctrl+3", "command": "workbench.action.openEditorAtIndex3" },
    { "key": "ctrl+4", "command": "workbench.action.openEditorAtIndex4" },
    { "key": "ctrl+5", "command": "workbench.action.openEditorAtIndex5" },
    { "key": "ctrl+6", "command": "workbench.action.openEditorAtIndex6" },
    { "key": "ctrl+7", "command": "workbench.action.openEditorAtIndex7" },
    { "key": "ctrl+8", "command": "workbench.action.openEditorAtIndex8" },
    { "key": "ctrl+9", "command": "workbench.action.openEditorAtIndex9" },
    //this will crteate the windows like switching back and forth in the next and previous editor
    {
          "key": "ctrl+tab",
          "command": "workbench.action.nextEditor"
      },
      {
          "key": "ctrl+shift+tab",
          "command": "workbench.action.previousEditor"
      },
      //this json will create the new file without sysyem popup
      {
        "key": "ctrl+n",
        "command": "explorer.newFile"
    }
  ]// Place your key bindings in this file to override the defaults

```