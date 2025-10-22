---
title: Components Examples
layout: default
author: Reagan McNeill Womack
nav_exclude: true # excludes file from navigation
---

# Examples of UI Components
This page displays UI components available through Just the Docs and their associated Markdown syntax. This page also serves as a library of all custom styling that has been added to the website.

To view all of the custom colors that have been defined for this webiste, check out the [Custom Scheme](https://github.com/oREAGanoWombat/CH730-Fall25/blob/main/_sass/color_schemes/custom-scheme.scss) file in our repository.

#### Table of Contents
1. [Typography](#typography)
2. [Buttons](#buttons)
3. [Labels](#labels)
4. [Tables](#tables)
5. [Lists](#lists)
6. [Horizontal Rules](#horizontal-rules)
7. [Color Palette](#color-palette)

<hr class="bold medgrey">

## Typography
> # Heading 1
> ## Heading 2
> ### Heading 3
> #### Heading 4
> ##### Heading 5
> ###### Heading 6

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

---

## Buttons
> [Default Button](#buttons){: .btn }
> [Primary Button](#buttons){: .btn .btn-primary }
> [Purple Button](#buttons){: .btn .btn-purple }
> [Blue Button](#buttons){: .btn .btn-blue }
> [Green Button](#buttons){: .btn .btn-green }
> [Grey Button](#buttons){: .btn .btn-grey } \
> [Image Caption](#buttons){: .btn .image-caption }
> [Footer Nav Button](#buttons){: .btn .footer-nav-button }
```markdown
> [Default Button](#buttons){: .btn }
> [Primary Button](#buttons){: .btn .btn-primary }
> [Purple Button](#buttons){: .btn .btn-purple }
> [Blue Button](#buttons){: .btn .btn-blue }
> [Green Button](#buttons){: .btn .btn-green }
> [Grey Button](#buttons){: .btn .btn-grey } \
> [Image Caption](#buttons){: .btn .image-caption }
> [Footer Nav Button](#buttons){: .btn .footer-nav-button }
```

---

## Labels
> Default label 
> {: .label }

> Blue label 
> {: .label .label-blue }
> Purple label
> {: .label .label-purple }
> Green label
> {: .label .label-green }
> Yellow label
> {: .label .label-yellow }
> Red label
> {: .label .label-red }

> Section label
> {: .label .label-blue .section-label }
> Section label
> {: .label .label-green .section-label }
> Section label
> {: .label .label-red .section-label }

> Centered label
> {: .label .label-purple .centered }
> Centered label
> {: .label .label-yellow .centered .section-label }

```markdown
Default label
{: .label }

Blue label
{: .label .label-blue }
Purple label
{: .label .label-purple }
Green label
{: .label .label-green }
Yellow label
{: .label .label-yellow }
Red label
{: .label .label-red }

Section label
{: .label .label-blue .section-label }
Section label
{: .label .label-green .section-label }
Section label
{: .label .label-red .section-label }

Centered label
{: .label .label-purple .centered }
Centered label
{: .label .label-yellow .centered .section-label }
```

---

## Tables

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

```markdown
| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |
```

---

## Lists
### Unordered list
> - Item 1
> - Item 2
> - Item 3
>
> _or_
> 
> * Item 1
> * Item 2
> * Item 3

```markdown
- Item 1
- Item 2
- Item 3

_or_

* Item 1
* Item 2
* Item 3
```

### Ordered list
> 1. Item 1
> 2. Item 2
> 3. Item 3

```markdown
1. Item 1
2. Item 2
3. Item 3
```

### Task List
> - [ ] Task 1
> - [ ] Task 2
> - [x] Completed Task

```markdown
- [ ] Task 1
- [ ] Task 2
- [x] Completed Task
```

---

## Horizontal Rules
Several custom horizontal rules have been defined for this website, below is what they look like. For a horizontal rule to be properly rendered, you must leave a blank link on either side of the horizontal rule

---

<hr>

<hr class="bold medgrey">

<hr class="dashed blue">

<hr class="dotted flame">

<hr class="content-break aqua">

```markdown
---

<hr>

<hr class="bold medgrey">

<hr class="dashed blue">

<hr class="dotted flame">

<hr class="content-break aqua">
```

---

## Color Palette
<div class="flex-display">
<img src="https://placehold.co/100/b40000/fff?text=red">
<img src="https://placehold.co/100/f28c0d/fff?text=flame">
<img src="https://placehold.co/100/fde565/fff?text=yellow">
<img src="https://placehold.co/100/bfcc46/fff?text=green">
<img src="https://placehold.co/100/2db597/fff?text=aqua">
<img src="https://placehold.co/100/80c3d4/fff?text=blue">
<img src="https://placehold.co/100/5b73bb/fff?text=purple\n(not+really)">
<img src="https://placehold.co/100/808080/fff?text=medgrey">
<img src="https://placehold.co/100/333333/fff?text=dkgrey">
</div>

> This is some **RED** text
> {: .red-text }

> This text is **YELLOW** on a **PURPLE** background
> {: .purple .yellow-text }

> Using the **INLINE-DISPLAY** class, we can prevent the background from taking up the whole width of the page.
> 
> This text is **DKGREY** highlighted in **AQUA**
> {: .aqua .dkgrey-text .inline-display }

<p class="dkgrey-text inline-display">Using HTML, you can <span class="aqua">HIGHLIGHT</span> select words</p>

```markdown
This is some **RED** text
{: .red-text }

This text is **YELLOW** on a **PURPLE** background
{: .purple .yellow-text }

Using the **INLINE-DISPLAY** class, we can prevent the background from taking up the whole width of the page.

This text is **DKGREY** highlighted in **AQUA**
{: .aqua .dkgrey-text .inline-display }

<p class="dkgrey-text inline-display">Using HTML, you can <span class="aqua">HIGHLIGHT</span> select words</p>
```

---