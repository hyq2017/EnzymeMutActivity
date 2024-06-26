# 酶蛋白突变体催化活性变化数据平台


# 简述:
单点位突变对酶活的影响, Mutation_Resi表示突变位点; Mutation_Type表示突变类型, 左边为突变前; label为突变对酶催化活性的影响（1表示升高，0表示降低）; Uniprot_Sequence是原始蛋白的序列信息.

# 用途
本数据库通过文献和数据库挖掘，并补充项目研究中获得的酶蛋白质突变体活性数据建立，数据库提供野生型酶蛋白序列、突变信息、突变体催化活性变化信息，为机器学习算法开发、模型构建提供标准的酶蛋白活性数据基础。

# 数据来源
酶活性部分数据挖掘自D3DistalMutation，Uniprot等公开数据库，来源于公开发表的文献；部分数据来源于项目研究过程中的实验结果，蛋白质表达和催化活性由上海交通大学、厦门大学、上海锐康生物技术有限公司等实验团队完成，质粒来源于碧云天生物技术有限公司等单位，菌株构建、突变构建、蛋白质表达及催化活性变化均采用通用流程。

# 使用方式
本数据库格式为纯文本tsv，文件内的数据以指标符 '\t' 分隔；用户可直接下载源文件到本地，进行数据查询或者机器学习建模。
