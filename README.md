# 指南针 Compass
## ver: 0.1.0-alpha
**上次更新**：更新-指南针架构基本模板

> **Latest update**: update-Basic Template of Compass stucture

## 结构 Structure
- **纯粹分类** **pure-classification** ([R tree Structure]())
  
  上级：分类学<br>
  同级：（计算机科学中的）索引构建<br>
  下级：Null(tentative)<br>
  
    Superior: Taxonomy<br>
    Level: Indexing(in computer science maybe?)<br>
    Subordinate: null(tentative)<br>

注意：**纯粹分类**的结构，应当遵循**R Tree**的结构形式。
  
- **模块属性** **modulization**
  
  前置：分类学，哲学<br>
  同类：Null(tentative)<br>
  附属：Null(tentative)<br>
  
    Prerequisite: Taxonomy,Philosophy<br>
    Homotype: null(tentative)<br>
    Belongling: null(tentative)<br>

## 定义 Definition
知识库构建指导：“Compass”架构

> Repository construction guidance: “Compass” Structure

## 用途 Usage
指南针架构的意图，是在依据更高普遍性(蕴含抽象性)的逻辑基础上，建立起易抽象性更好的知识库体系。其中，更高普遍性的意义在于：同样的对象和符号，能在不同的使用者手中同样地解读，并且所有人都能理解其编辑规则，共同进行库的丰富和整理；易抽象性的意义在于：对于高度统一、高度抽象的概念，库读者可以迅速找到其具象化的方法，或对应的案例，以此与自身使用需求对接。

从此出发，指南针架构的发展方向应当是：逻辑（结构）层次严谨而简明的，抽象具象两极化且内容和谐相生的，以相对固定流程为基础、开源可个性化为延展的。

> The intention of the compass architecture is to establish a knowledge base system that is easier to abstract based on a logical foundation of higher universality (containing abstraction). The significance of higher universality lies in the fact that the same objects and symbols can be interpreted equally by different users, and everyone can understand their editing rules to enrich and organize the library together; The significance of abstractness lies in the fact that for highly unified and abstract concepts, library readers can quickly find ways to concretize them or corresponding cases to match their own usage needs.

> From this point on, the development direction of the compass architecture should be: a logical (structural) hierarchy that is rigorous and concise, abstract and concrete that is polarized and harmonious in content, based on relatively fixed processes, and open source and customizable as extensions.

## 使用教程 Tutorial
### 申明必要概念 Declaration of necessary concepts

为了避免产生不必要的疑惑，在此申明一些必要的概念，以提供使用者在首次尝试使用Compass撰写知识单位页面时、可能所需的参照。

单位：一个物件对象，或事件对象，或方法对象。这也是库结构中，每个子项的标题，是所记录知识对象的总标题。<br>
为与微软的[GraphRAG](https://microsoft.github.io/graphrag/)项目同步概念，可以申明GraphRAG中的**实体**概念与此处**单元**概念是相似的。*然而，虽然它们可以被视为等同的，但我个人建议将实体作为单位的子类别*。这是因为**社区**概念（由*实体*和*关系*等等构建而成），*关系*概念等等在这里也可以是**单元**，并有自己的**单元页面**来介绍自己。

单位页面：这个对象的详细信息页面。这是在库中对该对象展开详细描述和知识记录的页面，是指南针架构的应用处。<br>
单位页面中两个至关重要的要素：**意义**，**合理性**。<br>
确保每个单元的副标题，都是单元的高级抽象部分；解释意义，并诠释其合理性。<br>
副标题的内容，建议分为两类：一类是高度抽象的、象征性的；另一种是对抽象事物的实际描述和解释。

> To avoid unnecessary confusion, some necessary concepts are hereby declared to provide users with references they may need when attempting to write a knowledge unit page using Compass for the first time.

> **Unit**: an object, or event, or method. This is also the title of each sub-item among the repository, and the overall title of the knowledge object u want to record.
> 
> to sync with Microsoft's [GraphRAG](https://microsoft.github.io/graphrag/), the concept **Entity** in GraphRAG is similar with **Unit**. However, while they can be deemed equivalent, I personally recommend **Entity** being a subcategory of **Unit**. That's because **Community**, constructed by **Entities** and  **Relationships**, can also be a **Unit** here, having its own **Unit Page** which introducing itself.

> **Unit Page**: Detailed description page of the unit. This is a page that provides a detailed description and knowledge record of the object in the library, where **Compass Structure** about to be applied.
> 
> two essential types of contents: **meaning** & **rationality** in **Unit Page**:
> 
> ensure every subtitle of the unit, is a high level abstract part of the unit; explaining the meaning, providing rationality.
> 
> the content of the subtitle, is recommended to be two types of parts: one highly abstract, symbolized; another is practical description, explaination of the abstract things.<br><br>

### 基本结构 Basic structure

以下为**Compass**架构下，单位页面的基本内容：
1. 结构<br>
   结构部分应当由两个系列组成，即**纯粹分类**与**模块属性**。
   1. **纯粹分类**：纯粹分类为你的总目录分级服务，应当严格服从总目录的分级分类；这是为了自下而上的顺序、以及追根溯源夯实知识基础的需要准备的。
   2. **模块属性**：模块属性中将展示学习和理解该单位（对象）可能所需的前置要求，同类替代以及可选的拓展等；这是为了自上而下学习顺序、以及实际应用产生的灵活需求准备的。<br>
2. （官方/公认）指导文件（或链接）<br>
   当单位页面不值得花费更多精力来陈列不必要的信息，指导文件的链接可以方便提供额外的参考。<br>
3. 抽象定义<br>
   此为**抽象具象两极**（以下简称**两级**）中抽象的极端；<br>
   应当追求逻辑严密和统一化下，最精炼的符号表达。<br>
   它的意义在于：能熟练运用该抽象定义时，用于简化描述实际问题，寻找同质性和提高处理问题效率。<br>
4. 抽象性质<br>
   是基于上述抽象定义，对该对象的性质进行的符号化描述。抽象定义与抽象性质两部分，在单位页面中可以灵活修改、命名，比如命名为“用途”。根据申明必要概念中的描述，这些抽象的内容只要围绕这个单位的“意义”和“合理性”展开，就达到了叙述的目的。<br>
   在传统课本和教案中，抽象的定义和具体案例通常交替出现并混杂在一起，本结构认为虽然这种混杂的结构是**自然**的，但并不适合**强目的性**的学习。当读者具有一定知识基础后，这种**自然形式**反而会降低学习的速度，使知识结构的**简明性**显著下降，这种**简明性**是必然基于抽象符号的，就像使用统一套代码语言的程序能够高效互通一样。<br>
5. 辅以实际案例的详细说明<br>
   是**两极**中具象的一极。事实上，抽象定义和抽象性质均来自于人对实际案例的总结过程（抽象过程）；<br>
   这通常会是一个循环上升、依靠量来逐步优化的过程，很少能一蹴而就。<br>
   因此，附录一些实际案例来辅助说明是必要的；<br>
   此外，抽象定义和性质通常为作者所熟悉、对读者来说很陌生，辅以实际案例的说明才能优化读者的理解。<br>
6. 辅以实际案例的应用<br>
   辅以实际案例的详细说明用实际案例佐证该对象的性质，这里则给出应用的实际案例。<br><br>

The following is the basic content of the **Unit Page** under the Compass architecture:
1. structure<br>
   The structural part should consist of two series, namely **pure classification** & **modulization**.
   1. **Pure classification**: **pure classification** service for the general directory classification, it should strictly comply with the classification of the general directory. This is prepared for the bottom-up learning sequence, and the need to trace back and solidify the knowledge foundation.
   2. **modulization**: **modulization** displays the prerequisite requirements, similar substitutions, and optional extensions that may be needed to grasp the unit (object). This is prepared for the top-down learning sequence, and flexible requirements generated by practical applications.<br>
2. (Official/Recognized) Guidance Doc(or links)<br>
   when the **Unit Page** is not worth investing in displaying unnecessary information, the links to other Tutorial can provide additional references conveniently.
3. Abstract Definition(**Def**)<br>
   this is the abstract pole of the two poles of abstraction and concreteness(**poles**);<br>
   the most refined symbol expression, under logical rigor and uniformity, is what should be pursued.<br>
   significance lies in: able to proficiently apply this **Def** to simplify the description of cases, find homogeneity among cases, thus improve efficiency.<br>
4. Abstract Properties<br>
   symbolic descriptions of the properties of the object, based on **Def** above.<br>
5. Detailed explanation supplemented by practical cases<br>
   the concrete pole of the **poles**. In fact, **Def** and abstract properties both come from summarization of actual cases(abstraction);<br>
   this is usually a cyclical process that relies on quantity to gradually optimize, rarely can be accomplished at one stroke.<br>
   thus necessary to provide some practical cases for explaination supplement;<br>
   **Def** and abstract properties are often familiar to authors, but unfamiliar to readers. Just enhance the readers' understanding through practical case studies.
6. Application supplemented by practical cases<br>
   here u can present a practical application case as a exemplary role.<br><br>

## 开源许可 License

The MIT License (MIT): https://opensource.org/license/mit/
