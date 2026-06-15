# Tagalog Revised 2005 Bible XML

This repository contains the **Tagalog Revised 2005 Bible** in structured XML format, enhanced with `<book_title>` and `<chapter_title>` tags for all 66 books.

## File

- `TagalogRevised2005Bible_final.xml` — Full Bible XML with book titles and chapter titles added to every book and chapter node.

## XML Structure

```xml
<bible translation="Tagalog 2005 Revised">
  <book number="1">
    <book_title>Genesis</book_title>
    <chapter number="1">
      <chapter_title>Creation</chapter_title>
      <verse number="1">Sa simula, nilikha ng Diyos...</verse>
    </chapter>
  </book>
</bible>
```

## Notes

- All 66 canonical books are included (Genesis to Revelation).
- Book titles follow the standard Protestant Bible canon order.
- Chapter titles are editorial headings based on standard Bible reference chapter headings.
- The full XML file is ~5.4MB. Use Git CLI to upload the main file.

## Upload Instructions

To upload the full XML file:

```bash
git clone https://github.com/NoelQAnonas/tagalog-revised-2005-bible.git
cd tagalog-revised-2005-bible
git checkout bible-xml-titles
cp /path/to/TagalogRevised2005Bible_final.xml .
git add TagalogRevised2005Bible_final.xml
git commit -m "Add full Tagalog Revised 2005 Bible XML with titles"
git push origin bible-xml-titles
```
