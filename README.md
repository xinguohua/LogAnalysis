# LogAnalysis
| Pipeline          | Function            | Project           | Link     |
|-------------------|---------------------|-------------------|----------|
| DataSet           | 日志数据集          | 处理大批量数据工具     | [jar包](https://github.com/xinguohua/ta3-java-consumer)     |
|                   |                     | 分析日志            | [分析日志](https://github.com/xinguohua/pythonProject)    |
|                   |                     | 分析日志            | [ATLAS](https://github.com/xinguohua/ATLAS)    |
| feature           | 处理特征             | FLASH     | [FLASH](https://github.com/DART-Laboratory/Flash-IDS)     |
|                   |                     | kairos            | [kairos](https://github.com/ubc-provenance/kairos)    |
| Log2Graph         | 日志到图            | 项目3             | [Krystal](https://github.com/xinguohua/Krystal)   |
| ThreatReort2Graph | 威胁报告到图        | 项目4             | ToDo     |
|                   |                     | 项目5             | ToDo     |
| GraphSearch       | 图匹配              | Baseline ProvG-Searcher | [ProvG-Searcher](https://github.com/xinguohua/ProvG-Searcher)     |
|                   |                    | Baseline DeepHunter|     |
|                   |                    | Baseline Poirot|    |
|                   |                    | Baseline SimGNN| [SimGNN](https://github.com/xinguohua/SimGNN?tab=readme-ov-file)    |
|                   |                    | 类似 Crosslingula | [Crosslingula](https://github.com/xinguohua/Crosslingula-KG-Matching) |
|                   |                    | Graph Matching Network参考代码| [Graph Matching Network](https://github.com/xinguohua/GMN) |
|                   |                     | SIMGNN部分代码注释             | [SIMGNN](https://github.com/git0254/LogAnalysis)     |
|                   |                    |  Crosslingula代码注释 | [Crosslingula](https://github.com/git0254/Crosslingula-KG-Matching) |
| GraphClassification | 图分类            | Baseline Unicorn             | [Unicorn](https://github.com/crimson-unicorn)     |
|                   |                     | Baseline ThreaTrace             | [ThreaTrace](https://github.com/threaTrace-detector/threaTrace/)     |
|                   |                     | Baseline MAGIC             | [MAGIC](https://github.com/FDUDSDE/MAGIC)     |
|                   |                     | GOG参考代码             | [ImbGNN](https://github.com/EnternalBlueIce/mask-code)     |
| Atlas             | 适配代码             | 数据处理             | [ATLAS适配](https://github.com/EnternalBlueIce/atlas.git)     |



| Components               | 版本                           | 负责人                                                             | 状态     | 是否需要集成 |
|--------------------------|--------------------------------|-----------------------------------------------------------------------------|----------|----------|
| 处理数据成图和特征        | DARPA                          |  guohua                                                                      | ✅ 已完成 | ✅ 是     |
|                          | ATLAS                          | tuoyu/yuebin                                                              | ✅ 已完成 | ✅ 是     |
| 图分割                    | 统一                           | guohua                                                                        | ✅ 已完成 | ✅ 是     |
| 特征向量                  | TransE                         | guohua                                                            | ✅ 已完成 | ❌ 否     |
|                          | word2Vec                       | tuoyu/yuebin                                                               | ⏳ 待完成 | ✅ 是     |
| 模型训练                  | 匹配                           | guohua                                                              | ✅ 已完成 | ✅ 是     |
|                          | 分类                           | tuoyu                                                             | ⏳ 待完成 | ✅ 是     |
|                          | 序列                           | yuebin                                                             | ⏳ 待完成 | ✅ 是     |
| 重构攻击链                | -                              | guohua                                                             | ⏳ 待完成 | ✅ 是     |
| 模型测试                  | 图级                           | guohua                                                             | ✅ 已完成 | ✅ 是     |
|                          | 节点级读数据集label              | tuoyu/yubin                                                             | ⏳ 待完成 | ✅ 是     |
|                          | 时间                           | guohua                                                              | ⏳ 待完成 | ✅ 是     |
|                          | 超参数                         | guohua                                                              | ⏳ 待完成 | ✅ 是     |
|                          |CPU/Memory（重要）                   | tuoyu/yubin                                                              | ⏳ 待完成| ✅ 是     |
|                          | 空间压缩                       | tuoyu/yubin                                                              | ⏳ 待完成 | ✅ 是     |
| Fine-tuning              | -                              | guohua                                                              | ⏳ 待完成 | ✅ 是     |
| **Fine-tuning实验不同参数**    | -                              | guohua                                                              | ⏳ 待完成 | ✅ 是     |
| 图匹配(2个数据集)          | Baseline [ProvG-Searcher](https://github.com/xinguohua/ProvG-Searcher)    |     guowei        | ⏳ 待完成 |  ❌ 否    |
|                          | Baseline DeepHunter            | guohua                                        | ✅ 已完成 | ❌ 否     |
|                          | Baseline Poirot                | yuzhang                                                                            | ⏳ 待补充 | ❌ 否     |
|                          | Baseline [SimGNN](https://github.com/xinguohua/SimGNN?tab=readme-ov-file)   |    guowei        | ⏳ 待完成 |  ❌ 否     |
|                          | [Crosslingula](https://github.com/git0254/Crosslingula-KG-Matching)             | yuzhang       | ⏳ 待完成 |  ❌ 否    |
| 图分类(2个数据集)                      | Baseline [Unicorn](https://github.com/crimson-unicorn)               |             mou                   |⏳ 待完成 |  ❌ 否     |
|                          | Baseline [ThreaTrace](https://github.com/threaTrace-detector/threaTrace/)   |    mou        | ⏳ 待完成 |  ❌ 否    |
|                          | Baseline [MAGIC](https://github.com/FDUDSDE/MAGIC)    |           tuoyu                      | ⏳ 待完成 |  ❌ 否     |
| 图序列 (2个数据集)                     | Baseline Atlas                 |                         peng                 | ⏳ 待完成 | ❌ 否    |
|                          | Baseline shadewashaer          |                         peng                | ⏳ 待完成 | ❌ 否     |
|                          | Baseline prographer            |                         yuebin                                                | ⏳ 待完成 | ❌ 否     |

