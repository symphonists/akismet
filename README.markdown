# Akismet Spam Filtering

* Version: 1.4
* Author: Symphony Community (https://github.com/symphonists)
* Build Date: 2011-03-04
* Requirements: Symphony 2.2

## Installation

1. Upload the 'akismet' folder in this archive to your Symphony 'extensions' folder.
2. Enable it at System > Extensions.
3. Go to System > Preferences and enter your Akismet API key.
4. Add the "Akismet Spam Filtering" filter rule to your Event via Blueprints > Events
5. Save the Event.
6. Follow the directions at the bottom of your Event's documentation section
7. Boogie all night long!

## Changelog

* **1.4** Markdownified README, updated Configuration accessors, removed reference to Wordpress in favour of Akismet
* **1.3** Fixed incorrectly escaped string
* **1.2** Uses the "Akismet CURL Class", written by [David Pennington](http://www.codexplorer.com), for connections to the Akismet server. This is faster than using fsockopen.