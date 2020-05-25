---
title: Interactions Intro
platform: sketch
type: prototype
order: 14
---
**Interactions** are **State** **Transitions** triggered by  Click, Hover, or  Timer **Actions**.

## States

 - A **State** is a canvas which contains all the layers imported from
   Sketch
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
 - An **Action** is a combination of a **Layer**, an **Event** and a
   **Target State**
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
