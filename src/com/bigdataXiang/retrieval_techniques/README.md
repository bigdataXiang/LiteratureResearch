#信息检索策略定制
##1.确定检索词
```
选择有实质意义的、概念明晰的、关键的词汇
问题：
How did water and energy cycle  influence the climate extremes in China?
关键词包括：
water and energy cycle
climate extremes
China
还有吗？
water and energy budget 
energy and water budget
water and energy balance
energy and water balance 
Meteorological Disaster 
meteorological  hazard
……

在同一概念的范畴内，列出这些词的所有拼写形式和方法，即从语言角度，选择不同的名
称、拼写方法和单复数形式。包括学名和俗名、简称和全称、事物的代码等
water and energy cycle —— water and energy budget —— water and energy
balance ——hydrological and energy cycle climate extremes —— climate extreme

这些词的广义词、狭义词、相关词及多义词等
climate extreme —— meteorological hazard ——meteorological  disaster
明确词根，列出相关同义派生词
meteorological —— meteorolog*

参考有关的叙词表（如汉语主题词表）或利用在线字典式检索功能，检查检索词（如人名、
地名、期刊名称等的正确表示方式，也可检查拼写等）、选准同义词和相关词。 
America ——United States——USA——U.S.

对于泛指的主题概念词，应多多注意，应选用其包容特性的具体内容来表达
climate extreme
drought 
extreme dry 
Flood ( flooding )
heavy rain
 extreme precipitation 
extreme wet event
 rainfall extremes
……

有些词的专指度太高，恐难查到文献时，可考虑对检索词可进行粗化，取其上位更宽范的
检索词
Pinus（松）——Pinaceae（松科）—— Gymnosperms（裸子植物）

分析隐含概念，抽取核心检索词
climate extreme —— drought
Influence —— accelerate
Water and energy cycle ——hydrological cycle 


有些词不能用
有些词概念已经体现在所使用的数据库中
例如，computer（计算机）一词在计算机数据库（The Computer Database）
有些比较泛指、检索意义不大的概念，如“发展Development”、“趋势Trends”、
“现状Status”等在不是专门查找综述类文献时也不用。

 同样，诸如“工艺Technology”、“分析Analysis”、“应用Application”等词，以及诸
 如“有机物”、“无机物”、“病虫害”等外延十分宽的概念，切记都应转换成具体的方法或
 材料、化合物及具体的病害与虫害的名称表示

```
##2.逻辑检索（布尔检索）功能的利用
```
布尔逻辑检索功能：布尔逻辑检索是把任何检索课题加工成可以进行逻辑运算的表达式，
布尔逻辑运算的优点是简单明确、易于理解、符合人们的思维习惯。其算符的相互匹配方
式主要有3种。

逻辑与（逻辑乘） 
“AND” 或 * 
例： “water and energy cycle”  and cliamte extremes
逻辑或（逻辑加）
 “OR” 或 “+” 
例：cliamte extremes or extreme events
逻辑非（逻辑减）
“NOT”或“—”
例：“NOT”或“—” 
括号（）：用于将布尔逻辑符分组，区分优先级

```
##3.词间位置检索功能的利用
```
文献记录中词语的相对次序不同，所表达的意思就可能不同。
同样在检索式中，检索词的相对次序不同，表达的检索意图也不一样，布尔逻辑运算符有
时难以表达某些信息需求的确切要求，用词间位置算符来限定和组合检索词，可弥补布尔
逻辑算符的不足。 

词间位置检索技术有时对检索质量影响很大。包括两种：
词间距的限制:即确定检索词之间距离位置关系
前后的限制:即确定检索词之间前后位置关系

例：(PQDT-B数据库)
W/n (两词间距小于n个单词，且前后位置任意)
   virus W/8 macro 
   "a virus that is hidden in a macro"
Pre/n (两词间距小于n个单词，且前后位置一定)
   macro Pre/2 virus
   "large macro-pores on virus passage through LPMs
   
   
   例：(SCI数据库)
   NEAR代表所链接的两个词之间的词语数量小于等于N，默认的使用Near的缺省值是15。
   Example:  canine NEAR/10 virus
                          canine NEAR virus
   SAME表示两个关键字必须同时出现在同一个‘文句’中，前后顺序不限。
   Example:  yale SAME hosp*
      “SAME”与“AND”很类似，但是检索限制更严格。要求两个关键字都必须出现，但必须同时出现在同一个‘文句’中，前后顺序不限。一个“文句”可代表文档摘要中的一句话、文档标题、一个关键字串或是作者的地址。

```
##4.截词检索功能的利用
```
有限截断 与 无限截断
前截断、后截断、中间截断
?Chemistry  可检出如:Cchemistry , Ochemistry , Lchemistry 
???Chemistry  可检出如:Biochemistry, Geochemistry, Ecochemistry 
*glycemia可检出如:hyperglycemia , hypoglycemia 


后截断
chem*  可检出：chemical、 chemism、 chemomorphosis、 chemosynthesis
ad???可检出：added、adult、adopt
中间截断
wom?n 可检出： woman，women
colo*r 可检出： colour、color


截词检索在中文数据库中截的是词意，在外文数据库中截的是词的后缀，截断后派生出的
词汇和原来的词属同一词根，含义基本一致。
例：北京？ 
分别检出了：北京产业、北京商务等。
例： metal*    
可检出  metal 、metals、metaled、metalist等。

利用截词检索时，截词的部位一定不能截的太深，否则误检率会很大。
例：rat* 可检出
   rate、rats、rational等词义不全不同的词   
   
   
所有可以使用单词和短语的检索字段均可以使用通配符。它们可在检索式中表示未知字符。 星号 (*) 表示任何字符组，包括空字符。 
问号 (?) 表示任意一个字符。
美元符号 ($) 表示零或一个字符（对可能包含空格、连字号或撇号的作者姓氏，查找同
一单词的英国/美国拼写非常有用）。
* 可位于检索词的中间或结尾，但不能位于开头。
双引号“”用于专用语或者专用词组的查询，如“adaptive optics”≠adaptive optics

TS= ("climat* change")OR"climat* variation"OR"global warming"OR"temperature ris*")
     AND TS=(bio* diversity OR bio* conservation "species richness"OR "species diversity")
     
```
##字段限制检索功能的利用
```
是指定检索词在记录中某一具体的字段中出现。字段限定检索可以分为三类：
后缀方式
       如：apple？ in TI 
        即 apple 或  apples 在篇名中出现即为检中。 
        如：chin* Acad* of sci* in AD 
          即在地址字段中出现中国科学院的即被检中。

前缀方式  
如：LA=Chinese  即限定原文语种为中文。 
 PY>=1995    即限定出版年份为1995及以后的文献。
 AU(smith)即限定作者为smith的文献。

```
##6.构造检索式要求
```
不失真
与数据库要匹配
简单明了 

```
##总结：如何构建良好的检索策略
```
确定检索词 :
  选择有实质意义的、概念明晰的、关键的词汇
  在同一概念的范畴内，列出这些词的所有拼写形式和方法，即从语言角度，选 择不同的名称、
拼写方法和单复数形式。包括学名和俗名、简称和全称、事 物的代码等 
  广义词、狭义词、相关词及多义词等 
  明确词根，列出相关同义派生词 
  参考有关的叙词表（如汉语主题词表）或利用在线字典式检索功能，检查检索 词（如人名、
地名、期刊名称等的正确表示方式，也可检查拼写等）、选准 同义词和相关词 分析隐含概念，
  抽取核心检索词 
  有些词不能用 
  
  构造检索式（合理安排检索词之间的关系）
  逻辑检索（布尔检索）功能的利用（ and/ or/ not ）
  词间位置检索功能的利用（ same/ near） 
  截词检索功能的利用（*/?/$） 
  字段限制检索功能的利用 

```
##文献数据库的选择
```
中文：cnki, cscd
外文：scie, ei, elsevier, ieee
文摘：cscd, scie, ei, 
全文：cnki, elsevier, ieee
综合性：cnki, cscd , elsevier, scie, ei
专业性：ieee, SciFinder
综述论文：reviews
研究论文：articles
```

##获取信息的途径
```
网络搜索引擎
新闻聚合系统
数据库（文摘、全文、学科专题、数值数据库等）
NSTL资源的获取与利用
学位论文数据库
专利数据库
开放获取类数据库
```
##如何看文献
```
学会阅读文献，读透文献。尽量多看核心期刊，其他不看。看10－20篇review后再看研究性论文。
研究性论文-先看标题，从问题入手，思考
想想别人这文章是怎么做的(可参考材料方法)？
作者为什么要做这项工作？
这篇论文会做哪些内容来说明其标题？
如果论文是近半年内发表的，该论文解决了什么问题？引出了什么问题(结合你看的综述)？
仔细看摘要，比较你的想法与作者的是否吻合
看实验结果，想想有什么地方不完善？是否可继续深入或拓展？

尽可能全面的信息
新的研究方法和研究思路
相关的交叉学科
密切相关但自己开始没有注意到的文献
相对高质量的文献
读一篇高质量文献和一篇低质量文献要花费相同的时间
取法乎上，得乎其中
多角度分析文献，快速了解课题的来龙去脉

```
##利用Web of Science帮助选题和开题
```
从一个主题角度开始
找出主题词
检索并从中找到研究的思路
从一篇高质量论文开始
了解目前论文所涉及到内容的最新动态
现有的理论基础和经典方法

英文字母不分大小写
如果在检索式中使用不同的运算符，则会根据下面的优先顺序处理检索式： NEAR/x ，SAME，NOT，AND，OR。
使用括号可以忽略运算符优先级，按照括号内的表达式优先执行
短语检索中，不能使用美元符号$
在“主题”和“标题”检索中，如果使用左/右截词符，那么必须在通配符前/后至少输入 3 个字符。例如：*bio，bio*

关于SAME的使用
主要在“地址”字段中可以使用 SAME。例如AD=(McGill Univ SAME Quebec SAME Canada) 查找，查询结果会出现 McGill University 以及 Quebec 和 Canada 的记录
当在其他字段（如“主题”和“标题”）中使用时，SAME 与 AND 的作用就完全相同。例如：TS=(cat SAME mouse) 与 TS=(cat AND mouse) 将得到相同的结果。

```
##Web of Science检索步骤
```
1.选择 Web of Science 核心合集数据库
2.打开下拉菜单选择检索项topic（Title ,Abstract, Author, Keywords, Keywords Plus®）
3. 输入关键词，注意逻辑运算符和通配符的使用
   检索策略范例：TS=(((“low* carbon*” not steel*) and (environment* or pollut* or energ* or climat*)) or “low* carbon* econom*” or “low* carbon* urban*” or “low* carbon* city“ or “low* carbon* cities“)

4.选择子库和年代
5.点击检索
6.得到初步检索结果后，精炼检索结果--学科、文献类型、作者、机构、国  家等选项
7.得到理想的检索结果
8.通过文献类型精炼 检索查看综述文献，快速了解该领域的研究概况
9.通过排序，找到最新、最早的文献，引用最高的经典文献
10.点击创建引文报告，生成引文报告
11.该主题的发文和被引情况；论文按照被引频次排序，可查看每篇论文的每年被引用次数和年均被引用次数，了解哪些是近几年高被引论文，确定热点论文，把握热点研究方向
12.可以选择从作者、会议标题、国家/地区、文献类型、机构名称、语种、出版年、来源出版物、学科类别等15个不同角度对检索结果进行分析，以获得课题全貌

```
##使用Google搜索应掌握的基本知识
```
  不使用" AND“:在Google查询时不需要使用"and"，因为Google会在关键词之间自动添加"AND"。
Google提供符合您全部查询条件的网页。如果您想逐步缩小您的搜索范围，只需输入更多的关键词。
  不支持“OR”，“NOT”: Google无法接受“或者包含词语A，或者包含词语B”的网页。
  忽略部分词语:Google忽略“http”和“com”等字符，以及数字和单字，此类字词过于频繁出现于大
部份网页，不仅无助于查询，而且大大降低搜索速度。　　
  支持“-”功能:有时候，排除一些关键词比增加关键词更有利于缩小查询范围。Google支持此项“-”功能，
用以有目的地删除某些无关的网页，但减号之前必须留一空格。 
  冒号功能:某些词后面添加冒号，在Google中便具有了特殊功能。Google支持这样的特殊操作符。
比如remote：pdf
  专用词语上加上双引号:专用语查询。只要在专用词语上加上双引号，就可以准确地进行查询。
这一方法在查找名言警句或专有名词时显得格外有用。

```
##房地产大数据类文献检索
```
1.关键词：
 network data，big data，real estate price,housing price,real estate
 Real Estate Values,
 
 TS=(("network data "OR "big data"OR"online data")AND(real estate price or housing price)OR(real estate (study OR research)))
```