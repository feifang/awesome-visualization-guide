# awesome-visualization-guide
🧾 A list of recommended guidelines and principles on data visualization. 整理收集数据可视化设计原则（选自 Edward Tufte 等大师著作）

## Principles 原则
| ID | Principle | Topic | Type | Note | Source | Chapter | Page |
|--|--|--|--|--|--|--|--|
|1| 记录可视化数据的来源及特征  | 统计图；可视化设计；可视分析 | 🔠 | - | III | 1 | 53 |
|2| 注重引导读者在阅读时进行比较  | 统计图；可视化设计；可视分析 | 🔠 | - | III | 2 | 53 |
|3| 在图表中展示因果机制（原因如何导致结果），最好使用量化的方式  | 统计图；可视化设计；可视分析 | 🔠 | - | III | 2 | 53 |
|4| 考虑问题自身的多个不同维度，尝试考虑不同的解释方法  | 统计图；可视化设计；可视分析 | 🔠 | - | III | 2 | 53 |
|5| 在保障图表清晰有效的前提下，尽可能减小各视觉元素的差异（从而提高信息容量）- the smallest effective difference  | 可视化设计 | 🔠 | - | III | 4 | 73 |
|6| 好的设计应该考虑数据的使用场景、时间和方式 | 可视化设计 | 🔠 | 例如需要随身携带的图表，需要考虑方便折叠使用 | III | 6 | 115 |
|7| 信息的组织形式最好是读者一眼就能看懂的 | 可视化设计 | 🔠 | 如果图表的组织复杂到需要画另一张阅读路线图来引导用户，就该反思一下了 | III | 7 | 125 |

## Guidelines/Strategies 策略技巧
| ID | Guideline | Topic | Type | Note | Source | Chapter | Page |
|--|--|--|--|--|--|--|--|
|1| 选择合适的图表长宽比，使折线的斜率（绝对值）集中在45度附近  | 折线图 | 🔢 | - | III | 1 | 25 |
|2| 对于涉及金钱的时序图表，应展示经过通胀调整后的数值  | 统计图；可视化设计；可视分析 | 🔢 | - | III | 3 | 70 |
|3| 弱化图表的网格、表格的边框（变浅、变细） | 统计图；表格；可视化设计 | 🔠 | 使之与背景的区别满足原则5，突出要展示的数据 | III | 4 | 74 |
|4| 优先用直接标注而不是编号标注 | 可视化设计 | 🔠 | 缩短阅读标注的路径（图-编号-编号-标注），提高阅读效率，空间不足或数据过于复杂时除外 | III | 5 | 98 |
|5| 使用多个子图的组合布局时，应注意同一方向上使用范围一致的 scale  | 可视化设计 | 🔢 | 例如横向多个图并列时，y轴的范围应一致，否则y方向上单位长度表示的值不同，难以比较 | III | 5 | 103 |


## Appendix 1 - List of Source
I. Tufte, Edward R., 1942-. **The Visual Display of Quantitative Information**. Cheshire, Conn. :Graphics Press, 2001.

II. Tufte, Edward R., 1942- author. Envisioning Information. Cheshire, Connecticut :Graphics Press, 1990.

III. Tufte, Edward R., 1942-. Visual Explanations : Images and Quantities, Evidence and Narrative. Cheshire, Conn. :Graphics Press, 1997.

IV. Tufte, Edward R., 1942-. Beautiful Evidence. Cheshire, Conn. :Graphics Press, 2006.

V. Tufte, Edward R., 1942- author. Seeing with Fresh Eyes : Meaning, Space, Data, Truth. Cheshire, Connecticut :Graphics Press LLC, 2020.

## Appendix 2 - List of Reference Text

### For Principles

1. documenting the sources and characteristics of the data
2. insistently enforcing appropriate comparisons
3. demonstrating mechanisms of cause and effect; expressing those mechanisms quantitatively
4. recognizing the inherently multivariate nature of analytic problems, and inspecting and evaluating alternative explanations
5. Make all visual distinctions as subtle as possible, but still clear and effective
6. Good design should take into account how, when, and where the information is used. (more examples on P115)
7. Ideally, structures that organize information should be transparent, straightforward, obvious, natural, ordinary, conventional -- with no need for hesitation or questioning on the part of the reader.
   
### For Guidelines/Strategies

1. Choose an aspect ratio that centers the absolute values of the slopes of selected line segments on 45 degree
2. economists agree that graphics depicting money over a period time should show inflation-adjusted (constant) monetary units
3. Calming the grid down clarifies the imprisoned data, as in these cases (right and below) of statistical graphics, spreadsheet entries, and visual timetables.
4. a code connects image and label: image->number->number->noun or, reading the other direction, noun->number->number->image...Such codes prevent us from seeing each part and its name right together, an efficient merger which assists our memory. In short, codes obstruct parallelism; replacing codes with direct labels unifies the information. Codes and keys are sometimes necessary for highly complex data (geological field maps, for example), or when there are a great many scattered elements (the photograph of 146 astronomers on the next page)
5. a regrettable lack of parallelism in the vertical scales of death rates for men and women. Equal vertical distances represent different quantities, which make visual comparisons of slopes (rates of change) between the two graphs most difficult...




## Q&A

1. What's the difference between principles and strategies?
> Principles are fundamental concepts or beliefs that guide actions or behavior. Strategies, on the other hand, are specific plans or approaches for achieving a goal or objective. Principles are often enduring and consistent over time, while strategies are often more flexible and adaptable to changing conditions. (src: https://qr.ae/pyiU1bhttps://qr.ae/pyiU1b)
