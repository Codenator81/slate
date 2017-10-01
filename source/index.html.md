---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - swift

toc_footers:
  - <a href='https://github.com/tripit/slate'>CheatSheet Powered by Codenator</a>

includes:
  - errors

search: true
---

# Intro

Swift and iOS cheatsheet

Main links:
[Apple Documentation Swift 4](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/index.html)

# Optionals

> The next several code snippets demonstrate how optional chaining differs from forced unwrapping and enables you to check for success.
> First, two classes called Person and Residence are defined:

```swift
class Person {
    var residence: Residence?
}

class Residence {
    var numberOfRooms = 1
}
```