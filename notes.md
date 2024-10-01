# HTML

-   HTML stands for Hypertext Markup Language.
-   It is not a programming language.
-   Hyper text is a special type of text document in which you can add hyperlink of another document.
-   Markup langauge is a text encoding system having certain set of symbols for writing text documents.
-   Initially HTML was invented to research papers as it was difficult to write back in time.
-   In modern days, HTML is use to structure web pages.
-   It is a skeleton of a web page.
-   HTML file is saved with `.html` extension.

## Tags

-   Tags are the building blocks of HTML.
-   Helps us to define a particular part of the webpage.
-   Example: `<tagName>Some information</tagName>`
-   Example: `</selfClosingTag>`

## Element

-   An opening and closing tag together makes an element.

## Heading Element

-   The heading element ranges from `<h1>` to `<h6>`.
-   Its used to create heading of a webpage.
-   `<h1>` is the largest heading and `<h6>` is the smallest heading.

```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
...
<h6>This is heading 6</h6>
```

## Paragraph element

-   Used to create paragraphs.

```html
<p>This is a paragraph</p>
```

## List element

-   We can put bullet point list by using the `<li>` element.

### Ordered list

-   Ordered list is a list in a particular order or sequence like 1, 2, 3... or a, b, c, ...

```html
<ol>
	<li>Java</li>
	<li>C++</li>
	<li>Python</li>
</ol>
```

![alt text](/images/Screenshot_20241001_070555.png)

### Unordered list

-   By default we get the unordered bullet list.

```html
<ul>
	<li>Java</li>
	<li>C++</li>
	<li>Python</li>
</ul>
```

![alt text](/images/Screenshot_20241001_070657.png)

## Images

- For any image on the internet, right click on the image > copy image address.
- We can add image using `<img>` tag which is a self closing tag.
- It has an attribute called `src` which represents the source of the image.
- Another attribute is `alt` which acts as caption for the image and is only used when in screen reader mode.
- The `alt` attribute is widely helpful for blind people.

```html
<img src = "https://hips.hearstapps.com/goodhousekeeping/assets/17/30/pembroke-welsh-corgi.jpg" alt="Dog image">
```

## Inline and block tags
- A block tag will always put the information of the next tag in a new line.
- For two inline tags together, they both will be on the same line.

### Division tag
- A generic container for dividing or creating sections.

```html
<div>
	<img src = "https://hips.hearstapps.com/goodhousekeeping/assets/17/30/pembroke-welsh-corgi.jpg" alt="Dog image">
</div>
```

- We embedded the image inside the generic `<div>` container.
- Every new `<div>` comes in a new line.
- Hence, we say that `<div>` is a block element.

### Span tag
- Its an inline tag used to put information next to each other on the same line.

```html
<span>Yo</span>
```