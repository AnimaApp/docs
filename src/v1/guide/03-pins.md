---
title: Pins
type: guide
order: 3
---

## Simple 

![](/docs/images/pins-simple.png)

Simple pinning allows you to pin a layer to its parent with the following:

* Top
* Right
* Bottom
* Left
* Center Horizontally
* Center Vertically

When selecting a pin, Auto-Layout will set the pin constant value as the current pixel value.  

*For example if a layer is 20px from the right and you select `Pin to Right`, the `right` pin constant value will be set to 20px.*

Once a pin is set, Auto-Layout will enforce the pin value when the artboard is resized.  

*For example if you pinned a layer to the right by 20px, you can resize the artboard by dragging its right side and you'll notice the layer always stays 20px from the right.*

![](https://cl.ly/3h0m151x0N1R/download/Screen%20Recording%202017-01-29%20at%2002.22%20PM.gif)

### Pin to Parent

* A `Layer` is always pinned to its `Parent`
* A parent can be either an `Artboard` or a `Group`
* Pinning between siblings can be achieved using `Stacks`

`Layer` in an `Artboard`
![](/docs/images/pins1.png)

`Layer` in a `Group`
![](/docs/images/pins2.png)

## Advanced 

![](/docs/images/pins-advanced.png)

* To reveal the advanced pinning panel click `Pins`
* You can pin a layer either by `pixels` or by `percent`.
* `Pixels` values are in the left text boxes, `Percent` values are in the right text boxes.
* Use the `Toggle` button to select which type of pinning.

![](https://cl.ly/0x3m3L2Z4628/download/Screen%20Recording%202017-01-29%20at%2002.51%20PM.gif)

### Pinning by Pixels

![](/docs/images/pins3.png)

### Pinning by Percent

![](/docs/images/pins4.png)
