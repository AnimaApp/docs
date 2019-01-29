
---
title: Actions
type: Prototype
order: 15
---

 - An **Action** is a combination of a **Layer**, an **Event** and a
   **Target State**
 - An **Action** is what triggers the transition between two **States**
 - Each transition contains one or more small animations of the different layers the **States** contain

![Actions Supported](http://f.cl.ly/items/0m392P3Z1E2H081S212B/Actions%20Supported.png)

As of now, supported events are:

* Mouse Click
* Mouse Enter
* Mouse Leave
* Timer

When the user performs the chosen event, a **Transition** is triggered onto the **Target State**.

For example, let's say there are 2 states: **initial** and **state1**.

If we add an **Action** to the **Button Layer** in the **initial state** with the event **On Mouse Enter** and target **state1**, then when the user hovers the mouse on the button, the component will perform a transition to **state1**.

![Adding Actions](http://f.cl.ly/items/0U321N1N0j3i3Y0r1444/[53570823639cec21b5ae615f08443441]_Action.gif)
