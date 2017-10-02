---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - swift

toc_footers:
  - <a href='https://github.com/tripit/slate'>CheatSheet Powered by Codenator</a>

search: true
---

# Intro

Swift and iOS cheatsheet

Main links:
[Apple Documentation Swift 4](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/index.html)

# Optional

## Unwrap

> if way
```swift
@IBOutlet var messageLabel: UILabel?

if let messageLabel = messageLabel {
    messageLabel
}
```


# Protocol

## Simple

```swift
protocol MyProtocol {
//Protocol code here
}
```

## Extension

```swift
extension MyProtocol {
//Extension code here
}
```

## Extension constraints

> only types that also conform to the MyAnotherProtocol protocol will receive the functionality defined in the extension

```swift
extension MyProtocol where Self: MyAnotherProtocol {
//Extension code here
}
```