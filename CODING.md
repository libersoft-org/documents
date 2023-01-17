# Liberland Software Foundation - Coding standards

In this document you'll find our coding standards for each use case. This is useful for the people who would like to code for us. This document will be continously updated, so check it from time to time, please.

## Common standards

For all programming languages we use these standards:

**Character encoding** - We use UTF-8 in most cases.
**Line endings** - We use LF for line endings.
**Comments** - We use English for all the comments.
**Indentation** - We use one space, no tabs, in every language where it's applicable.
**End of the code** - We add an empty line as a last line of the code.

```css
.content {
 padding: 10px;
 background-color: #336699;
}

```

**One line conditions** - We don't use curly brackets for one line conditions etc. and we write it on the same line.

## CSS

**Case** - We use kebab case everywhere. For example:

```css
.header-bar {
 padding: 10px;
}
```

## JavaScript

**Case** - We use camel case everywhere.
**Line endings** - We use ";" at the end of the line.
**Strings** - We use apostrophes everywhere it is not neccessary to use otherwise. Quotation marks in case of short text where it is needed and backquote in special cases like long text with more new lines etc.

For example:

```js
const shortText = 'Hello world';
const shortTextWithNewLine = "Hello,\nHow are you?";
const longTextWithMoreNewLines = `
 <div>
  Hello,<br />
  how are you?
 </div>
`;

if (shortText == 'Hello world') console.log('Hello.');
else console.log('Hi.');
```
