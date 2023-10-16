# Prose Fusion, 2023-10-16

## Topics

- Markdown, mark up
- Most important Git commands, Git workflow

## Markdown Quick Start

Markdown is sort of a "universal" way to add a few characters to any text, which can be read elsewhere as formatted text.

Here are the first things to learn with Markdown:

Words can be **bold** or _italic_ -- you'll see we just added two asterisks on each side of "bold" `**bold**` and one underline on each side of "italic" `_italic_`.

Then there are bullet lists, which start with a dash and a space `- ` at the beginning of a line:

- first bullet
- second bullet
- third bullet

And numbered lists, just put a number, then a full-stop / period character, then a space at the beginning of a line `1. `:

1. first
2. second
3. third

(Technically, you can put any number, and when the Markdown is processed by a Markdown processor, it will fix the numbering.)

Next, how about headings? Type 1 to 5 number sign / hashtag characters and a space `# ` at the beginning of a line. Fewer hashtag characters make a bigger heading:

- hash
- number sign
- pound 
- octothorpe

# heading 1
## heading 2
### heading 3

If you want to have a section of indented text, like a quote from an article or something, use a greater-than sign and a space `> ` at the beginning of a line:

> This is an indented quote.
> It can have multiple lines.

Three dashes (or more) on a line by themselves create a horizontal line:

---

If you ever need to type something that would get processed by Markdown but you don't want it to, use a backtick character (usually the key to the left of the "1" key on your keyboard) before and after a string of characters; if you need to do this for multiple lines, use a line with three backticks, then your lines, then another line of three backticks.

```
this is preformatted text

and you can use as many lines as you want
```
''
