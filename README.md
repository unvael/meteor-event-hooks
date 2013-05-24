##Event Hooks - Meteor Smart Package
[![endorse](https://api.coderwall.com/benjaminrh/endorsecount.png)](https://coderwall.com/benjaminrh)

Provides hooks for various user-triggered events.

###API

 * `Hooks.init()` (client) - Initialize the event system. Put this in your `Meteor.startup`.
 * `Hooks.updateFocus` (client) - Number of milliseconds to wait before checking whether the window is focused (default is 500)
 * `Hooks.onLoseFocus = function () { ... }` (anywhere) - Provide a callback to run when the window loses focus
 * `Hooks.onGainFocus = function () { ... }` (anywhere) - Provide a callback to run when the window loses focus
 * `Hooks.onCloseSession = function () { ... }` (anywhere) - Provide a callback to run when the window/tab is closed

###How to use?

1. Install [meteorite](https://github.com/oortcloud/meteorite)
2. `mrt add event-hooks`