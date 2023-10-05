# Daily Client SDK

## Getting started

If you are developing a video application and targeting iOS apps, we think Daily's iOS client sdk is a great choice! Below you'll find all you need to know to get started.

#### Adding the dependency

To depend on the Daily Client package, you can add this package via Xcode's package manager using the URL of this git repository directly, or you can declare your dependency in your `Package.swift`:

```swift
.package(url: "https://github.com/daily-co/daily-client-ios.git", from: "0.11.0"),
```

and add `"Daily"` to your application/library target, `dependencies`, e.g. like this:

```swift
.target(name: "YourApp", dependencies: [
    .product(name: "Daily", package: "daily-ios-client")
],
```

## Learn more

Find the full official documentation [here](https://docs.daily.co/guides/products/mobile/ios).
