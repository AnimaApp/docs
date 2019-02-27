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
>Your domain provider's settings should only have these two records to avoid any conflicts.


>**❗️Domain changes take between a few minutes to a few hours to take effect**

## 2. Add a Custom Domain

Next step is to add your domain to your **Projects** settings:

1. Go to [**Projects**](projects.animaapp.com)
2. Click [**...**] on your website and select **Settings**
3. Go to the **Website** tab and click **Add Domain**
4. Enter your domain and click **Add**
5. In the top right corner click on **Publish to www.mydomain.com**

![](http://f.cl.ly/items/3b0B2Y342x1U2l1p163P/Custom%20domain.gif)
![Publish a Custom Domain](http://f.cl.ly/items/0W0P0d3E2D353j3C0P2D/Publish%20To%20www.png)

## SSL Certification

If you need to setup SSL for your custom domain, please contact support@animaapp.com with your domain and Anima account email address.


## Examples

### GoDaddy

![](https://docs.animaapp.com/images/launchpad/domains/godaddy/1.png)![enter image description here](https://docs.animaapp.com/images/launchpad/domains/godaddy/3.png)
![](https://docs.animaapp.com/images/launchpad/domains/godaddy/2.png)
![](https://docs.animaapp.com/images/launchpad/domains/godaddy/4.png)
![](https://docs.animaapp.com/images/launchpad/domains/godaddy/5.png)
### Google Domains

![](https://docs.animaapp.com/images/launchpad/domains/google/1.png)
![](https://docs.animaapp.com/images/launchpad/domains/google/2.png)
