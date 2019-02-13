---
title: Export Sketch to HTML
type: export
order: 3
---

## Guide Overview

In this guide we will go over:

1.  How **Anima** converts Sketch documents into code
2.  How to export your Sketch document to an **HTML Code Pack**
3.  What the **HTML Code Package** looks like
4.  Frequently Asked Questions

## How Does Export Code Work

**Anima** enables designers to export full websites **HTML** & **CSS,** directly from a Sketch design.

Our process of transforming a Sketch design into a website involves many steps.

Basically, we’re converting Sketch artboards and layers into a bundle of files that includes HTML, CSS, images, and font files, ready to deploy.

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

Well, it’s pretty straightforward, just click **Export** in the Export tab.

![](https://downloads.intercomcdn.com/i/o/95946865/b50b9b07474675f6412fc32c/Export%402x.png)

For our example we are using a sample Portfolio website: [doe.myportfolio.design](http://doe.myportfolio.design/)

And here is a video tutorial (4:10):

> ❗️Video tutorial with newer interface is coming soon

<iframe width="560" height="315" src="https://www.youtube.com/embed/E3xZui2myUU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## The Code Package

The Code Package is a zip file that contains HTML files, CSS files, images and fonts.

Sample Code Package — [Download](https://cl.ly/33392Z3f3g3D)

![](https://downloads.intercomcdn.com/i/o/95946170/18d183d8ba89c0a3be9f3ea3/1%2A7pX8m2OcRohQS-jisc73-Q.png)

Opening the HTML files locally present the website perfectly in your browser.

![](https://downloads.intercomcdn.com/i/o/95946171/ac800bee0f0f17046bb6e40e/1%2AYDIyhtQnkGiqtkBQQCYjpA.png)

If you open the files in a text editor you’ll see a well structured HTML and CSS.

![](https://downloads.intercomcdn.com/i/o/95946174/5f1c4df3908408ac2d1196a1/1%2AgqcF2yZX74Rtk5pkn1YTbw.png)

![](https://downloads.intercomcdn.com/i/o/95946175/a309cb5874ab6d7a51cb08dd/1%2A8ww5nOrz-WFWquqwgQW2xQ.png)

## FAQ

In order to keep your website **pixel-perfect**, easily made **responsive**, load **crazy fast**, yet **clean** & **readable **— We made some choices for you about the code style. Here are some questions we get about code packs.

#### ** Why Absolute Positioning?**

Developers tend to use CSS _relative_ position, while Launchpad composes CSS with _absolute_ position by default. The upside here is getting high fidelity, bringing your design as close as possible to **pixel-perfect** in browser. You’re not likely to see a line break where you didn’t expect it (_relative_ position downside).

#### ** How to work with Dynamic Content?**

Usually, most of your content is static, rather than dynamic — i.e logos, titles, menu buttons, backgrounds, etc.

However, if you give your exported code to a developer, and need layers to move **relatively to one another**, simply use the [**Stacks**](https://medium.com/sketch-app-sources/auto-layout-introducing-stacks-flexbox-for-sketch-c8a11422c7b5) feature. When you use Stacks, layers expand and push each other. The composed CSS uses **Flex-boxes** rather than _absolute_ position.

Stacks also support symbol overrides for text, and hiding layers to realign.  
  
Yup, you can see it working inside Sketch. Cool 

![](https://downloads.intercomcdn.com/i/o/95946176/59f5c6cb3ba82101e4710d37/1%2AFV4NQwj_tHaGYvO_GY3tLA.gif)

#### ** How do Breakpoints work?**

[Breakpoints](https://docs.animaapp.com/v3/prototype/breakpoints.html) allows you to create an artboard for each screen width — for example **Mobile**, **Tablet** and **Desktop**. When generating code, Launchpad makes a single HTML file and a corresponding single CSS file from these artboards.

**Breakpoints** are efficient since it uses native CSS media queries. It allows the browser to skip rendering everything that isn’t relevant for the current screen size.

Another bonus, is that images are loaded only for user’s screen size, being sharp and not over sized. And, we’re loading it top to bottom for making it even more slick.

![](https://downloads.intercomcdn.com/i/o/95946177/f8aee6da54dcbded5cc2db8c/1%2AI-JdHAv39h69JBpx3pKicw.png)

####  Why did my Forms break?

When you’re hosting your website with us, we also give you a tiny backend server to support your forms. It allows users to send to that server, and we store it for you.

This server-side code cannot be simply exported and included in the code package, as it needs to run on a server rather than on the browser (which is called client-side code).

Therefore, when exporting code with forms, you’ll have to implement your own server to capture form submissions, and store your data.
