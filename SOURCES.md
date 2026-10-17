# 来源、更新日期与素材许可

核验日期：2026-10-16。只把原页面明确列出的日期当作发布/更新信息。未标日期的资料不称为“最新教程”。

| 类型 | 来源 | 原站时间 | 本站用途 |
| --- | --- | --- | --- |
| 官方教程 | [Observable：Beyond bar charts](https://old.observablehq.com/blog/beyond-bar-charts-a-guide-to-advanced-visualizations-in-observable-plot) | 2026-03-23 发布 | 进阶图表选型延伸阅读；不转载全文 |
| 官方指南 | [Observable：Choosing the right chart](https://old.observablehq.com/blog/right-chart-for-data) | 2025-09-19 发布 | 按数据结构选择图表 |
| 官方教程 | [Observable：Reshaping data for D3 and Plot](https://old.observablehq.com/blog/reshaping-data-plot-d3) | 2025-06-26 发布 | 宽长转换、聚合与嵌套数据参考 |
| 官方文档 | [D3 Getting Started](https://d3js.org/getting-started) | 未明示更新日；当前维护页面 | 比例尺、SVG 与坐标轴 API；本站固定 D3 7.9.0 |
| 技术文档 | [MDN SVG 中文入门](https://developer.mozilla.org/zh-CN/docs/Web/SVG/Tutorials/SVG_from_scratch/Getting_started) | 2025-06-24 更新 | SVG 元素与渲染顺序参考 |
| 作者素材 | [Kenney Tiny Farm](https://kenney.nl/assets/tiny-farm) | 1.0，2026 年发布（未明示月日） | 旧版树木和幼苗；当前页面不引用，保留 CC0 许可 |
| 教师资料 | [李昕《可视化导论》](https://cinger007.github.io/vis/) | 未统一标注更新日 | 原课程五章结构与完整讲义入口 |
| 经典工具 | [ColorBrewer 2.0](https://colorbrewer2.org/) | 未明示更新日 | 色板分类补充参考；不列作近期教程 |

## 当前本地素材

- `assets/vis-mark.svg`：2026-10-17 原创点阵标识。
- 编码示例页单位图和连续图：原创 D3/SVG，固定手工教学数据。每个单位格精确对应 2 本书。
- `assets/d3.v7.min.js`：D3 7.9.0（ISC），本地加载；许可 `assets/D3-LICENSE.txt`。
- 旧版猫、树木等文件不再被当前页面引用，仅保留版本追溯。当前宠物 UI 与交互逻辑已删除。

## 教学数据

五个类别的借阅量和参与人数、12 个时长/分数样本、28 日模拟借阅量，以及流程图的 6 条记录均为固定手工教学示例。数据直接写在 app.js，不对应真实调查、真实学生或真实课程成绩。不用这些示例声称现实世界的统计结论。

## 内容边界

本站文字为独立撰写的学习概括，没有复制上述教程全文。教师原讲义包含的完整案例、更多拟合方法、螺旋与故事线等内容，通过各章“教师完整讲义”入口继续查阅。本站交互覆盖五个代表性任务，并非原课程所有演示的完整移植。

## 排版参考

- [MIT OpenCourseWare 18.06 Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)：参考课程目录和资料分类；课程为 2010 年，不列作近期教程。
- [D3 线性比例尺官方文档](https://d3js.org/d3-scale/linear)：参考术语、公式、参数、例子的说明顺序。
- [MDN SVG](https://developer.mozilla.org/en-US/docs/Web/SVG)：参考无衬线文档排版、层级标题和主题目录。

本站没有使用上述机构的品牌标识，也不表示官方认可。

## 2026-10-17 界面修订

当前界面改为原创数据单位图与像素风控件，不再引用旧版 Kenney 树木、幼苗、蘑菇或猫 SVG。旧文件仅保留追溯。设计参考为用户指定的 Echo-Tail、鱼皮与 StyleKit 页面，链接、具体采用内容及取舍详见 DESIGN.md。它们不列作可视化学科的权威教程。
