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
