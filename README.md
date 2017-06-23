# Field Manager

Field Manager is a Craft CMS plugin to help make it easy to manage your fields and field groups. 

<img src="https://raw.githubusercontent.com/engram-design/FieldManager/master/screenshots/main.png" />


## Install

- Add the `fieldmanager` directory into your `craft/plugins` directory.
- Navigate to Settings -> Plugins and click the "Install" button.

**Plugin options**

- Change the plugin name as it appear in the CP navigation.
- Toggle the visibility of the plugin on the CP navgiation. Handy if you only need to use it from time to time.


## Cloning

Ever needed to clone a field - or even a whole field group? You can easily use Field Manager to do both!

Cloning an individual field gives you the opportunity to set its Group, Name, Handle and all other settings related to that field type. Settings available to edit are identical to settings available when using the regular field edit screen.

For cloning a field group, you'll be able to set the Name for this new group. All fields within this group will be duplicated.

One thing to note for field group cloning, is that fields are required to have unique handles. Therefore, Field Manager prefixes each field's handle with the group name you provide. For example, if your new group is called `New Group`, and it contains a field called `Body Content`, the field handle will be `newGroup_bodyContent`.

You may also set this yourself if you choose to, using the `Prefix` field when cloning a field group. Please note that it needs to be a valid handle (no spaces, no hyphens, underscores only).


## Export

You can export multiple fields, including their groups by simply using the checkboxes against each field or field group. The fields will be combined into a JSON document and downloaded through your browser. You can store this for later, or use the contents for your import.


## Import

Using the Import tab, you paste in your JSON file contents that you created through Field Managers export process. Once done so, you can configure the which fields to import, which group to add them to, and their name/handle.

<img src="https://raw.githubusercontent.com/engram-design/FieldManager/master/screenshots/import.png" />


## Supported FieldTypes

**Craft**

* Assets
* Categories
* Checkboxes
* Color
* Date/Time
* Dropdown
* Entries
* Lightswitch
* Matrix
* Multi-select
* Number
* Plain Text
* Position Select
* Radio Buttons
* Rich Text
* Table
* Tags
* Users

**[ButtonBox](https://github.com/supercool/Button-Box)**

* Buttons
* Colours
* Text Size
* Stars
* Width

**[SuperTable](https://github.com/engram-design/SuperTable)**

...and many more. Field Manager can handle just about any FieldType, the above are simply those that have been tested.


## Known Issues

* **Neo Fields** - although *cloning* of Neo fields appears to work, import and export is not currently supported. [#37](https://github.com/engram-design/FieldManager/issues/37)

Why not help out with this functionality and send a pull request? [Learn how](https://help.github.com/articles/about-pull-requests/).


## Bugs, feature requests, support

Found a bug? Have a suggestion? [Submit an issue](https://github.com/engram-design/FieldManager/issues)


## Changelog

[View JSON Changelog](https://github.com/engram-design/FieldManager/blob/master/changelog.json)
