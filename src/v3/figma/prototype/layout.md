
---
title: Responsive Design
platform: figma
type: prototype
sidebarSorting: 4
categories: 
- Prototype
order: 2
---

## Constraints

Figma's responsive constraints make it easier to design for multiple screen sizes. You can create fully responsive designs that can be resized both in the browser preview and in the code.

![Figma Constraints Demo](https://p46.f4.n0.cdn.getcloudapp.com/items/bLuRAk8r/Constraints%20demo%20GIF.gif?source=viewer&v=fda204d6fe522bb2d172eb2d4e5b6db2)


## How Does It Work?

An element’s responsive constraints are set in relation to its nearest parents. A parent can be a frame, a group, or a component.

**FOR EXAMPLE**
-   If we want the Purple Background layer in the example below to stretch full width when its parent, “Our Story-Mobile” frame, gets wider, we need to select **Left** and **Right** from the Constraints options.

![Figma Constraints enabled](https://p46.f4.n0.cdn.getcloudapp.com/items/geuzbgLz/Artboard%402x.png?source=viewer&v=dd2354a48a13cab63fa2e797fecc070a)

> **IMPORTANT:** Make sure that **Layout Constraints** are enabled in the Anima plugin
> 

**Constraints in Groups and Components**

As mentioned, the constraints settings apply in relation to the element’s closest parent. This means that if the elements are inside a Group or a Component, these need to have responsive settings applied to them as well.

**FOR EXAMPLE**

Inside this Announcement group below (Parent) we want:

-   The Purple background to stretch full width and always touch the top
-   The Announcement Text to always stay centered and 15px from the top
-   The Close icon to always be 17 pixels from the left corner
-   The entire Announcement Group (Parent) to stretch when its parent (Our Story frame) is stretched


 Then, we need the following Constraints settings:

![Figma Constraints Settings](https://p46.f4.n0.cdn.getcloudapp.com/items/geuzbbZW/Constraints%20settings.png?source=viewer&v=0b4b3fbd60684b8da56c122f627751da)


>[Learn more about Figma Constraints](https://help.figma.com/hc/en-us/articles/360039957734-Apply-Constraints-to-define-how-layers-resize). 
>

## Constraints + Breakpoints

If you have more than one screen size, connecting them with [**Breakpoints**](https://docs.animaapp.com/v3/figma/prototype/breakpoints.html) and adding **Constraints** is a very powerful combo! They will create a very smooth transition between all your screen sizes. Try it out!

![Breakpoints and Constraints Combo](https://p46.f4.n0.cdn.getcloudapp.com/items/2Nuywq1r/Breakpoints%20plus%20constraints@2x.png?source=viewer&v=b771a9f48aa17384ae9e8e795c6180bb)


## Try It!

Click “**Preview in Browser**” in the Anima plugin to see it come to life.

![Figma Constraints Demo](https://p46.f4.n0.cdn.getcloudapp.com/items/bLuRAk8r/Constraints%20demo%20GIF.gif?source=viewer&v=fda204d6fe522bb2d172eb2d4e5b6db2)

 - Preview [**live in the browser**](https://responsive-cupcake.animaapp.io)
 - Open [**Figma Sample File**](https://www.figma.com/file/9JyhAlwpiCEmnS7sVxao34/Miss-Cupcake-Responsive-Sample-File)

