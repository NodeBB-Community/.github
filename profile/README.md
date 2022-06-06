## What is the NodeBB Community Organization?

The NodeBB Community organization on GitHub manages a collection of third-party plugins that are considered under passive maintenance. This level of maintenance means that the plugin is no longer in active development, although bug fixes and pull requests are still accepted and reviewed.

Any additional functionality can be requested by emailing sales@nodebb.org directly.

## Why is *X* plugin in this org?

The plugin may be considered feature complete, or stable, or has been gifted to the NodeBB-Community org by the original plugin author. While they are no longer actively maintained by the core NodeBB team, plugins in this org should still work, and should be installable via npm.

Depending on the age of the plugin, they may not be in the ACP > Manage > Plugins list. If you install the plugin via npm and the plugin works as intended, feel free to open up an issue in that plugin's issue tracker, so they a developer can update the `nbbpm.compatibility` string.

## A plugin in this org does not work with NodeBB

If you have attempted to install a plugin in this org (via npm or otherwise) and it does not function (e.g. crashes NodeBB, functionality missing, etc.) — open an issue in that plugin's issue tracker.

Include the following for best results:

* The version of the plugin you installed
* Your version of NodeBB (look inside `package.json`, or run `git rev-parse HEAD` to get a commit hash—that also works.)
* A stack trace or error message if there is one
