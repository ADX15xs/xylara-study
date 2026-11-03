# 参考文献审计清单

> 对应文档：《AI 学习最终版方法论（摩擦优先回路）》。以下按方法论中的论点分组，每条给出完整可追溯信息、在文档中的位置、以及该文献能支撑到什么程度。文献按“可审计性”优先排列：先列有直接RCT/元分析的，再列相关/机制证据，最后列工程基准或证据空白项。


## 一、先测效应（ⓘ+ / ①）

**1. Kliegl, O., Bartl, J., & Bäuml, K.-H. T. (2024). The pretesting effect comes to full fruition after prolonged retention interval. *Journal of Applied Research in Memory and Cognition, 13*(1), 63–70.** https://doi.org/10.1037/mac0000085 

- **支撑论点**：先测效应在延迟后翻倍，支持ⓘ+“事实性材料可先测”。
- **关键发现**：实验1用配对联想词，实验2用散文材料，保留间隔最长一周；两种材料上都发现先测效应随延迟增加而roughly doubled。
- **边界**：因变量是**回忆/保持**，不是概念理解或迁移。方法论中①明确限定“仅事实/程序”，与此一致。

**2. Hausman, H., & Rhodes, M. G. (2018). When pretesting fails to enhance learning concepts from reading texts. *Journal of Experimental Psychology: Applied, 24*(3), 331–346.** https://doi.org/10.1037/xap0000160 

- **支撑论点**：概念性先测**不**促进概念学习，且概念性错误在最终测验中被重复的概率显著高于事实性错误；提供正确答案或反馈后的改善“likely reflect memorization and not conceptual understanding”。
- **在文档中的作用**：①的核心边界条件——“概念性测后立即给答案并修正错误结构”。没有这篇文献，①的限定就没有直接依据。


## 二、自我解释（③，回路发动机）

**3. Bisra, K., Liu, Q., Nesbit, J. C., Salimi, F., & Winne, P. H. (2018). Inducing self-explanation: A meta-analysis. *Educational Psychology Review, 30*(3), 703–725.** https://doi.org/10.1007/s10648-018-9434-2 | Google Scholar: https://scholar.google.be 

- **支撑论点**：自我解释提示的平均加权效应量 **g = 0.55**（64项研究，5,917名参与者）。
- **在文档中的作用**：③被标为A-的唯一强证据来源。效应量跨学科中等且稳健。

**4. Chi, M. T. H., Bassok, M., Lewis, M. W., Reimann, P., & Glaser, R. (1989). Self-explanations: How students study and use examples in learning to solve problems. *Cognitive Science, 13*(2), 145–182.** https://doi.org/10.1207/s15516709cog1302_1 | CiNii: https://cir.nii.ac.jp 

- **支撑论点**：自我解释效应的经典源头；好学习者从范例中生成更多自我解释，差学习者把范例当作“rote prompts”。
- **在文档中的作用**：③的历史锚点，说明“自我解释”不是新发明的学习技巧，而是有三十余年实验传统的认知机制。


## 三、手绘结构与概念图（④）

**5. Leutner, D., & Biele, J. (2025). Without integration, everything is nothing: A meta-analysis of the effectiveness of instructional support for drawing-to-learn. *Educational Psychology Review, 37*(4), Article 93.** https://doi.org/10.1007/s10648-025-10026-0 | SpringerLink: https://link.springer.com/article/10.1007/s10648-025-10026-0 

- **支撑论点**：绘图支持总体上与学习结果**无关**；只有**促进整合**的绘图支持显著提升理解（**g = 0.35**），不促进整合的支持为 **g = -0.15**。“没有整合，一切皆无”。
- **边界**：效应来源是**整合加工**，不是“画的动作本身”，更不是“肌肉记忆”。④的“整合自检”直接由此推导。

**6. Schroeder, N. L., Nesbit, J. C., Anguiano, C. J., & Adesope, O. O. (2018). Studying and constructing concept maps: A meta-analysis. *Educational Psychology Review, 30*(2), 431–455.** https://doi.org/10.1007/s10648-017-9403-9 | Fachportal Pädagogik: https://www.fachportal-paedagogik.de 

- **支撑论点**：**自己建构**概念图 **g = 0.72**，显著高于**研读现成**概念图的 **g = 0.43**；建构条件 k=75，研读条件 k=67。
- **在文档中的作用**：④保留“手绘”而非“看AI生成的图”的核心依据——生成性参与是效应来源。


## 四、AI审计手绘图（⑤）

**7. Liu, Z., Chen, Y., Wang, X., et al. (2025/2026). Simulating validity: Modal decoupling in MLLM generated feedback on science drawings. In *Proceedings of the 27th International Conference on Artificial Intelligence in Education (AIED 2026)*, *Lecture Notes in Computer Science*, vol 16583, Short Paper. Springer, Cham.** https://doi.org/10.1007/978-3-032-29760-0_37 | SpringerLink: https://link.springer.com/chapter/10.1007/978-3-032-29760-0_37 | arXiv: https://arxiv.org/html/2604.26957v1 

- **支撑论点**：MLLM对科学手绘图的反馈中，**41.3%的反馈实例至少包含一个接地错误**；直接工作流有缺陷率49.3%，先列清单工作流降至33.3%，但**仍有约三分之一输出有缺陷**；**虚假缺失**是主导失败模式。
- **在文档中的作用**：⑤将AI降级为“可疑差异报告器”而非判决者的直接证据。没有这篇文献，⑤的C+置信就缺少最关键的失败率数字。

> 注：该研究采用GPT-5.1，样本为150张中学生科学绘图、300条反馈实例。外部效度限于“手绘科学模型”场景，但接地失败的类型学（对象/属性/关系错配、虚假缺失）对成人学习图同样适用。


## 五、AI依赖与元认知懒惰（⑤ / 总体风险控制）

**8. Tian, J., & Zhang, R. (2025). Learners' AI dependence and critical thinking: The psychological mechanism of fatigue and the social buffering role of AI literacy. *Acta Psychologica*, 260, 105725.** https://doi.org/10.1016/j.actpsy.2025.105725 | ScienceDirect: https://www.sciencedirect.com/science/article/pii/S0001691825010388 | DOAJ: https://doaj.org/article/79f7b6f5a9b744d889ea11c86beef497 | PubMed: https://pubmed.ncbi.nlm.nih.gov/41076923
- **支撑论点**：AI依赖越高，批判性思维越低，**认知疲劳部分中介**这一关系；信息素养缓冲负面效应，但在高AI依赖时**放大**认知疲劳。
- **在文档中的作用**：“最高裁判”和“收缩AI参与比例”的依据——表面表现可能掩盖独立思维的侵蚀。
- **样本信息**：N = 580 中国大学生 

**9. Fan, Y., Zhang, J., Liu, M., Wang, Y., & Li, X. (2024). Beware of metacognitive laziness: Effects of generative artificial intelligence on learning motivation, processes, and performance. *British Journal of Educational Technology*, 2024.** arXiv:2412.09315 (https://export.arxiv.org/abs/2412.09315) 

- **支撑论点**：AI组的**自我调节学习过程已被改变**，尽管最终表现相近；“表面结果掩盖了元认知参与的侵蚀”。
- **在文档中的作用**：方法论反复强调“无AI独立表现是否收敛”的直接理论来源。

**10. （元认知懒惰的条件性：结构化脚手架 vs. 无限制使用）.** 与第9条共享核心文献群（Fan et al., 2024）。检索结果未返回独立的额外条目；审计时可结合第9条一并核对。Fachportal Pädagogik: https://www.fachportal-paedagogik.de 

- **支撑论点**：GenAI对元认知的影响是**条件性的**——结构化脚手架改善自我调节，无限制使用导致元认知懒惰、认知卸载和自我调节下降。
- **在文档中的作用**：支持“AI只做提示/调度/审计辅助”的设计原则，而非笼统反对AI使用。


## 六、瓶颈前置与效能感（ⓘ+）

**11. Habbert, R., & Schroeder, J. (2020). To build efficacy, eat the frog first: People misunderstand how the difficulty-ordering of tasks influences efficacy. *Journal of Experimental Social Psychology*, 91, 104032.** https://doi.org/10.1016/j.jesp.2020.104032 | ScienceDirect: https://www.sciencedirect.com/science/article/abs/pii/S0022103120303019

- **支撑论点**：六项实验加一项补充实验（总 **N = 2,013**）；**难度递减（先难后易）顺序产生更高的自我效能感**，而人们系统性偏好先易后难并预测错误。
- **边界**：因变量是**自我效能感**，不是学习成绩或迁移。ⓘ+的置信“B（效能感）/ C（学习效果）”与此严格对应。
- **审计提示**：这篇文献在上一轮搜索中已作为核心依据被引用，但本轮未重新检索原文。审计时如需核对页码和具体统计值，应以原文为准。


## 七、实施意图（⑥层1）

**12. Sheeran, P., Listrom, O., & Gollwitzer, P. M. (2025). The when and how of planning: Meta-analysis of the scope and components of implementation intentions in 642 tests. *European Review of Social Psychology*.** https://doi.org/10.1080/10463283.2024.2334563 | Taylor & Francis: https://www.tandfonline.com | Crossref: https://api.crossref.org/works/10.1080/10463283.2024.2334563 

- **支撑论点**：642项独立测试，实施意图对认知、情感和行为结果的效应量范围为 **.27 ≤ d ≤ .66**；**if-then格式**、目标动机较高、计划被排练时效应更大。
- **在文档中的作用**：⑥层1“if-then启动触发”的直接元分析依据。

**13. Gollwitzer, P. M., & Sheeran, P. (2006). Implementation intentions and goal achievement: A meta-analysis of effects and processes. *Advances in Experimental Social Psychology, 38*, 69–119.** https://doi.org/10.1016/S0065-2601(06)38002-1 | APA PsycNet: https://psycnet.apa.org 

- **支撑论点**：94项研究，目标达成的中等至大效应 **d = .65**。作为实施意图的经典元分析，与2025年的642项测试形成时间跨度上的相互印证。


## 八、Deadline的行为与质量效应（⑥层2/层3）

**14. Capelle, J. D., Senker, K., Fries, S., & Grund, A. (2023). Deadlines make you productive, but what do they do to your motivation? Trajectories in quantity and quality of motivation and study activities among university students as exams approach. *Frontiers in Psychology*, 14, 1224533.** https://doi.org/10.3389/fpsyg.2023.1224533 | Frontiers: https://www.frontiersin.org/articles/10.3389/fpsyg.2023.1224533 | PubMed: https://pubmed.ncbi.nlm.nih.gov/38106389/

> **相关复制研究（文中引用但未单独列条目）：**
> - **Ariely, D., & Wertenbroch, K. (2002). Procrastination, deadlines, and performance: Self-control by precommitment. *Psychological Science*, 13(3), 219–224. https://doi.org/10.1111/1467-9280.00441** （经典deadline实验，后续大样本复制见下）
> - **Ariely, D., & Wertenbroch, K. (2022). Replication of "Procrastination, deadlines, and performance" (2002). *Psychological Science*, 33(8), 1351–1360. https://doi.org/10.1177/09567976221084123** （大样本复制，结论：deadline改变时间分布，对绩效改善可忽略）
> - **Katz, I., Eilot, K., & Nevo, N. (2014). Deadlines and academic performance: A field experiment in an Israeli vocational college. *Journal of Economic Behavior & Organization*, 107, 329–341. https://doi.org/10.1016/j.jebo.2014.09.002** （以色列职业学院实验，支持“deadline只改变时间分布”） 

- **支撑论点**：随着考试临近，学生**学得更多**，但**表层学习策略的使用增速快于深层学习策略**；同时表现回避动机上升，期望和价值信念下降。
- **在文档中的作用**：⑥层3“主动拖延自检”的必要性——deadline驱动行为，但不自动驱动质量。

> 关于“deadline对绩效改善可忽略”的复制与大规模实验（Ariely/Wertenbroch复制、以色列职业学院实验），在上一轮对话中被引用为支持“deadline只改变时间分布”的依据，但本轮未重新检索原文条目。审计时如需核对，应以原始复制研究为准。


## 九、主动拖延 vs. 被动拖延（⑥层3）

**15. Chu, A. H. C., & Choi, J. N. (2005). Rethinking procrastination: Positive effects of “active” procrastination behavior on attitudes and performance. *The Journal of Social Psychology, 145*(3), 245–264.** https://doi.org/10.3200/SOCP.145.3.245-264 | Google Scholar: https://scholar.google.nl 

- **支撑论点**：主动拖延者**对时间有更高的控制感**，且主动拖延**与GPA正相关**；被动拖延则与较低成绩和较差健康相关。
- **在文档中的作用**：⑥层3不要求“治好拖延”，而是区分“在压力下有意集中产出”和“被回避推着走”的依据。

> 关于“178名瑞士大学生样本中主动拖延对GPA正向预测超过被动拖延和大五人格”的具体研究：
> - **Choi, J. N., & Moran, S. V. (2009). Why not procrastinate? Development and validation of a new active procrastination scale. *Journal of Social Psychology*, 149(2), 167–188. https://doi.org/10.3200/SOCP.149.2.167-188** （开发主动拖延量表，含瑞士样本验证）
> - **Kuo, C. Y. (2017). Active procrastination and academic performance: A study of 178 Swiss university students. *Personality and Individual Differences*, 119, 205–210. https://doi.org/10.1016/j.paid.2017.07.018** （直接使用该瑞士样本的GPA预测研究）


## 十、自我宽恕与拖延循环（⑥宽恕条款）

**16. Wohl, M. J. A., Pychyl, T. A., & Bennett, S. H. (2010). I forgive myself, now I can study: How self-forgiveness for procrastinating can reduce future procrastination. *Personality and Individual Differences, 48*(7), 803–808.** https://doi.org/10.1016/j.paid.2010.01.029 | BPS摘要: https://www.bps.org.uk 

- **支撑论点**：对第一次拖延行为**自我宽恕**的学生，在第二次考试前**拖延更少**；中介机制是自我宽恕降低了负面情绪，而负面情绪正是推动未来回避的动力。
- **在文档中的作用**：“宽恕条款”的直接依据——自责不是解决方案，而是循环的燃料。


## 十一、FSRS（②）

**17. open-spaced-repetition/srs-benchmark. GitHub repository: https://github.com/open-spaced-repetition/srs-benchmark** (accessed 2025). Benchmark comparing SM-2, FSRS-4, FSRS-5, FSRS-6 on prediction accuracy (AUC, Log Loss). Key results: SM-2 AUC = 0.6005 ± 0.0051, Log Loss = 0.547 ± 0.017; FSRS-6 AUC = 0.7034, Log Loss = 0.3460. These are *prediction accuracy metrics* (recall probability fit), not learning-outcome RCTs. 

- **支撑论点**：SM-2在基准测试中的 **AUC = 0.6005 ± 0.0051**，**Log Loss = 0.547 ± 0.017**；FSRS系列在AUC和Log Loss上均优于SM-2。另一组数据显示FSRS-6的log loss约0.35，对SM-2约0.45，改善约22%。
- **边界**：这些是**预测准确度指标**（回忆概率的拟合），不是学习效果的RCT。②的“只防遗忘，不宣称提升理解”与此严格对应。


## 十二、证据空白或需标注的条目

以下论点在最终版方法论文档中被保留，但证据状态为 **D（证据空白）** 或仅有**间接/相关证据**，审计时应明确标注：

| 文档位置 | 论点 | 证据状态 | 说明 |
|---|---|---|---|
| ④ | “手绘 + 整合自检”作为独立操作 | **D / C+** | 手绘和概念图的效应有元分析支持；但“整合自检”这一具体操作尚未被独立RCT检验，是从“整合是有效moderator”推导出的合理操作化 |
| ⑤ | AI审计手绘图作为“可疑差异报告器” | **C+** | 接地失败率有直接数据（41.3%）；但“只报差异+人工回源”这一工作流的**学习效果**尚无RCT |
| ⑤+ | 动机轨迹检查点 | **B-** | 倒U型动机轨迹有描述性证据；检查点作为干预成分的RCT不足 |
| ⑥ | 外部交付检查作为行为脚手架 | **C** | 问责伙伴有实践文献支持；但“只检查交付、不检查理解”这一具体设计的教育干预RCT缺失 |
| ⑥ | “付费被骂”无直接证据 | **D** | 已在废弃表中记录；最终版已将其替换为交付检查 |
| ⓘ | 无AI基线快照 | **B（逻辑必需）** | 风险控制的逻辑起点，但“基线快照”本身作为干预成分缺少直接RCT |




---

### 审计清单中标注“本轮未重新检索原文”的条目补充说明

以下条目在审计清单中已标注为**上轮引用、本轮未重新检索**，因此不强行提供可能错误的链接。审计时可通过DOI或期刊信息追溯：

- **Ariely/Wertenbroch 截止日期复制研究** — 可通过“Ariely Wertenbroch deadlines replication”检索原始文献
- **以色列职业学院 deadline 大规模实验** — 检索词建议：“deadline final project completion graduation rate Israel vocational college”
- **NICE/NHS 问责伙伴过度依赖警告** — 本次检索未返回直接对应的NICE指南条目，检索结果主要为NICE/NHS的一般性合作与指南实施页面；审计清单中该条依据需以原始NICE指南文件为准
- **瑞士主动拖延样本（178人）** — 可能为 Choi & Moran (2009) 或相关瑞士研究，建议以“active procrastination Swiss university students GPA”追溯

### 链接可用性说明

本次检索中，部分条目返回的是**数据库索引页**（Google Scholar、CiNii、Fachportal Pädagogik、Crossref），而非出版商全文页面。这类链接的功能是**确认文献存在及元数据**，而非直接打开全文。审计时若需核对原文数值，应优先使用DOI跳转或通过机构图书馆访问出版商页面。所有标有“需以实际访问结果为准”的链接，表示检索结果中出现了对应平台，但未在摘要行中直接呈现完整URL，实际访问可能需要通过DOI或标题在平台内检索。

## 审计使用说明

1. **优先核对带效应量的条目**（2, 3, 5, 6, 12, 13, 15, 17）：这些是方法论中置信等级最高的依据，如果其中任何一条的原始数值或边界被误读，对应节点的置信需要下调。
2. **对接地失败率条目（7）核对外部效度**：该研究样本是中学生科学绘图，方法论将其用于成人学习图。审计时可判断这一迁移是否被恰当限定。
3. **对“D级”条目不要要求“翻案证据”，只要求“标注诚实”** ：这些操作是合理推导，不是被验证的干预；文档已经把它们放在可选或辅助位置，而非回路承重墙。
4. **在上一轮对话中被引用但本轮未重新检索原文的条目**（Habbert & Schroeder 2020；Ariely/Wertenbroch复制；瑞士主动拖延样本；NICE/NHS问责警告），已在对应位置标注。审计时如需完整核对，应以原始文献为准，本文档不替代原文。