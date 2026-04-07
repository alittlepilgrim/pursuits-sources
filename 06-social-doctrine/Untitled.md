---
title: 20260407-113111
uid: 20260407-1775579472571
created: 2026-04-07
modified: 2026-04-07
publish: false
attachment: false
type: note
aliases:
  - 20260407-1775579472572
---
20260407-113111

# 
**Normalize headings in encyclical and social doctrine source files**

Standardized headings across 10 markdown files in `pursuits-sources/`:

- Removed bold (`**`) and italic (`*`) formatting from headings
- Applied title case throughout
- Preserved Roman numerals in uppercase (e.g. `III.`, `Chapter VI`)
- Added periods after standalone Roman numerals where appropriate (`I.`, `II.`)
- Replaced hyphens with en dashes (`–`) as separators in chapter headings where applicable
- Ensured the first content word after prefixes (`I.`, `A.`, `1.`) is always capitalized

**Files changed:** `laudato-si`, `mulieris-dignitatem`, `pastores-dabo-vobis`, `redemptoris-mater`, `redemptoris-missio`, `slavorum-apostoli`, `sollicitudo-rei-socialis`, `ut-unum-sint`, `veritatis-splendor`, `sd-02-intro`, `sd-03-part-I`, `sd-04-part-II`, `sd-05-part-III`, `sd-06-conclusion`

