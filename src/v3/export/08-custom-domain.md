
---
title: Custom Domains
type: Export
order: 7
---

You can use your own domain with a website created in Sketch using Anima.

There are 2 steps to do that:

1. Add your domain to your **Projects** settings
2. Point your domain by creating a **CNAME** record in your domain provider settings

## Add a Custom Domain
**Step 1: Add your domain to your **Projects** settings**

1. Go to **Projects**
2. Click [**...**] on your website and select **Settings**
3. Go to the **Website** tab and click '*Add Domain*'
4. Enter your domain (e.g: www.mysite.com) and click **Add**

![enter image description here](http://f.cl.ly/items/3b0B2Y342x1U2l1p163P/Custom%20domain.gif)
## Create CNAME record

Next thing you'll have to do is create a **CNAME** record that points your domain to our servers.

Step 2:  Create a new **CNAME** record:

* Type: **CNAME**
* Host: **www**
* Points to: **ns1.animaapp.com**

In the next step we are going to setup the "naked" domain which is your domain but without the '**www**'.

Create a new 'A' record:

* Type: **A**
* IP Address: **35.164.217.247**

After performing the 2 steps, your websites should be accessible from:

1. http://yourdomain.com
2. http://www.yourdomain.com

❗️**Domain changes take between a few minutes to a few hours to take effect**

 If you need to setup SSL for your custom domain please contact support@animaapp.com with your domain and Anima account email address.

## Examples

### GoDaddy

![](https://docs.animaapp.com/images/launchpad/domains/godaddy/1.png)![enter image description here](https://docs.animaapp.com/images/launchpad/domains/godaddy/3.png)
![](https://docs.animaapp.com/images/launchpad/domains/godaddy/2.png)
![](https://docs.animaapp.com/images/launchpad/domains/godaddy/4.png)
![](https://docs.animaapp.com/images/launchpad/domains/godaddy/5.png)
### Google Domains

![](https://docs.animaapp.com/images/launchpad/domains/google/1.png)
![](https://docs.animaapp.com/images/launchpad/domains/google/2.png)
