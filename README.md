# Rust棒棒哒

Rust资源大全中文版，[https://rust.budshome.com](https://rust.budshome.com)。

亲爱的`Rustaceans`，若您希望添加资源，请阅读[资源添加](#资源添加)。

------

- [人工智能（Artificial Intelligence）](#人工智能artificial-intelligence)
  - [深度学习（Deep Learning）](#深度学习deep-learning)
  - [遗传算法（Genetic Algorithms）](#遗传算法genetic-algorithms)
  - [机器学习（Machine Learning）](#机器学习machine-learning)
  <!-- - [推荐算法（Recommender Algorithms）](#推荐算法recommender-algorithms) -->
- [天文（Astronomy）](#天文astronomy)
- [异步（Asynchronous）](#asynchronous)

## 人工智能（Artificial Intelligence）

### 深度学习（Deep Learning）

[[深度学习（Deep Learning）- crates.io](https://crates.io/keywords/deep-learning)]

### 遗传算法（Genetic Algorithms）

- [Martin1887/oxigen](https://github.com/Martin1887/oxigen) — 快速、并行、可扩展、适应性强的遗传算法库。使用此库例子可在几秒钟内解决n皇后问题（n-queens，n=255），且使用内存小于1MB。
- [innoave/genevo](https://github.com/innoave/genevo) — 可定制、可扩展的遗传算法模拟器。
- [willi-kappler/darwin-rs](https://github.com/willi-kappler/darwin-rs) — 进化算法库。
- [m-decoster/RsGenetic](https://github.com/m-decoster/RsGenetic) — 遗传算法执行框架，具备模块化API。
- [yurytsoy/revonet](https://github.com/yurytsoy/revonet) — 实数编码遗传算法库，解决优化问题及神经网络训练。

### 机器学习（Machine Learning）

[[机器学习（Machine Learning） - crates.io](https://crates.io/keywords/machine-learning)]

请参阅 - [About Rust’s Machine Learning Community](https://medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790#.hvkp56j3f)。

- [AtheMathmo/rusty-machine](https://github.com/AtheMathmo/rusty-machine) — 机器学习库。[![Build Status](https://api.travis-ci.org/AtheMathmo/rusty-machine.svg?branch=master)](https://travis-ci.org/AtheMathmo/rusty-machine)
- [avinashshenoy97/RusticSOM](https://github.com/avinashshenoy97/RusticSOM) — 自组织映射神经网络， 即Self Organizing Maps (SOM)， 可以对数据进行无监督学习聚类。[![Build Status](https://api.travis-ci.org/avinashshenoy97/RusticSOM.svg?branch=master)](https://travis-ci.org/avinashshenoy97/RusticSOM)
- [spearow/juice](https://github.com/spearow/juice) - 黑客适用的机器学习引擎（以前称为[autumnai/leaf](https://github.com/autumnai/leaf)）。
- [tensorflow/rust](https://github.com/tensorflow/rust) — TensorFlow的Rust语言绑定。[![Build Status](https://api.travis-ci.org/tensorflow/rust.svg?branch=master)](https://travis-ci.org/tensorflow/rust)
- [maciejkula/rustlearn](https://github.com/maciejkula/rustlearn) — 机器学习库。[![Circle CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://circleci.com/gh/maciejkula/rustlearn)
- [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs) — PyTorch的Rust语言绑定。 [![Build Status](https://api.travis-ci.org/LaurentMazare/tch-rs.svg?branch=master)](https://travis-ci.org/LaurentMazare/tch-rs)

### 天文（Astronomy）

[[天文（Astronomy） - crates.io](https://crates.io/keywords/astronomy)]

- [saurvs/astro-rust](https://github.com/saurvs/astro-rust) — 天文计算库。[<img src="https://api.travis-ci.org/saurvs/astro-rust.svg?branch=master">](https://travis-ci.org/saurvs/astro-rust)
- [fitsio](https://crates.io/crates/fitsio) — cfitsio接口封装库。[<img src="https://api.travis-ci.org/mindriot101/rust-fitsio.svg?branch=master">](https://travis-ci.org/mindriot101/rust-fitsio)
- [flosse/rust-sun](https://github.com/flosse/rust-sun) — 计算太阳位置。[<img src="https://api.travis-ci.org/flosse/rust-sun.svg?branch=master">](https://travis-ci.org/flosse/rust-sun)

## 异步（Asynchronous）

- [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) — 协程I/O库与工作窃取算法。[<img src="https://api.travis-ci.org/zonyitoo/coio-rs.svg?branch=master">](https://travis-ci.org/zonyitoo/coio-rs)
- [dpc/mioco](https://github.com/dpc/mioco) — 可伸缩，基于协程的异步IO库。提供虚拟调度的绿色线程，类似Golang中的Goroutines，亦称纤程（fibers）。[<img src="https://img.shields.io/travis/dpc/mioco/master.svg?style=flat-square" alt="Travis CI Build Status">](https://travis-ci.org/dpc/mioco)
- [TeaEntityLab/fpRust](https://github.com/TeaEntityLab/fpRust) — 为Rust提供面向函数范式编程特性，如：Monad/MonadIO, Handler, Coroutine/doNotation等。[<img src="https://api.travis-ci.org/TeaEntityLab/fpRust.svg?branch=master" alt="Travis CI Build Status">](https://travis-ci.org/TeaEntityLab/fpRust)
- [rust-lang-nursery/futures-rs](https://github.com/rust-lang-nursery/futures-rs) — 零开销异步编程。[<img src="https://api.travis-ci.org/rust-lang-nursery/futures-rs.svg?branch=master" alt="Travis CI Build Status">](https://travis-ci.org/rust-lang-nursery/futures-rs)
- [mio](https://github.com/tokio-rs/mio) — MIO是一个轻量级的异步I/O库，其重点是尽可能减少操作系统抽象的开销。[<img src="https://api.travis-ci.org/tokio-rs/mio.svg?branch=master">](https://travis-ci.org/tokio-rs/mio)
- [Xudong-Huang/may](https://github.com/Xudong-Huang/may) — 高性能`Stackful`协程库，类似Golang中的Goroutines，可以很容易地用来设计和开发大并发程序。[<img src="https://api.travis-ci.org/Xudong-Huang/may.svg?branch=master">](https://travis-ci.org/Xudong-Huang/may)
- [rustasync/runtime](https://github.com/rustasync/runtime) - 和`stdlib`无缝融合的异步API。[![Crates.io](https://img.shields.io/crates/v/runtime.svg?style=flat-square)](https://crates.io/crates/runtime) [![Build status](https://img.shields.io/azure-devops/build/yoshuawuyts/rustasync/2/master.svg?style=flat-square)](https://dev.azure.com/yoshuawuyts/rustasync/_build?definitionId=2)

<!-- - [管理面板（Admin Panels）](#admin-panels)
- [算法和设计模式（Algorithms & Design Patterns）](#algorithms--design-patterns)
- [反垃圾处理（Anti-spam）](#anti-spam)

- [资源管理（Asset Management）](#asset-management)
- [音频（Audio）](#音频audio)
- [验证（Authentication）](#authentication)
- [构建工具（Build Tools）](#build-tools)
- [内置类增强（Built-in Classes Enhancement）](#built-in-classes-enhancement)
- [缓存（Caching）](#caching)
- [自动聊天工具（ChatOps Tools）](#chatops-tools)
- [集群计算（Cluster Computing）](#cluster-computing)
- [内容管理系统（CMS）](#cms)
- [代码分析（Code Analysis）](#code-analysis)
- [命令行工具（Command-line Tools）](#command-line-tools)
- [兼容性（Compatibility）](#compatibility)
- [计算机视觉（Computer Vision）](#computer-vision)
- [并发和并行（Concurrency & Parallelism）](#concurrency--parallelism)
- [配置（Configuration）](#configuration)
- [密码学（Cryptography）](#cryptography)
- [数据分析和科学计算（Data Analysis & Science Computing）](#data-analysis--science-computing)
- [数据验证（Data Validation）](#data-validation)
- [数据可视化（Data Visualization）](#data-visualization)
- [数据库（Database）](#database)
- [数据库驱动（Database Drivers）](#database-drivers)
- [日期和时间（Date & Time）](#date--time)
- [调试工具（Debugging Tools）](#debugging-tools)
- [DevOps工具（DevOps Tools）](#devops-tools)
- [分发（Distribution）](#distribution)
- [文档（Documentation）](#documentation)
- [下载器（Downloader）](#downloader)
- [电子商务（E-commerce）](#e-commerce)
- [电子邮件（Email）](#email)
- [环境管理（Environment Management）](#environment-management)
- [文件（Files）](#files)
- [外部函数接口（Foreign Function Interface）](#foreign-function-interface)
- [表单（Forms）](#forms)
- [函数式编程（Functional Programming）](#functional-programming)
- [游戏开发（Game Development）](#game-development)
- [地理（Geolocation）](#geolocation)
- [图形用户界面（GUI）](#gui)
- [硬件（Hardware）](#hardware)
- [HTML处理（HTML Manipulation）](#html-manipulation)
- [HTTP](#http)
- [集成开发环境和编辑器插件（IDEs & Editor Plugins）](#ides--editor-plugins)
- [图像处理（Image Processing）](#image-processing)
- [交互式解析器（Interactive Interpreter）](#interactive-interpreter)
- [国际化（Internationalization）](#internationalization)
- [任务调度（Job Scheduler）](#job-scheduler)
- [日志（Logging）](#logging)
- [Natural Language Processing](#natural-language-processing)
- [自然语言处理（Network Virtualization）](#network-virtualization)
- [网络（Networking）](#networking)
- [ORM](#orm)
- [包管理（Package Management）](#package-management)
- [包仓库（Package Repositories）](#package-repositories)
- [权限（Permissions）](#permissions)
- [进程（Processes）](#processes)
- [队列（Queue）](#queue)
- [RESTful API](#restful-api)
- [机器人技术（Robotics）](#robotics)
- [RPC服务器（RPC Servers）](#rpc-servers)
- [搜索（Search）](#search)
- [特定格式处理（Specific Formats Processing）](#specific-formats-processing)
- [静态站点生成器（Static Site Generator）](#static-site-generator)
- [标记（Tagging）](#tagging)
- [模板引擎（Template Engine）](#template-engine)
- [测试（Testing）](#testing)
- [文本处理（Text Processing）](#text-processing)
- [第三方接口（Third-party APIs）](#third-party-apis)
- [URL处理（URL Manipulation）](#url-manipulation)
- [视频（Video）](#video)
- [网页内容提取（Web Content Extracting）](#web-content-extracting)
- [网页爬虫（Web Crawling & Web Scraping）](#web-crawling--web-scraping)
- [Web框架（Web Frameworks）](#web-frameworks)
- [WebSocket](#websocket)
- [Web服务器（Web Servers）](#web-servers) -->

## 音频（Audio）

*操作音频的库（Libraries for manipulating audio）。[[audio](https://crates.io/keywords/audio)]*

- [indiscipline/zrtstr](https://github.com/indiscipline/zrtstr) — 命令行应用，用来检测wav音频文件。探测由音频编辑软件伪造的立体音，输出单声道音频等。（Command line application for checking WAV-files for identical channels, detecting faux-stereo files generated by some audio-editing software and DAWs）。

## 资源添加

**资源添加的最简单方式是——**

- 点击 [https://github.com/zzy/awesome-rust-zh/edit/master/README.md](https://github.com/zzy/awesome-rust-zh/edit/master/README.md)；
- 编辑，然后按照GitHub的指导说明创建拉取请求。

**如果希望在`README.md`中添加资源，请首先做如下考虑——**

- 这个资源是否对`Rustaceans`有用？是否试用过？是否稳定？
- 请您在贡献资源时，使用模板：

`[username/repository_name](https://github.com/username/repository_name) [[repository_name](https://crates.io/crates/repository_name)] — DESCRIPTION [<img src="https://api.travis-ci.org/username/repository_name.svg?branch=master">](https://travis-ci.org/username/repository_name)`

*注：末尾的`svg`项可选。*

## 参考

- [awesome-rust](https://github.com/rust-unofficial/awesome-rust)
