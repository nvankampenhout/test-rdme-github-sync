---
title: Guide
excerpt: Guide page synced from github
category: 65a6d974ae98f7003c22cc16
---

# Guide

## Introduction
Intro text

These pages are automatically synced from https://github.com/nvankampenhout/test-rdme-github-sync.

```
checkout@v3
```

## Header

Text 🙈

### Markdown image

![image in Markdown](https://github.com/nvankampenhout/test-rdme-github-sync/blob/main/Documentation/41d9b56-_Pattern.png?raw=true)

### Code block

Cocoapods

```
platform :ios, '17.2'
use_frameworks!

target 'MyApp' do
  pod "ExponeaSDK", "~> 2.21.2"
end
```

Swift

```swift
@IBAction func initializeSDK(sender: UIButton) {
    Exponea.logger.logLevel = .verbose
    Exponea.shared.configure(
        Exponea.ProjectSettings(
            projectToken: "<YOUR_TOKEN>",
            authorization: .token("<YOUR_API_KEY>"),
            baseUrl: "https://api.exponea.com"
        ),
        pushNotificationTracking: .disabled
    )
}
```

### Tabbed Code Blocks

Below is a tabbed code block:

```kotlin
// Hello World Program

fun main(args : Array<String>) {
    println("Hello, World!")
}
```
```java
// Your First Program

class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!"); 
    }
}
```

More text here.

### Github note

> [!NOTE]
> Useful information that users should know, even when skimming content.

### Readme note

> 📘 
> 
> Useful information that users should know, even when skimming content.
