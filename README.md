## SZU 2024最新版Latex专业硕士论文正文模板

> 模板源文件来自计算机与软件学院历年流传下的模板内容进行修改
>
> 根据学校2024年最新模板修改编辑完成

- 完成目录更改
- 完成页眉更改
- 完成文本格式更改
- 完成致谢和研究成果更改
- 完成参考文献格式更改

------

### <u>更新说明</u>

**2024-3-4** 更改 `master_pang.tex`文件中的96行代码 公式样式。 感谢@**[modest-Hamilton](https://github.com/modest-Hamilton)**  的指正。

```tex
% 公式更改为3-2样式
\renewcommand\theequation{{\thesection}-{\arabic{equation}}}
```

**2024-3-6** 修复`szu2024.cls`摘要显示问题 ，解决摘要部分由于 摘要页数为 2 导致页眉无法显示的问题

> 该内容中存在一个问题：若摘要页数为 2 ，请第二页尽量保持文字字数为 4 行以上，否则也会出现页眉被强制替换的情况

- 替换请替换 `szu2024.cls` 中 120-180的代码。

**2024-3-7** 中文硕士博士论文引用格式，感谢@**[disturb-yy](https://github.com/disturb-yy)** 的分享

>中文的硕士引用 和 博士引用基本一致。
>
>博士格式：
>[@PhDThesis](https://github.com/PhDThesis){zhu1996,
>title={新型流体有限元法及叶轮机械正反混合问题},
>author={朱刚},
>school={清华大学},
>address={北京},
>year={1996},
>}
>
>硕士：
>[@MasterThesis](https://github.com/MasterThesis){zhu1996,
>title={新型流体有限元法及叶轮机械正反混合问题},
>author={朱刚},
>school={清华大学},
>address={北京},
>year={1996},
>}

**2024-3-8** 修改目录二级、三级目录缩进过多问题，觉得不合适的可以微调。个人觉得合适的距离如下，具体修改如下

-  `szu2024.cls` 中 文件中的第 73 和 75 行 代码修改，具体代码行请自己对照

```tex
%二级标题 2em 改为 1em
\titlecontents{subsection}[1em]{\zihao{-4}}
%三级标题 4em 改为 1.8em
\titlecontents{subsubsection}[1.8em]{\zihao{-4}}
```

**2024-3-23**  部分Issues 修改和更新

- 科研成果页 标题和页眉存在写书错误，请修改。

```tex
% master_pang.tex 第149行 修改如下
\fancyhead[C]{\songti\zihao{5}{攻读硕士学位期间的学术成果}}
% chapter/myPapers.tex 第一行 修改如下
\begin{szuAppendixB}{攻读硕士学位期间的研究成果}
```

- 目录页面不存在新罗马页码问题

```tex
% szu2024.cls 第89行 修改如下
\pagestyle{empty} 改为 \pagestyle{plain}
```

- 脚注问题 请参考Issues#8  @**[modest-Hamilton](https://github.com/modest-Hamilton)** 用户的解决措施，问题不会关闭

- 参考文献会议和期刊卷码`volume`格式存在不统一、以及存在期刊名称大小写不一致问题，可以手动修改。

> 该部分错误来源于Bib引用本身的问题，引用会存在不一致，若需要修改。
>
> 1. `volume` 参考 Issues11 @**[ZFNSQM](https://github.com/ZFNSQM)** 用户的回答。
> 2. 期刊名称大小写不一致问题是指 一些期刊为 `Axxx,xxx,xxx` 一些为 `Bxxx,Cxxxxx,Dxxxxx`,可以在Bib引用中手动修改完成



------



### 使用教程

下载该文件zip导入到相关的latex编辑工具即可，推荐使用overleaf，注意更改编译器为XeLaTex。

### 删除内容

删除原始封面标题以及相关承诺的两页，直接使用来自SZU官方的最新模板页【生成PDF文件然后导入到论文首页】

### 不足

- 每一章节的大标题上下留白没有跟学校模板一致
- 章节标题的数字字体没有完成更改

### 感谢

> 欢迎start 和 fork，感恩。
>
> 若模板中存在个人信息或者有什么问题，请与我联系 fight233@sina.com。
>
> 若存在相关问题，欢迎提交issue。

## 免责声明

- 此模板仅用于学习研究，不保证其准确性、有效性，请根据情况自行判断，本人对此不承担任何保证责任本人对模板引发的问题概不负责，包括但不限于由模板错误引起的任何损失和损害。
- 与学学校模板存在任何冲突，请以学校通知模板为准，本人概不负责。
- 所有直接或间接使用、查看此模板的人均应该仔细阅读此声明。
- 本人保留随时更改或补充此声明的权利。一旦您使用或复制了此模板，即视为您已接受此免责声明
