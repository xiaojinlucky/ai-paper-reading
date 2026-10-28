下面按“研究问题—主要发现—机制证据—结论局限—复现参数”的顺序作答。所有判断只依据你提供的逐字摘录；凡涉及图像本体、补充图图注、Discussion 或表格数值的内容，均标为“材料未提供/不能判断”。引用时用 [P#]、[M#] 与 Fig. 编号定位。

## 一、研究问题

论文要回答的是：标准化疗（铂类+紫杉类）如何改变 HGSOC 中 CAF 的异质性，残余 CAF 是否通过 YAP1 通路抑制 CD8+ T 细胞，从而影响预后。[P1] 交代了回顾性配对队列（Retrospective Curie 1）的构成：诊断时取样、化疗后取样，平均年龄 67.6 岁，60% 铂敏感、40% 铂耐药。摘要进一步把问题收束为“化疗后残余 CAF-S1 维持与 CD8+ T 密度下降和预后差相关”，并提出 ECM-myCAF–YAP1 轴作为可干预节点。

## 二、化疗前后 YAP1 的变化：细胞与亚细胞位置

这是本次重点，需分三层看。

**（1）组织层面：基质 vs 上皮。** [P9] 与 Fig. 4E–F 报告，YAP1 H-score 在化疗后 HGSOC 基质中显著下降，而上皮中无显著变化（N = 35 配对患者，双侧配对 Wilcoxon）。因此“YAP1 下降”首先是基质区室事件，不是全肿瘤普遍下降。

**（2）细胞层面：CAF-S1/ECM-myCAF，而非 CAF-S4。** [P9] 与 Fig. 4G–H 显示基质 YAP1 H-score 与 FAP（CAF-S1 标志）和 ANTXR1（ECM-myCAF 标志）相关；与 SMA（CAF-S1 与 CAF-S4 共用标志）不相关（Supplementary Fig. S5D）。这把 YAP1 定位到 FAP+、ANTXR1+ 的 CAF-S1/ECM-myCAF，而非泛肌纤维母细胞。

**（3）亚细胞层面：核内 YAP1。** [P9] 与 Fig. 4I–J 报告，化疗后基质中以及癌细胞中“核 YAP1 染色”均显著减少；Fig. 4K–L 显示基质核 YAP1 下降与 FAP、ANTXR1 下降相关，与 SMA 无关（Supplementary Fig. S5E）。核定位是 YAP1 与 TEAD 结合的前提，作者据此把核 YAP1 作为通路活性读数。

**（4）残余细胞内部：ANTXR1+ CAF 的 YAP1 强度也下降。** [P9] 与 Fig. 4M–O 用连续切片共定位：治疗前多数 ANTXR1+ CAF 为 YAP1+，治疗后少数残余 ANTXR1+ CAF 以 YAP1−/Low 为主（n = 83,101 个基质细胞，双侧 Mann-Whitney 与 Fisher 精确检验）。作者据此提出双重解释：YAP1 下降“主要由于 ECM-myCAF 群体丢失，同时也由于残余 CAF-S1 中 YAP1 染色降低”[P9]。

需要强调：上述“细胞/亚细胞定位”来自 IHC 与连续切片共定位的蛋白水平证据；单细胞层面只报告了 ANTXR1 表达与 ANTXR1+ CAF-S1 比例下降（[P6]，Fig. 3E），并未在单细胞中直接报告 YAP1 的细胞类型定位。TEAD 靶基因活性下降来自 DoRothEA/VIPER 推断（[P9]、[M3]），属于计算推断而非直接测量。

## 三、YAP1 与 CYR61 的功能实验支持

**YAP1 的功能证据（Fig. 6A–F，[P12]、[M6]–[M7]）。** 设计是：从 HGSOC 患者样本分离 ECM-myCAF 与 Detox-iCAF 原代成纤维细胞（分别用塑料皿与 I 型胶原包被维持表型，[M4]），与健康供者 PBMC 来源 CD8+ T 细胞共培养 24 h；用两条独立 siYAP1 与 siCtrl 比较。读出包括：PD-1+ CD8+ 比例（Fig. 6A）、Granzyme B+（6B）、Perforin+（6C）、IFN-γ+（6D）、CD8+ T 杀伤 CAOV3 的能力（6E）、Transwell 迁移（6F）。结果：ECM-myCAF（而非 Detox-iCAF）提高 PD-1+、降低三种细胞毒标志并降低杀伤活性；siYAP1 可逆转这些效应，且在 Detox-iCAF 中无影响。迁移实验中 Detox-iCAF 促进 CD8+ 迁移，ECM-myCAF 不促进，siYAP1 不改变这一格局。统计单位为“独立实验次数”：6A–E 为 n = 5，6F 为 n = 8；配对 Wilcoxon 或配对/非配对 t 检验（Fig. 6 图注）。

**CYR61 的功能证据（Supplementary Fig. S7C–F，[P12]、[M6]）。** 依据是 CYR61 在 CAF-S1、尤其 ECM-myCAF 中高表达（S7C），且为已知 YAP1-TEAD 靶基因、编码分泌蛋白。用两条 siCYR61 沉默 ECM-myCAF 后，Granzyme B+、Perforin+、IFN-γ+ CD8+ 比例恢复，PD-1+ 比例下降（S7E），CD8+ 杀伤能力提高（S7F）。siRNA 效力见 S7B（YAP1）与 S7D（CYR61）。注意：S7 的图注文字未提供，因此 CYR61 实验的样本数、统计检验与具体分组只能从 [P12] 正文获知“两条 siRNA、ECM-myCAF、共培养读出”，不能判断是否有 Detox-iCAF 对照、n 值多少。

## 四、这些证据能否连成“已验证的机制链”？

按作者叙述可整理为：化疗 → ECM-myCAF（ANTXR1+ CAF-S1）减少且残余细胞 YAP1 降低 → TEAD 靶基因（含 CYR61）下调 → CYR61 等分泌因子减少 → CD8+ T 细胞细胞毒性恢复/PD-1 降低 → 瘤内 CD8+ 密度上升。支持该链的环节强弱不一：

- 关联环节较强：化疗后 ANTXR1+ ECM-myCAF 下降在多平台一致（IHC、流式、scRNAseq、独立 Turku 与 BC 队列、bulk BayesPrism、Visium；[P6]–[P8]，Fig. 3）；YAP1 与 FAP/ANTXR1 相关（[P9]，Fig. 4G–H、4K–L）；基质 YAP1 与 CD8+ 数量负相关、上皮 YAP1 无此关系（[P11]，Fig. 5K–L）；ANTXR1+ CAF 与 CD8+ 空间分离，且分离主要归于 YAP1+ANTXR1+ CAF（[P10]–[P11]，Fig. 5H、5M–N）。
- 因果环节是“体外、单向”的：siYAP1 与 siCYR61 在共培养中逆转免疫抑制表型（Fig. 6、S7E–F），支持 YAP1→CYR61→CD8 功能的方向性；但没有 YAP1 过表达/组成性激活的“充分性”实验，也没有在体内或患者样本中直接证明“化疗后残余 ECM-myCAF 的 YAP1 下降导致 CD8 浸润增加”。
- 关键缺口：YAP1 与 CYR61 之间是“已知靶基因+表达相关性”的连接（[P12] 称 CYR61 为 well-known YAP1-target gene，S7C 仅示表达），材料中未见 siYAP1 后 CYR61 表达/分泌直接下降的实验；也未见 CYR61 蛋白中和或受体阻断实验。因此严格说，这是一条“多环节有支持、但中间连接与体内因果未闭合”的机制链，而非全链已验证。作者自己在 [P12] 用“might be key”“suggest”措辞，与这一判断一致。

## 五、样本数与统计单位（便于回查）

- 回顾性 Curie 1：N = 35 配对患者、n = 70 样本（Fig. 1C–E、1G、1I；Fig. 2B–F；Fig. 3B；Fig. 4F、4J–L；Fig. 5K–L）。统计单位多为“患者/肿瘤”，配对检验用双侧配对 Wilcoxon。
- 前瞻性流式 cohort 1：Fig. 1K–L 为 N = 8 未治疗、N = 12 化疗后（非配对）；Fig. 2H 为各 N = 8；Fig. 2I–J 相关分析 N = 16 患者；Fig. 3D 为 N = 7 与 N = 9。统计单位为样本/患者，非配对检验。
- scRNAseq：Prospective cohort 2 共 12 例（5 未治疗、7 化疗后，Fig. 3E）；Curie 队列 5,618 个 CAF-S1、Turku 5,658 个（Fig. 3H–I）；TEAD 靶基因分析中 CAF-S1 为 n = 1,968 vs 3,650 细胞，ECM-myCAF 为 n = 1,099 vs 107 细胞（Fig. 4B）。此处统计单位是“细胞”，与患者层面的推断需区分。
- 空间转录组：10 个样本（4 未治疗、6 化疗后），来自 8 例患者（[M1]）；spot 数 13,438 vs 24,205（Fig. 3O、Fig. 4C–D）；Fig. 4D 基质 spot n = 2,410；Fig. 5D 距离分析 n = 10。统计单位为 spot/切片。
- SCANDARE Curie 2：70 个样本（45 未治疗、25 化疗后），来自 48 例卵巢癌患者（[M8]、Fig. 3J–M）；统计单位为样本。
- 多重免疫荧光与连续切片共定位：Fig. 5E–H 为单张治疗后切片示例；Fig. 5M 为 N = 2 配对 HGSOC；Fig. 4N–O 为 n = 83,101 个基质细胞。
- 功能实验：Fig. 6A–E n = 5 独立实验，6F n = 8；统计单位为独立实验，不是患者。
- [M9] 明确“原发患者标本未设重复（No replicates were generated for primary patient specimens）”，并说明先做 Shapiro–Wilk 再选参数/非参数检验，相关性用 Spearman，生存用 Kaplan–Meier 与 log-rank。

## 六、结论局限与仍需补充的材料

1. **因果层级**：核心因果来自体外 siRNA 共培养（Fig. 6、S7E–F），缺少体内模型、YAP1 激活的充分性实验、CYR61 蛋白阻断/中和实验，以及 siYAP1 后 CYR61 下调的直接生化证据。
2. **样本设计**：流式 cohort 1 为未配对样本，作者自己指出“这些非配对样本无法按患者比较化疗前后变化”[P5]；配对结论主要依赖 Curie 1 与 SCANDARE。
3. **空间证据的样本量**：Visium 仅 10 个样本、8 例患者（[M1]），Fig. 5M 仅 2 对配对样本；空间共定位与邻域富集分析的稳健性需看补充材料。
4. **统计与图像**：Fig. 1–7 与 S1–S7 的图片本体、S1–S7 图注、Supplementary Table S1–S2、Source Data 均未提供，无法核对门控、分割、阈值与逐点数值；Table 1/2 临床特征数值缺失，无法评估队列代表性。
5. **单细胞/空间中间参数**：细胞过滤阈值、整合与聚类参数、差异表达全表未提供（缺项清单第 4 条），复现 scRNAseq 与 cell2location 结果需补充。
6. **推断性读数**：TEAD 活性由 DoRothEA/VIPER 推断（[M3]），YAP1 定位由 IHC 与连续切片共定位推断，均非直接功能测量；材料未提供 YAP1 抗体特异性的图像证据（仅指向 Supplementary Fig. S5B、C）。
7. **外推**：BC 与 Turku 队列支持 ANTXR1+ CAF-S1 下降的普遍性（[P6]–[P7]），但 YAP1–CD8 轴的功能实验只在 HGSOC 来源 CAF 中完成，跨瘤种外推需谨慎。

## 七、复现实验所需关键参数（仅列材料中明确给出者）

- 原代 CAF 培养：塑料皿维持 ECM-myCAF、I 型胶原 9 μg/ml 包被维持 iCAF；DMEM + 10% FBS + 1% 双抗；37 °C、5% CO2、1.5% O2；至少 2 周；每周换液 2–3 次；传代不超过 P10（[M4]）。
- 流式鉴定 CAF：anti-FAP-APC 1:100、anti-CD29-Alexa700 1:100、anti-ANTXR1-AF405 1:25，含同型对照；LSRFORTESSA；至少记录 1×10^4 事件；FlowJo 10.4.2（[M4]）。
- CD8+ T 细胞：健康供者 PBMC，Lymphoprep，EasySep Human CD8+ Isolation Kit；可 4 °C 过夜于 RPMI + 10% FBS + 1% 双抗（[M5]）。
- siRNA：每条件 5×10^4 CAF，24 孔板，10 nM siRNA，DharmaFECT 2；siCtrl 为 AllStars negative control #1027281；两条 siYAP1 与两条 siCYR61 序列见 [M6]；48 h 验证沉默效率并维持至共培养（[M6]）。
- 共培养：5×10^4 CAF 于 24 孔板，1.5% O2 预处理 36 h；换 1% FBS 培养基后加 2.5×10^5 CD8+ T 细胞；37 °C、5% CO2、20% O2、24 h（[M7]）。
- 流式读出抗体与稀释：CD45-BUV395 1:100、CD3-AF700 1:50、CD8-BV510 1:50、PD-1-BV421 1:20；胞内 Perforin-FITC 1:25、Granzyme B-PE 1:25、IFN-γ-BV786 1:50；固定 4% PFA 15 min；至少记录 1×10^5 事件（[M7]）。
- 杀伤实验：CAOV3 与预孵育 CD8+ T 共 24 h 后测死亡（Fig. 6E 图注）；迁移为 24 h Transwell（Fig. 6F）。
- Visium：10 μm 切片， permeabilization 18 min，SpaceRanger v1.2.2，GRCh38；Seurat v4.1.0；cell2location 0.1，N_cells_per_location = 15，detection_alpha = 200，epoch 30,000；参考图谱去除 IL-iCAF 与 Acto-myCAF；ANTXR1− CAF = Detox-iCAF + IFNγ-iCAF，ANTXR1+ CAF = Wound/ECM/TGFβ/IFNαβ-myCAF；NMF 因子数 10（[M2]）。
- TF 活性：VIPER v1.32 + DoRothEA v1.10，仅纳入高置信度 A/B/C regulon（[M3]）。
- 统计：Shapiro–Wilk 定参数性；Spearman 相关；Kaplan–Meier + log-rank；显著性阈值 p ≤ 0.05；原发标本无重复（[M9]）。

---

**实际收到的编号清单（仅作核对）**：[P1]–[P12]；[M1]–[M9]；Fig. 1、Fig. 2、Fig. 3、Fig. 4、Fig. 5、Fig. 6、Fig. 7 图注。补充图 S1–S7 仅以正文引用形式出现，其图注文字未收到。