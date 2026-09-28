---
title: Leave it running
date: 2026-09-21 16:00:00 +0000
categories: [Work]
tags: [website, service]
description: A service is a website that answers when nobody is at the keyboard.
---

A folder on a laptop is not a service. The website has to answer when I am not sitting in front of it.

## A small promise

I keep a health check on the service. It does not explain the product. It only says the site is up.

```python
def health():
    return {"status": "ok"}
```

## What "up" means

The page loads. The account still knows who is asking. The work they left is still there. Those three are the bar I use before I call the website done for the day.

The rest of the craft is making that bar boring: a deploy that finishes, a page that still reads well on a phone, and a failure that is obvious instead of quiet.
