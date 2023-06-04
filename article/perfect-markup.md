# Treatise on My Perfect Lightweight Markup Language

## It would have...
- org-mode style inline syntax.
- with the ease of HTML hackery of textile.
- with the compiled language support that Markdown offers.

org-mode's inline attributes map nearly 1:1 with how I personally format in plain text, you have `__underscores__` that look like *underlines*,
`//italics//` that look like *italics*, and `**bold**` that actually looks like **bold**. I want a LML that has nearly all the same features that you'd find on
your common or garden word-processor, and with how often I refer to D&D 5e books, I want actual, *implemented* description lists. org-mode is absolutely
perfect for this, but it's nearly entirely confined to the single text editor it was created in. Markdown has amazing support, but as a general shorthand
for HTML, it feels sorely lacking. Textile makes up for it's shortcomings, but it suffers from a lesser problem that also plagues org-mode's development,
and it's syntax can feel woefully clunky at points, that being said, it has the absolute best numbered list syntax out of all of the above mentioned LMLs.

## Sample

```
= Heading 1
== Heading 2
=== Heading 3
====[id] Heading 4

- Here
- is
- an
- unordered
- list

#. Here
#. is
#. an
#. ordered
#. list

- Here :: is
- a :: single
- description :: list

!<an_image.png>

And here is **Bold**, //Italic//, __Underline__, ^^Superscript^^, & --Strikethrough-- %{color:red}We also have span support%, %(i)in diffent flavours!%

[Markdown's](https://en.wikipedia.org/wiki/Markdown) link format works //fine//.

\`\`\`c
// So do the code blocks.
\`\`\`
```