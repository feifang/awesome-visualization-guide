# awesome-visualization-guide
🧾 A non-exhaustive and in-progress list of guidelines and principles on data visualization, adapted from the works of visualization gurus such as Edward Tufte. 整理收集数据可视化设计原则（根据 Edward Tufte 等大师的著作总结、归纳而成，持续添加中）

## Principles 原则
High-level 的设计原则

| ID | Principle | Topic | Type | Note | Source | Chapter | Page |
|--|--|--|--|--|--|--|--|
|1| 记录可视化数据的来源及特征  | 统计图；可视化设计；可视分析 | 🔠 | - | III | 1 | 53 |
|2| ⭐ 注重引导读者在阅读时进行比较  | 统计图；可视化设计；可视分析；Graphical Excellence | 🔠 | 亦提及于 (I \| 1 \| 13) | III | 2 | 53 |
|3| 在图表中展示因果关系（原因如何导致结果），最好使用量化的方式  | 统计图；可视化设计；可视分析 | 🔠 | - | III | 2 | 53 |
|4| 考虑问题自身的多个不同维度，尝试考虑不同的解释方法  | 统计图；可视化设计；可视分析 | 🔠 | - | III | 2 | 53 |
|5| 在保障图表清晰有效的前提下，尽可能减小各视觉元素的差异（从而提高信息容量）- the smallest effective difference  | 统计图；可视化设计 | 🔠 | - | III | 4 | 73 |
|6| 好的设计应该考虑数据的使用场景、时间和方式 | 统计图；可视化设计 | 🔠 | 例如需要随身携带的图表，需要考虑方便折叠使用 | III | 6 | 115 |
|7| 信息的组织形式最好是读者一眼就能看懂的 | 可视化设计 | 🔠 | 如果图表的组织复杂到需要画另一张阅读路线图来引导用户，就该反思一下了 | III | 7 | 125 |
|8| 在可视分析中，信息展示的原则应该基于数据分析的思路和原则，而非根据市场需要或技术潮流 | 可视化设计；可视分析| 🔠 | - | IV | 0 | 9 |
|9| 大数据量的可视化需要使用数据密度高的图表呈现（至少200个数/平方厘米）| 可视化设计；可视分析 | 🔢 | 该量化标准是2006年提出的，随着屏幕分辨率的发展，该标准应只增不减 | IV | 2 | 53 |
|10| 通过检查视觉主体是否传达了数据主要信息，可以识别设计中是否引入了的视觉阻碍 | 视觉效果；可视化设计| 🔠 | 例如，如果最突出的视觉元素是图表的边框，没有传达任何信息，则说明边框造成了视觉阻碍 | IV | 2 | 62 |
|11| 区分视觉层级，能有效容纳更多数据，同时做到主次分明，避免视觉混乱 | 统计图；可视化设计 | 🔠 | 例如，图表中不要所有线（边框底纹、数据折线等）的粗细都一样；用不同的颜色区分层级等 | IV | 3 | 77 |
|12| 在需要对比/比较的可视化中，视线范围内能展示的数据越多越好，以减轻视觉记忆的压力，提高比较的效率 | 可视化设计；可视分析 | 🔠 | 能放进一屏/一页最好放一起，避免滚动/翻页 | II | 2 | 50 |
|13| 避免视觉混乱的关键在于使用能高效展示复杂数据的方法，而非一味地减少所展示的数据 | 可视化设计 | 🔠 | 数据量大不是造成混乱的原因，不良的设计才是；解决方案参考原则11 | II | 3 | 53 |
|14| ⭐ 有效呈现数据（Show the data） | 可视化设计；Graphical Excellence | 🔠 | - | I | 1 | 13 |
|15| ⭐ 引导读者关注数据本身，而不是炫技 | 可视化设计；Graphical Excellence | 🔠 | - | I | 1 | 13 |
|16| ⭐ 诚实地表现数据，避免歪曲数据内容 | 可视化设计；Graphical Excellence | 🔠 | 亦提及于 (I \| 1 \| 51) | I | 1 | 13 |
|17| ⭐ 高效展示数据（用小空间展示大量数据） | 可视化设计；Graphical Excellence | 🔠 | - | I | 1 | 13 |
|18| ⭐ 提供从概览到细节的多个层级的数据（Overview + Detail） | 可视化设计；Graphical Excellence | 🔠 | - | I | 1 | 13 |
|19| ⭐ 具有明确的目标，例如描述现象、探索发现、作为装饰等 | 可视化设计；Graphical Excellence | 🔠 | - | I | 1 | 13 |
|20| ⭐ 深度整合数据集的统计和描述性信息 | 可视化设计；Graphical Excellence | 🔠 | - | I | 1 | 13 |
|21| 对于（小于20项的）小数据集，用表格展示通常比图表更好 | 可视化设计 | 🔢 | - | I | 2 | 56 |
|22| 适当的装饰可以突出主题，但不能为了装饰效果扭曲数据 | 可视化设计 | 🔠 | - | I | 2 | 59 |
|23| 图形元素的实际尺寸应该与其所表示的数值成比例 | Graphical Integrity; 可视化设计 | 🔠 | - | I | 2 | 77 |
|24| 应通过清晰、详尽的标注（labeling）来避免图表的误读和表达不明确的问题 | Graphical Integrity; 可视化设计 | 🔠 | - | I | 2 | 77 |
|25| 保持图表中设计的一致性 | Graphical Integrity; 可视化设计 | 🔠 | 主要指数据映射方面，例如同一个指标在同一个坐标轴上的度量（scale）应该一致 | I | 2 | 77 |
|26| 图表中用于表示数据的维度个数，不应超过数据实际维度（变量）的数量 | Graphical Integrity; 可视化设计 | 🔠 | 这里是一个比较严格的标准，主要是指不要用高维图形来表示低维数据，例如用面积（二维）表示一个数值型变量，否则容易形成夸大数据的视觉效果 | I | 2 | 77 |
|27| 应提供数据的上下文（context） | Graphical Integrity; 可视化设计 | 🔠 | 与原则18相关，通常出现在时序数据，不要只给出很短一段时间的数值变化，缺乏比较的情况下容易得出偏颇的结论 | I | 2 | 77 |


## Guidelines/Strategies 策略技巧
涉及具体图表类型、视觉元素、视觉效果或数据类型的技巧

| ID | Guideline | Topic | Type | Note | Source | Chapter | Page |
|--|--|--|--|--|--|--|--|
|1| 选择合适的图表长宽比，使折线的斜率（绝对值）集中在45度附近  | 折线图 | 🔢 | 因为此时斜率的差异是最易于分辨的 | III | 1 | 25 |
|2| 对于涉及金钱的时序图表，应展示经过通胀调整后（deflated）的数值  | 统计图；可视化设计；可视分析 | 🔢 | 亦提及于 (I \| 2 \| 77) | III | 3 | 70 |
|3| 弱化图表的网格、表格的边框（变浅、变细） | 统计图；表格；可视化设计 | 🔠 | 使之与背景的区别满足原则5，突出要展示的数据 | III | 4 | 74 |
|4| 优先用直接标注而不是编号标注 | 可视化设计 | 🔠 | 缩短阅读标注的路径（图-编号-编号-标注），提高阅读效率，空间不足或数据过于复杂时除外 | III | 5 | 98 |
|5| 使用多个子图的组合布局时，应注意同一方向上使用范围一致的 scale  | 可视化设计 | 🔢 | 例如横向多个图并列时，y轴的范围应一致，否则y方向上单位长度表示的值不同，难以比较 | III | 5 | 103 |
|6| Sparkline 的长宽比选择：先把高度设置为可容纳的最大高度，然后根据[策略1]调整宽度 | Sparkline；可视化设计 | 🔢 | - | IV | 2 | 60 |
|7| 对于密集的线条，应避免容易产生摩尔纹（moiré pattern）干扰的设计 | Sparkline；视觉效果；可视化设计 | 🔠 | 例如避免线条和背景空白的粗细相近，或线条与背景色的亮度（value）对比很大 | IV | 2 | 62 |
|8| Sparkline 的周围不宜使用抢眼的粗边框，以免主次颠倒 | Sparkline；视觉效果；色彩；可视化设计 | 🔠 | - | IV | 2 | 62 |
|9| Sparkline 的排布应参照文本排版原则 | Sparkline；可视化设计 | 🔠 | Sparkline 可视为文段中的“单词” | IV | 2 | 63 |
|10| 用于可视分析的关系图的最佳实践：注重因果关系；使用尽可能多种数据进行深入的分析；给节点和连线添加标注；使用高效的设计；保障可信度（Credibility） | 关系图；可视分析；可视化设计 | 🔠 | 这里的关系图指广义的包含节点和连线的图表，可以是网络关系图、树、层级关系图等 | IV | 3 | 78 |
|11| 表格边框设计最佳实践：能不用边框就不用；只有当列间距太小，列与列之间容易混淆时才使用边框竖线；使用较细、颜色较浅的边框线 | 表格；可视化设计 | 🔠 | 相关原则：No.11 | II | 3 | 55 |
|12| 用色面积：鲜艳明亮或对比强烈的颜色在大面积、相邻使用时容易造成视觉负担，而当被少量、分散地使用时，可以起到正面的突出作用 | 色彩；视觉效果；可视化设计 | 🔠 | 鲜艳（**饱和度/彩度高**）明亮（**亮度高**）或对比强烈（例如红蓝）的颜色应该避免大面积集中使用；这些颜色就像重音，如果通篇都是重音，不仅无法突出任何内容，还会令人不适 | II | 5 | 82 |
|13| 色彩明暗对比：避免不良的协同效应（_1+1=3 effect_, by Josef Albers） | 色彩；视觉效果；可视化设计 | 🔠 | 这里的 _1+1=3效应_ 是指当两个视觉元素靠近时，会产生视觉上的交互，“激活”两者之间的的区域，使原本无实意的区域成为视觉干扰（与**亮度对比强度**成正比）；例如，黑色图形间的白色带状背景会比较刺眼，可改为浅灰图形，弱化与白色背景的亮度对比；相关策略：No.7 | II | 3 | 61 |
|14| 相较于白色，使用偏灰偏暗（dull, muted, grayish or neutral）的背景颜色能使眼色鲜艳的图形和谐共处，避免视觉混乱（clutter） | 色彩；视觉效果；可视化设计 | 🔠 | 例如使用浅灰色背景，主要是降低色彩饱和度对比；常与策略12、13结合使用 | II | 3 | 58 |
|15| 可视化中使用颜色的基本原则是：至少不要造成损害 | 色彩；可视化设计 | 🔠 | - | II | 5 | 81 |
|16| 用于视觉编码的颜色不宜超过20种 | 色彩；可视化设计 | 🔢 | 虽然人眼能分辨上万种颜色，但受限于视觉记忆的容量 | II | 5 | 81 |
|17| 三原色（红黄蓝）以及黑色可以达到最大的区分度 | 色彩；可视化设计 | 🔠 | 没有哪四种颜色之间的差异可以更大 | II | 5 | 86 |
|18| 设计色板的技巧是从自然界取材，因为对人眼比较熟悉和协调，更容易达到一种和谐、舒服的效果 | 色彩；可视化设计 | 🔠 | 尤其是代表天空和光影的蓝色、黄色、灰色等柔和的颜色 | II | 5 | 90 |
|19| 在复杂的可视化中，为避免色彩间互相作用带来的影响，用颜色来表现某项数据时，最好用多一种视觉元素辅助 | 色彩；可视化设计 | 🔠 | 但也要注意保障清晰度，不过分冗余 | II | 5 | 92 |
|20| 由于红绿色盲人群的存在，不宜用红色和绿色来表示数据的关键差异 | 色彩；可视化设计 | 🔠 | - | II | 5 | 93 |
|21| 在时序可视化中加入空间数据，能有效提升表现力 | 时序可视化；可视化设计 | 🔠 | - | I | 1 | 40 |



注：以上原则/技巧经过部分微调，使之更贴切或更易于理解，参考依据原文详见附录。有多处参考内容涉及同一条原则/技巧的，将在附录中补充，不在表格中逐一记录。

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
10. A good way to assesss a display for unintentional optical clutter is to ask "Do the prominent visual effects convey relevant content?"
11. ... the classical design error of _equal line weight for all visual elements_ (IV | 3 | 77). Among the most powerful devices for reducing noise and enriching the content of displays is the technique of layering and separation, visually stratifying various aspects of the data (II | 3 | 53).
12. If the visual task is contrast, comparison, and choice -- as so often it is -- then the more relevant information within eyespan, the better. Vacant, low-density displays, the dreaded posterization of data spread over pages and pages, require viewers to rely on visual memory -- a weak skill -- to make a contrast, a comparison, a choice (II | 2 | 50). Comparisons must be enforced within the scope of the eyespan, a fundamental point occasionally forgotten in practice (II | 4 | 76). 
13. Confusion and clutter are failures of design, not attributes of information. And so the point is to find design strategies that reveal detail and complexity -- rather than fault the data for an excess of complication. Or, worse, to fault viewers for a lack of understanding.
14. Graphical displays should show the data; induce viewer to think about the substance rather than about methodology, graphic design, the technology of graphic production, or something else; avoid distorting what the data have to say; present many numbers in a small space; make large data sets coherent; encourage the eye to compare different pieces of data; reveal the data at several levels of detail, from a broad overview to the fine structure; serve a reasonably clear purpose: description, exploration, tabulation, or decoration; be closely integrated with the statistical and verbal descriptions of a data set.
15. (same as above)
16. (same as above); And graphical excellence requires telling the truth about the data. (I | 1 | 51)
17. (same as above)
18. (same as above)
19. (same as above)
20. (same as above)
21. Table usually outperform graphics in reporting on small data sets of 20 numbers or less.
22. Sometimes decoration can help editorialize about the substance of the graphic. But it is wrong to distort the data measures -- the ink locating values of numbers -- in order to make an editorial comment or fit a decorative scheme.
23. The representation of numbers, as physically measured on the surface of the graphic ifself, should be directly proportional to the numberical quantities represented.
24. Clear, detailed, and thorough labeling should be used to defeat graphical distortion and ambiguity. Write out explanations of the data on the graphic itself. Label important events in the data.
25. Show data variation, not design variation.
26. The number of information-carrying (variable) dimensions depicted should not exceed the number of dimensions in the data.
27. Graphics must not quote data out of context.

    
   
### For Guidelines/Strategies

1. Choose an aspect ratio that centers the absolute values of the slopes of selected line segments on 45 degree (III | 1 | 25); Variations in slopes are best detected when the slopes are around 45 degree（IV | 2 | P60)
2. economists agree that graphics depicting money over a period time should show inflation-adjusted (constant) monetary units; (III | 3 | 70) In time-series displays of money, deflated and standardized units of monetary measurement are nearly always better than nominal units. (I | 2 | 77)
3. Calming the grid down clarifies the imprisoned data, as in these cases (right and below) of statistical graphics, spreadsheet entries, and visual timetables.
4. a code connects image and label: image->number->number->noun or, reading the other direction, noun->number->number->image...Such codes prevent us from seeing each part and its name right together, an efficient merger which assists our memory. In short, codes obstruct parallelism; replacing codes with direct labels unifies the information. Codes and keys are sometimes necessary for highly complex data (geological field maps, for example), or when there are a great many scattered elements (the photograph of 146 astronomers on the next page)
5. a regrettable lack of parallelism in the vertical scales of death rates for men and women. Equal vertical distances represent different quantities, which make visual comparisons of slopes (rates of change) between the two graphs most difficult...
6. These considerations yield practical advice for choosing aspect ratios for sparklines: use the _maximum_ reasonable vertical space available under the word-like constraint, then adjust the horizontal strech of the time-scale to meet the lumpy criterion.
7. Closely spaced lines produce moiré vibration, usually at its worst when data-lines (the figure) and spaces (the ground) between data-lines are approximately equal in size, and also when figure and ground constrast strongly in color value.
8. Areas surrounding data-lines may generate unintentional optical clutter. Strong frames produce melodramatic but content-diminishing visual effects.
9. Just as sparklines are like _words_, so then distributions of sparklines on a page are like _sentences_ and _paragraphs_. The graphical idea here is make it _wordlike_ and _typographic_ -- an idea that leads to reasonable answers for most questions about sparkline arragements.
10. This practical, workday diagram demonstrates excellent analytical practices for displays that use links and arrows to tie nouns together: timelines, trees, networks, organization charts, project management charts, and the like. These practices are: _Focus on causality_ ..., _Multiple sources and levels of data_ ..., _Annotated linking lines_ ..., _Annotated nouns_ ..., _Efficiency of design_ ..., _Credibility_
11. The setting of tables, ... First, try to do without rules all together. They should be used only when they are necessary. Vertical rules are needed only when the space between columns is so narrow that mistakes will occur in reading without rules. Tables without vertical rules look better; thin rules are better than thick ones.
12. Pure, bright or very strong colors have loud, unbearable effects when they stand unrelieved over large areas adjacent to each other, but extraordinary effects can be achieved when they are used sparingly on or between **dull background tones**... If one limits strong, heavy, rich, and solid colors to small areas of extremes, then expressive and beautiful patterns occur. If one gives all, especially large areas, glaring, rich colors, the pictures have brilliant, disordered, confusing and unpleasant effects.
13. Visual activation of negative areas of white space in these exhibits illustrates _the endlessly contextual and interactive nature of visual elements_. This idea is captured in a fundamental principle of information design _1+1=3 or more_. In the simplest case, when we draw two black lines, a third visual activity results, a bright white path between the lines. And a complexity of marks generates an exponential complexity of negative shapes. _Most of the time, that surplus visual activity is non-information, noise, and clutter_. (II | 3 | 61); The noise of 1+1=3 is directly proportional to the contrast in **value (light/dark)** between figure and ground. On white backgrounds, therefore, a varying range of lighter colors will minimize incidental clutter (II | 3 | 62).
14. Shown against a dull background rather than bright white, these colors remain both calm and distinctive, avoiding clutter (II | 3 | 58); The placing of **light, bright colors** mixed with white next to each other usually produce unpleasant results, especially if the colors are used for large areas (II | 5 | 82); _color spots against a light gray or muted field highlight and italicize data, and also help to weave an overall harmony_ (II | 5 | 83); Large area background or base-colors should do their work most quietly, allowing the smaller, bright areas to stand out most vividly, if the former are muted, grayish or neutral (II | 5 | 90)
15. ... the first principle in bringing color to information: _Above all, do no harm_.
16. Some 20,000 colors are accessible to many viewers, with the constraints for practical applications set by the early limits of human visual memory rather than the capacity to discriminate locally among adjacent tints. For encoding abstract information, however, more than 20 or 30 colors frequently produce not diminishing but negative returns.
17. Use of the primary colors and black provides maximum differentiation (no four colors differ more).
18. What palette of colors should we choose to represent and illuminate information? A grand strategy is to _use colors found in nature_, especially those on the lighter side, such as blues, yellows, and grays of sky and shadow. Nature's colors are familiar and coherent, possessing a widely accepted harmony to the human eye -- and their source has a certain definitive authority. A palette of nature's colors help suppress production of garish and content-empty colorjunk.
19. These perceived color shifts, while an infrequent threat to accuracy of reading in day-to-day information design, are surprising and vivid -- suggesting that color differences should not be relied upon as the sole method for sending a message admist a mosaic of complex and variable data (II | 5 | 92). Redundant and partially overlapping methods of data representation can yield a sturdy design, responding in one way or another to potential visual complication -- with, however, a resulting danger of fussy, cluttered, insecure, committee-style design. A crystalline, lucid redundancy will do (II | 5 | 93).
20. Because of color-deficient vision, it is best to avoid making crucial data distinctions depend on the difference between red and green.
21. An especially effective device for enhancing the explanatory power of time-series displays is to add spatial dimensions to the design of the graphic, so that the data are moving over space (in two or three dimensions) as well as over time.

## Appendix 3 - Reading Materials 附录 3

**[The Science of Visual Data Communication: What Works](https://doi.org/10.1177/15291006211051956)**
> This report presents research-backed guidelines for creating powerful and intuitive visualizations oriented toward communicating data to students, coworkers, and the general public.

**[Dataviz Accessibility Resources](https://github.com/dataviza11y/resources)**
> A non-exhaustive and in-progress list of people and resources in Accessibility and Data Visualization

More: 
* [Principles of Graphical Excellence from E.R. Tufte](https://sphweb.bumc.bu.edu/otlt/mph-modules/bs/datapresentation/DataPresentation3.html) by Boston University School of Public Health


## Q&A

1. What's the difference between principles and strategies?
> Principles are fundamental concepts or beliefs that guide actions or behavior. Strategies, on the other hand, are specific plans or approaches for achieving a goal or objective. Principles are often enduring and consistent over time, while strategies are often more flexible and adaptable to changing conditions. (src: https://qr.ae/pyiU1bhttps://qr.ae/pyiU1b)
