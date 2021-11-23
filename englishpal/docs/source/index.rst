.. EnglishPal documentation master file, created by
   sphinx-quickstart on Mon Nov 22 23:05:00 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

**Lab 1**: Dependency Analysis and Dependency Graph
======================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:



**小组成员**

201932110105沈音棋

201932110104马奕琪

201932110106孙仪杰

201932110107田西芷

**项目GitHub地址**: `EnglishPal`_.

.. _EnglishPal: https://github.com/ChiefEye-official/Test/

**项目Read the Doc地址**: `Read the Doc`_.

.. _Read The Doc: https://readthedocs.org/projects/testenglishpal/

Abstract
======================================

找出EnglishPal中模块/类/函数之间的依赖关系，绘制依赖图，分析EnglishPal当前依赖关系利弊。

Introduction
======================================

EnglishPal是智能捕捉阅读弱点，针对性提高用户的阅读水平的网站。提高用户的获取英文信息的速度与准确度。提供精选短文和生词簿，对于英语老师，English Pal 可以帮助掌握题目词汇规律，提高教学质量。对于英语学着，English Pal可以帮助迅速提高词汇，轻松应对各种考试。本次实验针对EnglishPal源代码，分析当前模块级依赖关系以及类/函数级依赖关系，分析当前体系结构。

Methods and materials
======================================

①Snakefood：从Python代码中生成依赖，过滤，聚类，并从依赖列表中生成图表。使用Snakefood捕获模块级依赖关系。

②Graphviz：开源的图形可视化软件。使用graphviz online渲染依赖关系图。

③Mermaid：基于Javascript的图表和图表工具，使用文本和代码创建图表和可视化，以便动态地创建和修改图表。使用mermaid live editor渲染类/函数级依赖关系图。

Results
======================================


.. image:: sfood.png

.. image:: mermaid.png
   
