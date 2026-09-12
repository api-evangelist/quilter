---
title: "How can I tell quilter not to edit the track that had finish"
url: "https://community.quilter.ai/t/how-can-i-tell-quilter-not-to-edit-the-track-that-had-finish/364#post_4"
date: "2026-04-08"
author: "@sergiy Sergiy Nesterenko"
feed_url: "https://community.quilter.ai/posts.rss"
---
Hi, yes it looks like you are using the macrofab stack ups - which overrides the custom stackup in your uploaded file. Any and all design elements in all internal layers will be deleted with this workflow. Please use the “custom stackup” feature - which will keep the stackup already present in your CAD file and will preserve all internal geometries.
