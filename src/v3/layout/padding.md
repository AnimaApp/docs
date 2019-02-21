---
title: Padding
type: Layout
order: 4
---
![Padding in Sketch](https://cdn-images-1.medium.com/max/1600/1*ECdwO4upxkecfHmRr7tQkw.gif)

## What is Padding? 

Padding means that when you change the content, the background changes dynamically with it. It works great when used with **Stacks**, **Pins**, and inside **Symbols**.

## How To Use Padding

Here’s the basic flow:

 1.   Create a **Text Layer** and select it
 2.   Click the **Padding** icon in the **Layout** tab
 3.   Adjust the distance you’d like that background rectangle to keep from the text
 4. Expand the **Padding Group** and select its **Background Layer** to customize it

![Padding in Sketch](http://f.cl.ly/items/3X4542273D1A2w2F3N0B/%5B07d36550d422eba97285191f6cbba76c%5D_Padding%20button.gif)![Edit Padding Background](http://f.cl.ly/items/3Q091t301u2i0c421g1x/%5B01206ff51d0e1d9243bc7ec852f932a8%5D_Edit%20padding%20background.gif)

### Padding Controls

-   Click the **Padding** input toggle 🔁 or click below the **Padding** values to switch input modes
-   Click & drag a label to adjust the **Padding** values

![](http://f.cl.ly/items/3s2b0S3m0p3I0V0Y1k3I/[8818d87c31887aea28df30c226afcb47]_Padding%20toggle.gif)

### Symbols — Padding Overrides

-   Select the **Padding** group and click '*Create Symbol*'
-   Change the text value using **Overrides** to see the **Padding** applied in real-time
-   It will also resizes the **Symbol** instance

![](http://f.cl.ly/items/090W2P2a0l0W2H3X1A0n/[d6fde6b4d79af62962bb146423f85143]_Text%20override.gif)

## Padding + Stacks

**Stacks** allows layers to push each other, and keep a constant spacing between them.

To see how **Padding** and **Stacks** play together:

-   **Stack** some groups with **Padding**
-   Adjust the **Padding** of the **Padding Group** to see how it works
-   Advanced: Create a Symbol from that **Stack** and edit Overrides
-   Advanced 2: Add a background with padding to the whole **Stack**

![Padding Inside Stacks](http://f.cl.ly/items/1M0q3a093p0V3g3U0v1T/[a5a8a7fc2a0d5dbe4f5b6efbca438c2d]_Padding%20inside%20Stacks.gif)

## Padding + Pins

To see how **Padding** and **Pins** play together:

-   Create a group with **Padding**
-  **Pin** it to the right of the **Artboard**
-   Edit content to see it in action

![Padding and Pins](http://f.cl.ly/items/2f3y0I0R3z2f1B160744/[39dc1a02aa366158a25a281ecd3d8456]_Paddings%20and%20Pins.gif)

## Padding for Nested Symbols

Example: You have a button **Symbol** with **Padding** inside a post cell **Symbol** that has a **Stack** and also has **Padding**.  

Here’s how it looks with Overrides:

![Override Padding Symbols](http://f.cl.ly/items/233z3w0o1R302t0q1i2o/Paddings%20for%20nested%20Symbols.png)

Sample Sketch File: [Download](https://animaapp.s3.amazonaws.com/tutorials/Anima%20Nested%20Padding%20Sample.sketch)

> ❗️Important
>
> Make sure that Padding and Stack for Neste Symbol is enabled from the Anima Settings.
> 
> ![Enable Padding and Stacks for Nested Symbols](http://f.cl.ly/items/470W0O2G0q0N0l1P0I3y/Enable%20nested%20Symbols.png)
