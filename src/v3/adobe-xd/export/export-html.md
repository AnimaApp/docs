
---
title: Export Adobe XD to HTML
platform: xd
type: export
order: 3
---

## Guide Overview

In this guide we will go over:

1.  How **Anima** converts Adobe XD documents into code
2.  How to export your Adobe XD document to an **HTML Code Pack**
3.  What the **HTML Code Package** looks like
4.  Frequently Asked Questions

## How Does Export Code Work

**Anima** enables designers to export full websites **HTML** & **CSS,** directly from an Adobe XD design.

Our process of transforming an Adobe XD design into a website involves many steps.

Basically, we’re converting Adobe XD artboards and layers into a bundle of files that includes HTML, CSS, images, and font files, ready to deploy.

![](https://downloads.intercomcdn.com/i/o/95946167/4284ff0a2edd319508bc9c1c/1%2Aq2qJ8DNisucOCcADibJJ1g.png)

## Host It with Us or Export It

Once the bundle is generated we’re doing numerous optimizations to improve the speed of the site loading time.

**Stuff like:**

-   Zipping text-based files
-   Optimizing PNG image files
-   Using Cache-Control headers for browser caching in our hosting servers
-   And more!

Nevertheless, sometimes our customers are interested in exporting the package of files to host on their service or add some custom logic to it.

####  We Believe the Design Is Yours

And while we encourage you to host it on our fast servers, whenever you want to export it — Well, that is your right.

To learn more, take a look at our guide on [How to Publish a Website and Host it With Anima](https://docs.animaapp.com/v3/export/05-publish-and-manage-website.html)  

## How To Export Code
There are 3 step:

1. First, create a **Preview in Browser** by clicking the button at the bottom of the Plugin panel.
![Export to Code](http://f.cl.ly/items/3B1q3Z3L1b1o3U053O1Y/Export%20Code2x.png)
2. Once you open the Preview in the browser, click **Sync to Project**  in the top right corner
3. And now the Export Code button will appear.

> ❗️**Important:** 
> - Once it's Sync'd to the Project, the code can be downloaded directly from the webapp.
> - This is great for developers and others who do not have access to the Adobe Xd file!
> 

For our example we are using a sample Portfolio website: [doe.myportfolio.design](http://doe.myportfolio.design/)

## The Code Package

The Code Package is a zip file that contains HTML files, CSS files, images and fonts.

Sample Code Package — [Download](https://cl.ly/33392Z3f3g3D)

![Code Package Files](http://f.cl.ly/items/1b0t3P1a0C3y3m0n3M0w/Code%20Package%20Files.png)

Opening the HTML files locally present the website perfectly in your browser.

![HTML Files locally](https://downloads.intercomcdn.com/i/o/95946171/ac800bee0f0f17046bb6e40e/1%2AYDIyhtQnkGiqtkBQQCYjpA.png)

If you open the files in a text editor you’ll see a well structured HTML and CSS.

![CSS Structure](https://downloads.intercomcdn.com/i/o/95946174/5f1c4df3908408ac2d1196a1/1%2AgqcF2yZX74Rtk5pkn1YTbw.png)

![CSS Structure](https://downloads.intercomcdn.com/i/o/95946175/a309cb5874ab6d7a51cb08dd/1%2A8ww5nOrz-WFWquqwgQW2xQ.png)

## FAQ

In order to keep your website **pixel-perfect**, easily made **responsive**, load **crazy fast**, yet **clean** & **readable **— We made some choices for you about the code style. Here are some questions we get about code packs.

#### ** Why Absolute Positioning?**

Developers tend to use CSS _relative_ position, while Launchpad composes CSS with _absolute_ position by default. The upside here is getting high fidelity, bringing your design as close as possible to **pixel-perfect** in browser. You’re not likely to see a line break where you didn’t expect it (_relative_ position downside).


#### ** How do Breakpoints work?**

[Breakpoints] allows you to create an artboard for each screen width — for example **Mobile**, **Tablet** and **Desktop**. When generating code, Anima makes a single HTML file and a corresponding single CSS file from these artboards.

**Breakpoints** are efficient since it uses native CSS media queries. It allows the browser to skip rendering everything that isn’t relevant for the current screen size.

Another bonus, is that images are loaded only for user’s screen size, being sharp and not over sized. And, we’re loading it top to bottom for making it even more slick.

![Breakpoints Code](http://f.cl.ly/items/3M3k100c3E3q0x0B1t00/Breakpoints%20code2x.png)

####  Why did my Forms break?

When you’re hosting your website with us, we also give you a tiny backend server to support your forms. It allows users to send to that server, and we store it for you.

This server-side code cannot be simply exported and included in the code package, as it needs to run on a server rather than on the browser (which is called client-side code).

Therefore, when exporting code with forms, you’ll have to implement your own server to capture form submissions, and store your data.
