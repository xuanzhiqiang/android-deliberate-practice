# Gradle


### 出现的背景

    软件开发过程中：依赖管理、测试、打包、发布等一系列繁琐、重复性工作，为了解决这些问题引入了构建工具。

    构建工具：
        依赖管理
            可以做依赖管理, 将jar包统一管理起来, 更加的清晰和方便, 而且仅仅是依赖, 没有拷贝jar包到项目中。
        自动化
            可以自动测试、打包、发布      

    主流的构建工具：
        Ant ( Apache Ant) 
            软件编译、测试、部署等步骤联系在一起加以自动化的一个工具，大多用于Java环境中的软件开发。

        Maven (Apache Maven)
            从Ant中借用了绝大多数构建任务, 其突出的是依赖管理和项目发布。

        Gradle
            使用Groovy语言构建脚本, 不再像Maven一样使用XML。


### 是什么

[什么是Gradle?](https://docs.gradle.org/current/userguide/what_is_gradle.html#five_things)

    - 一个开源的项目自动化构建工具
    - 建立在 Apache Ant 和 Apache Maven 概念的基础上
    - 并引入了基于 Groovy 的特定领域语言(DSL), 而不再使用 XML 形式管理构建脚本

    DSL（Domain Specific Language）定义：针对某一领域，具有受限表达性的一种计算机程序设计语言。只针对一个领域做出来的简洁语言, 而非为了通用而设计.


### 优势

[Gradle vs Maven](https://gradle.org/maven-vs-gradle/)

    - Gradle 是基于 JVM 构建工具的新一代版本，它融合了 Ant 跟 Maven 中的优点，并且将其优点发挥更加极致。
    - Gradle 使用了基于 Groovy 的 DSL，摈弃 XML，更加强大跟表达性强。开发者可以使用 Java，Groovy，Kotlin 等语言去编写构建逻辑。
    - Gradle提供了一套依赖管理方式，不仅高度可配置，而且能够 Maven，Ivy 相兼容。Gradle 的依赖管理不仅限于外部库，同时还支持多项目构建，项目之间依赖建模。
    - Gradle 还支持对 Ant 跟 Maven 的构建项目进行无缝迁移。


### 核心概念

[生命周期](https://docs.gradle.org/current/userguide/build_lifecycle.html#build_lifecycle)


