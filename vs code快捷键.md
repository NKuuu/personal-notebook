```json
// Place your key bindings in this file to override the defaults
[
    // 光标左移一位
    {
        "key": "alt+h",
        "command": "cursorLeft",
        "when": "textInputFocus"
    },
    // 光标右移一位
    {
        "key": "alt+l",
        "command": "cursorRight",
        "when": "textInputFocus"
    },
    // 光标上移一位
    {
        "key": "alt+k",
        "command": "cursorUp",
        "when": "textInputFocus"
    },
    // 光标下移一位
    {
        "key": "alt+j",
        "command": "cursorDown",
        "when": "textInputFocus"
    },
    // 光标左移一个单词
    {
        "key": "ctrl+alt+h",
        "command": "cursorWordLeft",
        "when": "textInputFocus"
    },
    // 光标右移一个单词
    {
        "key": "ctrl+alt+l",
        "command": "cursorWordRight",
        "when": "textInputFocus"
    },
    // 格式化
    {
        "key": "ctrl+alt+/",
        "command": "notebook.formatCell",
        "when": "editorHasDocumentFormattingProvider && editorTextFocus && inCompositeEditor && notebookEditable && !editorReadonly && activeEditor == 'workbench.editor.notebook'"
    },
    // 在当前行上方插入一行
    {
        "key": "ctrl+enter",
        "command": "editor.action.insertLineBefore",
        "when": "editorTextFocus && !editorReadonly"
    },
    // 在当前行下方插入一行
    {
        "key": "shift+enter",
        "command": "editor.action.insertLineAfter",
        "when": "editorTextFocus && !editorReadonly"
    },
    // 删除一行
    {
        "key": "alt+d",
        "command": "editor.action.deleteLines",
        "when": "editorTextFocus"
    },
    // ctrl+shift+/多行注释
    {
        "key":"ctrl+shift+/",
        "command": "editor.action.blockComment",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+w",
        "command": "workbench.action.closeWindow",
        "when": "!editorIsOpen && !multipleEditorGroups"
    },
    // 选中当前单词，或下一个
    {
        "key": "ctrl+w",
        "command": "editor.action.addSelectionToNextFindMatch",
        "when": "editorFocus"
    }
]
```

