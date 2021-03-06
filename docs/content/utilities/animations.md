---
title: Animations
path: utilities/animations
example_layout: toggle
status: Stable
source: 'https://github.com/primer/css/blob/master/src/utilities/animations.scss'
bundle: utilities
---

Animations are reusable animation classes that you can use to emphasize an element. All of these animations will animate if you toggle their visibility using the "Toggle" button.

 

## Fade In

The `.anim-fade-in` class is used to fade in an element on the page. This will run once when the element is revealed.

```erb
<span class="anim-fade-in"><%= octicon("mark-github", :height => 32, :class => "v-align-middle mr-2") %> Hello from GitHub!</span>
```

## Fade Out

The `.anim-fade-out` class is used to fade out an element on the page. This will run once when the element is revealed.

```erb
<span class="anim-fade-out"><%= octicon("mark-github", :height => 32, :class => "v-align-middle mr-2") %> Hello from GitHub!</span>
```

## Fade Up

The `.anim-fade-up` class is used to reveal an element on the page by sliding it up from below the fold. You should use this in a container with `overflow: hidden;` or on the bottom of the page.

```erb
<div class="anim-fade-up"><%= octicon("mark-github", :height => 32, :class => "v-align-middle mr-2") %> Hello from GitHub!</div>
```

## Fade Down

The `.anim-fade-down` class is used to slide an element down hiding it. You should use this in a container with `overflow: hidden;` or on the bottom of the page.

```erb
<div class="anim-fade-down"><%= octicon("mark-github", :height => 32, :class => "v-align-middle mr-2") %> Hello from GitHub!</div>
```

## Scale In

The `.anim-scale-in` class will scale the element in. This is useful on menus when you want them to appear more friendly.

```erb
<div class="anim-scale-in bg-gray-dark text-white p-2"><%= octicon("mark-github") %></div>
```

## Grow X

The `.anim-grow-x` class will grow an element width from 0-:100: real quick.

```html live
<div class="anim-grow-x py-2 bg-green"></div>
```

## Pulse

The `.anim-pulse` class will pulse an element infinitely.

```erb
<%= octicon("mark-github", :class => "anim-pulse") %>
```

## Hover animation

The `.hover-grow` class will increase the scale of the element upon hover.

```erb
<div class="Box hover-grow m-3 p-4">
  <%= octicon("mark-github", :height => 32) %>
</div>
```
