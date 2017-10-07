---
title: URL templates
---

You can include dynamic elements into your URLs. This is useful for things that
are fixed across a large amount of requests, for example API keys or
authentication information.

## How
Simply type `{{something}}`
into your URL, and then add `something` as a key here, along with a value for
that key, and it will be resolved for you. This value will be resolved across
all requests you have saved, making it great for things like API keys or IDs
that you may have to change in several URLs at once.


