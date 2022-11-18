# These are .html notes

    .html stands for "hypertext mark up language" 
html is used for primarily for structure.
it creates the backbone of most webpages.
It does this by following a set of rules and syntax that are baked in.
html can also interface with external sources and languages such as .css and .img files

HTML (HyperText Markup Language) is the code that is used to structure a web page and its content. For example, content could be structured within a set of paragraphs, a list of bulleted points, or using images and data tables. As the title suggests, this article will give you a basic understanding of HTML and its functions.

HTML is a markup language that defines the structure of your content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. The enclosing tags can make a word or image hyperlink to somewhere else, can italicize words, can make the font bigger or smaller, and so on. For example, take the following line of content:

Attributes contain extra information about the element that you don't want to appear in the actual content. Here, class is the attribute name and editor-note is the attribute value. The class attribute allows you to give the element a non-unique identifier that can be used to target it (and any other elements with the same class value) with style information and other things. Some attributes have no value, such as required.

Attributes that set a value always have:

A space between it and the element name (or the previous attribute, if the element already has one or more attributes).
The attribute name followed by an equal sign.
The attribute value wrapped by opening and closing quotation marks.
Note: Simple attribute values that don't contain ASCII whitespace (or any of the characters " ' ` = < >) can remain unquoted, but it is recommended that you quote all attribute values, as it makes the code more consistent and understandable.

Nesting elements
You can put elements inside other elements too — this is called nesting. If we wanted to state that our cat is very grumpy, we could wrap the word "very" in a <strong> element, which means that the word is to be strongly emphasized: