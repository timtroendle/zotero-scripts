# Migrate from Papers3 to Zotero

To migrate a Papers3 library or parts of it do the following. There are many annoying manual steps, but I cold not come up with a better solution, if highlights and notes are to be retained. The issue is that Papers3 does not save them in the PDF -- one of the reasons to avoid it.

1. Add tags for flags, ratings, and unread status inside of Papers3 as Zotero supports tags only.
2. Export all entries as bibtex, including complete metadata.
3. Run clean-papers-bibtex to remove references to Papers3 or its files.
4. Import the bibtex into Zotero. Do not sync before performing the next step!
5. Close Zotero and run update-date-added to apply the date-added fields from the bibtex file.
6. Export all PDFs from Papers3.
7. (optional) Papers3 3.4.10 has a bug (one of many) in which the comments aren't exported into the PDFs, only the highlights. To retain the comments, manually copy them.
8. Manually assign PDF files to Zotero entries.
9. Manually copy reviews from Papers to Zotero notes.
