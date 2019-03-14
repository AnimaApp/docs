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

![Actions Supported](http://f.cl.ly/items/0m392P3Z1E2H081S212B/Actions%20Supported.png)

As of now, supported **Events** are:

- Mouse Click
- Mouse Enter
- Mouse Leave
- Timer

When the user performs the chosen **Event**, a **Transition** is triggered onto the **Target State**.

For example, let's say there are 2 states: **initial** and **state1**.

If we add an **Action** to the **Button Layer** in the **initial state** with the event '**On Mouse Enter**' and connect it to **state1**, then when the user hovers the mouse on the button, the component will perform a **Transition** to **state1**.

![Adding Actions](http://f.cl.ly/items/0U321N1N0j3i3Y0r1444/[53570823639cec21b5ae615f08443441]_Action.gif)

## Transitions

-   A **Transition** is an animated transition between two **States**
-   Each **Transition** contains one or more small animations of the different layers the **States** contain
-   You can select a  **Transition** by clicking the blue arrow between two **States**

![Transition](http://f.cl.ly/items/0p1k1d063k1k3m200c2W/Transition.png)


## Sketch Tutorial 

![Sketch Tutorial File](http://f.cl.ly/items/0Q0T3w2t282b2E3j3i2i/Interaction%20Tutorial%20file.png)

- Sketch Tutorial File: [[Download]](https://www.dropbox.com/s/payd7gjthdkta3q/Interaction-Animation%20Tutorial%20v3.sketch?dl=1)

