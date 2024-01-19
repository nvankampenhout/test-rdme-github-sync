---
title: Guide
excerpt: Guide page synced from github
category: 65a6d974ae98f7003c22cc16
---

# Guide

## Introduction
Intro text

These pages are automatically synced from https://github.com/nvankampenhout/test-rdme-github-sync

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

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.