# awesome-visualization-guide
🧾 A list of recommended guidelines and principles on data visualization, adapted from the works of visualization gurus such as Edward Tufte. 整理收集数据可视化设计原则（根据 Edward Tufte 等大师的著作总结、归纳而成，持续添加中）

## Principles 原则
High-level 的设计原则

| ID | Principle | Topic | Type | Note | Source | Chapter | Page |
|--|--|--|--|--|--|--|--|
|1| 记录可视化数据的来源及特征  | 统计图；可视化设计；可视分析 | 🔠 | - | III | 1 | 53 |
|2| 注重引导读者在阅读时进行比较  | 统计图；可视化设计；可视分析 | 🔠 | - | III | 2 | 53 |
|3| 在图表中展示因果机制（原因如何导致结果），最好使用量化的方式  | 统计图；可视化设计；可视分析 | 🔠 | - | III | 2 | 53 |
|4| 考虑问题自身的多个不同维度，尝试考虑不同的解释方法  | 统计图；可视化设计；可视分析 | 🔠 | - | III | 2 | 53 |
|5| 在保障图表清晰有效的前提下，尽可能减小各视觉元素的差异（从而提高信息容量）- the smallest effective difference  | 统计图；可视化设计 | 🔠 | - | III | 4 | 73 |
|6| 好的设计应该考虑数据的使用场景、时间和方式 | 统计图；可视化设计 | 🔠 | 例如需要随身携带的图表，需要考虑方便折叠使用 | III | 6 | 115 |
|7| 信息的组织形式最好是读者一眼就能看懂的 | 可视化设计 | 🔠 | 如果图表的组织复杂到需要画另一张阅读路线图来引导用户，就该反思一下了 | III | 7 | 125 |
|8| 在可视分析中，信息展示的原则应该基于数据分析的思路和原则，而非根据市场需要或技术潮流 | 可视化设计；可视分析| 🔠 | - | IV | 0 | 9 |
|9| 大数据量的可视化需要使用数据密度高的图表呈现（至少200个数/平方厘米）| 可视化设计；可视分析 | 🔢 | 该量化标准是2006年提出的，随着屏幕分辨率的发展，该标准应只增不减 | IV | 2 | 53 |


注：以上原则经过部分微调，使之更贴切或更易于理解，参考依据原文详见附录

## Guidelines/Strategies 策略技巧
涉及具体图表类型、视觉元素、视觉效果或数据类型的技巧

| ID | Guideline | Topic | Type | Note | Source | Chapter | Page |
|--|--|--|--|--|--|--|--|
|1| 选择合适的图表长宽比，使折线的斜率（绝对值）集中在45度附近  | 折线图 | 🔢 | 因为此时斜率的差异是最易于分辨的（IV-Ch2-P60） | III | 1 | 25 |
|2| 对于涉及金钱的时序图表，应展示经过通胀调整后的数值  | 统计图；可视化设计；可视分析 | 🔢 | - | III | 3 | 70 |
|3| 弱化图表的网格、表格的边框（变浅、变细） | 统计图；表格；可视化设计 | 🔠 | 使之与背景的区别满足原则5，突出要展示的数据 | III | 4 | 74 |
|4| 优先用直接标注而不是编号标注 | 可视化设计 | 🔠 | 缩短阅读标注的路径（图-编号-编号-标注），提高阅读效率，空间不足或数据过于复杂时除外 | III | 5 | 98 |
|5| 使用多个子图的组合布局时，应注意同一方向上使用范围一致的 scale  | 可视化设计 | 🔢 | 例如横向多个图并列时，y轴的范围应一致，否则y方向上单位长度表示的值不同，难以比较 | III | 5 | 103 |
|6| Sparkline 的长宽比选择：先把高度设置为可容纳的最大高度，然后根据[策略1]调整宽度 | Sparkline；可视化设计 | 🔢 | - | IV | 2 | 60 |
|7| 对于密集的线条，应避免容易产生摩尔纹（moiré pattern）干扰的设计 | Sparkline；视觉效果；可视化设计 | 🔠 | 例如线条和背景空白的粗细相近，或线条与背景色的亮度对比很大 | IV | 2 | 62 |

注：以上技巧经过部分微调，使之更贴切或更易于理解，参考依据原文详见附录

## Appendix 1 - List of Source 附录 1
上述原则及技巧的相关参考依据出处

I. Tufte, Edward R., 1942-. **The Visual Display of Quantitative Information**. Cheshire, Conn. :Graphics Press, 2001.

II. Tufte, Edward R., 1942- author. Envisioning Information. Cheshire, Connecticut :Graphics Press, 1990.

III. Tufte, Edward R., 1942-. Visual Explanations : Images and Quantities, Evidence and Narrative. Cheshire, Conn. :Graphics Press, 1997.

IV. Tufte, Edward R., 1942-. Beautiful Evidence. Cheshire, Conn. :Graphics Press, 2006.

V. Tufte, Edward R., 1942- author. Seeing with Fresh Eyes : Meaning, Space, Data, Truth. Cheshire, Connecticut :Graphics Press LLC, 2020.

## Appendix 2 - List of Reference Text 附录 2
上述原则及技巧的相关参考依据详情原文（篇幅所限，仅截取关键内容，可根据上表中页码自行查看上下文）

### For Principles

1. documenting the sources and characteristics of the data
2. insistently enforcing appropriate comparisons
3. demonstrating mechanisms of cause and effect; expressing those mechanisms quantitatively
4. recognizing the inherently multivariate nature of analytic problems, and inspecting and evaluating alternative explanations
5. Make all visual distinctions as subtle as possible, but still clear and effective
6. Good design should take into account how, when, and where the information is used. (more examples on P115)
7. Ideally, structures that organize information should be transparent, straightforward, obvious, natural, ordinary, conventional -- with no need for hesitation or questioning on the part of the reader.
8. the principles of edvidence display are derived from the universal principles of analytical thinking -- and not from local customs, intellectual fashions, consumer convenience, marketing, or what the technologies of display happen to make available. The metaphore for evidence presentations is analytical thinking.
9. High-resolution graphics (200 numbers per square centimiter, or 1200 per square inch) help describe, present, and understand really big data sets. By 2006, the median data-graphic published in Nature and Science presented > 1000 numbers.
   
### For Guidelines/Strategies

1. Choose an aspect ratio that centers the absolute values of the slopes of selected line segments on 45 degree
2. economists agree that graphics depicting money over a period time should show inflation-adjusted (constant) monetary units
3. Calming the grid down clarifies the imprisoned data, as in these cases (right and below) of statistical graphics, spreadsheet entries, and visual timetables.
4. a code connects image and label: image->number->number->noun or, reading the other direction, noun->number->number->image...Such codes prevent us from seeing each part and its name right together, an efficient merger which assists our memory. In short, codes obstruct parallelism; replacing codes with direct labels unifies the information. Codes and keys are sometimes necessary for highly complex data (geological field maps, for example), or when there are a great many scattered elements (the photograph of 146 astronomers on the next page)
5. a regrettable lack of parallelism in the vertical scales of death rates for men and women. Equal vertical distances represent different quantities, which make visual comparisons of slopes (rates of change) between the two graphs most difficult...
6. These considerations yield practical advice for choosing aspect ratios for sparklines: use the _maximum_ reasonable vertical space available under the word-like constraint, then adjust the horizontal strech of the time-scale to meet the lumpy criterion.
7. Closely spaced lines produce moiré vibration, usually at its worst when data-lines (the figure) and spaces (the ground) between data-lines are approximately equal in size, and also when figure and ground constrast strongly in color value.

## Appendix 3 - Reading Materials 附录 3
* [Principles of Graphical Excellence from E.R. Tufte](https://sphweb.bumc.bu.edu/otlt/mph-modules/bs/datapresentation/DataPresentation3.html) by Boston University School of Public Health


## Q&A

1. What's the difference between principles and strategies?
> Principles are fundamental concepts or beliefs that guide actions or behavior. Strategies, on the other hand, are specific plans or approaches for achieving a goal or objective. Principles are often enduring and consistent over time, while strategies are often more flexible and adaptable to changing conditions. (src: https://qr.ae/pyiU1bhttps://qr.ae/pyiU1b)
