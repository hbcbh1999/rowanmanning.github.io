---
title: 'Styleguide'
layout: 'default'
---

# Styleguide #

This is a paragraph of text; it is being used to test basic typography and ensure that longer blocks of content are readable. The rest of this paragraph is going to be filler copy, feel free to ignore it as I'll be rambling on. Please don't let this set a precedent though – the rest of the content in this styleguide may be very useful, and will attempt to explain its purpose. Actually, thinking about it, that's exactly what this paragraph has done!


## Text-Level Semantics ##

Text-level semantics are important, right? Let's have a look at some of them. We'll start with the <strong>strong element</strong>, and swiftly move onto <em>emphasis</em>. Pretty standard stuff. I'll tag <sub>subscript</sub> and <sup>superscript</sup> onto the end of this paragraph too.

Let's show off some <abbr title="abbreviation">abbr</abbr>, and elements which <del>save the world</del> <ins>deal with edits to documents</ins>; it's worth noting that the 's' element is used <s>twice</s> once in this document.

In reminding myself how to use all these elements, I often refer to <a href="http://csswizardry.com/2011/01/html5-and-text-level-semantics/"><cite>this article from CSS Wizardry</cite></a>. He says: <q>The &lt;q&gt; element is simply used to mark up inline quotations; quotes that are in the context of surrounding copy</q>.

Last two elements now*: when writing about code, the aptly named <code>code</code> element comes into play; and lastly, the 'mark' element is useful for <mark>highlighting text</mark> or maybe search terms.

<small>* Not a guarantee</small>


## Lists ##

### Types Of List (unordered) ###

 * Unordered Lists
 * Ordered Lists
 * Definition Lists

### The Order In Which I Tackle A Front-End Build (ordered) ###

 1. Construct the markup
 2. Style elements
 3. Enhance with JavaScript

### What Lists Are For (definition) ###

<dl>
    <dt>Unordered Lists</dt>
    <dd>For lists of items where order is not important.</dd>

    <dt>Ordered Lists</dt>
    <dd>For lists of items where order has meaning.</dd>

    <dt>Definition Lists</dt>
    <dd>For lists of items which have a title and description.</dd>
</dl>

### Mixed And Complex Lists ###

 * List item with a paragraph.

 * List item with a nested list.
    * List item
    * List item
    * List item with *another* nested list.
       1. List item
       2. List item
       3. List item

 * List item with a paragraph.

   And another paragraph.


## Block Quotes ##

> Block quotes can be used to quote somebody.
<small>Rowan Manning</small>

With a citation:

> Block quotes can also have a citation!
<small>Rowan Manning in <cite>This styleguide</cite></small>


## Code ##
    
    sayMessage = (msg) -> alert "Styleguide says: #{ msg }"
    sayHello = (to) -> sayMessage "Hello #{ to }!"

    sayHello 'Reader'
    sayMessage 'Code blocks can be useful.'


## Tables ##

<table>
    <thead>
        <tr>
            <th>Table Heading</th>
            <th>Table Heading</th>
            <th>Table Heading</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cell content</td>
            <td>Cell content</td>
            <td>Cell content</td>
        </tr>
        <tr>
            <td>Cell content</td>
            <td>Cell content</td>
            <td>Cell content</td>
        </tr>
        <tr>
            <td>Cell content</td>
            <td>Cell content</td>
            <td>Cell content</td>
        </tr>
        <tr>
            <td>Cell content</td>
            <td>Cell content</td>
            <td>Cell content</td>
        </tr>
    </tbody>
</table>


## Headings ##

# Level 1 Heading #

This is a paragraph after a level 1 heading consectetur adipiscing elit. Donec malesuada volutpat libero, posuere lacinia felis aliquet eu. Maecenas venenatis suscipit dapibus. In venenatis dolor sodales diam volutpat tempus. In in augue a orci tincidunt hendrerit at non nibh.

## Level 2 Heading ##

This is a paragraph after a level 2 heading consectetur adipiscing elit. Donec malesuada volutpat libero, posuere lacinia felis aliquet eu. Maecenas venenatis suscipit dapibus. In venenatis dolor sodales diam volutpat tempus. In in augue a orci tincidunt hendrerit at non nibh.

### Level 3 Heading ###

This is a paragraph after a level 3 heading consectetur adipiscing elit. Donec malesuada volutpat libero, posuere lacinia felis aliquet eu. Maecenas venenatis suscipit dapibus. In venenatis dolor sodales diam volutpat tempus. In in augue a orci tincidunt hendrerit at non nibh.

#### Level 4 Heading ####

This is a paragraph after a level 4 heading consectetur adipiscing elit. Donec malesuada volutpat libero, posuere lacinia felis aliquet eu. Maecenas venenatis suscipit dapibus. In venenatis dolor sodales diam volutpat tempus. In in augue a orci tincidunt hendrerit at non nibh.

##### Level 5 Heading #####

This is a paragraph after a level 5 heading consectetur adipiscing elit. Donec malesuada volutpat libero, posuere lacinia felis aliquet eu. Maecenas venenatis suscipit dapibus. In venenatis dolor sodales diam volutpat tempus. In in augue a orci tincidunt hendrerit at non nibh.

###### Level 6 Heading ######

This is a paragraph after a level 6 heading consectetur adipiscing elit. Donec malesuada volutpat libero, posuere lacinia felis aliquet eu. Maecenas venenatis suscipit dapibus. In venenatis dolor sodales diam volutpat tempus. In in augue a orci tincidunt hendrerit at non nibh.