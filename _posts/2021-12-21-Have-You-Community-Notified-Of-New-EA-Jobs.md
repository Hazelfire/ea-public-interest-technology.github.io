---
layout: post
title: Have you community notified of new EA Jobs
author: Sam Nolan
categories: [Post]
---

Also crossposted to the [EA Forum](https://forum.effectivealtruism.org/posts/wh8GaGrWDHGivK7aP/have-your-community-notified-of-new-ea-jobs)

*Time spent: About 4 hours of dev work and writing*

**Tldr** I've recently made a webhook based chatbot that can notify communities of new jobs that appear on the 80,000 hours job board. If you are a moderator of a Slack or Discord EA community and want to be notified of new EA jobs, please get in contact and I will set up the integration for you.

* * * * *

In the [EA Public Interest Technologists](https://ea-public-interest-technology.github.io/) slack, we had an EA group organiser from Germany ask us whether we could build a project. They wanted a chatbot that notifies a slack group whenever there is a job for Germans published in the [80,000 hours job board](https://80000hours.org/job-board/).

I soon realised that doing this would be a lot easier it looks, and is well within the scope of automation software such as [IFTTT](https://ifttt.com/home). I spent about half an hour setting up the integration which creates a message on the EA Melbourne Discord whenever a new job shows up on the job board:

![](https://lh4.googleusercontent.com/pss2ga7yKSiKxqdqdH2xe8yPMiGhAb1Wb6-VYDy434_i12r2mRMIjKjPA0KtM8berxcAKc6O-CQb_30Xu7VjupHGJiw3SH6oBbuLmbjhzc55xktmQDATta8-KSrRncEPU8D0GRm4)

This however, ended up costing me about \$30 a month to run. So I am looking for other EA communities that would be interested in having this bot in their Discord or Slack groups. That way it is worth my money.

If you want this bot in your community, simply create a webhook and send the url to me privately.

To create a webhook in Slack or Discord:

**Slack:** <https://api.slack.com/messaging/webhooks> (Go up to step 3, and send me your webhook url)

**Discord:** Channel Settings -> Integrations -> Add Webhook.

Also let me know whether you want any filters on your feed. For instance, if you only want jobs relevant to undergraduates, or in a certain country/city, or about a certain cause area. I'll sort out the rest.

If you are still not sure about how to set this up, or if you have a different type of community, feel free to book a call with me using my [calendly link](https://calendly.com/sam_nolan/30min).

I'm looking for people who would be interested in improving this beyond a half an hour IFTTT integration. If you are a software dev and would be interested, please join us on the [EA Public Interest Technologist Slack](https://join.slack.com/t/ea-pub-interest-tech/shared_invite/zt-tar2i03b-3xqmTh1lLFn8NWB6X1ZA6Q) so we can chat about it. This is a project that is both very easy to do as a developer but also could be very impactful. I believe it to be extremely long hanging fruit in terms of technical EA work.

Have a happy holidays!
