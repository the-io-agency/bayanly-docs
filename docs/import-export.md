# Import & export (CSV)

Export a CSV, fill in the translations in Excel or Google Sheets, and import it back. In the export, choose the languages, the content and the file layout.

## File layouts

**One column per language** (default)

| Type | Identification | Field | Default content | fr | de |
| --- | --- | --- | --- | --- | --- |
| LINK | gid://shopify/Link/1 | title | Home | Accueil | Startseite |

Only edit the language columns.

**One row per language**: the same layout as Shopify's own translation export, with **Locale** and **Translated content** columns.

## Importing

* The import detects the layout automatically.
* Two-column files with **source** and **target** columns can be imported for theme text too.
* Empty cells are ignored, so importing never deletes translations.
* Rows whose original text changed since the export are skipped.
* Large imports run in the background; you can leave the page.
* Export files can be downloaded for 24 hours.

!!! info

    **Only export untranslated fields** gives you just the text that still needs translating, which is handy for translators.
