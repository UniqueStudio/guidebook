---
layout: default
title: Mobile
description: 2025 Mobile 春季招新指北
theme: jekyll-theme-caymanqq
---

# Mobile组2025年秋招入门指北

**Mobile，连接世界的触点！**

在移动互联网时代，Mobile 组专注于打造 Android 或 iOS 的原生体验，同时探索跨平台开发（如 Compose Multiplatform 和 Flutter）的无限可能。无论是原生性能还是快速迭代，我们的目标是让你的创意通过移动设备触达全球用户。

Mobile 组的学习计划从移动开发的基础入手，涵盖从界面设计到核心逻辑的全链路开发能力。你可以选择深入原生开发，掌握 Android 和 iOS 的独特魅力，或者投身跨平台技术，探索高效开发的新边界。

这里是一切移动创新的起点，加入我们，开启属于你的移动开发之旅！

---

# Android 方向

## 前言

自2008年诞生以来，Android 至今已走过十几个春秋。Android 操作系统运行在超过70% 的智能手机上，其开放包容的生态系统不断发展壮大，支持着全球数十亿用户的数字生活。

在 Mobile 组， 我们可以以 Android 系统为基础，实现自己的创意，探索应用和系统的方方面面。从 Android 应用原生开发到跨平台框架的使用，从音视频处理再到系统甚至硬件底层的优化开发，我们不会用条条框框限制你的探索与创造。加入 Mobile 组，大家一起 Make Android Great Again！

## 开发环境

[IDEA](https://www.jetbrains.com/idea/download/)，Java/Kotlin 开发指定 IDE， IDEA 分为 Community 版（社区版，免费使用）和 Ultimate 版（收费，但可以使用学生身份免费申请），学习阶段使用 Community 版即可

[Android Studio](https://developer.android.com/studio)，Android 开发唯一指定 IDE

[Visual Studio Code](https://code.visualstudio.com/)，或者你熟悉的任何代码编辑器/IDE，用于学习与编写C语言

## 科学上网

自己探索并使用一种与国际互联网联通的方法，并养成在 Google、Stack Overflow 以及 [Android 开发者文档](https://developer.android.com/guide)上查找技术资料的习惯。

## 编程语言基础

### C

无论沿着何种技术路线学习，熟练掌握**C语言**都是一项不成文的要求，打好扎实的C语言功底对于学习其它编程语言很有帮助。

### Java

对于 Android 开发初学者，推荐先学习 Java 编程语言。教程上推荐《Java 核心技术 卷一》，重点关注前六章，掌握基本的 Java 语法，初步建立起面向对象程序设计的基本思想。

- **重点关注**：基本语法（如函数定义、流程控制语句），面向对象（封装，继承，多态），容器类的使用（List, Set, Map 的使用）

- **进阶**：了解 Java 的高级特性，如异常、并发（线程）、泛型、Lambda 表达式和 IO 流等

### Kotlin

如果你已经掌握了 Java 的基础知识，可以尝试直接学习 Kotlin 编程语言。教程上，推荐结合《第一行代码》第三版（或是 [Kotlin 官方文档](https://kotlinlang.org/docs)），在实践中学习 Kotlin 的语言设计。

- **重点关注**：变量声明，when 语句， 空安全语法（?. 和 ?:），数据类 data class，单例 object，扩展函数

- **进阶**：了解 Kotlin 协程、泛型（泛型约束与协变逆变），内联函数等高级特性，以及 Kotlin Multiplatform 技术

## Git

1. 安装Git

2. 了解 Git 是什么，为什么要使用它

3. 学习 Git 的一些基本指令的意义和使用 （add, commit, push, pull等）；

4. 注册一个 GitHub 账号，开始你的开源之旅。

注：Mobile 组熬测的所有任务代码，都需要使用 Git 仓库进行版本管理，并且 push 到 GitHub远程仓库上

参考资料：

[廖雪峰的 Git 教程](https://liaoxuefeng.com/books/git/introduction/index.html)

[Pro Git](https://git.oschina.net/progit/)

[Learning Git Branching 交互式教程](https://learngitbranching.js.org/?locale=zh_CN)

## 开发入门

《Android 第一行代码》：使用 Java 语言学习安卓开发的同学可以选择第二版，使用或者想学习 Kotlin 开发安卓的同学选择第三版。

推荐初学者先从 Android 传统的 View + XML 布局方式学起，它相对易学且易于理解，学有余力的同学可以了解 Android 官方目前最新的 UI 框架 [Jetpack Compose](https://developer.android.com/jetpack/compose)

## Linux

注意：以下建议主要针对使用 Windows 系统的同学，如果你使用的是 macOS，切换到 Linux 系统的必要性不大。

尽管使用 Linux 并不是必选项，但 Linux 能极大程度地提升你接下来学习与开发的效率。

尝试实机安装 Linux，也就是在已有 Windows 的电脑上安装 Linux **双系统**。

同时，学习 Linux 系统基本知识、常用命令，并安装必要的软件，把你的主力开发平台切换到 Linux 上。

推荐安装 Mobile 组唯一指定 Linux 发行版 —— Arch Linux。你应当参考 [Arch Wiki Installation Guide](https://wiki.archlinux.org/title/Installation_guide)， 如果遇到困难，可以查阅 Arch Wiki 中的其它条目或者在 [Arch 社区论坛](https://bbs.archlinux.org/) 中搜索，也可以直接向团队内的同学求助。

也可以参考以下三篇团队学长出品的教程，但仅能作为官方教程的补充（如有冲突，以官方教程为准）：

[以官方 Wiki 的方式安装 Arch Linux](https://www.viseator.com/2017/05/17/arch_install/)

[Arch Linux 安装后的必须配置与图形界面安装教程](https://www.viseator.com/2017/05/19/arch_setup/)

[Arch Linux Installation Guide](https://github.com/JunkFood02/Arch-Linux-Installation-Guide)

---

# iOS 方向

## 前言

iOS 操作系统以其稳定性和优雅的用户体验，成为全球数亿用户的首选移动平台。在全球智能手机市场中，iOS 占据了重要的一席之地，其封闭而安全的生态系统不断创新，为用户提供了无缝的数字生活体验。

在 Mobile 组中，你可以充分发挥自己的创意，以 iOS 系统为基础，探索应用和系统的各个方面。从原生 iOS 应用开发到跨平台应用的开发，从图形渲染到性能优化，我们不拘泥于传统的思维模式，鼓励自由探索与创新！

## 开发环境

### macOS

进行 iOS 开发时，我们需要 macOS 的系统环境，即我们无法在 Windows 和 Linux 环境直接进行 iOS 应用开发。

- Mac 用户：如果你使用的是 Mac 电脑，那么电脑默认搭载的系统即为 macOS

- Hackintosh（黑苹果）：如果你暂时没有 Mac 设备但是对 iOS 开发非常感兴趣，那么你可以尝试让你的 Windows 电脑运行 macOS。自主安装黑苹果的过程会极大提升你对操作系统的理解：
  
  - [tonymacx86](https://www.tonymacx86.com/)
  
  - [远景论坛](https://bbs.pcbeta.com/index.php?gid=86)
  
  - [黑果小兵](https://blog.daliansky.net/)
  
  - [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

### Xcode

Xcode 是 iOS 开发的专用 IDE，它包含了一个 iOS App 从开发到调试到上架所需的一切，可以直接在 macOS 的 App Store 下载

## 科学上网

自己探索并使用一种与国际互联网联通的方法，并养成在 Google、Stack Overflow 以及 [Apple 开发者文档](https://developer.apple.com/documentation/)上查找技术资料的习惯。

## 编程语言基础

### C

无论沿着何种技术路线学习，熟练掌握**C语言**都是一项不成文的要求，打好扎实的C语言功底对于学习其它编程语言很有帮助。

### Objective-C / Objective-C++

Objective-C 是一门历史悠久的语言，它有着强大且灵活的 Runtime 特性，可深入系统底层，目前仍有许多旧项目使用 Objective-C 语言进行开发。

Objective-C++ 结合了 Objective-C 和 C++ 两门语言的语法特性，它允许开发者融合这两门语言的代码。

教程上，推荐阅读《Objective-C 基础教程》或《Objective-C 程序设计》

- **重点关注**：基础语法（函数定义、控制语句等），消息传递语法，类（包括属性和方法的定义与实现），内存管理（ARC 机制），Foundation 框架

- **进阶**：学习 Objective-C 的高级语法特性，例如闭包、协议(Protocol)、多线程等

### Swift

Swift 是苹果于 2014 年新推出的一门现代化的编程语言，它语法简洁，但更加安全、高效。目前，Swift 已经成为苹果推崇的主力语言，许多新项目和框架都基于 Swift 进行开发。

教程上，推荐阅读 [Swift 官方文档](https://docs.swift.org/swift-book/) 或者 [Swift 中文翻译文档](https://www.cnswift.org/)

- **重点关注**：基础语法（变量声明、函数定义、控制语句等），Swift 空安全语法，类（包括属性和方法的定义与实现），内存管理（ARC 机制），Foundation 框架

- **进阶**：学习 Swift 的高级语法特性，例如闭包、协议、泛型和 Swift 协程等

> Tip: 入门 iOS 开发时可以选择 Objective-C 或者 Swift 进行学习，语言的学习从来不是难点。

## Git

1. 安装Git

2. 了解 Git 是什么，为什么要使用它

3. 学习 Git 的一些基本指令的意义和使用 （add, commit, push, pull等）；

4. 注册一个 GitHub 账号，开始你的开源之旅。

注：Mobile 组熬测的所有任务代码，都需要使用 Git 仓库进行版本管理，并且 push 到 GitHub远程仓库上

参考资料：

[廖雪峰的 Git 教程](https://liaoxuefeng.com/books/git/introduction/index.html)

[Pro Git](https://git.oschina.net/progit/)

[Learning Git Branching 交互式教程](https://learngitbranching.js.org/?locale=zh_CN)

## 熟悉一个 UI 框架

### UIKit

Cocoa 是 macOS App 的开发框架，Cocoa Touch 是 iOS App 的开发框架。Cocoa 框架实际上就是一系列的库和工具，它使开发者可以快速创建强壮和全功能的 macOS / iOS(iPadOS)/ watchOS 应用。UIKit 是 Cocoa 中最重要的框架之一，它包含了创建一个应用的界面部分所需的全部控件，你需要掌握其中常用的控件，比如 **UIViewController**、**UIView**、UILabel、UIButton、UITableView、 UICollectionView 等的使用方法。

参考资料：

[UIKit 入门教程](https://uniquestudio.feishu.cn/docx/doxcnJ5UXVsAzcuGFVnMcGKE4yc)

[UIKit 进阶教程](https://uniquestudio.feishu.cn/docx/doxcnhSmGb20wsnG5rEdMFRILve)

[iOS 17 UIKit 实战心法（Appcoda 出品）](https://uniquestudio.feishu.cn/file/VNP0brWkyoEWIexzCzIcPi25nDf)

[Apple Tutorial(UIKit)](https://developer.apple.com/tutorials/app-dev-training/#uikit-essentials)

### SwiftUI

SwiftUI 是 Apple 近年来新开发并开始推广的全新框架，且自 iOS14 开始，其 LifeCycle 已实现完全独立。Apple 目前致力于将其用于为多个平台(包括 iOS、iPadOS、macOS、watchOS 和 tvOS)构建跨平台应用。SwiftUI 拥有 MVVM 的思想与极具便利性、适合敏捷开发的声明式布局。

参考资料：

[iOS 17 SwiftUI 实战心法（Appcoda 出品）](https://uniquestudio.feishu.cn/file/TZRZb3RMFo8IzTxMraicVgz3nQF)

[Apple Tutorial(SwiftUI)](https://developer.apple.com/tutorials/app-dev-training/#swiftui-essentials)

Tip: 目前还是推荐优先学习 UIKit，因为 SwiftUI 还是一个在细节上不够成熟、没有足够能力的框架。
