---
title: Protocol handlers
---

> Introduced in 2.2.0

With protocol handlers, you can design links that open in RESTED. For example if
you have API documentation, you could make links that import the request into
RESTED.

## HAR handler
`ext+har://{JSON-data}`

When the above URL is filled with HAR data, clicking the link will open RESTED
with the import window visible and the data pre-filled in the window. Then the
user only has to click "import", and the collection will be created.

See [the HAR documentation][HARDoc] for further information.

## URL handler
`ext+rested://{url}`

This will open RESTED with the URL prefilled into the URL field

[HARDoc]: http://www.softwareishard.com/blog/har-12-spec/
