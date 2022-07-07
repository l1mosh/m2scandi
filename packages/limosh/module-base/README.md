# Limosh Base Module

This module contains things which should not go in specific functionality
modules, the first example of needing this module was to add a Limosh tab
to the admin screen - this is a task that should not be done by any one of the
modules which adds to the tab (because if you removed the module that defined
it then all the other modules would fail to show their config), therefore the
base module exists to fulfill this purpose.

In future the scope of the module may grow but extreme care should be taken to
ensure that it does not become a "dumping ground" for miscellaneous code which
should exist in a seperate module.
