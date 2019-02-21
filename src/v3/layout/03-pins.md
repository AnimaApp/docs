---
title: Pins
type: Layout
order: 2
---

## How Pins Work

![Basic Pins Panel](http://f.cl.ly/items/371O1o3K1e2A3g2S031S/Artboard%201100%20small.png)


**Pins** allow you to pin a **Layer** to its **Parent** with the following:

* Top
* Right
* Bottom
* Left
* Center Horizontally
* Center Vertically

**For example:**

When selecting a **Pin**, **Layout** will set the pin constant value as the current pixel value.  

 - For example if a layer is 20px from the right and you select **Pin to Right**, the **Right Pin** constant value will be set to 20px

Once a **Pin** is set, **Layout** will enforce the pin value when the artboard is resized.  

 - For example if you **Pin** a layer to the **right** by 20px, you can resize the artboard by dragging its right side and you'll notice the layer always stays 20px from the **right**

![Pinned 20px to the Right](http://f.cl.ly/items/2J2a0A2V3A3r3w2Y0L3m/%5Bf22dcf422dbed623926f1d9cc72ca669%5D_Pinned%20to%20the%20right.gif)

### Pin to Parent

* A **Layer** is always pinned to its **Parent**
* A **Parent** can be either an **Artboard** or a **Group**
* Pinning between siblings can be achieved using **Stacks**

![Layer Pinned to its parent (Artboard)](http://f.cl.ly/items/0z1U1W3d3R3j1Y273W1d/Pinned%20to%20an%20artboard.png)
![Layers Pinned to a Group](http://f.cl.ly/items/1A2c282L3K3j0K2o1U3S/Pinned%20to%20a%20group.png)
## Advanced Pins

- To reveal the **Advanced** pinning panel click **Pins**
- You can pin a layer either by **Pixels** or by **Percent**
- **Pixels** values are in the left text boxes, **Percent** values are in the right text boxes
- Use the **Toggle Button** to select which type of pinning

![Advanced Pins Panel](http://f.cl.ly/items/3v002n291e0y451J0v0X/Artboard%20Copy%201100px.png)
![Toggle Pixes to Percentage](https://d1wuojemv4s7aw.cloudfront.net/items/0C0s1y0X243n1n0Z0k0A/%5B8586513de555cd8923eadc03aad9c4d3%5D_Pins+Pixels+to+Percentage.gif)
![Pinned by Pixels](http://f.cl.ly/items/190i1A1r2R0f3G3O0Z02/Group%202.png)
![Pinned by Percentage](http://f.cl.ly/items/2i3H0G0v0k241e1I1I2J/Group%203.png)
## Size

### Width & Height

![Anima Width and Height Values](http://f.cl.ly/items/1C281S0X2i2B0s0Z0E0Y/v3%20%E2%80%93%20Layout%20W%20H.png)

 - You can set a **Layer** width and height by checking the **Width** and **Height** boxes
   
 - When you check the **Width** or **Height** box, **Layout** will set the current value as the constraint value
   
 - The taken value will be either by **Pixels** or by **Percent**, depending on the current toggle state

### Min & Max 

 - You can set the **Miniumum** or **Maximum** value of the **Width** or the **Height** of a **Layer**
   
 - Once set, the layer **Width** or **Height** will never exceed the min/max values, no matter what the **Artboard** size is

![Min and Max Width Demo](http://f.cl.ly/items/2q3u1P0p391b3j3O2b2O/Layout%20Max%20and%20Min%20Width.gif)

**Tip:** 

> To keep the layer pinned to the left rather from the right, set the width to **%** and uncheck **Right Pin**

### Custom Height

In some cases you want to extend the **Height** of an artboard further than the default platform screen sizes, in order to show how the design looks when the user scrolls down.

**Layout** will automatically recognize artboards that do not have default screen sizes and will never decrease their height to less than their original height.


## Center

![Center Horizontal and Vertical](http://f.cl.ly/items/2g0Z3c1B1k1e3H0Q2z2H/Pins%20Center.png)
- A centered **Layer** is always centered to its **Parent** 
- A parent can be either an **Artboard** or a **Group**
- A **Layer** can be offset by entering different **Center** values

### Center Horizontally

You can center a **Layer** horizontally to its **Parent**.

![Center Horizontally](http://f.cl.ly/items/2S3i0S0C171r0o2p0E1J/%5Bd15341c631e4122245f9310032d56467%5D_Layout%20pins%20center%20horizontal.gif)

### Center Vertically

You can center a **Layer** vertically to its **Parent**.

![Center Vertically](http://f.cl.ly/items/0e2I412h2H3K3S1B1a0Z/%5Bd84f31e8a6b16cdb549471290c173d0b%5D_Layout-pins-vertical.gif)
## Multiple Selection

 - Sketch allows you to select multiple layers by holding **⇧ Shift** key while selecting layers
   
 - To speed up your workflow, you can apply or remove **Layout** constraints on multiple layers at once by selecting multiple layers in Sketch and using the **Layout** panel

![Pins Multiple Selection](http://f.cl.ly/items/3S0e191X3I40042B2t0q/Pin%20Multiple%20Selection.gif)
