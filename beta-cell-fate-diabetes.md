# 胰岛 β 细胞去分化与转分化研究进展：系统性综述

## 摘要

胰岛 β 细胞功能障碍是糖尿病发病的核心环节。近年来，β 细胞去分化和转分化作为 β 细胞数量与功能丧失的新机制引起了广泛关注。本综述基于 2021–2025 年间的最新文献，系统梳理了 β 细胞去分化的定义、鉴定方法、分子机制与可逆性，以及 α→β、δ→β、导管→β、腺泡→β 等多种转分化路径的证据等级与临床转化潜力。我们进一步讨论了去分化与转分化在 1 型和 2 型糖尿病发病机制中的意义，评价了阻止去分化、诱导重新成熟及体内重编程等治疗策略，并总结了学界共识与未来方向。

---

## 一、β 细胞去分化

### 1.1 主流定义

β 细胞去分化 指成熟 β 细胞在代谢应激下丧失其终末分化特征（如胰岛素基因表达下调、关键转录因子 Pdx1Nkx6.1MafA 减少），回退至不成熟的祖细胞样或内分泌前体状态，甚至获得其他内分泌细胞（如 α 细胞）的特征标志物（如胰高血糖素、Arx）的现象。该概念最早由 Talchai & Accili 于 2012 年在 FoxO1 敲除小鼠模型中系统性提出：

 Talchai C, Accili D. (2012). Pancreatic beta cell dedifferentiation into neurogenin3-positive progenitor cells and conversion into non-beta endocrine cells as mechanisms of diabetic beta cell failure. Diabetologia, 55(Suppl) S64.
 [论文链接](httpswww.aminer.cnpub5fc9cf30b0d046820d303dfe)
 研究类型：Animal study (FoxO1 knockout mice) · 证据等级：⭐⭐⭐
 核心结论：FoxO1 缺失导致 β 细胞去分化为 Ngn3⁺ 祖细胞，并可转分化为 αδPP 细胞，提出去分化是 β 细胞衰竭的主要机制。
 关联：本综述的概念基石，首次将去分化与糖尿病 β 细胞衰竭直接关联。

去分化与功能衰竭的关键区别在于：功能衰竭 是指 β 细胞在代谢压力下胰岛素分泌能力下降但仍保留细胞身份标志物；而 去分化 则涉及细胞身份标志物的丢失和去分化标志物（如 ALDH1A3、Sox9、Hes1）的上调。然而，两者在病程中可能重叠发生。

### 1.2 鉴定方法

 鉴定维度  标志物方法  参考文献 
------------------------------
 去分化标志物  ALDH1A3↑, Sox9↑, Hes1↑, Ngn3↑  Son et al. 2023; Li et al. 2025 
 身份标志物丢失  Insulin↓, Pdx1↓, Nkx6.1↓, MafA↓, FoxO1↓  Lee et al. 2022 
 表面标志物  CD81 (CD81^high 标记不成熟去分化 β 细胞)  Salinno et al. 2021 
 转分化中间态  双激素细胞 (Insulin⁺Glucagon⁺)  Lee et al. 2022 
 单细胞转录组  scRNA-seq 识别去分化细胞状态  Hrovatin et al. 2023; Wang et al. 2023 
 染色质可及性  scATAC-seq 识别调控程序改变  Chiou et al. 2021 
 人体组织  胰腺活检免疫染色（17 种标志物组合）  Brusco et al. 2023 

关键进展：

 Salinno C, et al. (2021). CD81 Marks Immature and Dedifferentiated Pancreatic β-Cells. Molecular Metabolism, 49 101188.
 [论文链接](httpswww.aminer.cnpub602b9867af79179a99f1324a)
 DOI 10.1016j.molmet.2021.101188
 研究类型：Original Article (小鼠 + 人 · 单细胞测序 + FACS + 影像)
 证据等级：⭐⭐⭐
 核心结论：CD81 表达在 β 细胞成熟过程中逐渐降低，但在应激和去分化 β 细胞中重新上调。CD81^high 群体富集不成熟去分化特征。
 关联：提供了首个可用于 FACS 分选和追踪去分化 β 细胞的表面标志物。

 Brusco N, et al. (2023). Intra-islet Insulin Synthesis Defects Are Associated with Endoplasmic Reticulum Stress and Loss of Beta Cell Identity in Human Diabetes. Diabetologia, 66(2) 283–297.
 [论文链接](httpswww.aminer.cnpub6359128c90e50fcafdfd62ea)
 DOI 10.1007s00125-022-05814-2
 研究类型：Original Article (人体研究 · 胰腺活检)
 证据等级：⭐⭐⭐
 核心结论：在人体胰腺活检中，胰岛素合成缺陷与 ER 应激和 β 细胞身份标志物丢失密切相关，ER 应激可能是去分化的上游驱动因素。
 关联：提供了人体水平上 ER 应激→去分化的直接证据，连接了 ER 应激与去分化两大 β 细胞衰竭机制。

### 1.3 分子机制

#### 1.3.1 FoxO1 通路

FoxO1 是维持 β 细胞身份的核心转录因子。在代谢应激下 FoxO1 核排除→降解，导致去分化。

 [匿名] (2021). An Inhibitor-Mediated Beta-Cell Dedifferentiation Model Reveals Distinct Roles for FoxO1 in Glucagon Repression and Insulin Maturation. Molecular Metabolism, 50 101329.
 [论文链接](httpswww.aminer.cnpub612cb5f35244ab9dcb4af2cb)
 DOI 10.1016j.molmet.2021.101329
 研究类型：Original Article (体外模型)
 证据等级：⭐⭐
 核心结论：FoxO1 在抑制胰高血糖素表达和促进胰岛素成熟中发挥双重作用，FoxO1 失活是去分化的关键节点。
 关联：阐明了 FoxO1 调控 β 细胞身份的具体分子机制。

#### 1.3.2 ER 应激  UPR 通路

 Lee K, et al. (2022). XBP1 Maintains Beta Cell Identity, Represses Beta-to-alpha Cell Transdifferentiation and Protects Against Diabetic Beta Cell Failure During Metabolic Stress in Mice. Diabetologia, 65(6) 984–996.
 [论文链接](httpswww.aminer.cnpub623c4d925aee126c0f8802a4)
 DOI 10.1007s00125-022-05669-7
 研究类型：Original Article (小鼠 · 条件性敲除 · Lineage tracing)
 证据等级：⭐⭐⭐
 核心结论：β 细胞特异性 XBP1 敲除导致去分化、β→α 转分化和 α 细胞质量增加；在代谢应激（高脂饮食obob）下引发糖尿病。XBP1 维持 β 细胞身份基因（Insulin, Pdx1, Nkx6.1）表达，抑制去分化（Aldh1a3）和 α 细胞基因（Glucagon, Arx）。
 关联：将 ER 应激（UPR）与去分化和 β→α 转分化直接关联，揭示 XBP1 作为 β 细胞身份守门人。

#### 1.3.3 ALDH1A3 通路

 Son J, et al. (2023). Genetic and Pharmacologic Inhibition of ALDH1A3 As a Treatment of β-Cell Failure. Nature Communications, 14 1684.
 [论文链接](httpswww.aminer.cnpub63de390590e50fcafd7eb8b8)
 DOI 10.1038s41467-023-36315-4
 研究类型：Original Article (小鼠 · Lineage tracing · 药理学干预)
 证据等级：⭐⭐⭐
 核心结论：ALDH1A3 阳性去分化 β 细胞可通过 Lineage tracing 证实可逆——重新分化为成熟功能 β 细胞。遗传或药理学抑制 ALDH1A3 降低血糖、增加胰岛素分泌，激活分化和再生通路。
 关联：证明去分化可逆，ALDH1A3 抑制剂具有治疗转化价值。

#### 1.3.4 代谢-表观遗传重编程

 Li X, et al. (2025). LDHA Induces Beta Cell Dedifferentiation in Diabetes Through Metabolic and Epigenetic Reprogramming. Diabetologia, online.
 [论文链接](httpswww.aminer.cnpub693bcbc294d1bc07b4903a58)
 DOI 10.1007s00125-025-06626-w
 研究类型：Original Article (人体 + 小鼠 · ChIP-seq + RNA-seq)
 证据等级：⭐⭐⭐
 核心结论：糖毒性下 LDHA 活化增加 H3K9 乳酸化修饰（H3K9la），在 Sox9Hes1Aldh1a3 启动子区富集并激活其转录，驱动去分化。LDHA 抑制可保护 β 细胞身份。
 关联：揭示了代谢-表观遗传偶联驱动去分化的全新机制，连接了代谢重编程与表观遗传学。

#### 1.3.5 氧化应激

 [匿名] (2021). Oxidative Stress Leads to β-Cell Dysfunction Through Loss of β-Cell Identity. Frontiers in Immunology, 12 690379.
 [论文链接](httpswww.aminer.cnpub619cc6075244ab9dcb11ddab)
 DOI 10.3389fimmu.2021.690379
 研究类型：Review
 证据等级：⭐⭐
 核心结论：氧化应激通过下调 β 细胞身份转录因子导致去分化，是 T1D 和 T2D 共有的 β 细胞损伤机制。
 关联：将氧化应激与去分化关联，解释了多种应激源如何汇聚到身份丢失。

#### 1.3.6 脂毒性与 SCD1

 Dobosz AM, et al. (2023). Inhibition of Stearoyl-CoA Desaturase 1 in the Mouse Impairs Pancreatic Islet Morphogenesis and Promotes Loss of β-Cell Identity and α-Cell Expansion in the Mature Pancreas. Molecular Metabolism, 67 101659.
 [论文链接](httpswww.aminer.cnpub639b4ca490e50fcafd8009a8)
 DOI 10.1016j.molmet.2022.101659
 研究类型：Original Article (小鼠)
 证据等级：⭐⭐
 核心结论：SCD1 抑制导致 β 细胞身份基因（Pdx1, Nkx6.1, MafA）下调、去分化标志物 Sox9 上调，同时 α 细胞扩增。Pdx1MafA 启动子异常甲基化是机制之一。
 关联：将脂代谢异常与表观遗传调控和去分化联系起来。

### 1.4 可逆性

去分化是可逆的——这是近年最重要的发现之一。

- Son et al. (2023) 通过 Lineage tracing 证明 ALDH1A3⁺ 去分化 β 细胞可重新转化为功能成熟的 β 细胞 ⭐⭐⭐
- Furth-Lavi et al. (2022) 证明严重高血糖阻断 β 细胞再生，但血糖纠正后再生潜力释放：

 Furth-Lavi J, et al. (2022). Glycemic Control Releases Regenerative Potential of Pancreatic Beta Cells Blocked by Severe Hyperglycemia. Cell Reports, 41(9) 111719.
 [论文链接](httpswww.aminer.cnpub638b2b8790e50fcafd76c4a6)
 DOI 10.1016j.celrep.2022.111719
 研究类型：Original Article (小鼠 · Lineage tracing)
 证据等级：⭐⭐⭐
 核心结论：极端高血糖（28 mmolL）阻断 β 细胞再生，但胰岛素SGLT2 抑制剂生酮饮食纠正血糖约 3 周后，β 细胞再生潜力恢复。存在一个葡萄糖阈值，将糖负荷从促再生转为抗再生。
 关联：解释了为何严格血糖控制可改善 β 细胞功能，支持去分化可逆的临床意义。

### 1.5 动物模型与人体证据

 证据来源  模型样本  关键发现  证据等级 
------------------------------------
 小鼠  FoxO1 KO (Talchai 2012)  β→祖细胞→αδPP  ⭐⭐⭐ 
 小鼠  XBP1 β-cell KO (Lee 2022)  β→α 转分化 + 去分化  ⭐⭐⭐ 
 小鼠  dbdb, HFD (Li 2025)  LDHAH3K9la 驱动去分化  ⭐⭐⭐ 
 小鼠  STZ + 血糖纠正 (Furth-Lavi 2022)  去分化可逆  ⭐⭐⭐ 
 人体  胰腺活检 (Brusco 2023)  ER 应激 + 身份丢失  ⭐⭐⭐ 
 人体  nPOD 胰腺 (Fasolino 2022)  T1D 单细胞图谱  ⭐⭐⭐ 
 人体  scRNA-seq 多供体 (Wang 2023)  T2D β 细胞亚型转换  ⭐⭐⭐ 
 体外  人 EndoC-βH1 (Salinno 2021)  CD81 标记应激 β 细胞  ⭐⭐ 

### 1.6 单细胞测序时代的 β 细胞状态图谱

 Hrovatin K, et al. (2023). Delineating Mouse β-Cell Identity During Lifetime and in Diabetes with a Single Cell Atlas. Nature Metabolism, 5 604–622.
 [论文链接](httpswww.aminer.cnpub63a54be790e50fcafd574f6c)
 DOI 10.1038s42255-023-00876-x
 研究类型：Original Article (小鼠 · scRNA-seq · 300,000 cells)
 证据等级：⭐⭐⭐
 核心结论：整合 9 个 scRNA-seq 数据集（56 样本），构建小鼠胰岛细胞图谱(MIA)。揭示 β 细胞在未成熟、衰老和糖尿病模型中共享的通路。STZ 模型 β 细胞与人类 T2D 和 dbdb 更相似，而与 T1DNOD 差异较大。
 关联：提供了 β 细胞状态转换的系统性图谱，对动物模型外推至人体的可靠性提供了关键参考。

 Wang G, et al. (2023). Integrating Genetics with Single-Cell Multiomic Measurements Across Disease States Identifies Mechanisms of Beta Cell Dysfunction in Type 2 Diabetes. Nature Genetics, 55(6) 984–994.
 [论文链接](httpswww.aminer.cnpub63b7c1d390e50fcafdc46fba)
 DOI 10.1038s41588-023-01397-9
 研究类型：Original Article (人体 · scRNA-seq + scATAC-seq · 34 供体)
 证据等级：⭐⭐⭐
 核心结论：鉴定出两个转录和功能不同的 β 细胞亚型，在 T2D 进展中发生丰度转换。两个亚型均激活应激反应程序并功能受损，T2D 风险变异富集于亚型定义的染色质可及区。
 关联：首次在单细胞水平将遗传风险与 β 细胞状态转换关联，提示去分化亚型转换可能是 T2D 遗传易感性的细胞基础。

 Chiou J, et al. (2021). Single Cell Chromatin Accessibility Reveals Pancreatic Islet Cell Type- and State-Specific Regulatory Programs of Diabetes Risk. Nature Genetics, 53(4) 455–466.
 [论文链接](httpswww.aminer.cnpub5f6734869fced0a24bcfba97)
 DOI 10.1038s41588-021-00823-0
 研究类型：Original Article (人体 · scATAC-seq · 14.2k cells)
 证据等级：⭐⭐⭐
 核心结论：鉴定出多种 αβδ 细胞状态（包括信号响应态），将 T2D GWAS 信号定位到细胞类型特异性调控区域。在 KCNQ1 位点，因果变异通过 β 细胞特异性增强子调控胰岛素表达。
 关联：从表观遗传调控层面揭示了 β 细胞状态特异性的糖尿病风险机制。

 Fasolino M, et al. (2022). Single-cell Multi-Omics Analysis of Human Pancreatic Islets Reveals Novel Cellular States in Type 1 Diabetes. Nature Metabolism, 4(2) 284–299.
 [论文链接](httpswww.aminer.cnpub61979fa05244ab9dcb17e32d)
 DOI 10.1038s42255-022-00531-x
 研究类型：Original Article (人体 · scRNA-seq + CyTOF + 影像质谱 · 24 供体 · ~80,000 cells)
 证据等级：⭐⭐⭐
 核心结论：T1D 胰岛中外分泌导管细胞获得耐受性树突状细胞特征，可能试图进行免疫抑制。多模态分析揭示了 T1D 免疫病理中的新细胞类型和过程。
 关联：T1D 中胰岛微环境的细胞可塑性证据，提示非 β 细胞也可能参与疾病调节。

---

## 二、β 细胞转分化

### 2.1 α→β 转分化

α→β 转分化是目前研究最深入的转分化方向。

#### 2.1.1 关键转录因子：Pax4  Arx

 Collombat P, et al. (2005). The Simultaneous Loss of Arx and Pax4 Genes Promotes A Somatostatin-Producing Cell Fate Specification at the Expense of the Alpha- and Beta-Cell Lineages in the Mouse Endocrine Pancreas. Development, 132(13) 2969–2980.
 [论文链接](httpswww.aminer.cnpub53e9bc15b7602d970487ba32)
 DOI 10.1242dev.01870
 研究类型：Original Article (小鼠 · 基因敲除)
 证据等级：⭐⭐⭐（经典里程碑）
 核心结论：Arx 和 Pax4 作为相互抑制的转录因子，共同决定 αβ 细胞命运。Arx 缺失促使 α→β 转分化，Pax4 过表达同样驱动 α→β 转化。
 关联：建立了 α↔β 转分化的转录因子调控范式，是后续所有 α→β 转分化研究的理论基础。

#### 2.1.2 药物诱导 α→β 转分化

 Jia J, et al. (2022). Artemether and Aspterric Acid Induce Pancreatic Alpha Cells to Transdifferentiate into Beta Cells in Zebrafish. British Journal of Pharmacology, 179(4) 690–706.
 [论文链接](httpswww.aminer.cnpub61d819615244ab9dcba6c5e7)
 DOI 10.1111bph.15769
 研究类型：Original Article (斑马鱼 · Lineage tracing · 体外 αTC1-6)
 证据等级：⭐⭐
 核心结论：青蒿素和 aspterric acid 在斑马鱼中诱导 α→β 转分化，通过上调 Pax4 表达（而非抑制 Arx）。在 β 细胞缺失和 α 细胞增生条件下同样有效。
 关联：为药物诱导 α→β 转分化提供了新候选化合物。

 Sarnobat D, et al. (2022). GABA and Insulin but Not Nicotinamide Augment α- to β-Cell Transdifferentiation in Insulin-Deficient Diabetic Mice. Biochemical Pharmacology, 199 115019.
 [论文链接](httpswww.aminer.cnpub62497abe5aee126c0f3d4573)
 DOI 10.1016j.bcp.2022.115019
 研究类型：Original Article (小鼠 · STZ 模型 · Lineage tracing)
 证据等级：⭐⭐
 核心结论：GABA 和胰岛素（而非烟酰胺）增强 α→β 转分化，增加双激素细胞数量。提示内源性胰岛素和 GABA 信号参与 α 细胞可塑性调控。
 关联：阐明 GABA 诱导 α→β 转分化的信号通路，为 GABA 相关疗法提供依据。

#### 2.1.3 人体证据

 [匿名] (2024). Cycling Alpha Cells in Regenerative Drug-Treated Human Pancreatic Islets May Serve As Key Beta Cell Progenitors. Med-X, 1 101832.
 [论文链接](httpswww.aminer.cnpub674de808ae8580e7ffa68eb6)
 DOI 10.1016j.xcrm.2024.101832
 研究类型：Original Article (人体胰岛 · 体外药物处理)
 证据等级：⭐⭐⭐
 核心结论：在再生药物处理的人胰岛中，增殖性 α 细胞可能是关键 β 细胞前体。首次在人体胰岛中提供了 α→β 转分化的直接证据。
 关联：将 α→β 转分化从动物模型推进至人体组织水平。

#### 2.1.4 GABA 临床试验争议

 [匿名] (2025). Long-term Gamma-Aminobutyric Acid (GABA) Treatment Fails to Regain Beta-Cell Function in Longstanding Type 1 Diabetes in a Randomized Trial. Scientific Reports, 15 95751.
 [论文链接](httpswww.aminer.cnpub67ef5fed163c01c85066e0d0)
 DOI 10.1038s41598-025-95751-y
 研究类型：Original Article (人体 · 随机对照试验)
 证据等级：⭐⭐⭐
 核心结论：长期 GABA 治疗未能恢复长期 T1D 患者的 β 细胞功能。
 关联：提示 α→β 转分化策略在长期 T1D 中可能面临挑战，疾病阶段和残余 β 细胞量是关键变量。

#### 2.1.5 GABA 争议

 [匿名] (2023). GABA Treatment Does Not Induce Neogenesis of New Endocrine Cells from Pancreatic Ductal Cells. Islets, 15(1) 2219477.
 [论文链接](httpswww.aminer.cnpub64a390e1d68f896efa1fa25b)
 DOI 10.108019382014.2023.2219477
 研究类型：Original Article (小鼠)
 证据等级：⭐⭐
 核心结论：GABA 处理未能诱导导管细胞产生新的内分泌细胞。
 关联：提示 GABA 的作用可能主要通过 α→β 转分化而非导管→β 路径。

#### 2.1.6 Pax4 基因治疗

 [匿名] (2024). PAX4 Gene Delivery Improves β-Cell Function in Human Islets of Type II Diabetes. Expert Opinion on Biological Therapy, 24(6) 2343538.
 [论文链接](httpswww.aminer.cnpub6648091501d2a3fbfcf0467d)
 DOI 10.108017460751.2024.2343538
 研究类型：Original Article (人体胰岛 · 体外基因治疗)
 证据等级：⭐⭐
 核心结论：PAX4 基因递送改善 T2D 人体胰岛的 β 细胞功能。
 关联：验证 Pax4 介导的 α→β 转分化策略在人体组织中的可行性。

### 2.2 β→α 转分化（反向转分化）

β→α 转分化是去分化的下游事件之一：

 Lee K, et al. (2022) (同上) 在 XBP1 敲除小鼠中直接通过 Lineage tracing 证实 β→α 转分化。XBP1 缺失后，β 细胞身份基因（Insulin, Pdx1, Nkx6.1）下调，α 细胞基因（Glucagon, Arx, Irx2）去抑制。

此发现的重要意义在于：β 细胞丢失不仅是凋亡，部分 β 细胞可能变身为 α 细胞，这可以解释 T2D 中 α 细胞扩增和胰高血糖素过多的现象。

### 2.3 ε→β 转分化

 [匿名] (2023). Pax4-Ghrelin Mediates the Conversion of Pancreatic ε-Cells to β-Cells after Extreme β-Cell Loss in Zebrafish. Development, 150(6) dev201306.
 [论文链接](httpswww.aminer.cnpub640c5de790e50fcafd619ab2)
 DOI 10.1242dev.201306
 研究类型：Original Article (斑马鱼 · Lineage tracing)
 证据等级：⭐⭐
 核心结论：极端 β 细胞缺失后，Pax4-Ghrelin 介导 ε 细胞（ghrelin 分泌细胞）转化为 β 细胞。
 关联：揭示了 ε 细胞作为 β 细胞再生来源的潜在可能。

### 2.4 导管→β 转分化

导管→β 转分化在人类中的证据仍存在争议：

 Spears E, et al. (2021). Debates in Pancreatic Beta Cell Biology Proliferation Versus Progenitor Differentiation and Transdifferentiation in Restoring β Cell Mass. Frontiers in Endocrinology, 12 722250.
 [论文链接](httpswww.aminer.cnpub6124d13b5244ab9dcb9ae36b)
 DOI 10.3389fendo.2021.722250
 研究类型：Review
 证据等级：⭐⭐
 核心结论：系统梳理了 β 细胞再生领域增殖 vs. 前体分化 vs. 转分化的争议，指出小鼠与人类之间存在差异，共识尚未形成。
 关联：提供了转分化各路径证据等级的全面评估框架。

 [匿名] (2023). Dynamic scRNA-Seq of Live Human Pancreatic Slices Reveals Functional Endocrine Cell Neogenesis Through an Intermediate Ducto-Acinar Stage. Cell Metabolism, 35(11) 2054–2069.
 [论文链接](httpswww.aminer.cnpub653f4529939a5f4082cb6bbc)
 DOI 10.1016j.cmet.2023.10.001
 研究类型：Original Article (人体 · 活组织切片 · 动态 scRNA-seq)
 证据等级：⭐⭐⭐
 核心结论：活体人胰腺切片动态 scRNA-seq 揭示功能性内分泌细胞新生，通过中间导管-腺泡阶段。
 关联：为人体中导管→β 转分化新生提供了动态转录组学证据。

### 2.5 腺泡→β 转分化

 [匿名] (2023). Charting a High-Resolution Roadmap for Regeneration of Pancreatic β Cells by in Vivo Transdifferentiation from Adult Acinar Cells. Science Advances, 9 eadg2183.
 [论文链接](httpswww.aminer.cnpub64874209d68f896efaf9b2dc)
 DOI 10.1126sciadv.adg2183
 研究类型：Original Article (小鼠 · 体内重编程 · Lineage tracing)
 证据等级：⭐⭐⭐
 核心结论：绘制了体内腺泡→β 转分化的高分辨率路线图，鉴定了关键中间状态和调控因子。
 关联：为体内重编程策略提供了分子路线图。

### 2.6 转分化路径证据等级总结

 转分化方向  关键转录因子信号  动物证据  人体证据  临床转化  证据等级 
----------------------------------------------------------------
 α→β  Pax4↑, Arx↓, GABA  ⭐⭐⭐ (小鼠斑马鱼)  ⭐⭐⭐ (人胰岛体外)  GABA 临床试验阴性 (T1D)  ⭐⭐ 
 β→α  XBP1↓, FoxO1↓  ⭐⭐⭐ (小鼠 Lineage tracing)  ⭐⭐ (人体免疫染色)  —  ⭐⭐ 
 ε→β  Pax4-Ghrelin  ⭐⭐ (斑马鱼)  无  —  ⭐ 
 导管→β  Ngn3, Pdx1, MafA  ⭐⭐ (小鼠)  ⭐⭐ (人胰腺切片)  —  ⭐ 
 腺泡→β  Ngn3, Pdx1, MafA  ⭐⭐⭐ (小鼠 Lineage tracing)  无  —  ⭐⭐ 
 δ→β  —  ⭐ (有限)  无  —  ⭐ 

---

## 三、对糖尿病发病机制的意义

### 3.1 1 型糖尿病 (T1DM)

#### 去分化是否帮助 β 细胞逃避免疫攻击？

推测性假说（尚有争议）：去分化的 β 细胞下调了自身抗原（如胰岛素、GAD65、ZnT8），可能降低自身免疫识别。支持证据包括：

- T1D 患者胰腺中残余 β 细胞中胰岛素表达降低
- 长病程 T1D 患者仍可检测到少量 β 细胞，但功能低下

 Fasolino M, et al. (2022) 发现 T1D 胰岛中导管细胞获得免疫调节特征，提示非 β 细胞的免疫调节作用。⭐⭐⭐

然而，该假说仍缺乏直接因果证据。反对观点认为：β 细胞的丢失主要由自身免疫攻击驱动，去分化可能是应激的次级反应而非主动免疫逃逸策略。

#### 是否存在重新分化的可能？

已有初步证据支持：

- 严重高血糖纠正后 β 细胞再生潜力恢复（Furth-Lavi et al. 2022）⭐⭐⭐
- ALDH1A3⁺ 去分化细胞可逆转为功能 β 细胞（Son et al. 2023）⭐⭐⭐
- 但长期 T1D 中 GABA 治疗未能恢复 β 细胞功能（2025 RCT）⭐⭐⭐

结论：在 T1D 早期新发阶段，β 细胞去分化可能部分可逆；但在长期 T1D 中，免疫破坏已不可逆，去分化的治疗窗口可能已关闭。

### 3.2 2 型糖尿病 (T2DM)

#### 去分化是否解释 β 细胞数量减少？

已证实：T2D 中 β 细胞质量减少约 24–65%（经典数据）。去分化提供了一个不依赖凋亡的 β 细胞消失机制：

- 去分化 β 细胞因丧失胰岛素表达而在常规染色中不可见
- Lineage tracing 证实去分化 β 细胞可转化为 α 细胞（Lee et al. 2022）

#### 去分化 vs. 凋亡：哪个更重要？

仍存在争议。当前证据倾向认为：

 机制  证据强度  说明 
---------------------
 去分化  ⭐⭐⭐  人体胰腺 + 单细胞 + Lineage tracing 
 凋亡  ⭐⭐  人体中凋亡检测率低且不一致 
 内质网应激  ⭐⭐⭐  人体活检直接关联 (Brusco 2023) 
 葡萄糖毒性  ⭐⭐⭐  血糖纠正后可逆 (Furth-Lavi 2022) 
 脂毒性  ⭐⭐  SCD1 抑制→身份丢失 (Dobosz 2023) 
 炎症  ⭐⭐  IAPP 诱导应激 (Diabetologia 2021) 

 Brusco et al. (2023) 的人体研究表明，胰岛素合成缺陷→ER 应激→身份丢失是一个连续过程，去分化可能是葡萄糖毒性和 ER 应激的下游后果。⭐⭐⭐

 Li et al. (2025) 证明糖毒性→LDHA→H3K9la→去分化标志物活化是一条完整的代谢-表观遗传通路。⭐⭐⭐

#### 与葡萄糖毒性、脂毒性、ER 应激、炎症的关系

基于现有证据，可以构建如下因果链条模型：

```
高血糖（葡萄糖毒性） ──→ FoxO1 核排除 ──→ 身份基因下调
        │                                    │
        ├──→ LDHA 活化 ──→ H3K9la ──→ 去分化基因激活
        │
        ├──→ ER 应激（XBP1PERK）──→ UPR ──→ 身份丢失 + β→α 转分化
        │
高脂（脂毒性） ──→ SCD1↓ ──→ Pdx1MafA 启动子甲基化 ──→ 身份丢失
        │
IAPP 聚集 ──→ ER 应激 ──→ β 细胞应激转录组（类似 T2D）
        │
炎症因子 ──→ 氧化应激 ──→ β 细胞身份丢失
                    ↓
            去分化 ←→ β→α 转分化 ←→ 凋亡
                    ↓
            β 细胞质量↓ + α 细胞质量↑
                    ↓
            胰岛素↓ + 胰高血糖素↑ = 高血糖
```

---

## 四、治疗意义

### 4.1 阻止 β 细胞去分化

 策略  靶点药物  证据  阶段 
---------------------------
 ALDH1A3 抑制  选择性 ALDH1A3 抑制剂  小鼠有效 ⭐⭐⭐  临床前 
 LDHA 抑制  LDHA 抑制剂  小鼠有效 ⭐⭐⭐  临床前 
 XBP1UPR 增强  XBP1 通路  小鼠敲除模型反证 ⭐⭐⭐  临床前 
 GLP-1 受体激动剂  利拉鲁肽  人胰岛体外抑制去分化基因 ⭐⭐  已上市（但非去分化适应症） 
 桑叶生物碱  Morus Alba alkaloids  小鼠防止去分化+凋亡 ⭐⭐  临床前 
 大柴胡汤  改良大柴胡汤  网络药理学+实验验证 ⭐  临床前 
 Sirt3  Sirt3 激活剂  T2D 模型 ⭐⭐  临床前 
 血管紧张素(1-7)  Mas受体WntFoxO1  体外 ⭐⭐  临床前 

### 4.2 诱导 β 细胞重新成熟

 Son et al. (2023) 的 ALDH1A3 抑制策略直接靶向去分化标志物，证明去分化 β 细胞可重新分化。⭐⭐⭐

 Furth-Lavi et al. (2022) 证明血糖纠正（胰岛素SGLT2i生酮饮食）可释放 β 细胞再生潜力，提示严格控制血糖本身就是最有效的重新成熟策略。⭐⭐⭐

### 4.3 α→β 转分化恢复 β 细胞数量

 策略  证据  阶段 
------------------
 GABA  小鼠 α→β ⭐⭐；人体 T1D RCT 阴性 ⭐⭐⭐  临床试验（失败） 
 青蒿素  斑马鱼 α→β ⭐⭐  临床前 
 Pax4 基因治疗  人 T2D 胰岛体外有效 ⭐⭐  临床前 
 DYRK1A 抑制剂 (harmine)  人胰岛增殖 ⭐⭐  临床前 
 胰高血糖素受体拮抗  小鼠 β 细胞再生 ⭐⭐⭐  临床前 

 [匿名] (2022). Glucagon-receptor-antagonism-mediated β-Cell Regeneration As an Effective Anti-Diabetic Therapy. Cell Reports, 39(8) 110872.
 [论文链接](httpswww.aminer.cnpub618516b26750f8642ef24fca)
 DOI 10.1016j.celrep.2022.110872
 研究类型：Original Article (小鼠)
 证据等级：⭐⭐⭐
 核心结论：胰高血糖素受体拮抗通过促进 α→β 转分化实现 β 细胞再生，有效抗糖尿病。
 关联：提供了一个已进入临床开发阶段（胰高血糖素受体抗体）的潜在转分化诱导策略。

### 4.4 干细胞衍生 β 细胞替代治疗

这是目前最接近临床应用的策略：

 [匿名] (2024). Transplantation of Chemically Induced Pluripotent Stem-Cell-derived Islets under Abdominal Anterior Rectus Sheath in a Type 1 Diabetes Patient. Cell, 187(20) 5772–5786.
 [论文链接](httpswww.aminer.cnpub66f438c101d2a3fbfcd5466e)
 DOI 10.1016j.cell.2024.09.004
 研究类型：Original Article (人体 · 个案报告)
 证据等级：⭐⭐⭐
 核心结论：化学诱导多能干细胞衍生胰岛移植至 T1D 患者腹直肌前鞘，患者恢复内源性胰岛素分泌。
 关联：中国首例干细胞衍生胰岛移植临床报告，展示了干细胞替代疗法的可行性。

VX-880 (zimislecel) 临床试验：

根据 web 搜索获取的公开信息，Vertex 公司的 VX-880 是首款获得 FDA 快速审批通道的干细胞衍生胰岛替代疗法。在 12 期临床试验中，10 名接受全剂量治疗的患者在 1 年后均不再需要每日胰岛素注射，这是历史上首次实现 T1D 患者持续内源性胰岛素产生。所有患者需持续免疫抑制治疗。2025 年 ADA 会议公布的数据显示 70%+ 时间在目标血糖范围内。然而，据报道首例接受治疗的患者（Brian Shelton）后续去世，临床试验一度暂停。（来源：[diatribe.org](httpsdiatribe.orgdiabetes-medicationsvertex-releases-new-data-potential-cure-type-1-diabetes)，[medlive.cn](httpsnews.medlive.cnallinfo-progressshow-207400_46.html)）

 [匿名] (2023). Developments in Stem Cell-Derived Islet Replacement Therapy for Treating Type 1 Diabetes. Cell Stem Cell, 30(5) 589–606.
 [论文链接](httpswww.aminer.cnpub64af65683fda6d7f06392a07)
 DOI 10.1016j.stem.2023.04.002
 研究类型：Review
 证据等级：⭐⭐⭐
 核心结论：系统综述了干细胞衍生胰岛替代疗法的发展，包括分化方案优化、免疫保护策略和临床试验进展。
 关联：全面概述干细胞替代疗法的现状与挑战。

### 4.5 治疗策略评价总结

 策略  机制  阶段  最大挑战 
---------------------------
 ALDH1A3 抑制  阻止逆转去分化  临床前  靶点特异性、体内递送 
 LDHA 抑制  阻止表观遗传去分化  临床前  全身毒性 
 血糖严格控制  释放再生潜力  已临床  早期干预窗口 
 GLP-1RA  抑制去分化基因  已临床  对去分化特异性效应有限 
 GABA  α→β 转分化  临床试验（T1D 阴性）  长期 T1D 无效 
 Pax4 基因治疗  α→β 转分化  临床前  基因递送安全性 
 胰高血糖素受体拮抗  α→β 转分化  临床前临床开发  需验证转分化机制 
 干细胞衍生胰岛 (VX-880)  β 细胞替代  12 期临床  免疫抑制、长期安全性 
 化学诱导 iPSC 胰岛  β 细胞替代  个案报告  规模化、免疫抑制 
 体内重编程 (腺泡→β)  转分化  临床前  效率、安全性 

---

## 五、目前学界共识与争议

### 5.1 已形成共识

1. β 细胞去分化确实发生 — 在 T2D 人体胰腺和多种动物模型中均有充分证据 ⭐⭐⭐
2. 去分化是可逆的 — Lineage tracing 在小鼠中明确证实；血糖纠正后人体 β 细胞功能可恢复 ⭐⭐⭐
3. FoxO1 是 β 细胞身份的核心守门因子 — 多项独立研究证实 ⭐⭐⭐
4. β→α 转分化在动物模型中存在 — XBP1FoxO1 敲除模型 + Lineage tracing ⭐⭐⭐
5. ER 应激与去分化密切相关 — 人体活检直接证据 (Brusco 2023) ⭐⭐⭐
6. 干细胞衍生胰岛可恢复胰岛素分泌 — VX-880 临床试验 ⭐⭐⭐
7. 严格血糖控制可改善 β 细胞功能 — 多项临床研究 ⭐⭐⭐

### 5.2 证据较充分但尚需确认

1. α→β 转分化在人体中可发生 — 人胰岛体外药物处理证据 (Med-X 2024)，但体内证据不足 ⭐⭐
2. 去分化比凋亡更重要 — 人体中凋亡率低且不一致，去分化可能贡献更大，但尚无直接定量比较 ⭐⭐
3. 去分化是 β 细胞消失的主要机制 — 去分化使 β 细胞在常规染色中不可见，但比例尚有争议 ⭐⭐
4. LDHAH3K9la 通路驱动去分化 — 人体+小鼠证据，但需独立验证 ⭐⭐

### 5.3 仍存在争议

1. 去分化是否帮助 T1D β 细胞逃避免疫攻击 — 仅有间接证据，缺乏因果证明 ⭐
2. 导管→β 转分化在成年人体中是否生理性发生 — 小鼠与人体结论不一致 ⭐
3. GABA 是否能在人体内诱导 α→β 转分化 — 临床试验阴性，但可能因疾病阶段 ⭐
4. STZ 模型是否适合研究人 T2D 去分化 — MIA 图谱显示 STZ 更类似 T2D 而非 T1D，但存在争议 ⭐⭐
5. β 细胞去分化 vs. 凋亡在 T2D 中的相对贡献 — 缺乏人体纵向定量研究 ⭐⭐

### 5.4 未来重点研究方向

1. 人体纵向研究 — 利用 nPOD 等生物样本库，结合单细胞多组学，追踪去分化转分化在疾病进程中的动态变化
2. 去分化 β 细胞的无创标志物 — CD81 等表面标志物的循环检测开发
3. 靶向去分化的药物开发 — ALDH1A3LDHA 抑制剂的临床转化
4. 免疫保护型干细胞衍生胰岛 — 基因编辑（HLA 敲除免疫检查点过表达）消除免疫抑制需求
5. 体内重编程的安全性优化 — 腺泡→β 转分化的可控递送系统
6. 早期干预窗口的确定 — 去分化可逆性的时间边界
7. 单细胞表观遗传组学 — 染色质可及性、DNA 甲基化、组蛋白修饰在去分化中的动态变化

---

## 参考文献

### 引用论文列表

 #  第一作者  年份  标题  期刊  DOI  研究类型  核心结论  与本综述关联 
-----------------------------------------------------------------
 1  Talchai C  2012  Pancreatic beta cell dedifferentiation into neurogenin3-positive progenitor cells...  Diabetologia  —  Original (Animal)  FoxO1缺失致β细胞去分化  概念基石 
 2  Salinno C  2021  CD81 Marks Immature and Dedifferentiated Pancreatic β-Cells  Mol Metab  10.1016j.molmet.2021.101188  Original (Animal+Human)  CD81标记去分化β细胞  鉴定方法 
 3  Spears E  2021  Debates in Pancreatic Beta Cell Biology Proliferation vs...  Front Endocrinol  10.3389fendo.2021.722250  Review  转分化争议综述  转分化证据评估 
 4  Lee K  2022  XBP1 Maintains Beta Cell Identity, Represses β-to-α Transdifferentiation...  Diabetologia  10.1007s00125-022-05669-7  Original (Animal)  XBP1缺失→去分化+β→α  ER应激机制 
 5  Wang W  2021  Targeting β-Cell Dedifferentiation and Transdifferentiation Opportunities...  Endocr Connect  10.1530ec-21-0260  Review  去分化转分化治疗综述  治疗策略框架 
 6  [匿名]  2021  An Inhibitor-Mediated Beta-Cell Dedifferentiation Model...  Mol Metab  10.1016j.molmet.2021.101329  Original (In vitro)  FoxO1双重角色  分子机制 
 7  [匿名]  2021  Oxidative Stress Leads to β-Cell Dysfunction Through Loss of Identity  Front Immunol  10.3389fimmu.2021.690379  Review  氧化应激→身份丢失  应激机制 
 8  Brusco N  2023  Intra-islet Insulin Synthesis Defects Are Associated with ER Stress...  Diabetologia  10.1007s00125-022-05814-2  Original (Human)  ER应激→身份丢失(人体)  人体证据 
 9  Son J  2023  Genetic and Pharmacologic Inhibition of ALDH1A3 As a Treatment...  Nat Commun  10.1038s41467-023-36315-4  Original (Animal)  ALDH1A3抑制→逆转去分化  可逆性+治疗 
 10  Li X  2025  LDHA Induces Beta Cell Dedifferentiation...Through Metabolic...  Diabetologia  10.1007s00125-025-06626-w  Original (Human+Animal)  LDHAH3K9la驱动去分化  表观遗传机制 
 11  Collombat P  2005  The Simultaneous Loss of Arx and Pax4 Genes Promotes...  Development  10.1242dev.01870  Original (Animal)  ArxPax4决定αβ命运  转分化理论基石 
 12  Jia J  2022  Artemether and Aspterric Acid Induce Pancreatic Alpha Cells...  Br J Pharmacol  10.1111bph.15769  Original (Zebrafish)  青蒿素诱导α→β  药物诱导转分化 
 13  Sarnobat D  2022  GABA and Insulin but Not Nicotinamide Augment α-to-β...  Biochem Pharmacol  10.1016j.bcp.2022.115019  Original (Animal)  GABA+胰岛素促α→β  转分化信号 
 14  [匿名]  2024  Cycling Alpha Cells in Regenerative Drug-Treated Human Pancreatic Islets...  Med-X  10.1016j.xcrm.2024.101832  Original (Human)  人胰岛中α→β证据  人体转分化证据 
 15  [匿名]  2025  Long-term GABA Treatment Fails to Regain Beta-Cell Function...  Sci Rep  10.1038s41598-025-95751-y  Original (Human RCT)  GABA对长期T1D无效  转分化临床争议 
 16  [匿名]  2023  GABA Treatment Does Not Induce Neogenesis...from Ductal Cells  Islets  10.108019382014.2023.2219477  Original (Animal)  GABA不诱导导管→β  转分化路径争议 
 17  [匿名]  2024  PAX4 Gene Delivery Improves β-Cell Function in Human Islets of T2D  Expert Opin Biol Ther  10.108017460751.2024.2343538  Original (Human)  PAX4改善人T2D胰岛功能  基因治疗 
 18  [匿名]  2023  Pax4-Ghrelin Mediates ε→β Conversion in Zebrafish  Development  10.1242dev.201306  Original (Zebrafish)  ε→β转分化  新转分化路径 
 19  [匿名]  2023  Charting a High-Resolution Roadmap for...Acinar→β  Sci Adv  10.1126sciadv.adg2183  Original (Animal)  腺泡→β体内重编程路线图  体内重编程 
 20  Furth-Lavi J  2022  Glycemic Control Releases Regenerative Potential...  Cell Rep  10.1016j.celrep.2022.111719  Original (Animal)  血糖纠正→β再生  可逆性+治疗 
 21  Fasolino M  2022  Single-cell Multi-Omics Analysis of Human Pancreatic Islets...T1D  Nat Metab  10.1038s42255-022-00531-x  Original (Human)  T1D单细胞图谱  T1D机制 
 22  Wang G  2023  Integrating Genetics with Single-Cell Multiomic...T2D  Nat Genet  10.1038s41588-023-01397-9  Original (Human)  T2D β细胞亚型转换  T2D机制 
 23  Hrovatin K  2023  Delineating Mouse β-Cell Identity...with a Single Cell Atlas  Nat Metab  10.1038s42255-023-00876-x  Original (Animal)  小鼠胰岛细胞图谱  模型比较 
 24  Chiou J  2021  Single Cell Chromatin Accessibility Reveals...Diabetes Risk  Nat Genet  10.1038s41588-021-00823-0  Original (Human)  表观遗传调控程序  遗传风险机制 
 25  Dobosz AM  2023  Inhibition of SCD1...Promotes Loss of β-Cell Identity...  Mol Metab  10.1016j.molmet.2022.101659  Original (Animal)  脂毒性→身份丢失  脂毒性机制 
 26  [匿名]  2022  Glucagon-receptor-antagonism-mediated β-Cell Regeneration...  Cell Rep  10.1016j.celrep.2022.110872  Original (Animal)  GlucR拮抗→β再生  转分化治疗 
 27  [匿名]  2024  Transplantation of...iPSC-derived Islets...in T1D Patient  Cell  10.1016j.cell.2024.09.004  Original (Human)  iPSC胰岛移植首例  干细胞治疗 
 28  [匿名]  2023  Developments in Stem Cell-Derived Islet Replacement Therapy...  Cell Stem Cell  10.1016j.stem.2023.04.002  Review  干细胞疗法综述  治疗综述 
 29  [匿名]  2023  Dynamic scRNA-Seq of Live Human Pancreatic Slices...  Cell Metab  10.1016j.cmet.2023.10.001  Original (Human)  人体内分泌细胞新生  导管→β证据 
 30  [匿名]  2024  ISL1 Controls Pancreatic Alpha Cell Fate and Beta Cell Maturation  Cell Biosci  10.1186s13578-023-01003-9  Original (Animal)  ISL1调控αβ命运  转录因子 
 31  [匿名]  2022  Pancreatic Islet Cell Plasticity Pathogenic or Therapeutically Exploitable  Diab Obes Metab  10.1111dom.15300  Review  胰岛可塑性综述  综合综述 
 32  [匿名]  2021  Brief Review of the Mechanisms of β-Cell Dedifferentiation in T2D  Nutrients  10.3390nu13051593  Review  T2D去分化机制综述  机制综述 
 33  [匿名]  2024  Pancreatic β-Cell Failure, Clinical Implications, and Therapeutic Strategies in T2D  Chin Med J  10.1097cm9.0000000000003034  Review  T2D治疗策略综述  治疗综述 

---

## 结语

β 细胞去分化与转分化研究在过去五年取得了显著进展。单细胞多组学技术革命性地推动了对 β 细胞状态异质性和疾病进程的理解。关键共识包括：去分化确实发生且可逆、FoxO1XBP1ALDH1A3 是核心调控节点、α→β 转分化在动物模型中证据充分但人体转化仍面临挑战。最大的治疗突破来自干细胞衍生胰岛替代疗法（VX-880），已实现 T1D 患者胰岛素独立。然而，去分化是否在 T1D 中具有免疫逃逸功能、导管→β 转分化在人体中的生理意义、以及如何安全有效地在体内诱导转分化等问题仍待解答。未来需要更多人体纵向研究、无创标志物开发和靶向药物的临床转化来推进这一领域。
