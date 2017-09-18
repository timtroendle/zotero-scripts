# Migrate from Papers3 to Zotero

To migrate a Papers3 library or parts of it do the following. There are many annoying manual steps, but I cold not come up with a better solution, if highlights and notes are to be retained. The issue is that Papers3 does not save them in the PDF -- one of the reasons to avoid it.

1. Export all entries as bibtex, including complete metadata.
2. Run clean-papers-bibtex to remove references to Papers3 or its files.
3. Import the bibtex into Zotero. Do not sync before performing the next step!
4. Close Zotero and run update-date-added to apply the date-added fields from the bibtex file.
5. Export all PDFs from Papers3.
6. (optional) Papers3 3.4.10 has a bug (one of many) in which the comments aren't exported into the PDFs, only the highlights. To retain them, manually add them.
7. Manually assign PDF files to Zotero entries.
8. Manually copy reviews from Papers to Zotero notes.
9. Manually copy flag, rating, and unread status from Papers to Zotero tags.
