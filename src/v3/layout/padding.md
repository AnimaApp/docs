---
title: Padding
platform: sketch
sidebarSorting: 2
type: Layout
order: 4
---
![Padding in Sketch](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Padding.gif)

## What is Padding? 

Padding means that when you change the content, the background changes dynamically with it. It works great when used with **Stacks**, **Pins**, and inside **Symbols**.

## How To Use Padding

Here’s the basic flow:

 1.   Create a **Text Layer** and select it
 2.   Click the **Padding** icon in the **Layout** tab
 3.   Adjust the distance you’d like that background rectangle to keep from the text
 4. Expand the **Padding Group** and select its **Background Layer** to customize it

![Padding in Sketch](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Padding%201.gif)
![Edit Padding Background](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Padding%202.gif)

### Padding Controls

-   Click the **Padding** input toggle 🔁 or click below the **Padding** values to switch input modes
-   Click & drag a label to adjust the **Padding** values

![Toggle Padding](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Padding%203.gif)

### Symbols — Padding Overrides

-   Select the **Padding** group and click '*Create Symbol*'
-   Change the text value using **Overrides** to see the **Padding** applied in real-time
-   It will also resizes the **Symbol** instance

![Padding Overrides](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Padding%204.gif)

## Padding + Stacks

**Stacks** allows layers to push each other, and keep a constant spacing between them.

To see how **Padding** and **Stacks** play together:

-   **Stack** some groups with **Padding**
-   Adjust the **Padding** of the **Padding Group** to see how it works
-   Advanced: Create a Symbol from that **Stack** and edit Overrides
-   Advanced 2: Add a background with padding to the whole **Stack**

![Padding Inside Stacks](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Padding%205.gif)

## Padding + Pins

To see how **Padding** and **Pins** play together:

-   Create a group with **Padding**
-  **Pin** it to the right of the **Artboard**
-   Edit content to see it in action

![Padding and Pins](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Padding%206.gif)

## Padding for Nested Symbols

Example: You have a button **Symbol** with **Padding** inside a post cell **Symbol** that has a **Stack** and also has **Padding**.  

Here’s how it looks with Overrides:

![Override Padding Symbols](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Padding%207.png)

Sketch Sample File: [[Download]](https://animaapp.s3.amazonaws.com/tutorials/Anima%20Nested%20Padding%20Sample.sketch)



> ❗️Important
>
> Make sure that Padding and Stack for Neste Symbol is enabled from the Anima Settings.
> 
> ![Enable Padding and Stacks for Nested Symbols](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Padding%208.png)
