---
title: "Uses"
draft: false
date: 2022-08-27T09:16:45.000Z
description: "Markdown is a powerful tool for creating rich text using a plain text editor. This cheatsheet is a quick reference for Markdown syntax."
categories:
  - Hello
tags:
  - Hello
  - WhatsApp
---

I get a lot of questions about the tools I use for different parts of my work, so inspired by my friend Wes Bos, I've put together this "uses" page that covers every part of my setup.

A few of the links below are affiliate links which means I get paid or rewarded in some way if you use them to purchase, but rest assured these are all tools and services I actually use.


## Workstation:
---

- 16" MacBook Pro, 2.4ghz 8-Core i9, 32GB of RAM, AMD Radeon Pro 5500M 8GB Graphics (2019)
  - Prior to this I was using a 2015 5K iMac as my main machine and a 2014 13" MacBook Pro for travel. This machine is more powerful than my iMac and feels just as portable as my 13" did — really love this computer.

- Apple Compact Wired Keyboard
  - I can't stand the arrow keys on the keyboards Apple makes today so I use this relic instead. They didn't make the wired version for very long so it can be hard to find but the wireless one takes AA batteries which is a huge pain.

-  Magic Mouse 2
  - Used to think I preferred the trackpad after being a laptop-only user for so long, but I love the extra precision you get with a real mouse, especially for video and audio editing.

- Magic Trackpad 2
  - I keep this on the left hand side of my keyboard but it doesn't see much use. Usually just to scroll Twitter if my right hand is busy holding a drink.

- IKEA BEKANT sit/stand desk
  - This desk has poor reviews for some reason but I think it's great. It's quite big, really deep, and super stable. I stand probably 25% of the time and don't really find the lack of presets to be a problem.

- Herman Miller Aeron chair
  - Super expensive but worth every penny for me.

## Development:
---


## Design:
---


## Productivity:
---

- Alfred
  - I forgot to add this originally because it's so baked into my workflow that I forgot it was even there. I use it to launch apps, for clipboard management, for customer support snippets, and probably tons more I'm still forgetting.

- Todoist
  - I use Todoist to keep track of my todos. I really like the scheduled and recurring tasks features, lets me use Todoist for a lot of stuff that you might normally put in a calendar.

- Calendly
  - I use Calendly to schedule podcast interviews and other meetings. So much nicer than trying to work out a time to chat by going back and forth in an email thread.

- 1Password
 - Such a great password manager, installing this for the first time was life-changing.


- Dropbox
 - I keep all my important files in Dropbox so they are available on both my machines. I don't use anything else for backups because literally nothing that isn't in Dropbox is important.


## Hosting:
---


## Workstation

---

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

# Emphasis

---

Emphasis, aka italics, with asterisks or underscores. **Strong emphasis**, aka bold, with asterisks or underscores. Combined emphasis with asterisks and underscores. ~~Strikethrough~~ with two tildes. **_Bold and nested italic_**. **_All bold and italic_**. **_*Bold and italic nested*_**.

# Images

---

{{< img
  src="cat.jpg"
  alt="Cat"
  caption="This is the default position of a figcaption, but it can be centered or at the end." >}}

# Lists

---

## Ordered:

1. First ordered list item
2. Another item
3. Actual numbers don't matter, just that it's a number
   1. 1st.
   1. 2nd.
   1. 3rd.

## Unordered:

- This is a list item
  - This is a nested list item
    - This is a nested list item
  - This is another list item
- This is another list item

## Task:

{{< task-list >}}

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

# Links

---

[This is a link](https://www.example.com).

[This link](https://www.example.com "Link Title") has a title attribute.

# Tables

---

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

# Blockquotes

---

> Blockquotes are very handy in email to emulate reply text. This line is part of the same quote.

You can reference a footnote like this.

> All generalizations are false, including this one. — Mark Twain. [^1]

[^1]: https://www.brainyquote.com/quotes/mark_twain_137872.

# Code

---

Inline `code` has `back-ticks around` it.

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print(s)
```

```plain
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

You can remove line numbers, change the highlighting theme, and more. See [Syntax Highlighting](https://gohugo.io/content-management/syntax-highlighting/) and [Highlight](https://gohugo.io/getting-started/configuration-markup/#highlight/).

```c {lineNos=false}
#include <stdio.h>

int main()
{
    printf("Hello, World!\n");
    return 0;
}
```

# Alerts

---

{{< alert info "Optional title" >}}
This is an info alert.
{{< /alert >}}

{{< alert warning "Optional title" >}}
This is a warning alert.
{{< /alert >}}

{{< alert error "Optional title" >}}
This is an error alert.
{{< /alert >}}

{{< alert success "Optional title" >}}
This is a success alert.
{{< /alert >}}

# Math

---

You can use LaTeX-style math with `$` and `$$` delimiters. For example, `$x^2$` renders as $x^2$, and `$$\frac{x}{y}$$` renders as: $$\frac{x}{y}$$

We can throw this scary-looking equation at you:

$$
\frac{1}{\Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{\frac25 \pi}} = 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {1+\frac{e^{-6\pi}} {1+\frac{e^{-8\pi}} {1+\ldots} } } }
$$

# Horizontal Rules

---

Three or more... Hyphens `---`, Asterisks `***`, or Underscores `___`.

---

---

---

# Miscellaneous

---

Tailwind lets you conditionally apply utility classes in different states using variant modifiers. For example, use `hover:scroll-auto` to only ~~The world is flat.~~
apply the scroll-auto utility on hover.

term
: definition
: another definition
