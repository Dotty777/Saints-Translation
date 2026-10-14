# Restoring Deuteronomy staging content

This archive concerns WordPress staging site 248834710 only. It does not restore the whole website or production.

`original-staging-backup.zip` contains the original book index (page 1039), all 34 reading chapters, metadata, original verse text and all 34 `saints_word_study` CSV records as read before this revision.

Before restoration, back up the current records and check for later edits. Restore content to the archived numeric page and study IDs. Retain titles, slugs, parents and status unless separately authorized. Use current WordPress block hashes and optimistic-lock tokens when replacing a page block. Restore reading chapters and their matching study records together.

`verified-staging-content.zip` contains the revised raw pages, revised study records and saved readbacks. Use it to recover this Bespoke edition instead of the earlier edition.

Read back every restored record and compare with the intended version. Check verse IDs, note targets and navigation, and open a sample highlight and note in the reader. Preserve both original chapter formats. Restoring English alone may break exact-phrase study matching.

The ZIP archives preserve JSON strings and CSV content in UTF-8. Repository records do not automatically deploy to WordPress.
