# SnippetManager
Snippet manager in LiveCode. Drop into plugins folder to use as plugin.<br>
MIT license

### Changes in version 1.2
- Tags are recognised in the entire text of the Notes field instead of only line 1, althogh that remains coloured and prefixed with 'Tagline:'. Any single word in the Notes field that tarts with a '#' will be recognised as a tag and a pill graphic created.
- Optimised code for repositioning tag graphics on stack resize.
- Further optimisatoin of colorisation code (initalisation called only once)
- Fixed issue with saving the snippet code
- Minor code refactoring

### Changes in version 1.1
- changed to a master-detail layout
- tags are now read from the first line of the 'notes' field which is colourised - any word prefixed with a '#' is treated as a tag and dynamically generates a pill box graphic on top of the snippet code for illustration.
- All layout is adaptable for desktop - stacked versions for mobile to come
- SQL code debugged
- Syntax colourisation code debugged
- If SQLite database file is missing (for example if only the stack is copied to plugins), a SQLite file is created, the snippets table inserted and any data already in the datagrid populates the new SQLite file.

<img width="1099" alt="Screenshot 2022-11-27 at 17 26 13" src="https://user-images.githubusercontent.com/5677273/204150560-693786c6-4f8b-493d-bb23-1692f28e5f0f.png">


#### TODO
- mobile layout
- Integration with gist
- Possible integration with LiveCloud 
