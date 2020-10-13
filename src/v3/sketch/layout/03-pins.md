---
title: Pins
platform: sketch
sidebarSorting: 2
type: Layout
order: 2
---
<iframe width="864" height="486" src="https://www.youtube.com/embed/nUgSBIMwXzc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## How Pins Work

![Basic Pins Panel](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Pins.png)


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

![Pinned 20px to the Right](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Pins%201.gif)

### Pin to Parent

* A **Layer** is always pinned to its **Parent**
* A **Parent** can be either an **Artboard** or a **Group**
* Pinning between siblings can be achieved using **Stacks**

![Layer Pinned to its parent (Artboard)](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Pin%20to%20parent.png)
![Layers Pinned to a Group](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Pins%202.png)

## Advanced Pins

<iframe width="864" height="486" src="https://www.youtube.com/embed/2sWxLGUVAI0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- To reveal the **Advanced** pinning panel click **Pins**
- You can pin a layer either by **Pixels** or by **Percent**
- **Pixels** values are in the left text boxes, **Percent** values are in the right text boxes
- Use the **Toggle Button** to select the type of pinning

![Advanced Pins Panel](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Pins%203.png)
![Toggle Pixels to Percentage](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Pins%20-%20Toggle%20percentage.gif)
![Pinned by Pixels](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Pins%204.png)
![Pinned by Percentage](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Pins%205.png)


## Size

### Width & Height

![Anima Width and Height Values](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Pins%206.png)

 - You can set a **Layer** width and height by checking the **Width** and **Height** boxes
   
 - When you check the **Width** or **Height** box, **Layout** will set the current value as the constraint value
   
 - The taken value will be either by **Pixels** or by **Percent**, depending on the current toggle state

### Min & Max 

 - You can set the **Miniumum** or **Maximum** value of the **Width** or the **Height** of a **Layer**
   
 - Once set, the layer **Width** or **Height** will never exceed the min/max values, no matter what the **Artboard** size is

![Min and Max Width Demo](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Pins%207.gif)

**Tip:** 

> * To keep the layer pinned to the left rather from the right, set the width to **%** and uncheck **Right Pin**

> * To keep min & max pinned to the center, set width to 100%, and set max & min in pixels. You can also enter -20px for example to have 10px on each side

### Custom Height

In some cases you want to extend the **Height** of an artboard further than the default platform screen sizes, in order to show how the design looks when the user scrolls down.

**Layout** will automatically recognize artboards that do not have default screen sizes and will never decrease their height to less than their original height.


## Center

![Center Horizontal and Vertical](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Pins%208.png)
- A centered **Layer** is always centered to its **Parent** 
- A parent can be either an **Artboard** or a **Group**
- A **Layer** can be offset by entering different **Center** values

### Center Horizontally

You can center a **Layer** horizontally to its **Parent**.

![Center Horizontally](http://f.cl.ly/items/2S3i0S0C171r0o2p0E1J/%5Bd15341c631e4122245f9310032d56467%5D_Layout%20pins%20center%20horizontal.gif)

### Center Vertically

You can center a **Layer** vertically to its **Parent**.

![Center Vertically](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Pins%209.gif)

## Multiple Selection

 - Sketch allows you to select multiple layers by holding **⇧ Shift** key while selecting layers
   
 - To speed up your workflow, you can apply or remove **Layout** constraints on multiple layers at once by selecting multiple layers in Sketch and using the **Layout** panel

![Pins Multiple Selection](https://s3.amazonaws.com/animaapp/docs/sketch/Layout%20-%20Pins%2010.gif)
