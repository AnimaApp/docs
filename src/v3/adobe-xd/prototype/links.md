---
title: Links
platform: xd
type: prototype
sidebarSorting: 3
categories: 
- Prototype
order: 2
---
<iframe width="864" height="486" src="https://www.youtube.com/embed/q6qc-2US6lA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

In **Adobe XD,** each artboard represents a webpage that can be connected to each other or other external websites via **Links**.

Anima supports the following **Adobe XD** native Prototype Interaction features:

- **Trigger** - Tap
- **Action** - Transition, Overlay, Previous Artboard

Anima also includes:
- **External Links** - A link to an external website
- **Anchor Links** - A type of link that directs the user to a specific section of the same artboard (webpage).

## Adobe XD Links

To connect artboards in the same Adobe XD document, use the **Tap** action and **Transition** type:

![Creating an Internal link with Adobe](https://p46.f4.n0.cdn.getcloudapp.com/items/xQuWA42W/XD%20Links%402x.png?v=5bb8b7cdd5d48fff14fec0ab7c79dd71 "Creating an Internal link with Adobe Links")

>❗️* IMPORTANT
>- Only **Tap** triggers and **Transition**, **Overlays**, **Previous Arboard** actions types are supported
>- Animation, Easing, and Duration settings are not currently supported

## External Links

Many times you want to create links to external websites that aren't a part of your website, for example,  links to Facebook, Twitter, App Stores, etc..

To create an **External Link**:

1. Select the layer which will trigger the navigation event  (i.e.: a social media icon or email address).
2. Click **Link**  in the **Flow** section
3. Select **External Link** from the Link Type drop-down menu
4. Enter the full URL for the external website or enter 'mailto: info@example.com' to link to an email address

![External Link](https://p46.f4.n0.cdn.getcloudapp.com/items/04uPOGwd/External%20Link%402x.png?v=a9f198f1e5d2462dde0db64e6306cb4e "Creating an External link")

## Overlays
An **Overlay** is a link type that lets you display another artboard on top of the existing one rather than as a separate destination screen.  

**Using Adobe XD Prototype Triggers* **

When you create a **Tap** trigger **Overlay** using Adobe XD, it automatically populates as an Anima **Overlay**.

>❗️*IMPORTANT
>- Only Transition and Overlays triggers are supported
>- Animation, Easing, and Duration settings are not currently supported
>- Overlay placement is currently fixed center

![Creating an Overlay with Adobe](https://p46.f4.n0.cdn.getcloudapp.com/items/WnuGrene/Adobe%20Overlay%402x.png?v=1c40a79d359450c44fb655eea5d586ca "Creating an Overlay with Adobe")

## Anchor Links

You can create **Links** to a different section in the same artboard (webpage).

To create an **Anchor Link**:
1. Select the layer which will trigger the navigation event*
2. Click **Link**  in the **Flow** section
3. Select **Anchor Linkk** from the Link Type drop-down menu
4. With your mouse, select the layer that will act as Anchor
5. Click **Done** to apply it

![Anima Anchor Links](https://p46.f4.n0.cdn.getcloudapp.com/items/9ZuE02Eo/anchor-link-Gif-ps.gif?v=8dec6c392485e58c784b61328d7b9c82)

>❗️IMPORTANT
> - Anchor Links can only be created to on the same artboard.

## Edit or Remove Links

If you created an Anima **Link** and now you want to remove it:

1. Select the **Layer** with the link you want to remove
2. Click the **Trash Icon** in the **Link** section

Adobe XD Triggers and actions can be edited or deleted in Prototype mode.


![Remove Links](https://p46.f4.n0.cdn.getcloudapp.com/items/YEuALpY0/Remove%20Link%402x.png?v=67dd7efa77421dc5fba7f2e7c365dd16)
