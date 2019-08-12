# Go 工程化编程

当我写下这个标题的时候，首先进入我脑海的是两个问题：

- 第一，什么是工程化编程
- 第二，为什么需要工程化

虽然是两个问题，但是关键词就一个，即**工程化**。

> **工程化是什么?**

为了更好的总结个人对于工程化模糊的定义，我特意在网上搜了一圈。其中，阿里云云栖社区的这篇文章：[《前端工程化概述》](https://yq.aliyun.com/articles/574270)中给的定义同样也是我想说的：

> **工程化**即系统化、模块化、规范化的一个过程。

> 如果说计算机科学要解决的是系统的某个具体问题，或者更通俗点说是面向编码的，那么工程化要解决的是如何提高整个系统生产效率。与其说软件工程是一门科学，不如说它更偏向于管理学和方法论。解决什么问题工程化解决的问题是，如何提高编码、测试、维护阶段的生产效率。

所谓**工程化编程**，即将编程覆盖到整个工程的生命周期中，包括需求分析、系统设计、编码、测试、发布等各阶段。系统性提升编码、测试、发布等各阶段的生产效率。

具体内容，计划通过具体的工程案例实践，一步步的记录整个过程。

## 留言区

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css">
<script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>
<div id="gitalk-container"></div>
<script>
  var gitalk = new Gitalk({
      clientID: '381ef6e29bdffb9ad797',
      clientSecret: '558305235c247d8766aa9d051cfce259818c0b85',
      repo: 'website',
      owner: 'gitdigg',
      admin: ['liujianping'],
      id: location.pathname,      // Ensure uniqueness and length less than 50
      distractionFreeMode: false  // Facebook-like distraction free mode
    })
    gitalk.render('gitalk-container')
</script>



