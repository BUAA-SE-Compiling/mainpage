# 北航软件学院编译原理实验

## 前言

我们写代码从第一天起就和编译器打交道，而编译原理就是一门探究编译器背后奥秘的课程。编译原理这门课程不仅理论性很强，同时也需要大量的实际编码才能理解学习到的知识和实践之间的关联，因此编译实验是课程非常重要的一部分。

以往的实验内容是一脉传承——第一次词法分析，第二次 OPG，第三次语法分析，第四次最终检查，基础是做 PL0，选做 C0，以及有 GUI 等加分项。我们两位助教都对编译实验有着极高的热情，在完成实验的过程中我们自然也觉察到了大量的不合理和潜在的问题，因此第二年我们申请了助教想着手改善实验整体的体验。

之前的实验最大的问题在于 OPG 和其他的实验毫无关系而且之后写一个完整编译器门槛太高，很多学生即使是选择 PL0 因为没有参考等原因也难以完成最基本的实验，所以我们本着让绝大多数同学能愉快完成编译实验的目标出发，模仿 6 系编译实验，设计了一个名为 miniplc0 的入门级编译器来帮助学生理解一个最小编译器的实现进而能平滑过渡到自己编译器的实现。

当然，我们要承认的是，由于精力所限这个实验仍然有很多的不足，但是我们也在着手让整个实验文档化，希望参加实验的你和之后的助教能帮助我们一起来改善这个实验，让更多的学生能更加愉快的完成编译原理课程！

有关实验设计的任何问题可以联系（尤其欢迎之后的助教）

孔子乔 kzqbuaa@126.com

李明 hambaka@163.com

目前实验所有源代码全部托管在 GitHub 上，欢迎参与实验的同学提 issue/pr 帮助我们一起改进，勘误或者建议会有一定加分，希望大家喜欢新实验。

> 编译原理，真的，特别，好。——孔子乔

> 好时代，到来吧。——李明

## miniplc0

实验的目标是补全 miniplc0 编译器的词法分析器和语法分析器，理论上直接阅读指导书就可以。

[指导书](https://mini.buaasecompiling.cn)

[虚拟机](https://vm.buaasecompiling.cn)

[工具链](https://github.com/BUAA-SE-Compiling/miniplc0-toolchain/releases)

[实验源代码](https://github.com/BUAA-SE-Compiling/miniplc0-compiler)

[标准环境](https://github.com/BUAA-SE-Compiling/compilers-env)

### FAQ

#### 这个实验要做什么？

> 补全 miniplc0 编译器的词法分析器和语法分析器

结果上应该写一个**完整**的 miniplc0 编译系统的编译器。

#### 为什么需要 docker？

docker 可以统一编译环境，我们统一使用的是上面提到的标准环境。

#### 我必须要在 container 中完成吗？

不需要，container 只是最终评测环境，你可以先用 IDE 写完再自行测试，也可以一开始配好远程调试环境。

#### 我的分数怎么构成？

提交后我们会自动化评测你的实现（填空），分数由通过样例数决定，类似没有即时结果的 OJ。

#### 我怎么提交？

目前暂定是软院的云平台提交。

## C0

留空


## 引用

由于 Github Page Build 有一定延迟加上浏览器会默认缓存静态页面，因此引用课程任何相关的文档或者代码时候请引用 Permanent Links。

Markdown 文件可以点击 blame 后按 y 得到 Permanent Links，一个例子是[这样](https://github.com/BUAA-SE-Compiling/mainpage/blame/3997b251df543b45f9519467d6d5ee63f1f82419/Readme.md#L15)，为什么是按 y 见[这里](https://help.github.com/en/github/managing-files-in-a-repository/getting-permanent-links-to-files)

代码文件直接在行号上选择即可，一个例子是[这样](https://github.com/BUAA-SE-Compiling/compilers-env/blob/bc2bd1638a5d0b7ef9a2e8d1bf6460ddcce02eb1/Dockerfile#L25)

以上对要求勘误也是一样，尤其是用邮件的方式提交勘误的时候。
