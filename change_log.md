
Change Log

* 0.1
  - Start of log.
  - MD/lua apis in place, with support for basic widgets.
* 0.2
  - Added integration into standard options menu.
* 0.3
  - Added submenu support to options menus.
  - Added size/position control to standalone menu.
* 0.4
  - Refined frame offset and size calculations.
  - Enabled vertical scrollbars.
  - Added "echo" arg to widgets.
  - Added callback support on menu closing.
* 0.5
  - Added generic property support for labels and buttons.
  - Added support for arguments referencing Helper constants.
* 0.6
  - Added generic property support for editboxes, sliders, dropdowns.
  - Replaced generic cue callbacks with ones for specific events.
* 0.7
  - Added checkbox support.
  - Added option to remove stock menu open animations.
* 0.8
  - Added support for dynamically updating widgets in live menus.
* 0.9
  - Added box-text, status-bar, icon widgets.
  - Added param support to Add_Row.
  - Changed args for Send_Command.
  - Added option to adjust mouseover font size globally.
  - Varous bugfixes and refinements.
* 0.10
  - Changed options menu $cue to $onOpen.
  - Added generic property support to frames and tables.
  - Added id and echo to rows and menus.
  - Added several menu level events.
  - Bug fix for confusion when a menu is created while the prior menu had pending events.
  - Various other tweaks.
* 0.11
  - Added support for changing column widths.
* 0.11.1  
  - Fixed reloaded signal to not depend on named pipes api.
* 0.12
  - Removed Display_Menu command. Options menus now autodisplay after one frame.
* 0.12.1
  - Dropdown callback value clarified as "option_id".
  - Add_Submenu_Link documentation typo fixed for arg "id".
* 0.13
  - Dropdown options changed to no longer use an "id" field, and callback now returns "option_index" and "option" instead of "option_id".
* 0.14
  - Add Refresh_Menu command for options menus.
  - Added in-game toggle to turn on api debug logging.
* 1.0
  - General release.
* 1.0.1
  - Update for x4 3.0 beta 4.
