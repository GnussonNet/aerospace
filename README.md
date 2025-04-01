Karabiner-Elements workaround:
```
{
    "description": "Change left_option to 3 modifiers combo (rcmd, ralt, rctrl), f17 when used alone",
    "manipulators": [
        {
            "from": {
                "key_code": "left_option",
                "modifiers": { "optional": ["any"] }
            },
            "to": [
                {
                    "key_code": "right_control",
                    "modifiers": ["right_command", "right_option"]
                }
            ],
            "to_if_alone": [{ "key_code": "f17" }],
            "type": "basic"
        }
    ]
}
```
