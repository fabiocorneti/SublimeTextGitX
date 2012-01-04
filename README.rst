SublimeTextGitX
===============

Very simple plugin to open GitX (http://gitx.laullon.com/) from Sublime Text 2 (http://www.sublimetext.com/2).

Installing
----------

**Using Git:** Clone the repository in your Sublime Text 2 Packages directory and restart Sublime Text 2:

    git clone https://github.com/fabiocorneti/SublimeTextGitX

**Using the Package Control plugin:** The easiest way to install SublimeTextGitX is through Package Control, 
which can be found at http://wbond.net/sublime_packages/package_control .

Once you install Package Control, restart Sublime Text 2 and open the Command Palette.

Select "Package Control: Install Package", wait while Package Control fetches the latest package list, 
then select SublimeTextGitX when the list appears.

The advantage of using this method is that Package Control will automatically keep this plugin up to date.

Usage
-----

Open GitX and enable terminal usage by clicking on the GitX menu and then on ``Enable Terminal Usage...``;
GitX will create an executable named ``gitx`` inside ``/usr/local/bin``.

Open the command palette and execute the ``GitX: Open GitX`` command to open the GIT repository 
in which the currently opened file is located.

Sample user key binding to execute the command::

    { "keys": ["super+."], "command": "gitx_open" }

Configuration
-------------

Additional settings can be configured in the User File Settings:

``gitx_path``: the path to the ``gitx`` executable (default: ``"/usr/local/bin/gitx"``)

Changelog
---------
v0.1 (01-04-2011):

* Initial version

License
-------
See the LICENSE.txt file.
