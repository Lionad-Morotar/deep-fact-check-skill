# 深度事实核查报告："Promises are cheap" by Gary Marcus

## 执行摘要

**元数据**：
- 原文作者：Gary Marcus (纽约大学心理学与神经科学荣誉教授，AI 评论家)
- 发布时间：2026年2月12日
- 核查时间：2026年2月13日
- 核查范围：全文核心事实主张

**可信度评级**：🟡 **B级 - 部分可信，需补充语境**

**核心结论**：
本文在经验事实层面（L1）基本准确，但在解释性框架（L2）和归因层面存在选择性呈现。作者作为知名的 AI 怀疑论者，系统性强调了 AI 技术的局限性，而对行业进步保持沉默。这种偏见并未通过捏造事实实现，而是通过**选择性报道**和**竞争性框架忽略**完成。

---

## 详细发现

### ✅ 准确属实（L1 经验事实）

#### 1. 律师 LLM 幻觉案例增长（112→914）
**原文**：
> "When I wrote about them less than a year ago there were 112 documented cases with lawyers who got called out in Damien Charlotin's database; now there are 914. That's 8x growth in less than 12 months!"

**验证结果**：✅ **已证实**

**证据链**：
- Damien Charlotin 的数据库确实存在，网址为 damiencharlotin.com/hallucinations [T1]
- Gary Marcus 确实在约一年前（2025年5月左右）的文章《AI literacy, hallucinations, and the law: A case study》中提到："In all, Charlotin's database lists 112 cases" [T1 - 原文作者自己的历史文章]
- 截至 2026年2月，数据库显示有 **914 个案例** [T1 - 实时数据]
- 数学验证：914 ÷ 112 ≈ 8.16，确实约为 8 倍增长

**时间线验证**：
- 112 案例文章发布时间：约 2025年5月
- 当前文章发布时间：2026年2月12日
- 时间跨度：约 9-10 个月，符合"less than a year"

---

#### 2. Remote Labor Index 2.5% 数据
**原文**：
> "according to December's Remote Labor Index, only 2.5% of human 'online tasks' (physical tasks were excluded) could be done by AI."

**验证结果**：✅ **已证实**

**证据链**：
- Remote Labor Index (RLI) 由非营利组织 Center for AI Safety (CAIS) 和 Scale AI 联合发布 [T2]
- 研究发表于 2025年12月（"December's Remote Labor Index"） [T2]
- 测试方法：240 个真实远程工作项目，涵盖 23 个领域 [T2]
- 最佳表现者 **Manus AI** 完成了 **2.5%** 的任务 [T2 - 多个独立报道交叉验证]
- 其他模型表现：Grok 4 和 Claude Sonnet 4.5 为 2.1%，GPT-5 为 1.7%，Gemini 2.5 Pro 为 0.8% [T2]

**重要语境补充**：
该测试评估的是 AI 完成**整个项目**的能力（end-to-end），而非单个任务辅助。Gary Marcus 的表述"online tasks"在原文中可能让人误解为单个任务，但 RLI 实际测量的是完整项目自动化率。这种措辞虽非错误，但属于**框架选择**——强调 AI 无法替代完整工作流，而非 AI 可辅助的具体任务比例。

---

#### 3. Geoff Hinton 放射科医生预言
**原文**：
> "A decade ago, Geoff Hinton, then working for Google, said 'We should stop training radiologists now. It's just completely obvious that within five years, deep learning is going to do better than radiologists.' (In fact, the number of radiologists keeps growing, and in some communities there is a shortage.)"

**验证结果**：✅ **已证实**

**证据链**：
- 引语来源：Geoff Hinton 在 2016年（约十年前）的公开演讲/采访 [T1 - 多个独立来源交叉验证]
- 完整引语："People should stop training radiologists now. It's just completely obvious that within five years deep learning is going to do better than radiologists... It might be ten years, but we've got plenty of radiologists already." [T1]
- 当时 Hinton 确实在 Google 工作（2013-2023年） [T1]
- 放射科医生现状：
  - 2025年美国诊断放射科住院医师项目提供 **1,208 个职位**，比 2024 年增长 4% [T2]
  - 放射科医生平均收入 $520,000，是美国第二高薪医疗专业 [T2]
  - 美国劳工统计局预测 2024-2034 年放射科就业增长 **5%**，高于所有职业平均 3% [T2]
  - 部分社区确实存在放射科医生短缺 [T1, T2]

**Hinton 后续回应**：
Hinton 在 2025年通过邮件向《纽约时报》承认，他 2016 年的评论"spoken too broadly"（说得过于宽泛） [T2]。这是一个重要的**时间线更新**，原文未提及 Hinton 的反思，可能让读者误以为他坚持原观点。

---

#### 4. 特斯拉市盈率近400倍
**原文**：
> "Tesla trades at nearly 400 times earnings not because they have ever made all that much money, but because Elon is a master of hype."

**验证结果**：✅ **已证实**

**证据链**：
- 2026年2月，特斯拉市盈率确实达到约 **400 倍** [T1 - MarketBeat, MacroTrends, Public.com 等多源交叉验证]
- 具体数据：
  - MacroTrends: 389.34（2026年2月12日） [T1]
  - Public.com: 398.02（2026年2月11日） [T1]
  - Stock Analysis: 412.00（2025年12月31日） [T1]
- 历史对比：特斯拉 5 年平均市盈率约 185 倍，10 年平均约 176 倍 [T1]
- 行业对比：福特汽车约 11-12 倍，通用汽车约 12-24 倍 [T1]

**解释性说明**：
原文将高市盈率归因于"Elon is a master of hype"（炒作大师），这是一个**解释性论断**（L2 层级），非可验证的事实。高市盈率可能反映多种因素：对未来增长的高预期、自动驾驶和 AI 业务的估值、电动车市场地位等。将此单一归因于"炒作"是**竞争性框架选择**——它忽略了其他同样合理的解释框架。

---

#### 5. Caltech 和 Stanford 的 LLM 推理研究
**原文**：
> "who has the kind of pervasive troubles with reasoning that researchers at Caltech and Stanford just documented"

**验证结果**：✅ **已证实**

**证据链**：
- 论文标题：《Large Language Model Reasoning Failures》 [T1 - arXiv]
- 发表时间：2026年2月9日（"just documented"） [T1]
- 作者机构：California Institute of Technology (Caltech) 和 Stanford University [T1]
- 第一作者：Peiyang Song (Caltech) [T1]
- 内容：系统性分类和分析了 LLM 在推理中的各类失败，包括：
  - 认知偏见（confirmation bias, anchoring bias, framing effects）
  - 逻辑推理失败（reversal curse, compositional reasoning）
  - 数学和算术限制
  - 物理常识推理缺陷 [T1]

**时间线验证**：
论文发表于 2026年2月9日，Gary Marcus 的文章发表于 2月12日，确实是非常近期的研究，"just documented"表述准确。

---

### ⚠️ 解释性框架争议（L2 层级）

#### Kevin Scott "blow away PhDs" 引语
**原文**：
> "Suleyman's colleague Kevin Scott hinted that GPT-5 would blow away PhDs, and be vastly better than GPT-4"

**验证结果**：🟡 **无法找到确切出处**

**搜索过程**：
- 对 Kevin Scott（Microsoft CTO）的公开演讲、博客、采访进行搜索 [T2]
- 找到了他 2022年对 AI 的乐观预测、对 GitHub Copilot 的评论、对 scaling laws 的讨论 [T2]
- **未找到**他直接说 GPT-5 会 "blow away PhDs" 的确切引语
- 他确实在 2022 年说过："you don't need to have a PhD in computer science anymore to build an AI application"（不再需要博士学位就能构建 AI 应用），但这是关于**民主化 AI 开发**，而非 GPT-5 能力的描述 [T2]

**竞争性解释框架**：
- **框架 A（原文）**：Kevin Scott 做出了过度承诺，GPT-5 将远超博士水平
- **框架 B（替代）**：引语可能被**断章取义**或**转述变形**，原意是关于 AI 降低技术门槛
- **框架 C（替代）**：引语可能来自非公开场合（内部会议、非正式谈话），无法验证

**评估**：
由于无法找到 "blow away PhDs" 的原始出处，这一主张的置信度降低。Gary Marcus 作为批评者，可能使用了二手转述或内部信息。建议标记为**无法独立核实**（TX 信源等级）。

---

### 🔍 信息操控手法识别

#### 1. 选择性报道（Cherry Picking）
**检测**：
- 原文系统性强调 AI 的失败案例（幻觉、推理错误、预测失败）
- 原文完全**忽略** AI 的实际进展：
  - 未提及 GPT-4 在医学考试、律师考试中的通过表现
  - 未提及 AI 在蛋白质折叠（AlphaFold）、材料科学等领域的突破
  - 未提及放射科医生使用 AI 作为辅助工具提高效率的正面案例

**沉默的证据**：
- FDA 已批准 **1,041 个** AI 赋能的放射科医疗设备 [T2]
- 放射科医生使用 AI 后，阅片时间缩短，处理能力提升 27-98% [T2]
- AI 未取代放射科医生，而是改变了他们的工作方式（从单纯阅片转向更多沟通和决策支持）

**认知原理**：
利用**确认偏误**，读者倾向于接受符合"AI 被过度炒作"预设的信息，不察觉遗漏的正面进展。

---

#### 2. 框架效应（Framing Effect）
**原文框架**：AI 行业是"炒作"（hype），高管们在做"廉价承诺"（cheap promises），类似 Elon Musk 的"画饼"

**竞争性框架**：
| 原文框架 | 竞争性框架 A | 竞争性框架 B |
|---------|------------|------------|
| 炒作与欺骗 | 技术发展的正常预期管理 | 转型期的投资驱动策略 |
| 承诺不会兑现 | 部分承诺会兑现，部分不会 | 承诺是方向性指引，非精确预测 |
| 媒体被操纵 | 媒体在平衡报道不同观点 | 公众对技术进步有信息需求 |

**评估**：
原文选择最悲观的框架，未呈现其他同样合理的解释框架。这属于**观点表达**（L3 价值判断），非事实错误，但限制了读者的认知范围。

---

#### 3. 归因简化（Attribution Oversimplification）
**原文归因**：
> "Tesla trades at nearly 400 times earnings not because they have ever made all that much money, but because Elon is a master of hype."

**竞争性归因**：
特斯拉高市盈率可能由多种因素共同导致：
- 自动驾驶技术的未来潜力估值
- 人形机器人 Optimus 的预期
- 能源业务的增长
- 品牌溢价和市场地位
- 确实包含 Elon Musk 个人影响力的"马斯克溢价"

**评估**：
将复杂现象单一归因于"炒作"，忽略了其他合理的财务和市场因素。这是一种**因果简化**（Causal Oversimplification）。

---

## 作者偏见分析

**预设立场检测**：
- Gary Marcus 是知名的 **AI 怀疑论者**和深度学习批评者
- 他主张"混合架构"（hybrid AI），反对纯神经网络路径
- 历史上多次批评 AI 行业的过度承诺

**立场一致性**：
本文立场与既往立场一致性：**高**（9/10）

**选择性模式**：
| 系统性强调 | 系统性忽略 |
|-----------|-----------|
| AI 失败案例 | AI 实际应用成功 |
| 预测错误 | 预测正确（如 GPT-4 的能力提升） |
| 财务风险 | 技术突破（科学发现、医疗应用） |
| 高管利益冲突 | AI 对社会的实际贡献 |

**语言分析**：
- 负面词汇密度：**高**（"hype", "cheap", "collapses", "careless"）
- 讽刺语气："Nope", "Back on planet earth", "master of hype"
- 绝对化表述："promises are cheap", "costs them nothing"

**客观性评分**：5/10  
（承认核心事实准确，但选择性呈现；有明确观点，但未充分透明标注）

---

## 证伪条件与更新协议

**本报告的脆弱性**：

以下新证据将改变本报告的结论：

1. **如果** Kevin Scott 确实在公开场合说过 GPT-5 会 "blow away PhDs" → 修正该引语的可信度评级为 ✅
2. **如果** Damien Charlotin 数据库案例数被证实有显著统计误差 → 修正 112→914 的增长评估
3. **如果** Remote Labor Index 的方法论被学界广泛质疑 → 修正 2.5% 数据的可靠性评级
4. **如果** Mustafa Suleyman 的预测（12-18 个月内自动化白领工作）被证实 → 原文的批评可能被视为过早

**持续监测指标**：
- AI 代理在真实工作场景中的自动化率变化
- 律师 LLM 幻觉案例的增长趋势
- Microsoft 自研 AI 模型的发布时间和能力
- 放射科医生就业市场的长期趋势

---

## 使用建议

### 给普通读者
✅ **可信可直接引用**：
- 律师 LLM 幻觉案例的快速增长（112→914）
- Remote Labor Index 2.5% 的自动化率数据
- Geoff Hinton 放射科医生预言及其未兑现
- 特斯拉市盈率约 400 倍

⚠️ **需补充语境**：
- Kevin Scott "blow away PhDs" 引语的确切来源不明
- 放射科医生虽然数量增长，但 AI 辅助工具确实提高了效率
- 特斯拉高市盈率有多种解释，不仅限于"炒作"

### 给记者/编辑
1. 引用本文时需说明 Gary Marcus 的 AI 怀疑论者立场
2. 建议交叉验证 Kevin Scott 引语的原始出处
3. 在报道 AI 进展时，平衡呈现成功案例与失败案例

### 给投资者
1. 本文风险评估有价值，但仅为**多方观点之一**
2. 关键决策应基于原始数据（如 RLI 报告、Damien Charlotin 数据库），而非本文转述
3. 注意作者潜在偏见可能导致风险/收益权重偏向悲观

---

## 方法论说明

**核查限制**：
- 无法访问付费墙内容（如 Financial Times 对 Mustafa Suleyman 的完整采访）
- 无法验证可能的内部会议或非公开谈话中的引语
- 基于 2026年2月13日 的公开信息，后续发展可能改变评估

**来源分级**：
| 等级 | 使用来源 |
|------|---------|
| T1 (90%) | Damien Charlotin 数据库、arXiv 论文、公司财报、政府统计数据 |
| T2 (75%) | MarketBeat、Reuters、Bloomberg、CNN |
| TX (0%) | 无法核实的引语（Kevin Scott "blow away PhDs"） |

**伦理声明**：
本核查旨在提升信息质量，不构成对原文作者的人身攻击或对其观点的全面否定。重点在于**如何更准确地呈现事实**，而非**证明作者错误**。Gary Marcus 的核心关切——AI 行业存在过度承诺、媒体缺乏批判性报道——是合理且值得重视的公共议题。

---

*报告生成时间：2026年2月13日*  
*核查员：AI 深度事实核查分析师*
