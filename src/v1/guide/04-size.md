---
title: Size
type: guide
order: 4
---

![](/docs/images/size.png)

## Width & Height

You can set a `Layer` `width` and `height` by checking the `width` and `height` checkboxes.  
When you check the `width` or `height` box, Auto-Layout will set the current value as the constraint value.
The taken value will be either by `pixels` or by `percent`, depending on the current toggle state.

## Min & Max 

You can set the `miniumum` or `maximum` value of the `width` or the `height` of a `Layer`  

Once set, the layer `width` or `height` will never exceed the min/max values, no matter what the `Artboard` size is.

![](https://cdn-images-1.medium.com/max/800/1*m6_5mu3TV_Idv7OMs2UIZQ.gif)

**To keep the layer pinned to the left rather from the right, set the width to % and uncheck `Right` pin.**

## Custom Height

In some cases you want to extend the height of an artboard further than the default platform screen sizes, in order to show how the design looks when the user scrolls down.

Auto-Layout will automatically recognize artboards that do not have default screen sizes and will never decrease their height to less than their original height.