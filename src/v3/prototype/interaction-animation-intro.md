---
title: Interaction & Animation
type: prototype
order: 11
---
## Overview

**Interactions** and **Animations** empower designers to create beautiful, interactive components right inside Sketch. 

- **Interaction** - Add Click, Hover, or  Timer actions to trigger state transitions
- **Animation** -  States transition automatically without a trigger

![Interactive Hover Animation](https://docs.animaapp.com/images/timeline/samples/components/buynow.gif)

## Create Interactions & Animations

 1. In the **Prototyping** tab, select **Interaction** or **Animation**
 2. Click Create

![Interaction and Animation Interface](https://d3dr1ze7164817.cloudfront.net/items/2n3K3T1x2g0k0e3v1B0y/Prototype%20UI.png)

## Layers

* When entering the Intereaction/Animation editor, each layer in the Sketch group or artboard will convert into an image
* The format of the image can be PNG, JPG or SVG, as selected in Sketch's Exportable panel (or PNG by default)
* Layers can be moved around, resized, rotated, hidden or shown, in each **State**(except the **Initial State**)

![Layers](https://docs.animaapp.com/images/timeline/terminology/layers.png)

### Position

![Change Position](https://docs.animaapp.com/images/timeline/position.gif)

### Resize

![Resize Layers](https://docs.animaapp.com/images/timeline/resize.gif)

### Rotation

![Rotate Layers](https://docs.animaapp.com/images/timeline/rotate.gif)

### Opacity

![Change Opacity](https://docs.animaapp.com/images/timeline/opacity.gif)

## States

 - A **State** is a canvas which contains all the layers imported from Sketch
 - The **Initial State** can be imported from a Sketch **Symbol, Artboard,** or **Group**
 - All the layers that exists in the **Initial State**, will exists in all other **Keyframes** (but can be hidden)
 - Layers cannot be added or removed from a **State**, but can be made hidden or visible
 - You can have as many **States** as you want, but to create an animation you need the **Initial State** and at least one more

### The Initial State

* The **Initial State** is the starting point. That means all the layers are positioned as they are positioned in the Sketch document
* You cannot change layers size or position or any other property in the **Initial State**
* To animate layers movement or resizing, create another **State** and move layers around

![Initial State](https://docs.animaapp.com/images/timeline/terminology/initial-state.png)

![States](https://docs.animaapp.com/images/timeline/terminology/states.png)

### States Left Sidebar

* The **States Sidebar** is a list of all the **States**. 
* In each **State** you can view and select all the sub layers and groups of the **State**.
* All the **States** contain exactly the same layers.
* The **State** has the same layer hierarchy as imported from the Sketch document.
* In each **State** (except the **Initial State**) you can show/hide layers and change their properties, which will result in an animation.

![States Sidebar](https://docs.animaapp.com/images/timeline/terminology/states-sidebar.png)

## Actions
 - An **Action** is a combination of a **Layer**, an **Event** and a **Target State**
 - An **Action** is what triggers the transition between two **States**
 - Each transition contains one or more small animations of the different layers the **States** contain

![Actions Supported](https://d1wuojemv4s7aw.cloudfront.net/items/0m392P3Z1E2H081S212B/Actions%20Supported.png)

As of now, supported **Events** are:

- Mouse Click
- Mouse Enter
- Mouse Leave
- Timer

When the user performs the chosen **Event**, a **Transition** is triggered onto the **Target State**.

For example, let's say there are 2 states: **initial** and **state1**.

If we add an **Action** to the **Button Layer** in the **initial state** with the event '**On Mouse Enter**' and connect it to **state1**, then when the user hovers the mouse on the button, the component will perform a **Transition** to **state1**.

![Adding Actions](https://d1wuojemv4s7aw.cloudfront.net/items/0U321N1N0j3i3Y0r1444/%5B53570823639cec21b5ae615f08443441%5D_Action.gif)


## Transitions

-   A **Transition** is an animated transition between two **States**
-   Each **Transition** contains one or more small animations of the different layers the **States** contain
-   You can select a  **Transition** by clicking the blue arrow between two **States**

![Transition](https://d1wuojemv4s7aw.cloudfront.net/items/0p1k1d063k1k3m200c2W/Transition.png)

## Timelines

Learn the properties of **Timeline** to achieve awesome animations!

A **Timeline** represents the duration, delay and easing of a specific movement of a layer.

> **Example:**
> 
> If a layer moves from left to right, **Timeline**  allows us to control how much time this movement will take (duration), if there is a delay, and the easing

![Timeline](https://docs.animaapp.com/images/timeline/terminology/timelines1.png)

## Timelines Properties

* Each layer can have its own **Timeline** 
* By moving and stretching a **Timeline** , you can determine the delay and duration of a specific animation
* To control the  **delay** of an animation, drag the **Timeline**  left or right
* To control the **duration** of an animation, stretch or shrink the **Timeline** 

![Timeline Properties](https://docs.animaapp.com/images/timeline/terminology/timelines2.png)

### Delay

![Timeline Delay](https://docs.animaapp.com/images/timeline/delay.gif)

### Duration

![Timeline Duration](https://docs.animaapp.com/images/timeline/duration.gif)

### Curve

Manages the easing function which determines rate of change of a parameter over time. 

In other words: "How to change a value (for example position of layer) over time".

![Easing Curve](https://d3dr1ze7164817.cloudfront.net/items/0F3x040Z0A393U0S1w3b/Ease%20Curve.png)

  
- **Linear:** As time moves along, the value increases in equal amounts
  
- **Ease-In:** Causes the animation to start more quickly than linear ones, and it also has deceleration at the end
  
- **Ease Out:** This is the opposite of Ease-In. Animation starts slow and ends fast
  
- **Ease In Out:** Slow start, fast middle, and slow end

![](https://downloads.intercomcdn.com/i/o/93593233/7df6be1d08861506d55d37e8/1%2A53GgH9lFyLuj5QNT8KgxrQ.gif)


## Sketch Tutorial 

![Sketch Tutorial File](https://d3dr1ze7164817.cloudfront.net/items/0Q0T3w2t282b2E3j3i2i/Interaction%20Tutorial%20file.png)

- Sketch Tutorial File: [[Download]](https://www.dropbox.com/s/payd7gjthdkta3q/Interaction-Animation%20Tutorial%20v3.sketch?dl=1)

