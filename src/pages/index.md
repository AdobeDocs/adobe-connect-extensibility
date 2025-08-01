---
title: Overview - Cat Analytics
description: This is the overview page of Cat Analytics
contributors:
  - https://github.com/icaraps 
---

<HeroSimple slots="heading, text"/>

# Adobe Developer Distribution

A self-service submission portal for developers to publish listings that extend Adobe products, on the Adobe marketplaces.

<Resources slots="heading, links"/>

#### Resources

* [Quickstart Guide](https://developer.adobe.com)
* [Cat Analytics Github Repo](https://github.com/AdobeDocs/dev-site)

## Overview

Adobe Developer Distribution is a new surface for developers to submit and manage their listings. The Developer Distribution surface offers a powerful and flexible approach to allow developers to create listings more rapidly, and receive approval with minimal reviewer turnaround time. This document provides guidance on how to use the Developer Distribution surface for listing submissions. Documentation will be updated as future releases support for additional Adobe products.​

## Discover

<DiscoverBlock width="100%" slots="heading, link, text"/>

### Get Started

[Quickstart Guide](guides/index.md)

Get started with the Cat Analytics APIs.

<DiscoverBlock slots="heading, link, text"/>

### Guides

[Calculated Metrics API](guides/dummy-metrics-api/index.md)

Returns information on the user's company that is necessary for making other Cat Analytics API calls.

<DiscoverBlock slots="link, text"/>

[Segments API](guides/dummy-oauth-client/index.md)

Provides configuration guidance and best practices for the /segments endpoint.

<DiscoverBlock slots="link, text"/>

[Reporting Guide API](guides/dummy-using-postman/index.md)

Provides configuration guidance and best practices for the /reports endpoint.

<DiscoverBlock slots="link, text"/>

[Migrating from 1.4 to 2.0](guides/migrating/index.md)

For help migrating from the 1.4 versions of the Analytics API to the newer and more capable /reports API.

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
