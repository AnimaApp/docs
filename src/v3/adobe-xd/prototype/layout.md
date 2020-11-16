---
title: Responsive Design
platform: xd
type: prototype
sidebarSorting: 2
categories: 
- Prototype
order: 3
---

Adobe XD’s **responsive resize constrainits** make it easier to design for multiple screen sizes. With Anima, you can create fully responsive designs that can be resized both in the browser preview and in the code.

![Responsive Cover](https://s3.amazonaws.com/animaapp/docs/adobe-xd/Prototype%20-%20XD%20Layout%20cover.gif)
[Preview Live Website](https://responsive-foodies.animaapp.io) | [Download Sample File](https://www.dropbox.com/s/bopwgypsmwk7p3i/Responsive%20Foodies.xd?dl=1)

## How Does it Work?

An element’s responsive constraints are set in relation to its nearest parents. A parent can be an artboard, a group, or a component/symbol.

**FOR EXAMPLE**

-   If we want a background layer to stretch full width when its parent, the “Homepage” artboard, gets wider, we need to select **Left, Right** from the Responsive Resize
-   And if we want it to keep the same distance to the top of its parent at all times, select **Top**

![Responsive Resize Settings](https://s3.amazonaws.com/animaapp/docs/adobe-xd/Prototype%20-%20XD%20Layout%20settings.png)

[Learn about Adobe XD’ Responsive Resize](https://helpx.adobe.com/xd/help/using-responsive-resize.html)

**Responsive Resize inside Groups and Components**

As mentioned, the responsive settings apply in relation to the element’s closest parent. This means that if the elements are inside a Group or a Component, these too need to have responsive settings applied to them.

**For example:**
Inside this Navigation group (Parent), we want the:

-   White Background to stretch the full width
-   Foodie logo to stay 30px from the left corner
-   Group of navigation Links to stay 30px from the right corner
-   The entire Group (Parent) to stretch when its parent (the artboard) is stretched

We can achieve this by adding the following resize constraints:

![Resize Settings example](https://s3.amazonaws.com/animaapp/docs/adobe-xd/Prototype%20-%20XD%20Layout%20example%20settings.png)

## Constraints + Breakpoints

If you have more than one screen size, connecting them with Breakpoints and adding Responsive Resize is a very powerful combo! They will create a very smooth transition between all your screen sizes. Try it out!

![XD Design with Breakpoints](https://s3.amazonaws.com/animaapp/docs/adobe-xd/Getting%20Started%20%E2%80%93%20Adobe%20XD%20cover.png)

Learn how to create [Breakpoints](https://docs.animaapp.com/v3/adobe-xd/prototype/breakpoints.html) with Anima for Adobe XD.

 **Preview it!**

Click “Preview in Browser” in the Anima plugin to [see it come to life!](https://responsive-foodies.animaapp.io)

![Responsive Cover](https://s3.amazonaws.com/animaapp/docs/adobe-xd/Prototype%20-%20XD%20Layout%20cover.gif)

[Preview Live Website](https://responsive-foodies.animaapp.io) | [Download Sample File](https://www.dropbox.com/s/bopwgypsmwk7p3i/Responsive%20Foodies.xd?dl=1)
