# WrongSolve-Quiz-App
Dynamic Quiz App using UIKit framework.

![Coding 03](https://github.com/sanakghosh/WrongSolve-Quiz-App/assets/68545769/bf6063d5-85f8-4f14-8e50-f60d01aba12c)


## Overview

This class sets up a tab bar interface with four tabs:
1. **Home**: Displays the home view controller.
2. **Test**: Displays the test view controller.
3. **Practice**: Displays the practice view controller.
4. **Packages**: Displays the packages view controller.

Each tab is represented by a UINavigationController with its root view controller set accordingly.

## Features

- Custom tab bar icons for each tab.
- Large title display mode for navigation bars.
- Tab bar tint color set to match the label color.

## Usage

To use MainTabBarViewController in your project:

1. Copy the provided code into your Xcode project.
2. Ensure that the necessary view controllers (`HomeViewController`, `TestController`, `PracticeController`, and `PackagesViewController`) are implemented and accessible.
3. Instantiate an instance of `MainTabBarViewController` and set it as the root view controller of your app or present it modally as needed.

```swift
// Example Usage:

let mainTabBarController = MainTabBarViewController()
window?.rootViewController = mainTabBarController
window?.makeKeyAndVisible()
