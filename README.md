## 📄 XLSX Structure Notes

### 🧩 When adding or removing worksheet files

Update the following files accordingly:

- `_rels/.rels`
- `xl/_rels/workbook.xml.rels`
- `xl/workbook.xml`
- `[Content_Types].xml`
- `xl/worksheets/` (add/remove the corresponding sheetX.xml file)

### 📝 When modifying string data in worksheets

If your cells use **shared strings (`t="s"`)**, you must update:

- `xl/sharedStrings.xml`
