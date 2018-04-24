---
id: DOC_1_getStarted
title: Get Started
sidebar_label: Start here!
---

***

Hi! Awesome that you are interested in our service. 

With IAM you can attach a **"Buy button"** to any image. Other websites can start selling your products by embedding a simple code snippet.
The embedded camouflaged webshop will look like a regular picture ;) !



## The Platform

There are three roles on the platform:

Role | Explanation | Function | How?
--- | --- | --- | ---
Shopper | Customer of a product | Buys a product | Runs in to an IAM Shoppable on a website
Merchant | Seller of products | Upload and sell products | Upload manually or through API
Affiliate | Online publisher/influencer | Promoter & reseller of a product | Place 'snippet' on website

And how they interact with the platform:
<p></p>
<p></p>

![IAM platform](/img/iam_infographic_architecture.png)

## Simple example..

How does it work? Copy the shortcode/snippet and embed an IAM Shoppable on your website. **Place this snippet on your website to load a Shoppable item.**

```

<script src="https://iamservice.azurewebsites.net/js/public/public.min.js"></script>
<div data-iam data-iam-product-id="8"></div>

```



> Make sure the `<script>` in positioned inbetween your `<head> </head>` tags.

### Try this simple webpage

Save this text file as `iam.html`; open it in your browser:

```

<!DOCTYPE html>
<html>
<body>

<head>
  <script src="https://iamservice.azurewebsites.net/js/public/public.min.js"></script>
</head>

<h1>IAM Shoppable Test</h1>

<div data-iam data-iam-product-id="8"></div>

</body>
</html> 

```

You can login to IAM Shoppable with your IAM Identity with the following `demo-credentials`: 

````

username: demo@iam.io
password: iamD3mo

````

## Result

It should look something like this:

..

## IAM Store

Where can you find these shortcode/snippets?! In our [IAM Store](http://www.iam.io)!

Select a product you like and copy the shortcode by clicking on this button below the product:


