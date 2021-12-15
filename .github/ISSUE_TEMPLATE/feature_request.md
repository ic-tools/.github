---
name: Feature Request
about: a request for adding additional functionality or features for the ci cd service
title: "[Request]"
labels: ''
assignees: ''

---

### Summary

The sentences of the Summary can be thought of different ways:
Context [, problem] and task, or
Current and future state

Examples:
On the predecessor we set up some basic logging infrastructure. Point services to use this new infrastructure.
The summary should almost always be no more than 2-3 sentences, and ideally short sentences. Make it concise so readers can get the gist quickly. Any details, parenthetical notes, or elaborations, can be offloaded to the Details section.

Summaries should be light on technical details, conveying a high-level scope for the story.

In Summaries, don't add phrases like "let's" or "we should." Give directives.

### Main Goals

Main Goals are business-oriented, and not the same as acceptance criteria. Main Goals are a high-level justification for why we need to take on this story.

After you write the goals, ask yourself why we would want to do those things. If you find yourself with a goal like, "Enable logging," it may be appropriate to ask yourself, Why do we need to enable logging? Well, because that is a key tool for dev, QA and support to understand what is happening. That's the level of abstraction these goals need to reach. From a business perspective, why does this matter?

### Details

As noted, these extend the Summary, but still from a largely high-level perspective. Sometimes technical details are relevant here.

Though the Acceptance Criteria formally and strictly capture a story's outcome, the Details section along with the Summary and Main Goals should be considered as generally part of the requirements of the story. This means implementation details should not be included here, since those may change once the work is underway.

### Acceptance Criteria

Acceptance Criteria should be broken up into discrete pieces. Make them concise, like Booleans. Don't include notes or ancillary information. Either that information should be formed into distinct criteria bullets of its own, or it belongs in the Details section.
