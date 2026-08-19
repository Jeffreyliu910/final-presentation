# Topic 1 创新性



可以。你这四个维度本身是对的，但用于比赛决赛 PPT 时，**不能只写成“我们有什么功能”**，而要回答评委真正关心的四个问题：

> **为什么别人没这么做？为什么你们的方法更好？为什么别人难以复制？未来能不能做大？**
> 
> 

WHO SMART Guidelines 恰好能把你们“**医疗指南 PDF → Skill → Agent 执行**”这条技术路线抬高一个层级。WHO 对 SMART Guidelines 的定义本身就是把传统指南向 **Standards\-based、Machine\-readable、Adaptive、Requirements\-based、Testable** 的数字化组件转化，以提高指南数字化落地时的忠实度和复用性。\([世界卫生组织](https://www.who.int/teams/digital-health-and-innovation/smart-guidelines?utm_source=chatgpt.com)\)

我建议你们把创新性概括成一句总纲：

> **从“让大模型检索指南”，升级为“让大模型执行指南”。**
> 
> 

这个表达非常适合做创新页的核心。



---

# 技术 / 方案原创性与差异化

### 核心创新：从 Guideline as Knowledge → Guideline as Skill

传统医疗 AI 对指南的利用，主要是：

**指南 PDF → 文本切块 → 向量数据库 → RAG 检索 → LLM 生成答案**

你们做的是：

**指南 PDF → 结构与临床逻辑解析 → 标准化 Skill → Agent 按需调用 → 基于患者证据执行指南逻辑 → 诊断决策**

这两者最大的区别不是“检索效果更好”，而是：

> **传统 RAG 将指南视为“知识”，我们将指南转化为 Agent 可调用、可执行、可组合的“临床能力单元”。**
> 
> 

WHO SMART Guidelines 的思路与这个方向高度一致。WHO 的 DAK 会将指南进一步拆解成核心数据元素、业务流程、决策支持逻辑、指标和功能需求，而其更高层的 Implementation Guide 则进一步把这些内容表达为机器可读逻辑，以供数字系统执行。\(世界卫生组织\)

你们的差异化可以画得非常直观：

所以 PPT 上建议不要写：

> “创新地使用 RAG 读取指南。”
> 
> 

而是写：

> **提出 Guideline\-as\-Skill 范式，将静态医学指南转化为大模型 Agent 可发现、可调用、可执行的临床能力单元。**
> 
> 

这句话的创新层级明显更高。

---

# 产品 × 数据 × 模式 × 场景组合创新

这个部分不要拆开讲，而应该强调：

> **单项技术并非全部原创，但它们的组合形成了新的医疗 AI 产品范式。**
> 
> 

可以概括成四层。

### 数据创新：权威指南不再只是知识库

把：

**PDF / Consensus / Guideline**

转换成：

**Recommendation Card → Clinical Skill → Skill Library**

指南中的：

- 适用人群

- 临床条件

- 推荐意见

- 推荐强度

- 证据等级

- 禁忌条件

- 检查建议

- 决策逻辑

不再被当成普通文本，而成为 Agent 推理过程中可以调用的结构化临床资产。

这与 WHO SMART Guidelines 强调把指南内容转化为可数字化使用的数据、决策支持逻辑和机器可读组件的方向一致。\(世界卫生组织\)

### 模式创新：LLM \+ Agent \+ Skill

不是单一“大医疗模型”，而是：

**基础大模型**
↓
**多 Agent 临床推理**
↓
**疾病级 Clinical Skills**
↓
**权威指南约束**

因此未来甚至可以：

> **模型可替换，Skill 可复用，指南可更新。**
> 
> 

这比“训练一个医疗大模型”更适合作为平台型能力来讲。

### 产品创新：Skill Compiler \+ Skill Runtime

你们实际上可以逐渐抽象为两个产品层：

**Guideline Skill Compiler**

> 医疗指南 → 自动解析 → 标准化 Clinical Skill
> 
> 

- 

**Clinical Skill Runtime**

> 患者 → Skill Router → Skill Execution → Multi\-Agent Reasoning → Diagnosis
> 
> 

这样一来，你们就不只是：

> “一个消化内科诊断系统”
> 
> 

而更像：

> **面向医疗指南的 Clinical Agent Infrastructure。**
> 
> 

### 场景创新：指南真正进入临床决策链

不是医生问：

> “克罗恩病指南怎么说？”
> 
> 

而是：

> 输入患者病例 → 系统识别临床问题 → 自动选择对应疾病 Skill → 根据患者证据执行指南 → 将结果纳入鉴别诊断。
> 
> 

这相当于把指南从：

**Passive Reference**

变成：

**Active Clinical Decision Component**

我认为这是你们这个项目最值得强调的创新之一。

---

# 技术壁垒与护城河

这一部分尤其不要只写：

> “申请软件著作权和专利。”
> 
> 

那样会比较弱。

应该把护城河拆成：

**专利壁垒 \+ 数据壁垒 \+ 工程壁垒 \+ 生态壁垒**

---

## ① 专利：保护核心方法链路

你们真正值得申请专利的并不是：

> “使用大模型诊断疾病”
> 
> 

这种范围太大。

而应该围绕几个具体技术链路形成专利组合，例如：

**专利方向 A**

> 一种将非结构化医学指南自动转换为大语言模型智能体可执行技能的方法及系统
> 
> 

重点保护：

PDF

→ 文档结构识别

→ Recommendation Unit

→ 字段映射

→ Skill Schema

→ Executable Skill

---

**专利方向 B**

> 一种基于患者临床表型与医学指南技能动态匹配的智能诊断方法
> 
> 

重点保护：

Patient Evidence

→ Clinical Feature

→ Skill Routing Profile

→ Top\-K Skill

→ Skill Execution

---

**专利方向 C**

> 一种基于多指南技能协同执行的多智能体临床辅助诊断方法
> 
> 

重点保护：

多个疾病 Skill

→ 多 Agent

→ Evidence accumulation

→ Conflict resolution

→ Diagnosis ranking

---

**专利方向 D**

以后多模态可以继续申请：

> 一种基于多模态患者信息与机器可执行临床指南协同推理的辅助诊断方法。
> 
> 

形成一个**专利族**，而不是一个孤立专利。

---

## ② 数据壁垒：Clinical Skill Library

这是你们长期最重要的壁垒之一。

随着系统运行，你们会积累：

> PDF → Recommendation Cards → Skill → Benchmark → Clinical Cases → Execution Trace
> 
> 

最终形成：

**Clinical Skill Library**

例如：

```Plain Text
Gastroenterology
├── Crohn's Disease Skill
├── Ulcerative Colitis Skill
├── Acute Pancreatitis Skill
├── Cirrhosis Skill
├── Biliary Disease Skill
└── ...
```

以后进一步扩展：

```Plain Text
Clinical Skill Hub
├── Gastroenterology
├── Cardiology
├── Neurology
├── Respiratory
├── Oncology
└── ...
```

**Skill 数量越多、验证病例越多、执行规则越成熟，后来者的复制成本越高。**

---

## ③ 工程壁垒：Skill Compiler

这个甚至可能比模型本身更重要。

因为任何团队都可以买 API、部署 Qwen/DeepSeek/OpenAI。

但如果你们拥有成熟的：

> **Guideline → Skill 自动编译 Pipeline**
> 
> 

新的指南进来：

```Plain Text
PDF
 ↓
Guideline Parser
 ↓
Structure Recognition
 ↓
Recommendation Extraction
 ↓
Clinical Normalization
 ↓
Skill Compiler
 ↓
Validation
 ↓
Clinical Skill
```

那么真正的壁垒就不是某一个模型，而是：

> **持续生产高质量 Clinical Skills 的能力。**
> 
> 

---

## ④ 标准与生态壁垒

后期可以逐渐将 Skill Schema 与：

- WHO SMART Guidelines

- ICD

- SNOMED CT

- LOINC

- HL7 FHIR

对齐。

WHO 的 SMART Implementation Guides 本身已经在部分领域采用机器可读数据模型、术语和逻辑，并面向互操作实施；WHO 当前 SMART Guidelines 页面也列出了 HIV 等领域的 FHIR Implementation Guide。\(SMART指南\)

这样最终形成：

> **Clinical Skill Standard \+ Clinical Skill Marketplace / Repository**
> 
> 

这才是最大的想象空间。

---

# 持续迭代与演进空间

你原来的：

> 消化内科 → 全科室
> 文字 → 多模态
> 
> 

完全正确。

但 PPT 上最好做成一个**二维扩展路线**，而不是简单两句话。

### 第一条轴：医学领域扩展

现在：

> **消化内科**
> 
> 

↓

近期：

> 消化内科完整疾病 Skill Library
> 
> 

↓

中期：

> 心血管 / 呼吸 / 神经 / 肿瘤 / 内分泌……
> 
> 

↓

长期：

> **全科 Clinical Skill Hub**
> 
> 

这得益于你们的核心架构不是给某一种疾病硬编码，而是：

> **Guideline → Standardized Skill**
> 
> 

因此原则上可以迁移到其他专科。

---

### 第二条轴：数据模态扩展

现在：

> Clinical Text
> 
> 

↓

未来：

> Text \+ Lab
> 
> 

↓

> Text \+ Lab \+ Imaging
> 
> 

↓

> Text \+ Lab \+ CT/MRI \+ Endoscopy \+ Pathology
> 
> 

↓

最终：

> **Multimodal Clinical Agent**
> 
> 

例如消化内科尤其适合：

**病历 \+ 实验室检查 \+ CT \+ 肠镜 \+ 病理**

然后不同 Agent/Skill 分别处理：

```Plain Text
Clinical Note Agent
Laboratory Agent
Radiology Agent
Endoscopy Agent
Pathology Agent
        ↓
Guideline Skills
        ↓
Diagnostic Reasoning Agent
```

---

### 第三条轴：从“诊断”扩展到完整临床路径

这一条建议你们一定加上，因为它比“多模态”还重要。

现在做：

> **Diagnosis**
> 
> 

未来可以自然扩展到：

**筛查 → 诊断 → 鉴别诊断 → 检查 → 治疗 → 随访 → 风险管理**

WHO 的 DAK 本身就不仅仅包含知识文本，而包括 workflows、decision support、core data elements、indicators 和 functional requirements，因此这种“从单点诊断向完整临床路径扩展”的叙事与 SMART Guidelines 的整体数字化思想是吻合的。\(世界卫生组织\)

---

# 我建议你们最终 PPT 把这页浓缩成下面 4 个框

你最开始提出的四个标题可以保留，但正文建议改成这种级别：

最下面再放一句“大字结论”：

> ### **我们不是为大模型增加一个医学知识库，而是在构建大模型时代的“机器可执行临床指南”。**
> 
> 

旁边小字标：

> **Inspired by / aligned with the direction of WHO SMART Guidelines**
> 
> 

这里我特别建议用 **“对齐 WHO SMART Guidelines 理念 / aligned with”**，而暂时不要写“**基于 WHO SMART Guidelines 标准实现**”或者“**符合 WHO SMART Guidelines**”。WHO SMART 不只是“把 PDF 结构化”，它还涉及标准术语、决策逻辑、机器可读实现、互操作性与可测试性等层级。\([世界卫生组织](https://www.who.int/teams/digital-health-and-innovation/smart-guidelines?utm_source=chatgpt.com)\)
以你们目前的 Medical Skill Hub 来说，\*\*“理念对齐 \+ 进一步探索 LLM/Agent 时代的 Guideline\-as\-Skill 实现”\*\*既准确，又能突出你们相对于 WHO SMART 现有体系的技术创新。

