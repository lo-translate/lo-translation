# Lo Translation

Initial translations based on Korean translation patch by BeepedWhenIShouldaBooped.
Some translations by Maurex found in Google Docs or the Discord.


## Editing

The translation files are text files in [PO format](https://www.gnu.org/software/gettext/manual/html_node/PO-Files.html).
They can be edited with a text editor or with a PO editor like [poedit](https://github.com/vslavik/poedit).

Some text on screen automatically wraps, some extends outside of the box, and
some will get cut off if it is more than 1 line.  There are also strings
that if replaced will prevent the game from loading (stuck at 0% loading). It
is important to test after translating to ensure the game loads and the text
displays how you expect.

## Testing

To test translations before submitting a pull request create a ZIP archive of
the repo files named "LoTranslation.zip" and place it in the same folder as 
[LoPatcher](https://github.com/lo-translate/lo-patcher). After launching the
patcher with the archive in the same folder, it will use the translations from
the archive when applying the patch.
