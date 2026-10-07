# Custom content

Use custom content for text that isn't translated by the other sections, for example text added by other apps or written directly in theme files.

Enter the original text exactly as it appears on your storefront, and its translation. It's replaced in the browser for customers viewing that language. Extra spaces and line breaks don't matter.

* **Page scope:** apply an entry everywhere, or only on certain pages (frontpage, product, collection, blog, article, custom pages or system pages).
* **Theme:** choose **All themes** or one theme.
* **Types:** text, HTML, image (replaced by file name) and link.

## Placeholders

For text with a part that changes, write the changing part as a placeholder:

| Original | Translation |
| --- | --- |
| `Skin type ({{ amount }})` | `Type de peau ({{ amount }})` |

`Skin type (9)` then shows as `Type de peau (9)`, `Skin type (12)` as `Type de peau (12)`, and so on.

!!! info

    Filter counts like "(9)" after a translated name are handled automatically: if "Dry skin" has a translation, "Dry skin (12)" is translated too.

!!! warning

    Custom content needs the **Translations** app embed switched on in your theme (see [Getting started](getting-started.md)).
