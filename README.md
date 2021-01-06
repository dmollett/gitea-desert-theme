# Gitea Desert Theme 🏜️
A super simple desert style theme for Gitea tested on 1.14.0.

**Not Yet Completed! Expected 13/01/2021**

## Colors Used
- #FBE8A6 (Yellow)
- #F4976C (Orange)
- #303C6C (Dark Blue)
- #B4DFE5 (Mid Blue)
- #D2FDFF (Light Blue)

## Installation
### Prerequisite
If you have not customed Gitea before than there is a file at `custom/conf/app.example.ini`.

This needs to be copied and renamed to `app.ini` now your gitea instance will be using a custom configuration.

### Method
1. Edit the `app.ini` and you will find a line that says `[ui]`. Under that will be `themes = gitea,arc-green`, just add a comma and `desert` to the list.
2. OPTIONALLY you can also set `DEFAULT_THEME = desert`
3. Copy the `theme-desert.css` file into `custom/public/css/theme-desert.css`
4. Restart Gitea

## Selecting a Theme
When logged in you can now select a theme to be user in the account settings

## Feedback and Issues
If you find an issue please do put it in the issue tracker so it can be looked into.
