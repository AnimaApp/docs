---
title: Size
type: layout
order: 4
---
![Anima Width and Height Values](http://f.cl.ly/items/1C281S0X2i2B0s0Z0E0Y/v3%20%E2%80%93%20Layout%20W%20H.png)

## Width & Height

You can set a `Layer` `width` and `height` by checking the `width` and `height` checkboxes.  
When you check the `width` or `height` box, **Layout** will set the current value as the constraint value.
The taken value will be either by `pixels` or by `percent`, depending on the current toggle state.

## Min & Max 

You can set the `miniumum` or `maximum` value of the `width` or the `height` of a `Layer`  

Once set, the layer `width` or `height` will never exceed the min/max values, no matter what the `Artboard` size is.

![Min and Max Width Demo](http://f.cl.ly/items/2q3u1P0p391b3j3O2b2O/Layout%20Max%20and%20Min%20Width.gif)

**Tip:** 

> To keep the layer pinned to the left rather from the right, set the
> width to % and uncheck `Right` pin

## Custom Height

In some cases you want to extend the height of an artboard further than the default platform screen sizes, in order to show how the design looks when the user scrolls down.

**Layout** will automatically recognize artboards that do not have default screen sizes and will never decrease their height to less than their original height.
