[TOC]

## Weka

[Waikato Environment for Knowledge Analysis](https://www.cs.waikato.ac.nz/ml/weka/)是新西兰怀卡托大学开发的一个开源机器学习平台，它使用Java语言编写，提供了一个图形用户界面、命令行接口以及Java API。

Weka集成了数据挖掘任务相关的机器学习算法。这些算法可以直接应用于数据集，或者你也可以自己编写Java代码调用它们。Weka包含各种用于数据预处理、分类、回归、聚类、关联规则以及可视化的工具。它也非常适合用于开发新的机器学习方法。

Weka是开源软件，基于GNU GPL发行。著名的开源商务智能软件[Pentaho](https://sourceforge.net/projects/pentaho/)就是采用Weka作为它的数据挖掘组件。

Weka同时也是一种只在新西兰生存的鸟，它不会飞，但是拥有好奇的天性。

Weka的下载地址为：
[https://www.cs.waikato.ac.nz/ml/weka/downloading.html](https://www.cs.waikato.ac.nz/ml/weka/downloading.html)。可以选择相应平台的安装包进行下载。

安装完成后运行Weka，首先显示GUI Chooser界面。

![Chooser](http://img.blog.csdn.net/20171229162619293?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaG9yc2Vz/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

选择器界面包含了5个不同的应用，分别是：

 1. Explorer，WEKA中进行数据探索的软件环境。
 2. Experimenter，针对不同的机器学习方法进行实验和统计测试。
 3. KnowledgeFlow，功能和Explorer类似，但是使用拖拽的方式进行操作，同时它还支持增量学习。
 4. Workbench，包含了其他应用的组合，可供用户选择使用。
 5. SimpleCLI，一个简易的命令行接口，可以在不支持命令行的操作系统中直接调用Weka命令。

### Explorer

Explorer是Weka的主要图形用户界面，包括预处理、分类、聚类、关联、属性选择以及可视化。

![Explorer](http://img.blog.csdn.net/20180123104721241?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaG9yc2Vz/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

 - Preprocess，预处理，加载数据集，可以进行编辑。
 - Classify，分类，用于分类或回归的学习方案，执行训练和测试。
 - Cluster，聚类，数据集的聚类学习。
 - Associate，关联，学习数据关联规则。
 - Select attributes，属性选择，选择数据集中最相关的属性。
 - Visualize，可视化，创建交互式2D散点图。

### Experimenter

Experimenter可以用于比较不同的学习方案，选择一组数据集，使用不同的学习算法，运行之后收集性能统计数据，同时可以实现自动化。

![Experimenter](http://img.blog.csdn.net/20180123110702356?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaG9yc2Vz/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

### KnowledgeFlow

KnowledgeFlow允许通过拖曳的方式，按照一定顺序将数据源、预处理工具、学习算法、评估手段和可视化模块的各构件组合在一起，形成数据流。如果选取的过滤器和学习算法具有增量学习功能，可以实现大型数据集的增量分批读取和处理。

![KnowledgeFlow](http://img.blog.csdn.net/20180123112943629?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaG9yc2Vz/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

### Workbench

Workbench为其他的界面提供了统一的操作接口。

![Workbench](http://img.blog.csdn.net/20180123134245046?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaG9yc2Vz/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

### SimpleCLI

SimpleCLI提供了一个简易的命令行接口，可以调用所有的Weka类。

![SimpleCLI](http://img.blog.csdn.net/20180123135026443?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaG9yc2Vz/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

### Package Manager

从Weka 3.8开始，提供了一个图形化的包管理系统，用于安装和管理扩展包。包管理器位于Weka GUI Chooser的Tools菜单中。

![Package Manager](http://img.blog.csdn.net/20180123142050893?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvaG9yc2Vz/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

## 免费课程

怀卡托大学在网络上提供了几门关于Weka机器学习和数据挖掘的免费课程，包括[Data Mining with Weka](https://www.futurelearn.com/courses/data-mining-with-weka)，[More Data Mining with Weka](https://www.futurelearn.com/courses/more-data-mining-with-weka)和[Advanced Data Mining with Weka](https://www.futurelearn.com/courses/advanced-data-mining-with-weka)。这些课程的视频也可以通过[Youtube](https://www.youtube.com/user/WekaMOOC)查看。

