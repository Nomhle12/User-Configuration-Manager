# User-Configuration-Manager
l build a User Configuration Manager that allows users to manage their settings such as theme, language, and notifications.

This program manages user settings stored in a dictionary.

Functions:
add_setting
Adds a new setting (key, value)
Converts both to lowercase
Fails if key already exists

update_setting
Updates an existing setting
Converts key and value to lowercase
Fails if key doesn’t exist

delete_setting
Removes a setting
Accepts string or tuple input
Converts key to lowercase
Returns success or “not found”

view_settings
Shows all settings
If empty → “No settings available.”
Otherwise formats as:
Current User Settings:
Theme: dark
