---
title: Custom Domains
type: export
order: 7
---

You can use your own domain with a website created in Sketch using Anima.

There are 2 steps to do that:

1.  Create a **CNAME** and an **'A'** record in your domain provider settings
2.  Add your custom domain to your Anima **Website Settings**


## 1. Create a CNAME Record

Create a **CNAME** record that points your domain to our servers:

* Type: **CNAME**
* Host: **www**
* Points to: **ns1.animaapp.com**

Next, we are going to setup the "naked" domain which is your domain but without the '**www**'.

Create a new 'A' record:

* Type: **A**
* Host: **@**
* IP Address: **35.164.217.247**


Now, your websites should be accessible from:

1. http://yourdomain.com
2. http://www.yourdomain.com


>**❗️Important**:
>
>- To avoid any conflicts, your domain provider's settings should only have these two Anima records. Please delete any other existing record
>
>- Domain changes can take between a few minutes to a few hours to take effect

## 2. Add a Custom Domain

Next step is to add your domain to your **Projects** settings:

1. Go to your [**Projects**](projects.animaapp.com) dashboard
2. Click [**...**] on your website/project and select **Settings**
3. Go to the **Website** tab and click **Add Domain**
4. Enter your domain after '**www.**' and click **Add**
5. In the top right corner click on **Publish to www...**

![](http://f.cl.ly/items/3b0B2Y342x1U2l1p163P/Custom%20domain.gif)
![Publish a Custom Domain](http://f.cl.ly/items/2R2O1D3W2S130b093m0W/Publish%20to%20Custom%20Domain2x.png)

## SSL Certification

If you need to setup SSL for your custom domain, please contact support@animaapp.com with your domain and Anima account email address.


## Examples

### GoDaddy

![](http://f.cl.ly/items/3k0q3M0A2O2c2a2Y361p/GoDaddy%201x2.png)
![](http://f.cl.ly/items/2R0s0S1S3A2v2K2Z341b/GoDaddy%202x2.png)
![](http://f.cl.ly/items/0O3O0F1v130s2J1D1Y1a/GoDaddy%203x2.png)
![](http://f.cl.ly/items/3m301m3F0J0m3d3X0Y3t/GoDaddy%204x2.png)
![](http://f.cl.ly/items/1I0E0x1z331v2h350K1V/GoDaddy%205x2.png)

### Google Domains

![](http://f.cl.ly/items/1N3P1G1Q0g1k1A2z473y/Google%20Domains%2012x.png)
![](http://f.cl.ly/items/0y012p2j3H3l3x0a1t0p/Google%20Domains%2022x.png)
