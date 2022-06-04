## Introduction

### What is Flutter?

Flutter is a 'tool' allow you wo build native vross-platform(IOS, Android)apps with one programming language and codebase.

- A SDK(Software Development Kit)
  Tools to compile your code to native machine code + develop with ease.
- A Framework/Widget Library
  Re-usable UI building blocks(=widgets), utility functions, packages.

### What is Dart?

Dart is a programming language developed by Google and focused on frontend(monile apps, web)user interface(UI)development.

- Object-oriented & Stringly Typed
- Syntax is like mixture of JavaScript. Java, C#

### Flutter Architecture

- UI as Code: Build a Widget Tree
  - The total App's UI is a Widget Tree
  - Everything's a Widget
- Embrace Platform Difference
- One Codebase

### How is Flutter/Dart "transformed" to a Native App?

One Code Compiled by Flutter SDK, then turn out two Native App

### Flutter Does Not Use Platform Primitives

Flutter does not compile your code to some native euqivalence or native alternatives, instead Flutter ships with its own engine which controls the entire screen, everything the user sees and renders every pixel on its own and that gives Flutter a lot of control and a lot of flexibility.

### Set Up Flutter On MacOS

#### Flutter Docker

### Material Design Everywhere

- Material is a **Design System** create(and heavily used)by Google
- It's **NOT** Google's Style for Everyone! It is indeed **highly customizable** (and works on iOS devices, too)
- Material Design is **build into Flutter** but you also find Apple-styled(Cupertino)widgets

### Flutter vs React Native vs Ionic

- Flutter(Google)

  - Dart + Flutter
  - Compiled Native Apps
  - Does NOT compile to iOS/Android UI Componentsuser
  - Cross-platfrom(mobile apps. web aps, desktop apps)

- React Native(Facebook)

  - JavaScript + React.js
  - Partly compiled(UI Components)Native Apps
  - Does compile to iOS/Android UI Components
  - Mostly mobile apps(+React Native Web)

- Ionic(Ionic)
  - JavaScropt(any or no Framework)
  - WebView-hosted Web Apps
  - Does NOT compile to iOS/Android UI Component
  - Cross-platfrom(mobile apps. web aps, desktop apps)
