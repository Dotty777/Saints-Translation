# Restoring earlier Exodus staging content

The archive contains 44 original WordPress page records and a SHA-256 manifest: 40 reading chapters, index 1036, and reference pages 23433, 18960 and 20675. The three reference pages were not edited. This is not a full-site backup.

1. Extract into a new folder and verify the manifest hashes.
2. Confirm staging site **248834710**, not the live site. Match each page by its saved ID and URL.
3. Preserve current content before restoration. Reconcile later edits instead of overwriting them.
4. Restore only the intended content from the corresponding original record. Keep title, slug, parent and status. Prefer a checked first-block restoration when later blocks remain unchanged.
5. Read back the result and verify text, anchors, chapter navigation, notes and comparison links.

Do not bulk-restore reference or comparison pages as part of an English wording update.
