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
- [异步（Asynchronous）](#异步asynchronous)
- [音频（Audio）](#音频audio)

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

## 音频（Audio）

[[音频（Audio） - crates.io](https://crates.io/keywords/audio)]

- [indiscipline/zrtstr](https://github.com/indiscipline/zrtstr) — 命令行应用，用来检测wav音频文件。探测由音频编辑软件伪造的立体音，输出单声道音频等。[<img src="https://api.travis-ci.org/indiscipline/zrtstr.svg?branch=master">](https://travis-ci.org/indiscipline/zrtstr)
- [GuillaumeGomez/rust-fmod](https://github.com/GuillaumeGomez/rust-fmod) — [FMOD](https://www.fmod.com) bindings [![Build Status](https://api.travis-ci.org/GuillaumeGomez/rust-fmod.svg?branch=master)](https://travis-ci.org/GuillaumeGomez/rust-fmod)
- [jhasse/ears](https://github.com/jhasse/ears) — A simple library to play Sounds and Musics, on top of OpenAL and libsndfile [<img src="https://api.travis-ci.org/jhasse/ears.svg?branch=master">](https://travis-ci.org/jhasse/ears)
- [jpernst/alto](https://github.com/jpernst/alto) — OpenAL 1.1 bindings [<img src="https://api.travis-ci.org/jpernst/alto.svg?branch=master">](https://travis-ci.org/jpernst/alto)
- [musitdev/portmidi-rs](https://github.com/musitdev/portmidi-rs) — [PortMidi](http://portmedia.sourceforge.net/portmidi/) bindings [<img src="https://api.travis-ci.org/musitdev/portmidi-rs.svg?branch=master">](https://travis-ci.org/musitdev/portmidi-rs)
- [hound](https://crates.io/crates/hound) — A WAV encoding and decoding library [<img src="https://api.travis-ci.org/ruuda/hound.svg?branch=master">](https://travis-ci.org/ruuda/hound)
- [tomaka/rodio](https://github.com/tomaka/rodio) — A Rust audio playback library [![Build Status](https://api.travis-ci.org/tomaka/rodio.svg?branch=master)](https://travis-ci.org/tomaka/rodio)
- [RustAudio/rust-portaudio](https://github.com/RustAudio/rust-portaudio) — [PortAudio](http://www.portaudio.com/) bindings [<img src="https://api.travis-ci.org/RustAudio/rust-portaudio.svg?branch=master">](https://travis-ci.org/RustAudio/rust-portaudio)

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
