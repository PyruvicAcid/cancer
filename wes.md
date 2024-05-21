## TMB

**Tumor mutation burden 肿瘤突变负荷**

**定义：** 样本中的突变总数除以 WES 检测捕获的基因组（编码）区域的长度，单位`mut/Mb`。

> Chalmers, Z.R., Connelly, C.F., Fabrizio, D. *et al.* Analysis of 100,000 human cancer genomes reveals the landscape of tumor mutational burden. *Genome Med* **9**, 34 (2017).

**高TMB：**`>10 mut/Mb`

**优化：** 靶向基因Panel测序（__MSK-IMPACT__，__FoundationOne CDx__），提高测序深度，降低测序成本，检出罕见突变。

| 方法                    | WES                                      | FM NGS                                                       | MSKCC NGS                            |
| ----------------------- | ---------------------------------------- | ------------------------------------------------------------ | ------------------------------------ |
| **基因数量**            | 22000                                    | 324                                                          | 468                                  |
| **捕获的突变类型**      | 编码肿瘤基因组中的错义突变               | 每 Mb 肿瘤基因组的编码、错义和插入缺失突变                   | 每 Mb 肿瘤基因组编码错义突变         |
| **种系突变**            | 使用患者匹配的正常样本进行减去           | 通过生物信息学算法估计并减去                                 | 使用患者匹配的血液样本进行减去       |
| **捕获区域（肿瘤DNA）** | 〜30 Mb                                  | 0.8 Mb                                                       | 1.22 Mb                              |
| **TMB定义**             | 已测序的肿瘤基因组中体细胞错义突变的数量 | 体细胞数量、编码突变（同义和非同义）、每 Mb 肿瘤基因组的短插入缺失 | 每 Mb 肿瘤基因组的体细胞错义突变数量 |

![](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6249620/bin/tlcr-07-06-703-f3.jpg)

> Chan T A, Yarchoan M, Jaffee E, et al. Development of tumor mutation burden as an immunotherapy biomarker: utility for the oncology clinic[J]. Annals of Oncology, 2019, 30(1): 44-56.
>
> Allgäuer M, Budczies J, Christopoulos P, et al. Implementing tumor mutational burden (TMB) analysis in routine diagnostics—a primer for molecular pathologists and clinicians[J]. Translational lung cancer research, 2018, 7(6): 703.

### Truncal TMB

### Subclonal TMB (clonal in >1 region)

## Subclonal diversity within region (min)

## Recent subclonal expansion score

## WGII

## FLOH

## SCNA ITH

**Somatic copy number alteration 体细胞拷贝数改变**

**定义：**

- **Copy number alteration (CNA) 拷贝数改变：** 所有大于 10 KB 的子臂获得或损失。
- **Aneuploidy 非整倍性：** 影响整个染色体臂（不包括近端着丝粒染色体的短臂）或整个染色体的所有 CNA 。
- **Indels：** 所有其他CNA。
- **Somatic copy number alteration (SCNA) 体细胞拷贝数改变：** 体细胞中合子后产生的 CNA 。
- **Copy number variants (CNV) 拷贝数变异：** 发生在生殖系中并因此可遗传的 CNA 。

### ASCAT

**Allele-specific copy number analysis of tumors 肿瘤的等位基因特异性拷贝数分析**

输入SNP阵列数据（BAF， logR），输出等位基因特异性拷贝数及肿瘤纯度。

> Van Loo P, Nordgard S H, Lingjærde O C, et al. Allele-specific copy number analysis of tumors[J]. Proceedings of the National Academy of Sciences, 2010, 107(39): 16910-16915.

1. PhyloCCF
2. Mutation cluster nesting
3. Growing the phylogenetic tree
4. 亚克隆比例
5. Simulation framework
6. WGD
7. De novo extraction of mutational signatures



