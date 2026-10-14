# Restoring the earlier Genesis staging content

The archive contains original raw WordPress page content and metadata plus SHA-256 integrity hashes. It is a Genesis backup, not a complete site export.

1. Extract the archive into a new folder and verify file/content hashes against its manifest.
2. Confirm the target is staging site **248834710**, not the live site. Match each page by its stored ID and URL.
3. Read the current page and preserve it before restoration. If later edits exist, reconcile them rather than overwriting them.
4. Restore only the intended page content from its original JSON record, preserving its original slug, parent, title and status. Prefer an individually checked first-block restoration where subsequent blocks are unchanged.
5. Read the saved page back and compare the restored content with the backup. Check chapter navigation, verse anchors, notes and comparison links in the browser.

Do not run a bulk restore or replace comparison streams as part of an editorial wording update.
