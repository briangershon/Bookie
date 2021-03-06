User Docs
=========


Importing
----------
Bookie currently supports the Delicious export and the Google Bookmarks export
formats.


- Delicious: You can export from Delicious by going to `Settings` and clicking
  the `Import / Upload Bookmarks` link under the `Bookmarks` section.
- Google Bookmarks: TBD

The importer might take a bit on large sets of bookmarks. Let us know if you
run into any issues so we can improve our import process.

Settings to think about
------------------------

allow_edit: set this to 1 if you want to enable edits via the web ui. Since
your site isn't protected by a username and password, you don't want to do this
on a publicly available instance of Bookie. Leave it at 0 and use an API tool
such as the `Chrome Plugin`_ to make edits and remove bookmarks.

ToDo
-----
Look into other formats to import, create the ability to choose/detect the
import format for new importers.

Make sure we force submitting your API Key once that's complete as part of the
form submission. Help prevent people from using the importer against you.

.. _Chrome Plugin: https://github.com/mitechie/delicious-chrome-extension
