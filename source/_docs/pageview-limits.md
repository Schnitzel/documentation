---
title: Pageview Limits and Overages
description: Information on how Pantheon measures site traffic
tags: [pricing]
categories: []
---

Unlike traditional providers where enough requests will crash the server, Pantheon's platform can absorb massive amounts of traffic. One of the main benefits of Pantheon is our ability to provide quality service and uptime under heavy traffic loads.

However, this does mean that websites can run happily even though they are over their plan's traffic limit. If this is happening on a sustained basis, you may receive notice from customer support that your site's plan isn't adequate to its needs, and an upgrade may be in order.

## How We Measure Site Traffic

Pantheon defines plan levels based on pageviews to help site owners pick the right plan based on expected or historical traffic. To verify that sites receive traffic within their plan limit, we count requests served by the platform from the CMS. Cached responses count as pageviews.

This includes not only HTML pages served by the CMS, but also responses in formats such as JSON and XML that are not tracked by standard analytics suites. API calls and AJAX requests do count as traffic, and are considered against plan limits. If you are planning to run a high traffic decoupled or "headless" implementation, you should contact sales in advance to discuss pricing.

## Does Pantheon Charge for Overages?

There is no mechanical "overage" process that will surprise you with a shock bill for something that happened in the past. However, where there is a pattern of consistent overage, we will align a site's plans with its load on the platform going forward. We reserve the right to terminate service for abusers who are unwilling to use an appropriate plan.

Pantheon takes site plan limits seriously, but we recognize that sometimes these situations are complicated. We always start with a conversation. If you are surprised by a notice that your site is over its traffic limit, our team is ready, willing, and able to dig into the inevitable differences between our measurements of traffic served and any other analytics you may have.

## Why Doesn't Pantheon's Traffic Match My Analytics?

There are some inherent limitations with using an analytics suite (e.g. Google Analytics) when measuring site traffic. The following traffic will be collected in our logs, but will not be present in most analytics:

 - API requests and AJAX requests.
 - Browsers/users that block cookies or javascript, including adblockers.
 - Users that close the browser before the tracking script loads.
 - Any page with a JavaScript error.
 - Content pre-fetching, by browsers or [apps](https://www.facebook.com/business/help/1514372351922333){.external}.
 - Automated traffic from bots or load testing.

Finally, analytics implementations can be variable. It may be that your analytics solution isn't tracking all pageviews for good reason. For example, you may exclude CMS administrators to give you a view of "visitors only". Misconfiguration may also play a factor.

Due to the fact that analytics doesn't measure _traffic_, it's not a suitable metric for determining platform use/abuse.

## What About Static Assets?

Static requests (images PDFs, CSS, JS, etc) are not included in our normal traffic metrics. Under regular CMS use-cases, these supporting requests to render HTML pages for users with browsers are not a concern.

However we do reserve the right to review individual sites that are excessive bandwidth consumers. If sites are serving static assets at an excessive rate, this can be considered plan abuse.

## What About Bots?

Although it places load on the platform, Pantheon excludes automated traffic from legitimate crawlers and bots that would otherwise count towards your website's total traffic. We do this by examining the user-agent of traffic, as well as the source IP address.

Having high performance responses to crawlers is _beneficial_ to SEO, which is one reson people choose Pantheon, but we respect that you cannot control this kind of traffic. We are continually refining our model to ensure our traffic reports are as accurate as possible.

## What About Load Tests or Pen Tests?

Our onboarding team performs load tests prior to every Elite site launch, and we encourage customers to load test prior to releasing a big update. We also fully support customers who want to penetration test their site, which can result in significant spikes in traffic.

However, if you are load or pen testing in extreme excess of your plan limits, or do so on a regular and repeated basis, we reserve the right to charge for a plan that is appropriate to the load placed on the platform. This is one of the reasons we ask customers to notify us of such tests as a courtesy.

## What About Legitimate Traffic Spikes?

We understand that the internet can make any website famous overnight and that this isn't under your control. Pantheon's platform is specifically designed to shine under this circumstance, and it's one of the main reasons people choose us to run their sites.

Luckily, traffic spikes are easily discerned, and we take this into account when it comes to monitoring plan abuse. However, similar to the above, if a site is achieving internet fame on a regular basis, we reserve the right to right-size the site's plan in relation to the load it puts on the platform.

## What About Denial of Service and Other Attacks?

We are well aware that malicious actors can create a ton of traffic out of nowhere and that this is not a fair measure of what a customer should pay for. We are more than willing to investigate discrepancies between our traffic measurements and other site analytics on a case by case basis.

As above, in cases where these events are regular or sustained, we reserve the right to right-size a site plan. If a site's real load on the platform is consistently higher than what appears in end-user analytics, fairness demands that the site plan fit its usage.

## Let's Talk

Site traffic is rarely a black and white issue, and cases of clear plan abuse are outliers. We always start with a conversation, and are equipped to go deep in determining what is causing an excessive amount of traffic for your site.

The Site Dashboard does not expose pageviews and our support engineers do not have the ability to determine pageviews at this time. If you receive a communication from us about possible plan abuse, don't panic. We will work with you to fully understand the situation and find a solution, whether that involves shutting down a malicious bot, or adjusting your site's plan.
