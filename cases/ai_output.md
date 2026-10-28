## 一、本次实际收到的材料与阅读边界

本次输入为论文正文（摘要、Results 第 2.1–2.6 节，[P1]–[P12]）、Fig. 1–7 图注全文、Methods 关键段落 [M1]–[M9]，以及一份缺项清单。**图片本体（Fig. 1–7、Supplementary Fig. S1–S7）、Supplementary Table S1–S2、Source Data、Table 1/2 数值、Discussion 与 Introduction 均未进入输入**。因此下文凡涉及“染色强度、点位分布、散点形状”的描述，只能转述图注与正文文字，不能声称看过图像。材料中未见截断标记；[P1]–[P12] 均为完整自然段。另需注意：Fig. 3E 图注写“N = 12，5 treatment-naïve 和 7 after chemotherapy”，而 [P6] 正文写“12 HGSOC patients before and after treatment”，两处措辞不完全一致，下文按图注的 5+7 处理并标注此歧义。

## 二、研究问题与框架

对象：高级别浆液性卵巢癌（HGSOC）患者组织与来源其中的 CAF-S1 原代成纤维细胞。处理：以铂类+紫杉类标准化疗为“处理”，比较诊断时（treatment-naïve）与化疗后（residual disease）样本。读出：CAF 亚群比例（IHC H-score、流式、scRNAseq、空间转录组反卷积）、YAP1 蛋白总量与核定位、TEAD 靶基因活性、CD8+ T 细胞密度与细胞毒功能。核心主张可拆为四条关系：(i) 化疗后 ANTXR1+ ECM-myCAF 减少最多；(ii) 化疗后 CAF-S1/基质中 YAP1 与 TEAD 靶基因下降；(iii) ECM-myCAF 在体外抑制 CD8+ T 细胞毒性，且依赖 YAP1；(iv) CYR61 作为 YAP1 下游分泌因子参与该抑制。

## 三、主张—证据表

| 关系/具体主张 | 原文锚点 | 实际观察或干预及对照 | 支持到哪一步 | 重要限制 |
|---|---|---|---|---|
| 化疗后 CAF-S1、CAF-S4 比例下降，S2/S3 上升 | [P2]；Fig. 1F–I | 35 例配对样本 IHC，FAP/CD29/SMA/FSP1 H-score 用决策树归类；配对 Wilcoxon、卡方 | 观察性关联，配对设计较强 | 决策树归类依赖既往定义的阈值；H-score 为半定量 |
| 流式证实 FAPHigh CAF-S1 与 CAF-S4 下降 | [P3]；Fig. 1J–L | 前瞻队列 1：8 例未治疗 vs 12 例化疗后，非配对 | 独立方法学佐证 | 非配对，不能做患者内前后比较（[P5] 亦承认） |
| 化疗后 ANTXR1+ myCAF/ECM-myCAF 减少最多 | [P6][P7]；Fig. 3A–P | IHC（N=35 配对）、流式（7 vs 9）、scRNAseq（Curie 5 vs 7；Turku 11 配对；BC 31 vs 11）、bulk 反卷积（SCANDARE 45 vs 25）、Visium（4 vs 6 切片） | 多平台、多队列一致，支持“减少”这一观察 | 各平台样本量与统计单位不同；scRNAseq 为不同患者而非配对；Visium 仅 10 张切片 |
| 化疗后 CAF-S1 中 TEAD 活性与靶基因下降 | [P9]；Fig. 4A–D | DoRothEA/VIPER 推断 TF 活性；TEAD 靶基因模块评分；空间转录组 | 转录推断+空间一致性 | TF 活性为算法推断，非直接蛋白活性测定；未做 TEAD 报告基因 |
| 化疗后基质 YAP1 H-score 下降、上皮不变；核 YAP1 在基质与癌细胞均下降 | [P9]；Fig. 4E–J | 配对 IHC，N=35；核染色百分比 | 蛋白水平与亚细胞定位的观察 | 抗体特异性仅称在 Supplementary Fig. S5B、C 验证，图未提供；H-score 与核百分比为不同读出，不可互换 |
| 残余 ANTXR1+ CAF 本身 YAP1 也降低 | [P9]；Fig. 4M–O | 连续切片共定位，n=83,101 个基质细胞 | 支持“总量下降+残余细胞单细胞水平下降”双重解释 | 连续切片而非同一切片多重染色；细胞数为统计单位，患者数未在该图注给出 |
| 基质 YAP1 与 CD8+ T 密度负相关，上皮 YAP1 无关联 | [P11]；Fig. 5K、L | 化疗后样本，N=35，Spearman | 关联 | 横断面相关，不能定因果方向 |
| ANTXR1+ CAF 与 CD8+ T 空间分离，YAP1+ANTXR1+ 邻域 CD8 更少 | [P10][P11]；Fig. 5A–N | Visium 反卷积+NMF；多重免疫荧光共occurrence；IHC 共染；Fig. 5M 仅 N=2 配对 | 空间关联 | Fig. 5M/N 样本极少；共occurrence 为概率比，受分割与半径参数影响 |
| ECM-myCAF 增加 PD-1+、降低 Granzyme B+/Perforin+/IFN-γ+ CD8，并降低杀瘤能力；Detox-iCAF 无此效应 | [P12]；Fig. 6A–E | 原代 CAF 与健康供者 PBMC 来源 CD8 共培养，n=5 独立实验 | 受控体外功能实验，支持 ECM-myCAF 的功能贡献 | 供者数与独立实验数的映射未给；CAF 来源患者数未在 Fig. 6 图注给出 |
| 敲低 YAP1 逆转上述表型，对 Detox-iCAF 无影响 | [P12]；Fig. 6A–F；[M6][M7] | 两条独立 siRNA（siYAP1(1)(2)）vs siCtrl；10 nM；48 h 验证敲低 | loss-of-function 支持 YAP1 在该体系中的功能贡献 | 两条 siRNA 同向敲低，不构成 gain-of-function 或 rescue；未回补 YAP1；未测 YAP1 蛋白定位是否恢复 |
| 敲低 CYR61 恢复细胞毒标志并提高杀瘤 | [P12]；Supplementary Fig. S7D–F | 两条 siRNA vs siCtrl | 支持 CYR61 参与 | 仅在补充图，图注文字未提供；未做 CYR61 回补或与 YAP1 的上位实验 |
| Detox-iCAF 促进 CD8 迁移，ECM-myCAF 不促进 | [P12]；Fig. 6F | Transwell，n=8 | 两亚群功能互补 | 与 YAP1 敲低的关系仅部分呈现 |

## 四、化疗前后 YAP1 变化的细胞与亚细胞定位

按 [P9] 与 Fig. 4E–J：**细胞归属**上，YAP1 H-score 在基质显著下降、在上皮无显著变化；但核 YAP1 阳性比例在基质与癌细胞中均显著下降（Fig. 4J 左右两栏）。这两句必须分开读——总量（H-score）的下降限于基质，而核定位的下降是基质与上皮都有的。**亚细胞位置**上，作者以“核 YAP1 占 YAP1+ CAF 的百分比”和“核 YAP1 癌细胞百分比”为读出（Fig. 4J），并在 Fig. 4M–O 用 ANTXR1/YAP1 连续切片显示残余 ANTXR1+ CAF 多为 YAP1−/Low。需要强调：Fig. 4J 的“核 YAP1”是定性/半定量的定位读出，不能等同于总蛋白量；Fig. 4N 的“YAP1 mean intensity in ANTXR1+ CAF”是强度读出，也不能直接换算为核内浓度。此外，Fig. 4G/H/K/L 的相关性分析把基质 YAP1 与 FAP、ANTXR1 挂钩，而与 SMA 无相关（Supplementary Fig. S5D、E），这是“YAP1 变化主要落在 CAF-S1/ECM-myCAF 而非 CAF-S4”的间接支持，但仍是相关而非细胞类型特异性的直接测量。

## 五、YAP1 与 CYR61 的功能实验支持

YAP1 侧：Fig. 6A–E 用两条 siRNA 敲低 ECM-myCAF 中的 YAP1，观察到 PD-1+ CD8 比例回落、Granzyme B+/Perforin+/IFN-γ+ 比例回升、CAOV3 癌细胞死亡增加；同样的敲低在 Detox-iCAF 中无效应（[P12]）。这是**同一细胞体系内的 loss-of-function + 亚群特异性对照**，支持 YAP1 对 ECM-myCAF 免疫抑制表型的功能贡献。但它不证明 YAP1 是“必需”的：没有 gain-of-function、没有 YAP1 表达回补、没有证明敲低只影响 YAP1-TEAD 而不影响其他通路；两条 siRNA 是同一方向的两个工具，不是正反操纵。

CYR61 侧：Supplementary Fig. S7C 显示 CYR61 在 CAF-S1、尤其 ECM-myCAF 高表达；S7D 为敲低效率；S7E 显示敲低 CYR61 恢复 Granzyme B/Perforin/IFN-γ 并降低 PD-1+；S7F 显示杀瘤能力提高（[P12]）。这支持 CYR61 作为分泌因子参与该抑制，但**没有 CYR61 回补实验，也没有 YAP1 敲低后 CYR61 表达是否下降的直接测量**（正文只说 CYR61 是“well-known YAP1-target gene”，属先验知识而非本研究证明）。

## 六、能否连成一条“已验证”的机制链

按证据用途分层：

- **观察/关联层**：化疗后 ECM-myCAF 减少、YAP1/TEAD 信号下降、CD8 密度上升，三者在患者样本中同时出现且方向一致（[P6]–[P11]）。这一层较扎实，但都是伴随变化。
- **受控干预层**：体外敲低 YAP1 或 CYR61 可逆转 ECM-myCAF 对 CD8 的抑制（Fig. 6；S7E–F）。这支持“ECM-myCAF→YAP1→CD8 功能”的方向性，但限于体外共培养体系。
- **机制连接层**：YAP1→CYR61 这一环在本文中**没有被直接检验**（无 YAP1 敲低后 CYR61 蛋白/分泌测定，无 CYR61 回补挽救 YAP1 敲低表型，无上位实验）。空间上“YAP1+ANTXR1+ CAF 邻域 CD8 少”是关联，不是因果。
- **体内/患者层**：没有任何 YAP1 或 CYR61 干预的体内实验；化疗后 YAP1 下降与 CD8 上升的因果方向未被干预验证。

因此，**不能**说本文已连成“化疗→ECM-myCAF 减少/YAP1 下降→CYR61 减少→CD8 毒性恢复”的完整已验证链条。可以说的是：本文建立了“ECM-myCAF 经 YAP1 依赖方式抑制 CD8 毒性”的体外功能证据，以及“化疗后该亚群与 YAP1 信号同步下降、CD8 同步上升”的临床关联；CYR61 是候选介导者，YAP1→CYR61 的连接仍属推断。

## 七、样本数与统计单位（易混淆处）

- Fig. 1C–I：N=35 患者、n=70 配对样本；统计单位为患者（配对检验）。
- Fig. 1K–L：8 例未治疗 vs 12 例化疗后，非配对；统计单位为样本/患者。
- Fig. 2B–F：N=35 患者；Fig. 2H：8 vs 8；Fig. 2I/J：N=16 患者。
- Fig. 3B：N=35；3D：7 vs 9；3E：12 例（5 vs 7，图注口径）；3F：11 配对；3G：42 例（31 vs 11）；3H：5,618 个 CAF-S1 细胞；3I：5,658 个细胞；3J–M：70 个样本（45 vs 25），来自 48 例患者（[M8]）；3O：4 张切片 13,438 spots vs 6 张 24,205 spots；3P：10 张切片。
- Fig. 4B：CAF-S1 中 1,968 vs 3,650 个细胞，ECM-myCAF 中 1,099 vs 107 个细胞，N=12 患者；4D：2,410 个基质 spots；4F/J：N=35 患者；4N/O：n=83,101 个基质细胞（患者数未在该图注给出）。
- Fig. 5D：n=10；5M：N=2 配对；5K/L：N=35。
- Fig. 6A–E：n=5 独立实验；6F：n=8 独立实验。**独立实验与供者/患者的对应关系未报告**，不能把 n=5 当作 5 名供者或 5 名患者。
- [M9] 明确“primary patient specimens 未设重复”，这影响患者样本层面的统计解释。

## 八、复现关键参数表

| 要素 | 内容 | 锚点 |
|---|---|---|
| 对象来源 | HGSOC 手术新鲜组织；Retrospective Curie 1（配对）、Prospective 1（流式）、Prospective 2（scRNAseq）、SCANDARE Curie 2（bulk）、Turku 与 BC 公共数据 | [P1][P3][P6][P7][M8] |
| CAF 培养 | 组织小块贴塑料皿维持 ECM-myCAF，I 型胶原 9 μg/ml 包被维持 iCAF；DMEM+10% FBS+1% P/S；37 °C、5% CO2、1.5% O2；≥2 周；传代至 P10 | [M4] |
| siRNA | 5×10⁴ CAF/孔（24 孔），10 nM，DharmaFECT 2，48 h 验证敲低；siCtrl 为 AllStars negative control；YAP1 两条、CYR61 两条序列见 [M6] | [M6] |
| 共培养 | CAF 5×10⁴/孔，1.5% O2 36 h；换 1% FBS 培养基后加 2.5×10⁵ CD8+ T；24 h，37 °C、5% CO2、20% O2 | [M7] |
| CD8 来源 | 健康供者 PBMC（EFS 血库），Lymphoprep，EasySep 磁分选 | [M5] |
| 读出 | 流式：CD45/CD3/CD8/PD-1 表面，Perforin/Granzyme B/IFN-γ 胞内；杀瘤：CAOV3 死亡；迁移：Transwell 24 h | [M7]；Fig. 6E、F |
| 空间 | Visium 10 μm 切片，渗透 18 min；SpaceRanger v1.2.2，GRCh38；cell2location v0.1，N_cells_per_location=15，detection_alpha=200，30,000 epochs；NMF 因子数 10 | [M2] |
| TF 活性 | VIPER v1.32 + DoRothEA v1.10，仅高置信 A/B/C regulon | [M3] |
| 统计 | Shapiro–Wilk 定参数/非参数；相关用 Spearman；生存 Kaplan-Meier/Log-rank；p≤0.05 | [M9] |
| 缺项 | 细胞过滤/整合/聚类参数、差异表达全表、补充图图注、Table 1/2 数值、供者-实验映射、YAP1 抗体验证图 | 缺项清单；Fig. 4 图注 |

## 九、结论的三段式

**当前证据支持**：在 HGSOC 中，化疗后 ANTXR1+ ECM-myCAF 是 CAF-S1 内减少最多的亚群（多平台、多队列）；化疗后基质 YAP1 总量与核 YAP1 下降，TEAD 靶基因活性下降；ECM-myCAF 在体外经 YAP1 依赖方式抑制 CD8+ T 细胞毒性，CYR61 敲低可产生类似逆转。

**不能直接推出**：不能推出 YAP1→CYR61 的因果连接已被验证；不能推出化疗后 YAP1 下降“导致”CD8 浸润增加（无体内干预）；不能把体外 siRNA 结果外推为患者治疗靶点的有效性；不能把核 YAP1 百分比与总 YAP1 量混为同一读出；不能把 n=5 独立实验等同于 5 名供者或患者。

**优先补查/最小判别实验**：(1) 在 ECM-myCAF 中敲低 YAP1 后测 CYR61 蛋白与分泌，并做 CYR61 回补能否挽救 siYAP1 表型——这是打通机制链的最小实验；(2) 索取 Fig. 4N/O 的患者数与 Fig. 6 的供者-实验映射，以判断统计单位；(3) 查看 Supplementary Fig. S5B、C 的 YAP1 抗体验证与 S7D 的 CYR61 敲低效率原始图。以上均为建议，非论文已做。

## 十、实际收到的编号清单

正文段落：[P1]、[P2]、[P3]、[P4]、[P5]、[P6]、[P7]、[P8]、[P9]、[P10]、[P11]、[P12]。
Methods 段落：[M1]、[M2]、[M3]、[M4]、[M5]、[M6]、[M7]、[M8]、[M9]。
图注：Fig. 1、Fig. 2、Fig. 3、Fig. 4、Fig. 5、Fig. 6、Fig. 7。