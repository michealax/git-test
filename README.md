# git-test

# conflict contents test b
shane
{
    "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
    "type": "AdaptiveCard",
    "version": "1.4",
    "body": [
        {
            "type": "TextBlock",
            "text": "My App",
            "weight": "Bolder",
            "size": "Medium",
            "spacing": "None"
        },
        {
            "type": "TextBlock",
            "text": "Pick an item from the dropdown list:",
            "wrap": true
        },
        {
            "type": "Input.ChoiceSet",
            "id": "dropdown",
            "style": "compact",
            "choices": [
                { "title": "Option 1", "value": "option1" },
                { "title": "Option 2", "value": "option2" },
                { "title": "Option 3", "value": "option3" }
            ],
            "placeholder": "Select an item"
        },
        {
            "type": "TextBlock",
            "text": "This is a section block with a button.",
            "wrap": true,
            "spacing": "Medium"
        },
        {
            "type": "ActionSet",
            "actions": [
                {
                    "type": "Action.Submit",
                    "title": "Click Me",
                    "data": {
                        "action": "clickMe"
                    }
                }
            ]
        }
    ],
    "actions": [
        {
            "type": "Action.Submit",
            "title": "Submit",
            "data": {
                "action": "submit"
            }
        },
        {
            "type": "Action.Submit",
            "title": "Cancel",
            "data": {
                "action": "cancel"
            }
        }
    ]
}
{
    "$schema": "http://adaptivecards.io/schemas/adaptive-card.json",
    "type": "AdaptiveCard",
    "version": "1.4",
    "body": [
        {
            "type": "Container",
            "items": [
                {
                    "type": "ColumnSet",
                    "columns": [
                        {
                            "type": "Column",
                            "width": "auto",
                            "items": [
                                {
                                    "type": "Image",
                                    "url": "https://via.placeholder.com/32", // 替换为实际图标 URL
                                    "size": "Small",
                                    "style": "Person"
                                }
                            ]
                        },
                        {
                            "type": "Column",
                            "width": "stretch",
                            "items": [
                                {
                                    "type": "TextBlock",
                                    "text": "My App",
                                    "weight": "Bolder",
                                    "size": "Medium",
                                    "spacing": "None"
                                }
                            ]
                        }
                    ]
                }
            ]
        },
        {
            "type": "TextBlock",
            "text": "Pick an item from the dropdown list:",
            "wrap": true,
            "spacing": "Medium"
        },
        {
            "type": "Input.ChoiceSet",
            "id": "dropdown",
            "style": "compact",
            "choices": [
                { "title": "Option 1", "value": "option1" },
                { "title": "Option 2", "value": "option2" },
                { "title": "Option 3", "value": "option3" }
            ],
            "placeholder": "Select an item"
        },
        {
            "type": "Container",
            "items": [
                {
                    "type": "TextBlock",
                    "text": "This is a section block with a button.",
                    "wrap": true,
                    "spacing": "Medium"
                },
                {
                    "type": "ActionSet",
                    "actions": [
                        {
                            "type": "Action.Submit",
                            "title": "Click Me",
                            "data": {
                                "action": "clickMe"
                            }
                        }
                    ]
                }
            ],
            "spacing": "Medium"
        }
    ],
    "actions": [
        {
            "type": "ActionSet",
            "actions": [
                {
                    "type": "Action.Submit",
                    "title": "Cancel",
                    "data": {
                        "action": "cancel"
                    }
                },
                {
                    "type": "Action.Submit",
                    "title": "Submit",
                    "style": "positive",
                    "data": {
                        "action": "submit"
                    }
                }
            ]
        }
    ]
}
