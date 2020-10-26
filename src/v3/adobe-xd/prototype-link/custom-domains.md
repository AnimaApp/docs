---
title: Custom Domains
platform: xd
type: prototype-link-settings
sidebarSorting: 4
categories: 
- Prototype Link Settings
order: 3
---
You can use your own domain with a website created on **Sketch**, **Adobe XD** or **Figma** using Anima.

There are 2 steps:

1.  Create a **CNAME** and an **'A'** record in your domain provider settings
2.  Add your custom domain to your Anima project settings

> ❗️**IMPORTANT** 
> We are not a Custom Domain provider. You first need to get a domain from GoDaddy, Google Domains, or any domain provider.


## 1. Create a CNAME Record

In your domain providers's settings, create a **CNAME** record that points your domain to our servers:

* Type: **CNAME**
* Host: **www**
* Points to: **ns1.animaapp.com**

Next, we are going to setup the **"A"** record which will allow visitors to access your website without inlcuding '**www**'.

Create a new 'A' record:

* Type: **A**
* Host: **@**
* IP Address: **35.164.217.247**


Now, your websites should be accessible from:

1. http://yourdomain.com
2. http://**www**.yourdomain.com


>**❗️Important**:
>
>- To avoid any conflicts, please delete any other CNAME and A records on your domain provider's settings.
>
>- Domain changes can take between a few minutes to a few hours to take effect.

## 2. Add a Custom Domain

Next step is to add your domain to your **Projects** settings:

1. In [**Anima**](https://projects.animaapp.com), go to your project
2. Click the **cogwheel icon** in the top right corner to access the project settings
3. In the **Prototype Link** tab, enter your domain twice: one with '**www.**' and without '**www'.** the domain 
4. Click **"Add"**
5. In the top right corner click on **"Publish to www..."**



## SSL Certification

If you need to setup SSL for your custom domain, please contact support@animaapp.com with your domain and Anima account email address.


# Examples

### GoDaddy

![](https://s3.amazonaws.com/animaapp/docs/sketch/Export%20-%20Custom%20Domain%20-%20Godaddy1.png)
![](https://s3.amazonaws.com/animaapp/docs/sketch/Export%20-%20Custom%20Domain%20-%20Godaddy1.png)![](https://s3.amazonaws.com/animaapp/docs/sketch/Export%20-%20Custom%20Domain%20-%20Godaddy2.png)![](https://s3.amazonaws.com/animaapp/docs/sketch/Export%20-%20Custom%20Domain%20-%20Godaddy3.png)![](https://s3.amazonaws.com/animaapp/docs/sketch/Export%20-%20Custom%20Domain%20-%20Godaddy4.png)

### Google Domains

![](https://s3.amazonaws.com/animaapp/docs/sketch/Export%20-%20Custom%20Domain%20-%20Google1.png)
![](https://s3.amazonaws.com/animaapp/docs/sketch/Export%20-%20Custom%20Domain%20-%20Google2.png)
