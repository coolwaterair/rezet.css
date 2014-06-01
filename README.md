rezet.css
===

is another CSS reset for developer who perefer to build layout from scratch instead of using the framework.
Everything is up to you, your layout is totally in your control.

>Just code your layout. We've reset the needed html for you


API
---
###Table

We provide the most basic table's bone. Your part is styling and customizing.
```
<div class="table">
    <div class="row">
        <div class="column">Column 1</div>
        <div class="column">Column 2</div>
        <div class="column">Column 3</div>
    </div>
    <div class="row">
        <div class="column">Column 1</div>
        <div class="column">Column 2</div>
        <div class="column">Column 3</div>
    </div>
</div>
```
&nbsp;

&nbsp;

###Columns Group

Do you need something __simpler__ than table? Awesome! Use `colsgroup`
```
<div class="colsgroup">
    <div class="column">Column 1</div>
    <div class="column">Column 2</div>
</div>
```
&nbsp;

&nbsp;

###Transition
Need basic of transition effect when hover-ed or click-ed? We provide some class:
- `transition-all`
- `transition-bg`
- `transition-color`
- `transition-opacity`

__Example :__

In the html:
```
<div class="yourclass transition-bg">Hi</div>
```
In the css:
```
.yourclass {
    background-color: #000;
}

.yourclass:hover {
    background-color: #ff0;
}
```
&nbsp;

&nbsp;

###Color
Sometimes these classes are useful :P

- `.black`
- `.white`
- `.blue`
- `.red`

example:
```
<a href="http://github.com/" class="black">Black link</a>

<div class="red">Red text</div>
```
&nbsp;

&nbsp;

###Space
Need inline space?
- `.space5`
- `.space10`
- `.space15`
- `.space20`
- `.space25`
- `.space30`
- `.space35`
- `.space40`
- `.space45`
- `.space50`

__Example__

Insert 20px and 25px inline space :

```
I prefer to code layout <div class="space20"></div> from scratch.
Because my need is <span class="space25"></span>just simple
```
&nbsp;

&nbsp;

###Line Break
Here is some _line break_ class to be used when you're bored with conventional _<br>_ tag.
- `.break5`
- `.break10`
- `.break15`
- `.break20`
- `.break25`
- `.break30`
- `.break35`
- `.break40`
- `.break45`
- `.break50`

__Example__

Make a 30px breaking space :
```
Design is really about solving problem
<div class="break30"></div>
And don't code what you can't love tomorrow :P
```
&nbsp;

&nbsp;

###Formatting
Maybe these can help :)
- `.bold`
- `.italic`
- `.bold-italic`

Example :
```
<span class="bold-italic">This is text :P</span>
```
&nbsp;

&nbsp;

###Positioning
- `.absolute`
- `.relative`
- `.fixed`
- `.static`

- `.center` (centering element, not centering text)
- `.right`
- `.left`
- `.clear` (ever heard clearfix? Yeah, this is shorter :P)

__Example__

1. Creating floating layout :
    
    ```
    <div class="yourdiv">
        <div class="left">Im floating left</div>
        <div class="right">Im right</div>
        
        <div class="clear"></div>
    </div>
    ```
&nbsp;
2. Centering element:

    ```
    <div style="width: 900px; background: #eee;">
        <div style="width: 400px; background: #999;" class="center">Yeah !</div>
    </div>
    ```
&nbsp;

&nbsp;

###Display
- `.none` (the element would be hidden, and javascript will not be able to get innerHTML)
- `.block`
- `.none`
- `.inline`
- `.inline-block`
- `.table-cell`
- `.hidden` (Hiding the element without affecting the layout. But it's not "none" :) . So, Javascript can still do innerHTML and other methods)

Example :
```
<div class="none">Im not displayed</div>

<div class="hidden">Im just hidden. But not affect the layout</div>
```
&nbsp;

&nbsp;

###Special Reset
- `.no-overflow` (prevent your element from overflowing the parent)
- `.no-outline` (if you want to remove the natural `<input>` outline :D)
- `.not-list` (_totally_ remove the `<ul>` & `<ol>` default style)

__Example__

Using `ul` without padding & margin :)
```
<ul class="not-list">
    <li>One</li>
    <li>Two</li>
    <li>Three</li>
</ul>
```

How about resetting navigation? Easy! You don't have to reset them manually. It would be reset automatically :
```
<nav>
    <ul>
        <li>Home</li>
        <li>About</li>
        <li>Contact</li>
    </ul>
</nav>
```
&nbsp;

&nbsp;

> This is focused for HTML5. So, deprecated tag is not included in the reset.
> 
> Support modern browsers like: latest Chrome, FF, Opera. Sure, we love __IE__, so we support them from version 10+
&nbsp;

&nbsp;

&nbsp;

License
---

###MIT

_It's free!_