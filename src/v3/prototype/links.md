---
title: Links
platform: sketch
sidebarSorting: 3
type: prototype
order: 3
---

 **Prototype** enables you to create both internal and external links between artboards (webpages).

There are 5 types of **Links**:

1. **Internal Link** - A link between different artboard 
2. **External Links** - A link to an external website
3. **Scroll To Links** - A link that will direct the user to different section on the same screen
4. **Overlay Links** - A link that displays an artboard (webpage)  over the existing one it was clicked from
5. **Back Links** - A link that directs back to the previous screen
 
## Internal Links

In **Sketch**, each artboard represents a webpage. You can create **Links** to connect different artboards (webpages):

1. Select the layer which will trigger the navigation event (Usually this will be a button)
2. Click **Links**  in the **Flow** section of **Prototype**
3. Select the target artboard  (webpage)

![Creating Page Link](https://s3.amazonaws.com/animaapp/docs/sketch/Prototype%20-%20Links%20-%20Internal.gif)

>❗️If the Artboard is in another Sketch Page, use Sketch native [Prototype Links](https://www.sketch.com/docs/prototyping/links) and select the Page from the Target option.


## External Links

Many times you want to create links to external websites that aren't a part of your website, for example,  links to Facebook, Twitter, App Stores, etc..

To create an **External Link**:

1. Select the layer which will trigger the navigation event. Usually this will be a text layer or a button
2.  Click **Links**  in the **Flow** section of **Prototype**
3. Point arrow and click **External Link** button at the top bar
4. Enter the URL for the external website or enter 'mailto: info@example.com' to link to an email address

![](http://f.cl.ly/items/2X2a401i0E0Q3612461o/[97f25f716beb06086dc5f2e469aba5d0]_External%20Link.gif)

## Scroll To Links

You can create **Links** to a different section in the same artboard (webpage).

To create an **Scroll To Link**:
1. Select the layer which will trigger the navigation event
2. Click **Links**  in the **Flow** section of **Prototype**
3. Select the target **Layer** in the Layers List  (webpage) 

>❗️Note: This does not work on **Groups folders**, only **Layers** & **Symbols**

![Scroll To Links](https://s3.amazonaws.com/animaapp/docs/sketch/Prototype%20-%20Links%20-%20anchor.gif)


## Overlays
An **Overlay** is a link type that lets you display another artboard on top of the existing one rather than as a separate destination screen.  

**Overlays** can be used for modal windows, drop-down menus, pop-up notifications, all without leaving your current screen.

Creating an **Overlay** is as easy as creating two links:

1.  Select the **Layer** that will trigger the **Overlay** 
2. With **Links** , connect it to the **Overlay** artboard
3.  Check the **Overlay** box in **Links**
4.  Now, select the **Overlay** component and link it to the "**Dismiss Overlay**" option at the top menu bar
5.  Change the **Overlay** artboard background color to transparent by moving the transparency slide to the left. Make sure that "*Include in export*" is checked in

> **ℹ️ Overlay Tips:**
>  - For a cooler **Overlay** effect, set its artboard background color to 70% Transparent
   
![Transparent Overlay Background](https://s3.amazonaws.com/animaapp/docs/sketch/Prototype%20-%20Links%20-%20overlay%20bg.png)

![Overlay Links](https://s3.amazonaws.com/animaapp/docs/sketch/Prototype%20-%20Links%20-%20overlay.gif)

[[Download]](http://bit.ly/Anima-Dashboard-Tutorial) this High-Fidelity Prototype Sketch file to try it yourself.

## Removing Links

If you created a link and now you want to remove it:

1. Select the **Layer** with the link you want to remove
2. Click the **Trash Icon** in the **Links** section

![Remove Links](https://s3.amazonaws.com/animaapp/docs/sketch/Prototype%20-%20Links%20-%20remove.gif)
