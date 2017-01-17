moodle-local_resort_courses
===========================

Moodle plugin which sorts a category page automatically as soon as a course has been added or modified


Requirements
------------

This plugin requires Moodle 3.2+


Installation
------------

Install the plugin like any other plugin to folder
/local/resort_courses

See http://docs.moodle.org/en/Installing_plugins for details on installing Moodle plugins


Usage & Settings
----------------

The local_resort_courses plugin acts completely behind the scenes. After installing local_resort_courses, as soon as a course has been added or modified in a category, local_resort_courses verifies that the containing category page is automatically sorted just as it would be sorted when you click the "Re-sort courses by name" button on the category page.
To configure the behaviour of the plugin, please visit Site administration -> Courses -> Re-sort courses.

There, you find two sections:

### 1. Sort order

By default, local_resort_courses sorts categories by course full name in ascending order, just as the "Re-sort courses by name" button on the category page does. By setting the "Sort order" setting to another value, you can control the sort order of the course list.

### 2. Skip categories

By default, local_resort_courses handles re-sort jobs for every category. By selecting one or multiple categories in the "Skip categories" setting, you can define categories which mustn't be sorted automatically and whose sort order can still be controlled manually.

By default, when you select one or multiple categories in the "Skip categories" setting, local_resort_courses skips only the categories which are selected in the preceding setting. By checking the "Skip categories recursively" setting, you can define that local_resort_courses should skip the selected categories and all of their descendant categories when handling re-sort jobs.


Themes
------

The local_resort_courses plugin acts behind the scenes, therefore it works with all moodle themes.


Further information
-------------------

local_resort_courses is found in the Moodle Plugins repository: http://moodle.org/plugins/view/local_resort_courses

Report a bug or suggest an improvement: https://github.com/moodleuulm/moodle-local_resort_courses/issues


Moodle release support
----------------------

Due to limited resources, local_resort_courses is only maintained for the most recent major release of Moodle. However, previous versions of this plugin which work in legacy major releases of Moodle are still available as-is without any further updates in the Moodle Plugins repository.

There may be several weeks after a new major release of Moodle has been published until we can do a compatibility check and fix problems if necessary. If you encounter problems with a new major release of Moodle - or can confirm that local_resort_courses still works with a new major relase - please let us know on https://github.com/moodleuulm/moodle-local_resort_courses/issues


Right-to-left support
---------------------

This plugin has not been tested with Moodle's support for right-to-left (RTL) languages.
If you want to use this plugin with a RTL language and it doesn't work as-is, you are free to send us a pull request on
github with modifications.


PHP7 Support
------------

Since Moodle 3.0, Moodle core basically supports PHP7.
Please note that PHP7 support is on our roadmap for this plugin, but it has not yet been thoroughly tested for PHP7 support and we are still running it in production on PHP5.
If you encounter any success or failure with this plugin and PHP7, please let us know.


Copyright
---------

Ulm University
kiz - Media Department
Team Web & Teaching Support
Alexander Bias
