---
created: 2026-08-05
topic: "[[The Odin Project]]"
source:
tags:
  - learning
category: "[[Study notes]]"
---
As I understand it , according to [[Introduction to Flexbox  The Odin Project]] , flexbox is a [[CSS]] system(basically a really special css property) that allows for elements to grow/shrink to fill the available space. The rate in which they grow and shrink can also be set.

Put the css declaration and property, `display: flex` to "enable" flex in to an element.
If any elements are nested inside this element then this element would be a ==flex container== and the elements inside will be called ==flex items== , these ==flex items== can also become ==flex containers== if they were to also have elements inside them, making them both flex items and containers depending where you look at it from.

![[Pasted image 20260805061119.png]]



## Growing and Shrinking 

![[Pasted image 20260805061534.png]]

flex: 1 tells an item how to grow and shrink within its container. It is also a ==shorthand property== for 3 different properties. 

*==Shorthand properties== are CSS properties that let you set the values of multiple other CSS properties simultaneously. Using a shorthand property, you can write more concise (and often more readable) stylesheets, saving time and energy.*

*Source: [Shorthand properties on MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand_properties)*

flex would be shorthand for , flex-grow, flex-shrink and flex basis

### flex-grow

flex-grow expects a single number in which it will determine how much it would grow to take up the available space compared to the other items in the container. say i give an element a flex-grow value of 4 and the other element in the container remains at 1, there is 100px available space for them to grow . the element with the 4 value will grow 80px while the other,20px.

the value represents the ratio in which an element grows according to the available space and the other items in the container with it


### flex-shirnk

pretty much the opposite of flex-grow, the higher the value the more an element will shrink compared to the other items.
flex-shrink : 0 will have an element not shrink if the container would become smaller than all the items . say a container becomes 100px wide and the 2 items are 60px each, the item that would have flex-shrink : 0 would not change and the other one would become 40px

### flex-basis

sets the base size of an item the growing and or shrinking of an item is based on that initial size. the shorthand defaults to flex-basis : 0% .
flex-basis : 0 , ignores an elements set and starts growing and or shrinking depending on the values
flex-basis : auto . looks for the elements set width first before starting its growing and or shrinking.

*There is a difference between the default value of `flex-basis` and the way the `flex` shorthand defines it if no `flex-basis` is given. The actual default value for `flex-basis` is `auto`, but when you specify `flex: 1` on an element, it interprets that as `flex: 1 1 0`. If you want to only adjust an item’s `flex-grow` you can do so directly, without the shorthand. Or you can be more verbose and use the full 3 value shorthand `flex: 1 1 auto`, which is also equivalent to using `flex: auto`.*

### flex auto

`flex: auto` is one of the shorthands of flex. When `auto` is defined as a flex keyword it is equivalent to the values of `flex-grow: 1`, `flex-shrink: 1` and `flex-basis: auto` or to `flex: 1 1 auto` using the flex shorthand.  `flex: auto` is not the default value when using the flex shorthand despite the name being “auto” 

#### In practice

In practice you will likely not be using complex values for `flex-grow`, `flex-shrink` or `flex-basis`. Generally, you’re most likely to use declarations like `flex: 1;` to make divs grow evenly and `flex-shrink: 0` to keep certain divs from shrinking.

It _is_ possible to get fancy, and set up layouts where some columns relate to each other in a specific ratio, so it’s useful to know that you can use other values, but those are relatively rare.