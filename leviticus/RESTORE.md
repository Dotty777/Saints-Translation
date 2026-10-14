# Restoring Leviticus staging content

This archive concerns WordPress staging site 248834710 only. It does not restore the whole website or production.

`original-staging-backup.zip` contains the original book index (page 1037), all 27 reading chapters, their metadata and original verse text, and all 27 `saints_word_study` CSV records. These are the records read before this revision.

Before restoration, take a fresh backup of the current records and check for later edits. Restore content to the original numeric page and study IDs; retain each record's title, slug, parent and status unless an independently authorized change is required. Use WordPress's current block and optimistic-lock tokens when replacing a page block. The reading chapters and their matching word-study records should be restored together.

`verified-staging-content.zip` contains the revised raw pages, revised word-study records and saved readbacks. It can be used to recover this completed Bespoke edition instead of the earlier edition.

After any restore, read back every changed page and study record, compare the content with the intended archived version, check verse IDs and navigation, and open a sample highlight in the reader. Do not assume that restoring English alone preserves exact-phrase study matching.

The ZIP archives preserve JSON strings and CSV content in UTF-8. Repository records do not automatically deploy to WordPress.
