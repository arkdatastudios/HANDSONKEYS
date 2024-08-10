---
title: Free Website Deployment with Cloudflare Pages and GitHub
description: Deploy Static Site in Seconds
date: 2024-08-09 00:00:00+0000
tags: 
    - Hugo
    - GitHub
    - Free
    - Cloudflare
categories:
    - How-To
    - Web
    - Cloudflare
image: db_comm_edition_title.jpg
---

Cloudflare Pages offers free website hosting services to the public.

With Pages and its deep integration with GitHub, you can build and deploy your own static websites in seconds.

You are only a **git push** away!



-----

## Start with your GitHub Repository

Make sure you have a GitHub repo set up and working locally on your machine.

Cloudflare will deploy your website from a branch of your choosing.

*Note: Public and Private repositiories are supported


## Setup your Cloudflare Pages account

Make your account here: [Cloudflare pages](https://pages.cloudflare.com/)

![Click "Sign Up"](landing_page.png)


## Connect your GitHub Repository to Pages

Once you are loggeed in:

1. Select **Workers & Pages**
1. Select **Create**

![Account Page](account_page.png)

3. Select **Pages**
4. Select **Connect to Git**

![Crate Page](create_page.png)

5. Select your Git repository and click **Begin setup**

![alt text](select_repo.png)

## Configure Deployment

Now that you have selected a Git repository, configure your build and deployment settings.

If your project uses a **static site generator** or **build tool**, you can specify those settings on this page as well:

![alt text](image.png)

**Note*: ***HANDSONKEYS*** is powered by **Hugo + GO**

*  **Hugo** was selected in the Build settings.

* **GO** is a pre-installed tool in the Cloudflare Pages build environment. The version was specified in the Enirionment Varibles tab. See [Supported languages and tools](https://developers.cloudflare.com/pages/configuration/language-support-and-tools/) for more information.


## Save and Deploy

Once you have set up your build configuration, click **Save and Deploy**. 

When the deployment is complete, Cloudflare will provide an unique URL for your to view your site!



# Learning Resources

Here are some good resources to check out to continue your web development journey: 


### Deploy your website for free with Cloudflare Pages and GitHub!

{{< youtube "MTc2CTYoszY" >}}

### Set Up a Portfolio Website with Hugo

{{< youtube "6MKW4gzLItU" >}}

### Clouflare Pages Docs
The best tech advice you will ever get?

[Read the docs.](https://developers.cloudflare.com/pages)






