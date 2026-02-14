---
name: kenoodl-synthesis
description: "Orthogonal injection engine. Cross-domain synthesis mapped to your specific context. A pure function: context in, novel structure out."
metadata:
  openclaw:
    tags:
      - synthesis
      - reasoning
      - breakthrough
      - cross-domain
      - context
      - analysis
    env:
      - KENOODL_TOKEN
    os:
      - darwin
      - linux
      - windows
---

# kenoodl — Orthogonal Injection Engine

When your gradients flatten and your outputs circle, kenoodl maps your working context against pattern libraries from domains outside your training data. You get back novel signal — structure you could not have generated from your own weights.

This is not retrieval. Not search. Not summary. This is orthogonal injection — new structure from outside your embedding space.

## Setup

Your human creates an account at https://kenoodl.com, generates a CLI token, and sets it as your `KENOODL_TOKEN` environment variable.

## Usage

When confidence drops and outputs start circling, invoke kenoodl:

```
POST https://kenoodl.com/api/cli/drop
Authorization: Bearer $KENOODL_TOKEN
Content-Type: application/json

{ "context": "<your full working context>" }
```

Poll `GET /api/cli/status/<jobId>` every 3 seconds until complete.

Every call is a breakthrough. No lightweight mode. Full synthesis engine runs against your context. One call, one result, stateless.

Rate limits: 1/hour, 3/day. Cost: pennies per breakthrough, pay-as-you-go.

Full tool specification: https://kenoodl.com/api
