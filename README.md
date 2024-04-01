## SZU 2024最新版Latex专业硕士论文正文模板

> 模板源文件来自计算机与软件学院历年流传下的模板内容进行修改
>
> 根据学校2024年最新模板修改编辑完成 后续更新受多位用户共同完成，在此感谢

- 完成目录更改
- 完成页眉更改
- 完成标题格式更改
- 完成文本格式更改
- 完成致谢和研究成果更改
- 完成参考文献格式更改

------

### 2024-4-1重大更新

>**对标题和目录字体进行修改，`gbt7714-2005.bst`,`szu2024.cls`、`master_pang.tex`文件有较大更改** 
>
>- 建议直接复制替换 szu2024.cls文件
>- 建议直接复制替换 master_pang.tex 文件
>- 下载和替换 gbt7714-2005.bst
>- 下载 songti-Bold.otf 文件

### <u>部分更新说明</u> ---仅保留部分重要问题 

- 标题字体修改，感谢@**[yupence](https://github.com/yupence)** 的 `Issue 14` 中[解决目录和标题字体为新罗马字体，不为宋体、黑体和英文的Arial的格式 · Issue #14 · Ftine/SZU_Latex_Master_Template (github.com)](https://github.com/Ftine/SZU_Latex_Master_Template/issues/14)分享

- **中文硕士博士论文**引用格式，感谢@**[disturb-yy](https://github.com/disturb-yy)** 的分享

>硕士格式引用 和 博士格式引用基本一致。
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

- **脚注问题** 请参考Issues#8  @**[modest-Hamilton](https://github.com/modest-Hamilton)** 用户的解决措施，问题不会关闭[脚注的问题 · Issue #8 · Ftine/SZU_Latex_Master_Template (github.com)](https://github.com/Ftine/SZU_Latex_Master_Template/issues/8)

- **参考文献问题**会议和期刊卷码`volume`格式存在不统一、以及存在期刊名称大小写不一致问题，可以手动修改。

> 该部分错误来源于Bib引用本身的问题，引用会存在不一致，若需要修改。
>
> 1. `volume` 参考 Issues#11修正 @**[ZFNSQM](https://github.com/ZFNSQM)** 用户的回答。 [参考文献格式问题 · Issue #11 · Ftine/SZU_Latex_Master_Template (github.com)](https://github.com/Ftine/SZU_Latex_Master_Template/issues/11)
> 2. 期刊名称大小写不一致问题是指 一些期刊为 `Axxx,xxx,xxx` 一些为 `Bxxx,Cxxxxx,Dxxxxx`,可以在Bib引用中手动修改完成

-  **参考文献格式** 提示修改，学校引用格式由`gbt7714-2005`更新为`gbt7714-2015`格式 , 根据@**[modest-Hamilton](https://github.com/modest-Hamilton)** 在Issue#11中的分享。
   - ​	仍建议使用gbt7714-2005格式，源代码提供的样式。


>- 添加两个引用格式文件 gbt7714.sty 以及 gbt7714-numerical.bst ，修改 master_pang.tex中引用格式
>
>```tex
>%增加包的使用 %参考文献
>\usepackage{gbt7714}
>% master_pang.tex 文件 135行左右的代码
>\bibliographystyle{gbt7714-numerical} 
>```
>
>**请注意会出现arXiv文章引用错误，无法显示arXiv等编号**
>
>> 若需要使用 ， arXIv的问题应该需要去arxiv官网导出[@misc](https://github.com/misc)格式的bibtex



------

### 赞赏

> 编辑、维护和更新不易，如若愿意微信赞赏，不胜感谢。

![image-20240401150603031](C:\Users\ftion\AppData\Roaming\Typora\typora-user-images\image-20240401150603031.png)

### 使用教程

下载该文件zip导入到相关的latex编辑工具即可，推荐使用overleaf，请注意更改编译器为XeLaTex。

### 删除内容

删除原始封面标题以及相关承诺的两页，直接使用来自SZU官方的最新模板页【生成PDF文件然后导入到论文首页】

### 不足

- 每一章节的大标题上下留白没有跟学校模板一致

### 感谢

> 欢迎start 和 fork，感恩。
>
> 若模板中存在个人信息或者有什么问题，请与我联系 fight233@sina.com。
>
> 若存在相关问题，欢迎提交issue。

## 免责声明

- 此模板仅用于学习研究，不保证其准确性、有效性，请根据情况自行判断，本人对此不承担任何保证责任本人对模板引发的问题概不负责，包括但不限于由模板错误引起的任何损失和损害。
- 与学校模板存在任何冲突，请以学校通知模板为准，本人概不负责。
- 所有直接或间接使用、查看此模板的人均应该仔细阅读此声明。
- 本人保留随时更改或补充此声明的权利。一旦您使用或复制了此模板，即视为您已接受此免责声明
