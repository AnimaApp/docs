---
title: Custom Domains
type: launchpad
order: 12
---

You can use your own domain with `Launchpad`.

There are 2 steps to do that:

1. Add your domain to your `Launchpad` website using `Manage Site`
2. Point your domain by creating a `CNAME` record in your domain provider settings.

## Add a Custom Domain

![](/docs/images/launchpad/domains/1.png)

1. Click `Custom Domain`
2. In `Address` Enter your domain
3. Click `Apply`

## Create CNAME record

Next thing you'll have to do is create a `CNAME` record that points your domain to `Launchpad`.
In your domain provider domain settings:

Create a new `CNAME` record:

* Type: `CNAME`
* Host: `www`
* Points to: `ns1.animaapp.com`

In the next step we are going to setup the "naked" domain which is your domain but without the `www`.

Create a new 'A' record:

* Type: `A`
* IP Address: `35.164.217.247`

After performing the 2 steps, your websites should be accessible from:

1. http://yourdomain.com
2. http://www.yourdomain.com

**Domain changes take between a few minutes to a few hours to take effect**

> If you need to setup SSL for your custom domain please contact us: support@animaapp.com

## Examples

### GoDaddy

![](/docs/images/launchpad/domains/godaddy/1.png)
![](/docs/images/launchpad/domains/godaddy/2.png)
![](/docs/images/launchpad/domains/godaddy/3.png)
![](/docs/images/launchpad/domains/godaddy/4.png)
![](/docs/images/launchpad/domains/godaddy/5.png)

### Google Domains

![](/docs/images/launchpad/domains/google/1.png)
![](/docs/images/launchpad/domains/google/2.png)
