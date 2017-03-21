---
layout: post
title: A full style demo
---

# Heading 1
## Heading 2
### Heading 3
#### Heading 4


## Simple paragraph
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla nulla massa, tristique sit amet dui sit amet, mattis 
tempus sem. Suspendisse bibendum sed enim a eleifend. Morbi vel orci malesuada, dictum sapien eleifend, fermentum nisi. 
Morbi tempor mi ut sapien mollis finibus. Duis mollis erat ex, eget consectetur turpis ornare sit amet. 
Aliquam vitae urna bibendum, maximus est in, luctus nisl. Donec accumsan augue nunc, eu lacinia ligula blandit at. 
Morbi ac lacinia ipsum. Phasellus convallis elementum dolor, vel tempor nunc. Cras gravida elit a maximus mattis. 
Duis feugiat dignissim tellus ut molestie. Maecenas porttitor sem vel sagittis dapibus. 
Vestibulum mollis sem ac massa ornare, sit amet fringilla velit auctor.


## Links
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

## Code blocks

<pre class="md">
Simple quote inline `code`
</pre>

Simple quote inline `code`

---

<pre class="md">
```
Generic code block, without syntax highlight
```
</pre>

```
Generic code block, without syntax highlight
```

---

{% raw %}
<pre class="md">
{% highlight js %}

// Javascript code
var _ = function(obj) {
    if (obj instanceof _) return obj;
    if (!(this instanceof _)) return new _(obj);
    this._wrapped = obj;
};

{% endhighlight %}
</pre>
{% endraw %}

{% highlight js %}

// Javascript code
var _ = function(obj) {
    if (obj instanceof _) return obj;
    if (!(this instanceof _)) return new _(obj);
    this._wrapped = obj;
};

{% endhighlight %}

---

{% raw %}
<pre class="md">
{% highlight js linenos %}

// Javascript code
var cb = function(value, context, argCount) {
  if (value == null) return _.identity;
  if (_.isFunction(value)) return optimizeCb(value, context, argCount);
  if (_.isObject(value)) return _.matcher(value);
  return _.property(value);
};
_.iteratee = function(value, context) {
  return cb(value, context, Infinity);
};
1234567890123456789012345678901234567890123456789012345678901234567890123456789012345678901
0         10       20        30        40        50        60        70        80        90

{% endhighlight %}
</pre>
{% endraw %}

{% highlight js linenos %}

// Javascript code
var cb = function(value, context, argCount) {
  if (value == null) return _.identity;
  if (_.isFunction(value)) return optimizeCb(value, context, argCount);
  if (_.isObject(value)) return _.matcher(value);
  return _.property(value);
};
_.iteratee = function(value, context) {
  return cb(value, context, Infinity);
};
1234567890123456789012345678901234567890123456789012345678901234567890123456789012345678901
0         10       20        30        40        50        60        70        80        90

{% endhighlight %}


## Emphasis
<pre class="md">
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
</pre>


Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

## Non markdown emphasis
The <a href="#">a element</a> example  
The <abbr>abbr element</abbr> example  
The <b>b element</b> example  
The <cite>cite element</cite> example  
The <code>code element</code> example  
The <del>del element</del> example  
The <em>em element</em> example  
The <i>i element</i> example  
The <ins>ins element</ins> example  
The <kbd>kbd element</kbd> example  
The <mark>mark element</mark> example  
The <q>q element <q>inside</q> a q element</q> example  
The <s>s element</s> example  
The <samp>samp element</samp> example  
The <small>small element</small> example  
The <span>span element</span> example  
The <strong>strong element</strong> example  
The <sub>sub element</sub> example  
The <sup>sup element</sup> example  
The <var>var element</var> example  
The <u>u element</u> example  

## Images

![Large image](http://demo.ghost.io/content/images/2014/09/testimg1.jpeg){: .block-image }
Caption for big image

![Small image][small-image]{: .block-image }
Caption for small image


## List Types

1. Item 1
1. Item 2
   1. Subitem 1
   1. Subitem 2
   1. Subitem 3
1. Item 3


- Item 1
- Item 2
- Item 3
  - Subitem 1  
    You can have properly indented paragraphs within list items. Notice the the leading spaces (at least one, align the raw Markdown).
  - Subitem 2
  - Subitem 3
- Item 4
- Item 5


## Table

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


## Blockquotes

> Good afternoon, gentlemen. I am a HAL 9000 computer. 
> I became operational at the H.A.L. plant in Urbana, Illinois on the 12th of January 1992. 
> My instructor was Mr. Langley, and he taught me to sing a song. If you’d like to hear it I can sing it for you. 

[small-image]: http://demo.ghost.io/content/images/2014/09/testimg2.jpg "Small image"
[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
