# SnippetManager
Snippet manager in LiveCode - for syntax colouring should run as plugin.<br>
MIT license

### Changes from original version
- changed to a master-detail layout
- tags are now read from the first line of the 'notes' field which is colourised - any word prefixed with a '#' is treated as a tag and dynamically generates a pill box graphic on top of the snippet code for illustration.
- All layout is adaptable for desktop - stacked versions for mobile to come
- SQL code debugged
- Syntax colourisation code debugged
- If SQLite database file is missing (for example if only the stack is copied to plugins), a SQLite file is created, the snippets table inserted and any data already in the datagrid populates the new SQLite file.

#### TODO
- mobile layout
- Integration with gist
- Possible integration with LiveCloud 
