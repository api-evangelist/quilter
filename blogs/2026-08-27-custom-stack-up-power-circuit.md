---
title: "Custom Stack up & power circuit"
url: "https://community.quilter.ai/t/custom-stack-up-power-circuit/393#post_2"
date: "2026-08-27"
author: "@justin1 Justin - Quilter"
feed_url: "https://community.quilter.ai/posts.rss"
---
Hi there, Thanks for the post here! We don’t natively allow you to set the bottom layer to be a solid ground plane within Quilter, but you can add a ground pour in your ECAD tool and preserve it while also selecting single sided placement to get that result. We can also support multiple components for a single switching converter if you add a row to the switching converter comprehension section (step 5) and set the same switching converter reference designator you can add additional inductors & input/output capacitors.
