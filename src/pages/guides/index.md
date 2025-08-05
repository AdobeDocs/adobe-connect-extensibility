---
title: Developer Distribution Documentation for Adobe Connect 
description: This documentation relates to the Adobe Connect Custom Pods submission and review on Adobe Developer Distribution
contributors:
  - https://github.com/skhadiya
---

<HeroSimple slots="heading, text"/>

# Adobe Developer Distribution

A self-service submission portal for developers to publish listings that extend Adobe products, on the Adobe marketplaces.

<Resources slots="heading, links"/>

## Overview

Adobe Developer Distribution is a new surface for developers to submit and manage their listings. The Developer Distribution surface offers a powerful and flexible approach to allow developers to create listings more rapidly, and receive approval with minimal reviewer turnaround time. This document provides guidance on how to use the Developer Distribution surface for listing submissions. Documentation will be updated as future releases support for additional Adobe products.​

## Discover

<DiscoverBlock width="100%" slots="heading, link, text"/>

### Get Started

[Quickstart Guide](guides/index.md)

Get started with the Cat Analytics APIs.

<DiscoverBlock slots="heading, link, text"/>

### Submission Guidelines

[Create a new listing](guides/create_listing/index.md)

Learn about creating a custom pod listing on Developer Distribution

<DiscoverBlock slots="link, text"/>

[Listing details](guides/listing_details/index.md)

Learn how to add listing details for your Adobe Connect Custom Pods. 

<DiscoverBlock slots="link, text"/>

[Version details](guides/version_details/index.md)

Learn how to add version details for your Adobe Connect Custom Pods.

<DiscoverBlock slots="link, text"/>

[Version packaging](guides/version_packaging/index.md)

Learn how to package your Adobe Connect Custom Pods for successful submission. 

<DiscoverBlock width="100%" slots="heading, link, text"/>

### API References

[Try the API](api/index.md)

Try the Analytics API with Swagger UI. Explore, make calls, with full endpoint descriptions.

## Contributing

We encourage you to participate in our open documentation initiative, if you have suggestions, corrections, additions
or deletions for this documentation, check out the source from [this github repo](https://github.com/adobe/gatsby-theme-spectrum-example), and submit a pull
request with your contribution. For more information, refer to the [contributing page](support/contribute/index.md).

## API Requests & Rate Limits

The timeout for API requests through adobe.io is currently *60 seconds*.

The default rate limit for an Cat Analytics Company is *120 requests per minute*. (The limit is enforced as *12 requests every 6 seconds*).
When rate limiting is being enforced you will get `429` HTTP response codes with the following response body: `{"error_code":"429050","message":"Too many requests"}`.
