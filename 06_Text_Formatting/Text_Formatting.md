HTML Text Formatting

________________________________________
HTML contains several elements for defining text with a special meaning.

### [Example](Text_Formatting.html)

<p>This text is <b>bold</b> </p>
<p>This text is <i>italic</i> </p>
<p>This is <sub>subscript</sub> and <sup>superscript</sup> </p>



## HTML Formatting Elements
Formatting elements were designed to display special types of text:
- `<b>` - Bold text
- `<strong>` - Important text
- `<i>` - Italic text
- `<em>` - Emphasized text
- `<mark>` - Marked text
- `<small>` - Smaller text
- `<del>` - Deleted text
- `<ins>` - Inserted text
- `<sub>` - Subscript text
- `<sup>` - Superscript text

## HTML `<b>` and `<strong>` Elements
The HTML `<b>` element defines bold text, without any extra importance.

### **`<b>` Tag**
```html
<p>This text is <b>bold</b> </p>
```
<p>This text is <b>bold</b> </p>

The HTML `<strong>` element defines text with strong importance The content inside is typically displayed in bold.

### **`<strong>` Tag**
```html
<strong>This text is important!</strong>
```
<p>This text is <strong>important! </strong> </p>

## HTML `<i>` and` <em>` Elements
The HTML `<i>` element defines a part of text in an alternate voice or moodThe content inside is typically displayed in italic.
Tip: The `<i>` tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.

### `<i>` Tag
```html
<p>This text is <i>italic</i> </p>
```
<p>This text is <i>italic</i> </p>

The HTML `<em>` element defines emphasized textThe content inside is typically displayed in italic.
Tip: A screen reader will pronounce the words in `<em>` with an emphasis, using verbal stress.

### `<em>` Tag
```html
<p>This text is <em>emphasized</em> </p>
```
<p>This text is <em>emphasized</em> </p>

## HTML `<small>` Element
The HTML `<small>` element defines smaller text:
### `<small>` Tag
```html
<small>This is some smaller text.</small>
```
<p>This is some <small>smaller</small> text.</p>

## HTML `<mark>` Element
The HTML `<mark>` element defines text that should be marked or highlighted:
### `<mark>` Tag
```html
<p>Do not forget to buy <mark>milk</mark> today.</p>
```
<p>Do not forget to buy <mark>milk</mark> today.</p>

## HTML `<del>` Element
The HTML `<del>` element defines text that has been deleted from a document Browsers will usually strike a line through deleted text:
### `<del>` Tag
```html
<p>My favorite color is <del>blue</del> red.</p>
```
<p>My favorite color is <del>blue</del> red.</p>

## HTML `<ins>` Element
The HTML `<ins>` element defines a text that has been inserted into a document Browsers will usually underline inserted text:

### `<ins>` Tag
```html
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>
```
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>

## HTML `<sub>` Element
The HTML `<sub>` element defines subscript textSubscript text appears half a character below the normal line, and is sometimes rendered in a smaller fontSubscript text can be used for chemical formulas, like H2O:
### `<sub>` Tag
```html
<p>This is <sub>subscripted</sub> text.</p>
```
<p>This is <sub>subscripted</sub> text.</p>

## HTML `<sup>` Element
The HTML `<sup>` element defines superscript textSuperscript text appears half a character above the normal line, and is sometimes rendered in a smaller fontSuperscript text can be used for footnotes, like WWW[1]:
### `<sup>` Tag
```html
<p>This is <sup>superscripted</sup> text.</p>
```
<p>This is <sup>superscripted</sup> text.</p>