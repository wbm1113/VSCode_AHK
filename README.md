# VSCode_AHK
Syntax highlighting for AHK

# Installation
Download the extension and add it to your local extension directory.

Add the following to your user settings:

```"editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "AHKString",
                "settings": {
                    "foreground" : "#CE9178"
                }
            },
            {
                "scope": "AHKBool", 
                "settings": {
                    "foreground" : "#569CD6"
                }
            },
            {
                "scope": "AHKFlowLogical",
                "settings": {
                    "foreground" : "#C586C0"
                }
            },
            {
                "scope": "AHKKeywords",
                "settings": {
                    "foreground" : "#9CDCFE"
                }
            },
            {
                "scope": "AHKKeywords2",
                "settings": {
                    "foreground" : "#569CD6"
                }
            },
            {
                "scope": "AHKDirectives",
                "settings": {
                    "foreground" : "#569CD6"
                }
            },
            {
                "scope": "AHKBuiltInVar",
                "settings": {
                    "foreground" : "#569CD6"
                }
            },
            {
                "scope": "AHKClassProperty",
                "settings": {
                    "foreground" : "#9CDCFE"
                }
            },
            {
                "scope": "AHKClassItem",
                "settings": {
                    "foreground" : "#4EC9B0"
                }
            },
            {
                "scope": "AHKFunction",
                "settings": {
                    "foreground" : "#DCDCAA"
                }
            },
            {
                "scope": "AHKCommand",
                "settings": {
                    "foreground" : "#DCDCAA"
                }
            },
            {
                "scope": "AHKSubroutine",
                "settings": {
                    "foreground" : "#DCDCAA"
                }
            },
            {
                "scope": "AHKEscape",
                "settings": {
                    "foreground" : "#D7BA7D"
                }
            },
            {
                "scope": "AHKNumber",
                "settings": {
                    "foreground" : "#B5CEA8"
                }
            },
            {
                "scope": "AHKComment",
                "settings": {
                    "foreground" : "#6A9955"
                }
            },
            {
                "scope": "AHKPunctuation",
                "settings": {
                    "foreground" : "#dadada"
                }
            },
            {
                "scope": "EverythingElse",
                "settings": {
                    "foreground" : "#9CDCFE"
                }
            },
        ]
    },```
