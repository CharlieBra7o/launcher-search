# Launcher Search
These are a couple of example desktop files on how to launch a browser search - completely launcher independent.

## Setup

### Installation
Just copy the **.desktop** files to **~/.local/share/applications/**.

### Configuration
In case Chromium is /not/ your default browser you need to modify all the **.desktop** files according to your setup.

### Adding your own engines
Basically just copy any **.desktop** file and Modify it. The **Name** entry is the shortcut you want to assign to the specific engine.

**IMPORTANT:** you /should always/ add a space (e.g. "g " behind said engine shortcut. Otherwise some (all?) launchers might launch different shortcuts in some cases.
**Reason:** Spaces between a shortcut and the search query are /not/ mandatory. In other words: "gfoobar" would launch the "g" shortcut with the query "foobar"
if both "g" and "gi" (/without/ trailing spaces) are registered as shortcuts,  "gi foobar" would be equivalent to "g i foobar" and the actual "gi" shortcut would be entirely inaccessible.

## Example
Type "g I hate it when" into your application launcher to initiate a Google search.
