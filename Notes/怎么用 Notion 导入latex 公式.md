# 怎么用 Notion 导入latex 公式

Notion不能直接导入latex公式, 并且导出markdown的时候也会出现错误,本文为了解决这个问题,使用了GitHub上的 [md2notion](https://github.com/Cobertos/md2notion) 库



它提供的功能有:

- Picking a Notion.so page to upload to (instead of them all uploading to the root)
- Code fences keep their original language (or as close as we can match it)
- Code fences are formatted properly
- Inline HTML is preserved
- (Optionally) Upload images that are memtioned in the HTML `<img>` tags.
- Markdown frontmatter is preserved
- Local image references will be uploaded from relative URLs
- Image alts are loaded as captions instead of as `TextBlock`s
- Handles nested lists properly
- Among other improvements...



