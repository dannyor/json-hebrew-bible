# json-hebrew-bible
A convenient JSON bible.
(Generated from resources produced by [UXLC](https://tanach.us/))

Contains both simple text and text with diacritics (Niqud and Teamim).

The JSON file is stuctured by:
1. Books
   - name
   - Hebrew name
   - total number of verses
   - book enum value (you may map it to an enum structure in your favorite programming language)
3. Chapters
4. Verses
   - simple text
   - with diacritics

![preview](./json-bible-preview.png)

If you are looking for an API that works with this JSON bible, you may find a kotlin implementation at:

[bible4kotlin-and-java](https://github.com/dannyor/bible4kotlin-and-java)
