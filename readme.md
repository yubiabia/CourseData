# **课程域描述可视化 Course-domain data Visualization**

## 使用环境 Environment 
-工具:html, JavaScript Tool:html, JavaScript
-库:D3 Library: D3
-数据文件:tsv Data Format:tsv

## 可视化1: 7选3课程的可折叠树状图
数据:CourseSelection.json Data: CourseSelection.json
可视化文件：TreeDiagram.html Interface: TreeDiagram.html
该可视化展现了高三学生在2018/7/1的考试（高二第二学期期末考）后确认的选考科目情况
-颜色深浅及气泡半径：展现该选课组合的概率
-例如：
（1）学科-技术（0.638）则表示有63.8%的高三学生选择了"技术"课程
（2）学科-技术-化学(0.594)则表示在选择了"技术"课程的高三学生中，有59.4%的学生同时选择了"化学"课程
（3）学科-技术-化学-物理(0.697)则表示在选择了"技术+化学"组合的学生，有69.7%同时选择了"物理"课程
备注：在数据探索阶段，我们注意到一部分高三学生在高二期末后有7选4的情况（而不是选3），我们保留了该部分的数据用于追踪这部分学生及进行未来细节的可视化。

## 可视化2: 课程历史最高最低分的趋势图
数据：MaxMinScore.tsv DAta: MaxMinScore.tsv
可视化文件：MultiLine_MaxMin.html Interface: MultiLine_MaxMin.html
该可视化展现了2014-2019年十六个学科（包括1B模块总分）的历史最高最低分趋势
-颜色：用于区分各学科
-实线：最高分趋势
-虚线：最低分趋势
-右侧图例：用于展现、隐藏所呈现的学科最高/低分
-下侧笔刷：可延长、缩短、平移所呈现的历史时期

