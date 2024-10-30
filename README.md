# ZJU 报告模板

## 主要内容

LaTeX 的模板在 `latex` 文件夹下，Markdown 的主题和模板在 `markdown` 文件夹下。由于 LaTeX 每个学院基本上都有自己的毕设或者答辩的模板，这里就不怎么提供了。这里的 Markdown 主题都是我在已有主题的基础上修改的，主要是为了适应自己的需求；修改的地方都用`@nenhang`标注了。

- [x] [mygithub 主题](typora-markdown/mygithub/mygithub.css) 
    这个主题是我在 Typora 自带的 GitHub 主题上修改的，主要是修改了代码块的字体（加入了JetBrains Mono和Consolas）和侧边栏的样式（改为了和 Drake 类似的带有颜色的风格）。
- [x] [mylatex 主题](typora-markdown/mylatex/mylatex.css)
    这个主题是我在经典的 [typora-latex-theme](https://github.com/Keldos-Li/typora-latex-theme.git) 的基础上修改的，我主要做了如下方面的修改：

    - 修改了代码块的字体和行内代码、代码块的风格；
    - 修改了正文字体“家族宋”被解释为楷体的bug；
    - 稍微调整了部分字体的样式，去除了一些冗余的字体；

    对应这个主题，在 `typora-markdown/mylatex/project-template` 文件夹下有一些报告模板，适用于浙江大学的本科生实验报告、课程设计报告等。
    <table><tr>
        <td><img src=./typora-markdown/mylatex/project-template/cover_examples/lab-report_cover.png border=0></td>
        <td><img src=./typora-markdown/mylatex/project-template/cover_examples/project-report_cover.png border=0></td>
    </tr></table>

## 使用方法

1. 下载对应的 CSS 文件，放到 Typora 的主题文件夹下；
2. 安装仓库中主题文件夹和模板文件夹下的`fonts`文件夹中的字体，具体版权和来源可以参考相应文件夹下的`README.md`文件；少数几个字体是我自己添加的，如 **Consolas**，**方正公文仿宋**等，剩下的字体中，除了系统自带的字体外，我唯一没有提供的是 **JetBrains Mono**，因为这个字体是一直在更新的，所以我没有提供 fonts 文件，大家可以自行到[官网](https://www.jetbrains.com/lp/mono/)下载；
