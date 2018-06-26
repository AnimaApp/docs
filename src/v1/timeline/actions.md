---
title: Actions
type: timeline
order: 6
---

An `Action` is a combination of a `Layer`, an `Event` and a `Target State`.

![](/docs/images/timeline/terminology/actions1.png)

As of now, supported events are:

* Mouse Click
* Mouse Enter
* Mouse Leave

When the user performs the chosen event, a `Transition` is triggered onto the `Target State`.

For example, let's say there are 2 states: `state0` and `state1`.

If we add an `Action` to the button layer, with the event 'Click' and target `state`, then when the user clicks the button, the component will perform a transition to `state1`.

![](/docs/images/timeline/actions.gif)
