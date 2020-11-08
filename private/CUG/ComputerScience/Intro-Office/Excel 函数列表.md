# Excel 函数列表（按类别列出）

*Microsoft 365 专属 Excel* *Microsoft 365 Mac 版专属 Excel* *Excel 网页版* *Excel 2019* *Excel 2016* *Excel 2019 for Mac* *Excel 2013* *Excel 2010* *Excel 2007* *Excel 2016 for Mac* *Excel for Mac 2011* *Excel Starter 2010* 

工作表函数按其功能分类。 单击某个类别可浏览其功能。 也可以通过按住 Ctrl+F 并键入前几个字母或描述性单词来查找函数。 若要获取有关某个函数的详细信息，请在第一列中单击其名称。

## [最常用的 10 个函数](javascript:)

下面是大家见得最多的 10 个函数。

| **函数**                                                     | **说明**                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [SUM 函数](https://support.microsoft.com/zh-cn/office/sum-函数-043e1c7d-7726-4e80-8f32-07b23e057f89) | 此函数用于对单元格中的值求和。                               |
| [IF 函数](https://support.microsoft.com/zh-cn/office/if-函数-69aed7c9-4e8a-4755-a9bc-aa8bbff73be2) | 此函数用于在条件为真时返回一个值，条件为假时返回另一个值。 [下面是 IF 函数的用法视频](https://support.microsoft.com/zh-cn/office/3f12e6c7-887b-487e-a8f3-31742d060729)。 |
| [LOOKUP 函数](https://support.microsoft.com/zh-cn/office/lookup-函数-446d94af-663b-451d-8251-369d5e3864cb) | 需要查询一行或一列并查找另一行或列中的相同位置的值时，请使用此函数。 |
| [VLOOKUP 函数](https://support.microsoft.com/zh-cn/office/vlookup-函数-0bbc8083-26fe-4963-8ab8-93a18ad188a1) | 如果需要按行查找表或区域中的内容，请使用此函数。 例如，按员工号查找某位员工的姓氏，或通过查找员工的姓氏查找该员工的电话号码（就像使用电话簿）。 [请观看这个 VLOOKUP 用法视频](https://support.microsoft.com/zh-cn/office/视频-vlookup-何时以及如何使用它-9a86157a-5542-4148-a536-724823014785)。 |
| [MATCH 函数](https://support.microsoft.com/zh-cn/office/match-函数-e8dffd45-c762-47d6-bf89-533f4a37673a) | 使用此函数搜索单元格区域中的某个项目，然后返回该项目在区域中的相对位置。 例如，如果区域 A1： A3 包含值5、7和38，则公式 = MATCH （7，A1： A3，0）将返回数字2，因为7是区域中的第二个项目。 |
| [CHOOSE 函数](https://support.microsoft.com/zh-cn/office/choose-函数-fc5c184f-cb62-4ec7-a46e-38653b98f5bc) | 此函数用于根据索引号从最多 254 个数值中选择一个。 例如，如果 value1 到 value7 表示一周的 7 天，那么将 1 到 7 之间的数字用作 index_num 时，CHOOSE 将返回其中的某一天。 |
| [DATE 函数](https://support.microsoft.com/zh-cn/office/date-函数-e36c0c8c-4104-49da-ab83-82328b832349) | 此函数用于返回代表特定日期的连续序列号。 此函数在公式，而非单元格引用提供年、月和日的情况中非常有用。 例如，可能有一个工作表所包含的日期使用了 Excel 无法识别的格式（如 YYYYMMDD）。[DATEDIF](https://support.microsoft.com/zh-cn/office/datedif-函数-25dba1a4-2812-480b-84dd-8b32a451b35c) 函数用于计算两个日期之间的天数、月数或年数。 |
| [DAYS 函数](https://support.microsoft.com/zh-cn/office/days-函数-57740535-d549-4395-8728-0f07bff0b9df) | 此函数用于返回两个日期之间的天数。                           |
| [FIND、FINDB 函数](https://support.microsoft.com/zh-cn/office/find、findb-函数-c7912941-af2a-4bdf-a553-d0d89b0a0628) | 函数 FIND 和 FINDB 用于在第二个文本串中定位第一个文本串。 这两个函数返回第一个文本串的起始位置的值，该值从第二个文本串的第一个字符算起。 |
| [INDEX 函数](https://support.microsoft.com/zh-cn/office/index-函数-a5dcf0dd-996d-40a4-a822-b56b061328bd) | 此函数用于返回表格或区域中的值或值的引用。                   |



## [兼容性函数](javascript:)

在 Excel 2010 或更高版本中，用新函数替换了这些函数，这些新函数有更高的精确度，且其名称能更好地反映其用途。 你仍可使用它们以与 Excel 早期版本兼容，但如果不需要向后兼容，则应开始改用新函数。 有关新函数的详细信息，请参阅[统计函数（参考）](https://support.microsoft.com/zh-cn/office/统计函数（参考）-624dac86-a375-4435-bc25-76d659719ffd)和[数学与三角函数（参考）](https://support.microsoft.com/zh-cn/office/数学和三角函数（参考）-ee158fd6-33be-42c9-9ae5-d635c3ae8c16)。

如果您使用的是 Excel 2007 ，则可以在 "**公式**" 选项卡上的 "**统计**" 或 "**数学" Excel 2007 三角函数**中找到这些函数。

| **函数**                                                     | **说明**                                     |
| :----------------------------------------------------------- | :------------------------------------------- |
| [BETADIST 函数](https://support.microsoft.com/zh-cn/office/betadist-函数-49f1b9a9-a5da-470f-8077-5f1730b5fd47) | 返回 beta 累积分布函数                       |
| [BETAINV 函数](https://support.microsoft.com/zh-cn/office/betainv-函数-8b914ade-b902-43c1-ac9c-c05c54f10d6c) | 返回指定 beta 分布的累积分布函数的反函数     |
| [BINOMDIST 函数](https://support.microsoft.com/zh-cn/office/binomdist-函数-506a663e-c4ca-428d-b9a8-05583d68789c) | 返回一元二项式分布的概率                     |
| [CHIDIST 函数](https://support.microsoft.com/zh-cn/office/chidist-函数-c90d0fbc-5b56-4f5f-ab57-34af1bf6897e) | 返回 χ2 分布的单尾概率                       |
| [CHIINV 函数](https://support.microsoft.com/zh-cn/office/chiinv-函数-cfbea3f6-6e4f-40c9-a87f-20472e0512af) | 返回 χ2 分布的单尾概率的反函数               |
| [CHITEST 函数](https://support.microsoft.com/zh-cn/office/chitest-函数-981ff871-b694-4134-848e-38ec704577ac) | 返回独立性检验值                             |
| [CONCATENATE 函数](https://support.microsoft.com/zh-cn/office/concatenate-函数-8f8ae884-2ca8-4f7a-b093-75d702bea31d) | 将 2 个或多个文本字符串联接成 1 个字符串     |
| [CONFIDENCE 函数](https://support.microsoft.com/zh-cn/office/confidence-函数-75ccc007-f77c-4343-bc14-673642091ad6) | 返回总体平均值的置信区间                     |
| [COVAR 函数](https://support.microsoft.com/zh-cn/office/covar-函数-50479552-2c03-4daf-bd71-a5ab88b2db03) | 返回协方差（成对偏差乘积的平均值）           |
| [CRITBINOM 函数](https://support.microsoft.com/zh-cn/office/critbinom-函数-eb6b871d-796b-4d21-b69b-e4350d5f407b) | 返回使累积二项式分布小于或等于临界值的最小值 |
| [EXPONDIST 函数](https://support.microsoft.com/zh-cn/office/expondist-函数-68ab45fd-cd6d-4887-9770-9357eb8ee06a) | 返回指数分布                                 |
| [FDIST 函数](https://support.microsoft.com/zh-cn/office/fdist-函数-ecf76fba-b3f1-4e7d-a57e-6a5b7460b786) | 返回 F 概率分布                              |
| [FINV 函数](https://support.microsoft.com/zh-cn/office/finv-函数-4d46c97c-c368-4852-bc15-41e8e31140b1) | 返回 F 概率分布的反函数                      |
| [FLOOR 函数](https://support.microsoft.com/zh-cn/office/floor-函数-14bb497c-24f2-4e04-b327-b0b4de5a8886) | 向绝对值减小的方向舍入数字                   |
| [FORECAST 函数](https://support.microsoft.com/zh-cn/office/预测和预测。线性函数-50ca49c9-7b40-4892-94e4-7ad38bbeda99) | 使用现有值来计算或预测未来值。               |
| [FTEST 函数](https://support.microsoft.com/zh-cn/office/ftest-函数-4c9e1202-53fe-428c-a737-976f6fc3f9fd) | 返回 F 检验的结果                            |
| [GAMMADIST 函数](https://support.microsoft.com/zh-cn/office/gammadist-函数-7327c94d-0f05-4511-83df-1dd7ed23e19e) | 返回 γ 分布                                  |
| [GAMMAINV 函数](https://support.microsoft.com/zh-cn/office/gammainv-函数-06393558-37ab-47d0-aa63-432f99e7916d) | 返回 γ 累积分布函数的反函数                  |
| [HYPGEOMDIST 函数](https://support.microsoft.com/zh-cn/office/hypgeomdist-函数-23e37961-2871-4195-9629-d0b2c108a12e) | 返回超几何分布                               |
| [LOGINV 函数](https://support.microsoft.com/zh-cn/office/loginv-函数-0bd7631a-2725-482b-afb4-de23df77acfe) | 返回对数累积分布函数的反函数                 |
| [LOGNORMDIST 函数](https://support.microsoft.com/zh-cn/office/lognormdist-函数-f8d194cb-9ee3-4034-8c75-1bdb3884100b) | 返回对数累积分布函数                         |
| [MODE 函数](https://support.microsoft.com/zh-cn/office/mode-函数-e45192ce-9122-4980-82ed-4bdc34973120) | 返回在数据集内出现次数最多的值               |
| [NEGBINOMDIST 函数](https://support.microsoft.com/zh-cn/office/negbinomdist-函数-f59b0a37-bae2-408d-b115-a315609ba714) | 返回负二项式分布                             |
| [NORMDIST 函数](https://support.microsoft.com/zh-cn/office/normdist-函数-126db625-c53e-4591-9a22-c9ff422d6d58) | 返回正态累积分布                             |
| [NORMINV 函数](https://support.microsoft.com/zh-cn/office/norminv-函数-87981ab8-2de0-4cb0-b1aa-e21d4cb879b8) | 返回正态累积分布的反函数                     |
| [NORMSDIST 函数](https://support.microsoft.com/zh-cn/office/normsdist-函数-463369ea-0345-445d-802a-4ff0d6ce7cac) | 返回标准正态累积分布                         |
| [NORMSINV 函数](https://support.microsoft.com/zh-cn/office/normsinv-函数-8d1bce66-8e4d-4f3b-967c-30eed61f019d) | 返回标准正态累积分布函数的反函数             |
| [PERCENTILE 函数](https://support.microsoft.com/zh-cn/office/percentile-函数-91b43a53-543c-4708-93de-d626debdddca) | 返回区域中数值的第 k 个百分点的值            |
| [PERCENTRANK 函数](https://support.microsoft.com/zh-cn/office/percentrank-函数-f1b5836c-9619-4847-9fc9-080ec9024442) | 返回数据集中值的百分比排位                   |
| [POISSON 函数](https://support.microsoft.com/zh-cn/office/poisson-函数-d81f7294-9d7c-4f75-bc23-80aa8624173a) | 返回泊松分布                                 |
| [QUARTILE 函数](https://support.microsoft.com/zh-cn/office/quartile-函数-93cf8f62-60cd-4fdb-8a92-8451041e1a2a) | 返回一组数据的四分位点                       |
| [RANK 函数](https://support.microsoft.com/zh-cn/office/rank-函数-6a2fc49d-1831-4a03-9d8c-c279cf99f723) | 返回一列数字的数字排位                       |
| [STDEV 函数](https://support.microsoft.com/zh-cn/office/stdev-函数-51fecaaa-231e-4bbb-9230-33650a72c9b0) | 基于样本估算标准偏差                         |
| [STDEVP 函数](https://support.microsoft.com/zh-cn/office/stdevp-函数-1f7c1c88-1bec-4422-8242-e9f7dc8bb195) | 基于整个样本总体计算标准偏差                 |
| [TDIST 函数](https://support.microsoft.com/zh-cn/office/tdist-函数-630a7695-4021-4853-9468-4a1f9dcdd192) | 返回学生 t-分布                              |
| [TINV 函数](https://support.microsoft.com/zh-cn/office/tinv-函数-a7c85b9d-90f5-41fe-9ca5-1cd2f3e1ed7c) | 返回学生 t-分布的反函数                      |
| [TTEST 函数](https://support.microsoft.com/zh-cn/office/ttest-函数-1696ffc1-4811-40fd-9d13-a0eaad83c7ae) | 返回与学生 t-检验相关的概率                  |
| [VAR 函数](https://support.microsoft.com/zh-cn/office/var-函数-1f2b7ab2-954d-4e17-ba2c-9e58b15a7da2) | 基于样本估算方差                             |
| [VARP 函数](https://support.microsoft.com/zh-cn/office/varp-函数-26a541c4-ecee-464d-a731-bd4c575b1a6b) | 计算基于样本总体的方差                       |
| [WEIBULL 函数](https://support.microsoft.com/zh-cn/office/weibull-函数-b83dc2c6-260b-4754-bef2-633196f6fdcc) | 返回 Weibull 分布                            |
| [ZTEST 函数](https://support.microsoft.com/zh-cn/office/ztest-函数-8f33be8a-6bd6-4ecc-8e3a-d9a4420c4a6a) | 返回 z 检验的单尾概率值                      |



## [多维数据集函数](javascript:)

| **函数**                                                     | **说明**                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [CUBEKPIMEMBER 函数](https://support.microsoft.com/zh-cn/office/cubekpimember-函数-744608bf-2c62-42cd-b67a-a56109f4b03b) | 返回重要性能指示器 (KPI) 属性，并在单元格中显示 KPI 名称。 KPI 是一种用于监控单位绩效的可计量度量值，如每月总利润或季度员工调整。 |
| [CUBEMEMBER 函数](https://support.microsoft.com/zh-cn/office/cubemember-函数-0f6a15b9-2c18-4819-ae89-e1b5c8b398ad) | 返回多维数据集中的成员或元组。 用于验证多维数据集内是否存在成员或元组。 |
| [CUBEMEMBERPROPERTY 函数](https://support.microsoft.com/zh-cn/office/cubememberproperty-函数-001e57d6-b35a-49e5-abcd-05ff599e8951) | 返回多维数据集中成员属性的值。 用于验证多维数据集内是否存在某个成员名并返回此成员的指定属性。 |
| [CUBERANKEDMEMBER 函数](https://support.microsoft.com/zh-cn/office/cuberankedmember-函数-07efecde-e669-4075-b4bf-6b40df2dc4b3) | 返回集合中的第 n 个或排在一定名次的成员。 用来返回集合中的一个或多个元素，如业绩最好的销售人员或前 10 名的学生。 |
| [CUBESET 函数](https://support.microsoft.com/zh-cn/office/cubeset-函数-5b2146bd-62d6-4d04-9d8f-670e993ee1d9) | 通过向服务器上的多维数据集发送集合表达式来定义一组经过计算的成员或元组（这会创建该集合），然后将该集合返回到 Microsoft Office Excel。 |
| [CUBESETCOUNT 函数](https://support.microsoft.com/zh-cn/office/cubesetcount-函数-c4c2a438-c1ff-4061-80fe-982f2d705286) | 返回集合中的项目数。                                         |
| [CUBEVALUE 函数](https://support.microsoft.com/zh-cn/office/cubevalue-函数-8733da24-26d1-4e34-9b3a-84a8f00dcbe0) | 从多维数据集中返回汇总值。                                   |



## [数据库函数](javascript:)

| **函数**                                                     | **说明**                                     |
| :----------------------------------------------------------- | :------------------------------------------- |
| [DAVERAGE 函数](https://support.microsoft.com/zh-cn/office/daverage-函数-a6a2d5ac-4b4b-48cd-a1d8-7b37834e5aee) | 返回所选数据库条目的平均值                   |
| [DCOUNT 函数](https://support.microsoft.com/zh-cn/office/dcount-函数-c1fc7b93-fb0d-4d8d-97db-8d5f076eaeb1) | 计算数据库中包含数字的单元格的数量           |
| [DCOUNTA 函数](https://support.microsoft.com/zh-cn/office/dcounta-函数-00232a6d-5a66-4a01-a25b-c1653fda1244) | 计算数据库中非空单元格的数量                 |
| [DGET 函数](https://support.microsoft.com/zh-cn/office/dget-函数-455568bf-4eef-45f7-90f0-ec250d00892e) | 从数据库提取符合指定条件的单个记录           |
| [DMAX 函数](https://support.microsoft.com/zh-cn/office/dmax-函数-f4e8209d-8958-4c3d-a1ee-6351665d41c2) | 返回所选数据库条目的最大值                   |
| [DMIN 函数](https://support.microsoft.com/zh-cn/office/dmin-函数-4ae6f1d9-1f26-40f1-a783-6dc3680192a3) | 返回所选数据库条目的最小值                   |
| [DPRODUCT 函数](https://support.microsoft.com/zh-cn/office/dproduct-函数-4f96b13e-d49c-47a7-b769-22f6d017cb31) | 将数据库中符合条件的记录的特定字段中的值相乘 |
| [DSTDEV 函数](https://support.microsoft.com/zh-cn/office/dstdev-函数-026b8c73-616d-4b5e-b072-241871c4ab96) | 基于所选数据库条目的样本估算标准偏差         |
| [DSTDEVP 函数](https://support.microsoft.com/zh-cn/office/dstdevp-函数-04b78995-da03-4813-bbd9-d74fd0f5d94b) | 基于所选数据库条目的样本总体计算标准偏差     |
| [DSUM 函数](https://support.microsoft.com/zh-cn/office/dsum-函数-53181285-0c4b-4f5a-aaa3-529a322be41b) | 对数据库中符合条件的记录的字段列中的数字求和 |
| [DVAR 函数](https://support.microsoft.com/zh-cn/office/dvar-函数-d6747ca9-99c7-48bb-996e-9d7af00f3ed1) | 基于所选数据库条目的样本估算方差             |
| [DVARP 函数](https://support.microsoft.com/zh-cn/office/dvarp-函数-eb0ba387-9cb7-45c8-81e9-0394912502fc) | 基于所选数据库条目的样本总体计算方差         |



## [日期和时间函数](javascript:)

| **函数**                                                     | **说明**                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [DATE 函数](https://support.microsoft.com/zh-cn/office/date-函数-e36c0c8c-4104-49da-ab83-82328b832349) | 返回特定日期的序列号                                         |
| [DATEDIF 函数](https://support.microsoft.com/zh-cn/office/datedif-函数-25dba1a4-2812-480b-84dd-8b32a451b35c) | 计算两个日期之间的天数、月数或年数。 此函数在需要计算年龄的公式中很有用。 |
| [DATEVALUE 函数](https://support.microsoft.com/zh-cn/office/datevalue-函数-df8b07d4-7761-4a93-bc33-b7471bbff252) | 将文本格式的日期转换为序列号                                 |
| [DAY 函数](https://support.microsoft.com/zh-cn/office/day-函数-8a7d1cbb-6c7d-4ba1-8aea-25c134d03101) | 将序列号转换为月份日期                                       |
| [DAYS 函数](https://support.microsoft.com/zh-cn/office/days-函数-57740535-d549-4395-8728-0f07bff0b9df) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回两个日期之间的天数                                       |
| [DAYS360 函数](https://support.microsoft.com/zh-cn/office/days360-函数-b9a509fd-49ef-407e-94df-0cbda5718c2a) | 以一年 360 天为基准计算两个日期间的天数                      |
| [EDATE 函数](https://support.microsoft.com/zh-cn/office/edate-函数-3c920eb2-6e66-44e7-a1f5-753ae47ee4f5) | 返回用于表示开始日期之前或之后月数的日期的序列号             |
| [EOMONTH 函数](https://support.microsoft.com/zh-cn/office/eomonth-函数-7314ffa1-2bc9-4005-9d66-f49db127d628) | 返回指定月数之前或之后的月份的最后一天的序列号               |
| [HOUR 函数](https://support.microsoft.com/zh-cn/office/hour-函数-a3afa879-86cb-4339-b1b5-2dd2d7310ac7) | 将序列号转换为小时                                           |
| [ISOWEEKNUM 函数](https://support.microsoft.com/zh-cn/office/isoweeknum-函数-1c2d0afe-d25b-4ab1-8894-8d0520e90e0e) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回给定日期在全年中的 ISO 周数                              |
| [MINUTE 函数](https://support.microsoft.com/zh-cn/office/minute-函数-af728df0-05c4-4b07-9eed-a84801a60589) | 将序列号转换为分钟                                           |
| [MONTH 函数](https://support.microsoft.com/zh-cn/office/month-函数-579a2881-199b-48b2-ab90-ddba0eba86e8) | 将序列号转换为月                                             |
| [NETWORKDAYS 函数](https://support.microsoft.com/zh-cn/office/networkdays-函数-48e717bf-a7a3-495f-969e-5005e3eb18e7) | 返回两个日期间的完整工作日的天数                             |
| [NETWORKDAYS.INTL 函数](https://support.microsoft.com/zh-cn/office/networkdays-intl-函数-a9b26239-4f20-46a1-9ab8-4e925bfd5e28) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回两个日期之间的完整工作日的天数（使用参数指明周末有几天并指明是哪几天） |
| [NOW 函数](https://support.microsoft.com/zh-cn/office/now-函数-3337fd29-145a-4347-b2e6-20c904739c46) | 返回当前日期和时间的序列号                                   |
| [SECOND 函数](https://support.microsoft.com/zh-cn/office/second-函数-740d1cfc-553c-4099-b668-80eaa24e8af1) | 将序列号转换为秒                                             |
| [TIME 函数](https://support.microsoft.com/zh-cn/office/time-函数-9a5aff99-8f7d-4611-845e-747d0b8d5457) | 返回特定时间的序列号                                         |
| [TIMEVALUE 函数](https://support.microsoft.com/zh-cn/office/timevalue-函数-0b615c12-33d8-4431-bf3d-f3eb6d186645) | 将文本格式的时间转换为序列号                                 |
| [TODAY 函数](https://support.microsoft.com/zh-cn/office/today-函数-5eb3078d-a82c-4736-8930-2f51a028fdd9) | 返回今天日期的序列号                                         |
| [WEEKDAY 函数](https://support.microsoft.com/zh-cn/office/weekday-函数-60e44483-2ed1-439f-8bd0-e404c190949a) | 将序列号转换为星期日期                                       |
| [WEEKNUM 函数](https://support.microsoft.com/zh-cn/office/weeknum-函数-e5c43a03-b4ab-426c-b411-b18c13c75340) | 将序列号转换为代表该星期为一年中第几周的数字                 |
| [WORKDAY 函数](https://support.microsoft.com/zh-cn/office/workday-函数-f764a5b7-05fc-4494-9486-60d494efbf33) | 返回指定的若干个工作日之前或之后的日期的序列号               |
| [WORKDAY.INTL 函数](https://support.microsoft.com/zh-cn/office/workday-intl-函数-a378391c-9ba7-4678-8a39-39611a9bf81d) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回日期在指定的工作日天数之前或之后的序列号（使用参数指明周末有几天并指明是哪几天） |
| [YEAR 函数](https://support.microsoft.com/zh-cn/office/year-函数-c64f017a-1354-490d-981f-578e8ec8d3b9) | 将序列号转换为年                                             |
| [YEARFRAC 函数](https://support.microsoft.com/zh-cn/office/yearfrac-函数-3844141e-c76d-4143-82b6-208454ddc6a8) | 返回代表 start_date 和 end_date 之间整天天数的年分数         |



## [工程函数](javascript:)

| **函数**                                                     | **说明**                                 |
| :----------------------------------------------------------- | :--------------------------------------- |
| [BESSELI 函数](https://support.microsoft.com/zh-cn/office/besseli-函数-8d33855c-9a8d-444b-98e0-852267b1c0df) | 返回修正的贝赛耳函数 In(x)               |
| [BESSELJ 函数](https://support.microsoft.com/zh-cn/office/besselj-函数-839cb181-48de-408b-9d80-bd02982d94f7) | 返回贝赛耳函数 Jn(x)                     |
| [BESSELK 函数](https://support.microsoft.com/zh-cn/office/besselk-函数-606d11bc-06d3-4d53-9ecb-2803e2b90b70) | 返回修正的贝赛耳函数 Kn(x)               |
| [BESSELY 函数](https://support.microsoft.com/zh-cn/office/bessely-函数-f3a356b3-da89-42c3-8974-2da54d6353a2) | 返回贝赛耳函数 Yn(x)                     |
| [BIN2DEC 函数](https://support.microsoft.com/zh-cn/office/bin2dec-函数-63905b57-b3a0-453d-99f4-647bb519cd6c) | 将二进制数转换为十进制数                 |
| [BIN2HEX 函数](https://support.microsoft.com/zh-cn/office/bin2hex-函数-0375e507-f5e5-4077-9af8-28d84f9f41cc) | 将二进制数转换为十六进制数               |
| [BIN2OCT 函数](https://support.microsoft.com/zh-cn/office/bin2oct-函数-0a4e01ba-ac8d-4158-9b29-16c25c4c23fd) | 将二进制数转换为八进制数                 |
| [BITAND 函数](https://support.microsoft.com/zh-cn/office/bitand-函数-8a2be3d7-91c3-4b48-9517-64548008563a) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回两个数的“按位与”                     |
| [BITLSHIFT 函数](https://support.microsoft.com/zh-cn/office/bitlshift-函数-c55bb27e-cacd-4c7c-b258-d80861a03c9c) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回左移 shift_amount 位的计算值接收数   |
| [BITOR 函数](https://support.microsoft.com/zh-cn/office/bitor-函数-f6ead5c8-5b98-4c9e-9053-8ad5234919b2) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回两个数的“按位或”                     |
| [BITRSHIFT 函数](https://support.microsoft.com/zh-cn/office/bitrshift-函数-274d6996-f42c-4743-abdb-4ff95351222c) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回右移 shift_amount 位的计算值接收数   |
| [BITXOR 函数](https://support.microsoft.com/zh-cn/office/bitxor-函数-c81306a1-03f9-4e89-85ac-b86c3cba10e4) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回两个数的按位“异或”                   |
| [COMPLEX 函数](https://support.microsoft.com/zh-cn/office/complex-函数-f0b8f3a9-51cc-4d6d-86fb-3a9362fa4128) | 将实系数和虚系数转换为复数               |
| [CONVERT 函数](https://support.microsoft.com/zh-cn/office/convert-函数-d785bef1-808e-4aac-bdcd-666c810f9af2) | 将数字从一种度量系统转换为另一种度量系统 |
| [DEC2BIN 函数](https://support.microsoft.com/zh-cn/office/dec2bin-函数-0f63dd0e-5d1a-42d8-b511-5bf5c6d43838) | 将十进制数转换为二进制数                 |
| [DEC2HEX 函数](https://support.microsoft.com/zh-cn/office/dec2hex-函数-6344ee8b-b6b5-4c6a-a672-f64666704619) | 将十进制数转换为十六进制数               |
| [DEC2OCT 函数](https://support.microsoft.com/zh-cn/office/dec2oct-函数-c9d835ca-20b7-40c4-8a9e-d3be351ce00f) | 将十进制数转换为八进制数                 |
| [DELTA 函数](https://support.microsoft.com/zh-cn/office/delta-函数-2f763672-c959-4e07-ac33-fe03220ba432) | 检验两个值是否相等                       |
| [ERF 函数](https://support.microsoft.com/zh-cn/office/erf-函数-c53c7e7b-5482-4b6c-883e-56df3c9af349) | 返回误差函数                             |
| [ERF.PRECISE 函数](https://support.microsoft.com/zh-cn/office/erf-precise-函数-9a349593-705c-4278-9a98-e4122831a8e0) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回误差函数                             |
| [ERFC 函数](https://support.microsoft.com/zh-cn/office/erfc-函数-736e0318-70ba-4e8b-8d08-461fe68b71b3) | 返回互补误差函数                         |
| [ERFC.PRECISE 函数](https://support.microsoft.com/zh-cn/office/erfc-precise-函数-e90e6bab-f45e-45df-b2ac-cd2eb4d4a273) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回从 x 到无穷大积分的互补 ERF 函数     |
| [GESTEP 函数](https://support.microsoft.com/zh-cn/office/gestep-函数-f37e7d2a-41da-4129-be95-640883fca9df) | 检验数字是否大于阈值                     |
| [HEX2BIN 函数](https://support.microsoft.com/zh-cn/office/hex2bin-函数-a13aafaa-5737-4920-8424-643e581828c1) | 将十六进制数转换为二进制数               |
| [HEX2DEC 函数](https://support.microsoft.com/zh-cn/office/hex2dec-函数-8c8c3155-9f37-45a5-a3ee-ee5379ef106e) | 将十六进制数转换为十进制数               |
| [HEX2OCT 函数](https://support.microsoft.com/zh-cn/office/hex2oct-函数-54d52808-5d19-4bd0-8a63-1096a5d11912) | 将十六进制数转换为八进制数               |
| [IMABS 函数](https://support.microsoft.com/zh-cn/office/imabs-函数-b31e73c6-d90c-4062-90bc-8eb351d765a1) | 返回复数的绝对值（模数）                 |
| [IMAGINARY 函数](https://support.microsoft.com/zh-cn/office/imaginary-函数-dd5952fd-473d-44d9-95a1-9a17b23e428a) | 返回复数的虚系数                         |
| [IMARGUMENT 函数](https://support.microsoft.com/zh-cn/office/imargument-函数-eed37ec1-23b3-4f59-b9f3-d340358a034a) | 返回参数 theta，即以弧度表示的角         |
| [IMCONJUGATE 函数](https://support.microsoft.com/zh-cn/office/imconjugate-函数-2e2fc1ea-f32b-4f9b-9de6-233853bafd42) | 返回复数的共轭复数                       |
| [IMCOS 函数](https://support.microsoft.com/zh-cn/office/imcos-函数-dad75277-f592-4a6b-ad6c-be93a808a53c) | 返回复数的余弦                           |
| [IMCOSH 函数](https://support.microsoft.com/zh-cn/office/imcosh-函数-053e4ddb-4122-458b-be9a-457c405e90ff) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回复数的双曲余弦值                     |
| [IMCOT 函数](https://support.microsoft.com/zh-cn/office/imcot-函数-dc6a3607-d26a-4d06-8b41-8931da36442c) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回复数的余弦值                         |
| [IMCSC 函数](https://support.microsoft.com/zh-cn/office/imcsc-函数-9e158d8f-2ddf-46cd-9b1d-98e29904a323) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回复数的余割值                         |
| [IMCSCH 函数](https://support.microsoft.com/zh-cn/office/imcsch-函数-c0ae4f54-5f09-4fef-8da0-dc33ea2c5ca9) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回复数的双曲余割值                     |
| [IMDIV 函数](https://support.microsoft.com/zh-cn/office/imdiv-函数-a505aff7-af8a-4451-8142-77ec3d74d83f) | 返回两个复数的商                         |
| [IMEXP 函数](https://support.microsoft.com/zh-cn/office/imexp-函数-c6f8da1f-e024-4c0c-b802-a60e7147a95f) | 返回复数的指数                           |
| [IMLN 函数](https://support.microsoft.com/zh-cn/office/imln-函数-32b98bcf-8b81-437c-a636-6fb3aad509d8) | 返回复数的自然对数                       |
| [IMLOG10 函数](https://support.microsoft.com/zh-cn/office/imlog10-函数-58200fca-e2a2-4271-8a98-ccd4360213a5) | 返回复数的以 10 为底的对数               |
| [IMLOG2 函数](https://support.microsoft.com/zh-cn/office/imlog2-函数-152e13b4-bc79-486c-a243-e6a676878c51) | 返回复数的以 2 为底的对数                |
| [IMPOWER 函数](https://support.microsoft.com/zh-cn/office/impower-函数-210fd2f5-f8ff-4c6a-9d60-30e34fbdef39) | 返回复数的整数幂                         |
| [IMPRODUCT 函数](https://support.microsoft.com/zh-cn/office/improduct-函数-2fb8651a-a4f2-444f-975e-8ba7aab3a5ba) | 返回从 2 到 255 的复数的乘积             |
| [IMREAL 函数](https://support.microsoft.com/zh-cn/office/imreal-函数-d12bc4c0-25d0-4bb3-a25f-ece1938bf366) | 返回复数的实系数                         |
| [IMSEC 函数](https://support.microsoft.com/zh-cn/office/imsec-函数-6df11132-4411-4df4-a3dc-1f17372459e0) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回复数的正切值                         |
| [IMSECH 函数](https://support.microsoft.com/zh-cn/office/imsech-函数-f250304f-788b-4505-954e-eb01fa50903b) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回复数的双曲正切值                     |
| [IMSIN 函数](https://support.microsoft.com/zh-cn/office/imsin-函数-1ab02a39-a721-48de-82ef-f52bf37859f6) | 返回复数的正弦                           |
| [IMSINH 函数](https://support.microsoft.com/zh-cn/office/imsinh-函数-dfb9ec9e-8783-4985-8c42-b028e9e8da3d) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回复数的双曲正弦值                     |
| [IMSQRT 函数](https://support.microsoft.com/zh-cn/office/imsqrt-函数-e1753f80-ba11-4664-a10e-e17368396b70) | 返回复数的平方根                         |
| [IMSUB 函数](https://support.microsoft.com/zh-cn/office/imsub-函数-2e404b4d-4935-4e85-9f52-cb08b9a45054) | 返回两个复数的差                         |
| [IMSUM 函数](https://support.microsoft.com/zh-cn/office/imsum-函数-81542999-5f1c-4da6-9ffe-f1d7aaa9457f) | 返回多个复数的和                         |
| [IMTAN 函数](https://support.microsoft.com/zh-cn/office/imtan-函数-8478f45d-610a-43cf-8544-9fc0b553a132) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回复数的正切值                         |
| [OCT2BIN 函数](https://support.microsoft.com/zh-cn/office/oct2bin-函数-55383471-3c56-4d27-9522-1a8ec646c589) | 将八进制数转换为二进制数                 |
| [OCT2DEC 函数](https://support.microsoft.com/zh-cn/office/oct2dec-函数-87606014-cb98-44b2-8dbb-e48f8ced1554) | 将八进制数转换为十进制数                 |
| [OCT2HEX 函数](https://support.microsoft.com/zh-cn/office/oct2hex-函数-912175b4-d497-41b4-a029-221f051b858f) | 将八进制数转换为十六进制数               |



## [财务函数](javascript:)

| **函数**                                                     | **说明**                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [ACCRINT 函数](https://support.microsoft.com/zh-cn/office/accrint-函数-fe45d089-6722-4fb3-9379-e1f911d8dc74) | 返回定期支付利息的债券的应计利息                             |
| [ACCRINTM 函数](https://support.microsoft.com/zh-cn/office/accrintm-函数-f62f01f9-5754-4cc4-805b-0e70199328a7) | 返回在到期日支付利息的债券的应计利息                         |
| [AMORDEGRC 函数](https://support.microsoft.com/zh-cn/office/amordegrc-函数-a14d0ca1-64a4-42eb-9b3d-b0dededf9e51) | 使用折旧系数返回每个记帐期的折旧值                           |
| [AMORLINC 函数](https://support.microsoft.com/zh-cn/office/amorlinc-函数-7d417b45-f7f5-4dba-a0a5-3451a81079a8) | 返回每个记帐期的折旧值                                       |
| [COUPDAYBS 函数](https://support.microsoft.com/zh-cn/office/coupdaybs-函数-eb9a8dfb-2fb2-4c61-8e5d-690b320cf872) | 返回从票息期开始到结算日之间的天数                           |
| [COUPDAYS 函数](https://support.microsoft.com/zh-cn/office/coupdays-函数-cc64380b-315b-4e7b-950c-b30b0a76f671) | 返回包含结算日的票息期天数                                   |
| [COUPDAYSNC 函数](https://support.microsoft.com/zh-cn/office/coupdaysnc-函数-5ab3f0b2-029f-4a8b-bb65-47d525eea547) | 返回从结算日到下一票息支付日之间的天数                       |
| [COUPNCD 函数](https://support.microsoft.com/zh-cn/office/coupncd-函数-fd962fef-506b-4d9d-8590-16df5393691f) | 返回结算日之后的下一个票息支付日                             |
| [COUPNUM 函数](https://support.microsoft.com/zh-cn/office/coupnum-函数-a90af57b-de53-4969-9c99-dd6139db2522) | 返回结算日与到期日之间可支付的票息数                         |
| [COUPPCD 函数](https://support.microsoft.com/zh-cn/office/couppcd-函数-2eb50473-6ee9-4052-a206-77a9a385d5b3) | 返回结算日之前的上一票息支付日                               |
| [CUMIPMT 函数](https://support.microsoft.com/zh-cn/office/cumipmt-函数-61067bb0-9016-427d-b95b-1a752af0e606) | 返回两个付款期之间累积支付的利息                             |
| [CUMPRINC 函数](https://support.microsoft.com/zh-cn/office/cumprinc-函数-94a4516d-bd65-41a1-bc16-053a6af4c04d) | 返回两个付款期之间为贷款累积支付的本金                       |
| [DB 函数](https://support.microsoft.com/zh-cn/office/db-函数-354e7d28-5f93-4ff1-8a52-eb4ee549d9d7) | 使用固定余额递减法，返回一笔资产在给定期间内的折旧值         |
| [DDB 函数](https://support.microsoft.com/zh-cn/office/ddb-函数-519a7a37-8772-4c96-85c0-ed2c209717a5) | 使用双倍余额递减法或其他指定方法，返回一笔资产在给定期间内的折旧值 |
| [DISC 函数](https://support.microsoft.com/zh-cn/office/disc-函数-71fce9f3-3f05-4acf-a5a3-eac6ef4daa53) | 返回债券的贴现率                                             |
| [DOLLARDE 函数](https://support.microsoft.com/zh-cn/office/dollarde-函数-db85aab0-1677-428a-9dfd-a38476693427) | 将以分数表示的价格转换为以小数表示的价格                     |
| [DOLLARFR 函数](https://support.microsoft.com/zh-cn/office/dollarfr-函数-0835d163-3023-4a33-9824-3042c5d4f495) | 将以小数表示的价格转换为以分数表示的价格                     |
| [DURATION 函数](https://support.microsoft.com/zh-cn/office/duration-函数-b254ea57-eadc-4602-a86a-c8e369334038) | 返回定期支付利息的债券的每年期限                             |
| [EFFECT 函数](https://support.microsoft.com/zh-cn/office/effect-函数-910d4e4c-79e2-4009-95e6-507e04f11bc4) | 返回年有效利率                                               |
| [FV 函数](https://support.microsoft.com/zh-cn/office/fv-函数-2eef9f44-a084-4c61-bdd8-4fe4bb1b71b3) | 返回一笔投资的未来值                                         |
| [FVSCHEDULE 函数](https://support.microsoft.com/zh-cn/office/fvschedule-函数-bec29522-bd87-4082-bab9-a241f3fb251d) | 返回应用一系列复利率计算的初始本金的未来值                   |
| [INTRATE 函数](https://support.microsoft.com/zh-cn/office/intrate-函数-5cb34dde-a221-4cb6-b3eb-0b9e55e1316f) | 返回完全投资型债券的利率                                     |
| [IPMT 函数](https://support.microsoft.com/zh-cn/office/ipmt-函数-5cce0ad6-8402-4a41-8d29-61a0b054cb6f) | 返回一笔投资在给定期间内支付的利息                           |
| [IRR 函数](https://support.microsoft.com/zh-cn/office/irr-函数-64925eaa-9988-495b-b290-3ad0c163c1bc) | 返回一系列现金流的内部收益率                                 |
| [ISPMT 函数](https://support.microsoft.com/zh-cn/office/ispmt-函数-fa58adb6-9d39-4ce0-8f43-75399cea56cc) | 计算特定投资期内要支付的利息                                 |
| [MDURATION 函数](https://support.microsoft.com/zh-cn/office/mduration-函数-b3786a69-4f20-469a-94ad-33e5b90a763c) | 返回假设面值为 ￥100 的有价证券的 Macauley 修正期限          |
| [MIRR 函数](https://support.microsoft.com/zh-cn/office/mirr-函数-b020f038-7492-4fb4-93c1-35c345b53524) | 返回正和负现金流以不同利率进行计算的内部收益率               |
| [NOMINAL 函数](https://support.microsoft.com/zh-cn/office/nominal-函数-7f1ae29b-6b92-435e-b950-ad8b190ddd2b) | 返回年度的名义利率                                           |
| [NPER 函数](https://support.microsoft.com/zh-cn/office/nper-函数-240535b5-6653-4d2d-bfcf-b6a38151d815) | 返回投资的期数                                               |
| [NPV 函数](https://support.microsoft.com/zh-cn/office/npv-函数-8672cb67-2576-4d07-b67b-ac28acf2a568) | 返回基于一系列定期的现金流和贴现率计算的投资的净现值         |
| [ODDFPRICE 函数](https://support.microsoft.com/zh-cn/office/oddfprice-函数-d7d664a8-34df-4233-8d2b-922bcf6a69e1) | 返回每张票面为 ￥100 且第一期为奇数的债券的现价              |
| [ODDFYIELD 函数](https://support.microsoft.com/zh-cn/office/oddfyield-函数-66bc8b7b-6501-4c93-9ce3-2fd16220fe37) | 返回第一期为奇数的债券的收益                                 |
| [ODDLPRICE 函数](https://support.microsoft.com/zh-cn/office/oddlprice-函数-fb657749-d200-4902-afaf-ed5445027fc4) | 返回每张票面为 ￥100 且最后一期为奇数的债券的现价            |
| [ODDLYIELD 函数](https://support.microsoft.com/zh-cn/office/oddlyield-函数-c873d088-cf40-435f-8d41-c8232fee9238) | 返回最后一期为奇数的债券的收益                               |
| [PDURATION 函数](https://support.microsoft.com/zh-cn/office/pduration-函数-44f33460-5be5-4c90-b857-22308892adaf) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回投资到达指定值所需的期数                                 |
| [PMT 函数](https://support.microsoft.com/zh-cn/office/pmt-函数-0214da64-9a63-4996-bc20-214433fa6441) | 返回年金的定期支付金额                                       |
| [PPMT 函数](https://support.microsoft.com/zh-cn/office/ppmt-函数-c370d9e3-7749-4ca4-beea-b06c6ac95e1b) | 返回一笔投资在给定期间内偿还的本金                           |
| [PRICE 函数](https://support.microsoft.com/zh-cn/office/price-函数-3ea9deac-8dfa-436f-a7c8-17ea02c21b0a) | 返回每张票面为 ￥100 且定期支付利息的债券的现价              |
| [PRICEDISC 函数](https://support.microsoft.com/zh-cn/office/pricedisc-函数-d06ad7c1-380e-4be7-9fd9-75e3079acfd3) | 返回每张票面为 ￥100 的已贴现债券的现价                      |
| [PRICEMAT 函数](https://support.microsoft.com/zh-cn/office/pricemat-函数-52c3b4da-bc7e-476a-989f-a95f675cae77) | 返回每张票面为 ￥100 且在到期日支付利息的债券的现价          |
| [PV 函数](https://support.microsoft.com/zh-cn/office/pv-函数-23879d31-0e02-4321-be01-da16e8168cbd) | 返回投资的现值                                               |
| [RATE 函数](https://support.microsoft.com/zh-cn/office/rate-函数-9f665657-4a7e-4bb7-a030-83fc59e748ce) | 返回年金的各期利率                                           |
| [RECEIVED 函数](https://support.microsoft.com/zh-cn/office/received-函数-7a3f8b93-6611-4f81-8576-828312c9b5e5) | 返回完全投资型债券在到期日收回的金额                         |
| [RRI 函数](https://support.microsoft.com/zh-cn/office/rri-函数-6f5822d8-7ef1-4233-944c-79e8172930f4) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回某项投资增长的等效利率                                   |
| [SLN 函数](https://support.microsoft.com/zh-cn/office/sln-函数-cdb666e5-c1c6-40a7-806a-e695edc2f1c8) | 返回固定资产的每期线性折旧费                                 |
| [SYD 函数](https://support.microsoft.com/zh-cn/office/syd-函数-069f8106-b60b-4ca2-98e0-2a0f206bdb27) | 返回某项固定资产按年限总和折旧法计算的每期折旧金额           |
| [TBILLEQ 函数](https://support.microsoft.com/zh-cn/office/tbilleq-函数-2ab72d90-9b4d-4efe-9fc2-0f81f2c19c8c) | 返回国库券的等价债券收益                                     |
| [TBILLPRICE 函数](https://support.microsoft.com/zh-cn/office/tbillprice-函数-eacca992-c29d-425a-9eb8-0513fe6035a2) | 返回面值 ￥100 的国库券的价格                                |
| [TBILLYIELD 函数](https://support.microsoft.com/zh-cn/office/tbillyield-函数-6d381232-f4b0-4cd5-8e97-45b9c03468ba) | 返回国库券的收益率                                           |
| [VDB 函数](https://support.microsoft.com/zh-cn/office/vdb-函数-dde4e207-f3fa-488d-91d2-66d55e861d73) | 使用余额递减法，返回一笔资产在给定期间或部分期间内的折旧值   |
| [XIRR 函数](https://support.microsoft.com/zh-cn/office/xirr-函数-de1242ec-6477-445b-b11b-a303ad9adc9d) | 返回一组现金流的内部收益率，这些现金流不一定定期发生         |
| [XNPV 函数](https://support.microsoft.com/zh-cn/office/xnpv-函数-1b42bbf6-370f-4532-a0eb-d67c16b664b7) | 返回一组现金流的净现值，这些现金流不一定定期发生             |
| [YIELD 函数](https://support.microsoft.com/zh-cn/office/yield-函数-f5f5ca43-c4bd-434f-8bd2-ed3c9727a4fe) | 返回定期支付利息的债券的收益                                 |
| [YIELDDISC 函数](https://support.microsoft.com/zh-cn/office/yielddisc-函数-a9dbdbae-7dae-46de-b995-615faffaaed7) | 返回已贴现债券的年收益；例如，短期国库券                     |
| [YIELDMAT 函数](https://support.microsoft.com/zh-cn/office/yieldmat-函数-ba7d1809-0d33-4bcb-96c7-6c56ec62ef6f) | 返回在到期日支付利息的债券的年收益                           |



## [信息函数](javascript:)

| **函数**                                                     | **说明**                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [CELL 函数](https://support.microsoft.com/zh-cn/office/cell-函数-51bd39a5-f338-4dbe-a33f-955d67c2b2cf) | 返回有关单元格格式、位置或内容的信息                         |
| [ERROR.TYPE 函数](https://support.microsoft.com/zh-cn/office/error-type-函数-10958677-7c8d-44f7-ae77-b9a9ee6eefaa) | 返回对应于错误类型的数字                                     |
| [INFO 函数](https://support.microsoft.com/zh-cn/office/info-函数-725f259a-0e4b-49b3-8b52-58815c69acae) | 返回有关当前操作环境的信息注意：此函数在 Excel 网页版 中不可用。 |
| [ISBLANK 函数](https://support.microsoft.com/zh-cn/office/is-函数-0f2d7971-6019-40a0-a171-f2d869135665) | 如果值为空，则返回 TRUE                                      |
| [ISERR 函数](https://support.microsoft.com/zh-cn/office/is-函数-0f2d7971-6019-40a0-a171-f2d869135665) | 如果值为除 #N/A 以外的任何错误值，则返回 TRUE                |
| [ISERROR 函数](https://support.microsoft.com/zh-cn/office/is-函数-0f2d7971-6019-40a0-a171-f2d869135665) | 如果值为任何错误值，则返回 TRUE                              |
| [ISEVEN 函数](https://support.microsoft.com/zh-cn/office/iseven-函数-aa15929a-d77b-4fbb-92f4-2f479af55356) | 如果数字为偶数，则返回 TRUE                                  |
| [ISFORMULA 函数](https://support.microsoft.com/zh-cn/office/isformula-函数-e4d1355f-7121-4ef2-801e-3839bfd6b1e5) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 如果有对包含公式的单元格的引用，则返回 TRUE                  |
| [ISLOGICAL 函数](https://support.microsoft.com/zh-cn/office/is-函数-0f2d7971-6019-40a0-a171-f2d869135665) | 如果值为逻辑值，则返回 TRUE                                  |
| [ISNA 函数](https://support.microsoft.com/zh-cn/office/is-函数-0f2d7971-6019-40a0-a171-f2d869135665) | 如果值为错误值 #N/A，则返回 TRUE                             |
| [ISNONTEXT 函数](https://support.microsoft.com/zh-cn/office/is-函数-0f2d7971-6019-40a0-a171-f2d869135665) | 如果值不是文本，则返回 TRUE                                  |
| [ISNUMBER 函数](https://support.microsoft.com/zh-cn/office/is-函数-0f2d7971-6019-40a0-a171-f2d869135665) | 如果值为数字，则返回 TRUE                                    |
| [ISODD 函数](https://support.microsoft.com/zh-cn/office/is-函数-0f2d7971-6019-40a0-a171-f2d869135665) | 如果数字为奇数，则返回 TRUE                                  |
| [ISREF 函数](https://support.microsoft.com/zh-cn/office/is-函数-0f2d7971-6019-40a0-a171-f2d869135665) | 如果值为引用值，则返回 TRUE                                  |
| [ISTEXT 函数](https://support.microsoft.com/zh-cn/office/is-函数-0f2d7971-6019-40a0-a171-f2d869135665) | 如果值为文本，则返回 TRUE                                    |
| [N 函数](https://support.microsoft.com/zh-cn/office/n-函数-a624cad1-3635-4208-b54a-29733d1278c9) | 返回转换为数字的值                                           |
| [NA 函数](https://support.microsoft.com/zh-cn/office/na-函数-5469c2d1-a90c-4fb5-9bbc-64bd9bb6b47c) | 返回错误值 #N/A                                              |
| [SHEET 函数](https://support.microsoft.com/zh-cn/office/sheet-函数-44718b6f-8b87-47a1-a9d6-b701c06cff24) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回引用工作表的工作表编号                                   |
| [SHEETS 函数](https://support.microsoft.com/zh-cn/office/sheets-函数-770515eb-e1e8-45ce-8066-b557e5e4b80b) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回引用中的工作表数                                         |
| [TYPE 函数](https://support.microsoft.com/zh-cn/office/type-函数-45b4e688-4bc3-48b3-a105-ffa892995899) | 返回表示值的数据类型的数字                                   |



## [逻辑函数](javascript:)

| **函数**                                                     | **说明**                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [AND 函数](https://support.microsoft.com/zh-cn/office/and-函数-5f19b2e8-e1df-4408-897a-ce285a19e9d9) | 如果其所有参数均为 TRUE，则返回 TRUE                         |
| [FALSE 函数](https://support.microsoft.com/zh-cn/office/false-函数-2d58dfa5-9c03-4259-bf8f-f0ae14346904) | 返回逻辑值 FALSE                                             |
| [IF 函数](https://support.microsoft.com/zh-cn/office/if-函数-69aed7c9-4e8a-4755-a9bc-aa8bbff73be2) | 指定要执行的逻辑检测                                         |
| [IFERROR 函数](https://support.microsoft.com/zh-cn/office/iferror-函数-c526fd07-caeb-47b8-8bb6-63f3e417f611) | 如果公式的计算结果错误，则返回您指定的值；否则返回公式的结果 |
| [IFNA 函数](https://support.microsoft.com/zh-cn/office/ifna-函数-6626c961-a569-42fc-a49d-79b4951fd461) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 如果该表达式解析为 #N/A，则返回指定值；否则返回该表达式的结果 |
| [IFS 函数](https://support.microsoft.com/zh-cn/office/ifs-函数-36329a26-37b2-467c-972b-4a39bd951d45) ![2019](https://support.content.office.net/zh-cn/media/69779dc0-cc5c-46f2-9ba8-f64b98107de4.png) | 检查是否满足一个或多个条件，且是否返回与第一个 TRUE 条件对应的值。 |
| [NOT 函数](https://support.microsoft.com/zh-cn/office/not-函数-9cfc6011-a054-40c7-a140-cd4ba2d87d77) | 对其参数的逻辑求反                                           |
| [OR 函数](https://support.microsoft.com/zh-cn/office/or-函数-7d17ad14-8700-4281-b308-00b131e22af0) | 如果任一参数为 TRUE，则返回 TRUE                             |
| [SWITCH 函数](https://support.microsoft.com/zh-cn/office/switch-函数-47ab33c0-28ce-4530-8a45-d532ec4aa25e) ![Excel 2016](https://support.content.office.net/zh-cn/media/d41ff42e-0755-4d86-93c8-9729cfadb181.png) | 根据值列表计算表达式，并返回与第一个匹配值对应的结果。 如果不匹配，则可能返回可选默认值。 |
| [TRUE 函数](https://support.microsoft.com/zh-cn/office/true-函数-7652c6e3-8987-48d0-97cd-ef223246b3fb) | 返回逻辑值 TRUE                                              |
| [XOR 函数](https://support.microsoft.com/zh-cn/office/xor-函数-1548d4c2-5e47-4f77-9a92-0533bba14f37) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回所有参数的逻辑“异或”值                                   |



## [查找和引用函数](javascript:)

| **函数**                                                     | **说明**                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [ADDRESS 函数](https://support.microsoft.com/zh-cn/office/address-函数-d0c26c0d-3991-446b-8de4-ab46431d4f89) | 以文本形式将引用值返回到工作表的单个单元格                   |
| [AREAS 函数](https://support.microsoft.com/zh-cn/office/areas-函数-8392ba32-7a41-43b3-96b0-3695d2ec6152) | 返回引用中涉及的区域个数                                     |
| [CHOOSE 函数](https://support.microsoft.com/zh-cn/office/choose-函数-fc5c184f-cb62-4ec7-a46e-38653b98f5bc) | 从值的列表中选择值                                           |
| [COLUMN 函数](https://support.microsoft.com/zh-cn/office/column-函数-44e8c754-711c-4df3-9da4-47a55042554b) | 返回引用的列号                                               |
| [COLUMNS 函数](https://support.microsoft.com/zh-cn/office/columns-函数-4e8e7b4e-e603-43e8-b177-956088fa48ca) | 返回引用中包含的列数                                         |
| [FILTER 函数](https://support.microsoft.com/zh-cn/office/filter-函数-f4f7cb66-82eb-4767-8f7c-4877ad80c759)![Office 365 按钮](https://support.content.office.net/zh-cn/media/8f5fa894-48e1-47bc-a16b-6d4e8b42aba9.png) | 根据定义的条件筛选数据区域                                   |
| [FORMULATEXT 函数](https://support.microsoft.com/zh-cn/office/formulatext-函数-0a786771-54fd-4ae2-96ee-09cda35439c8) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 将给定引用的公式返回为文本                                   |
| [GETPIVOTDATA 函数](https://support.microsoft.com/zh-cn/office/getpivotdata-函数-8c083b99-a922-4ca0-af5e-3af55960761f) | 返回存储在数据透视表中的数据                                 |
| [HLOOKUP 函数](https://support.microsoft.com/zh-cn/office/hlookup-函数-a3034eec-b719-4ba3-bb65-e1ad662ed95f) | 查找数组的首行，并返回指定单元格的值                         |
| [HYPERLINK 函数](https://support.microsoft.com/zh-cn/office/hyperlink-函数-333c7ce6-c5ae-4164-9c47-7de9b76f577f) | 创建快捷方式或跳转，以打开存储在网络服务器、Intranet 或 Internet 上的文档 |
| [INDEX 函数](https://support.microsoft.com/zh-cn/office/index-函数-a5dcf0dd-996d-40a4-a822-b56b061328bd) | 使用索引从引用或数组中选择值                                 |
| [INDIRECT 函数](https://support.microsoft.com/zh-cn/office/indirect-函数-474b3a3a-8a26-4f44-b491-92b6306fa261) | 返回由文本值指定的引用                                       |
| [LOOKUP 函数](https://support.microsoft.com/zh-cn/office/lookup-函数-446d94af-663b-451d-8251-369d5e3864cb) | 在向量或数组中查找值                                         |
| [MATCH 函数](https://support.microsoft.com/zh-cn/office/match-函数-e8dffd45-c762-47d6-bf89-533f4a37673a) | 在引用或数组中查找值                                         |
| [OFFSET 函数](https://support.microsoft.com/zh-cn/office/offset-函数-c8de19ae-dd79-4b9b-a14e-b4d906d11b66) | 从给定引用中返回引用偏移量                                   |
| [ROW 函数](https://support.microsoft.com/zh-cn/office/row-函数-3a63b74a-c4d0-4093-b49a-e76eb49a6d8d) | 返回引用的行号                                               |
| [ROWS 函数](https://support.microsoft.com/zh-cn/office/rows-函数-b592593e-3fc2-47f2-bec1-bda493811597) | 返回引用中的行数                                             |
| [RTD 函数](https://support.microsoft.com/zh-cn/office/rtd-函数-e0cc001a-56f0-470a-9b19-9455dc0eb593) | 从支持 COM 自动化的程序中检索实时数据                        |
| [SORT 函数](https://support.microsoft.com/zh-cn/office/sort-函数-22f63bd0-ccc8-492f-953d-c20e8e44b86c)![Office 365 按钮](https://support.content.office.net/zh-cn/media/8f5fa894-48e1-47bc-a16b-6d4e8b42aba9.png) | 对区域或数组的内容进行排序                                   |
| [SORTBY 函数](https://support.microsoft.com/zh-cn/office/sortby-函数-cd2d7a62-1b93-435c-b561-d6a35134f28f)![Office 365 按钮](https://support.content.office.net/zh-cn/media/8f5fa894-48e1-47bc-a16b-6d4e8b42aba9.png) | 根据相应区域或数组中的值对区域或数组的内容进行排序           |
| [TRANSPOSE 函数](https://support.microsoft.com/zh-cn/office/transpose-函数-ed039415-ed8a-4a81-93e9-4b6dfac76027) | 返回数组的转置                                               |
| [UNIQUE 函数](https://support.microsoft.com/zh-cn/office/unique-函数-c5ab87fd-30a3-4ce9-9d1a-40204fb85e1e)![Office 365 按钮](https://support.content.office.net/zh-cn/media/8f5fa894-48e1-47bc-a16b-6d4e8b42aba9.png) | 返回列表或区域中的唯一值的列表                               |
| [VLOOKUP 函数](https://support.microsoft.com/zh-cn/office/vlookup-函数-0bbc8083-26fe-4963-8ab8-93a18ad188a1) | 在数组第一列中查找，然后在行之间移动以返回单元格的值         |
| [XLOOKUP 函数](https://support.microsoft.com/zh-cn/office/xlookup-函数-b7fd680e-6d10-43e6-84f9-88eae8bf5929)![Office 365 按钮](https://support.content.office.net/zh-cn/media/8f5fa894-48e1-47bc-a16b-6d4e8b42aba9.png) | 搜索区域或数组，并返回与找到的第一个匹配项相对应的项。 如果不存在匹配项，则 XLOOKUP 可返回最接近（近似值）的匹配项。 |
| [XMATCH 函数](https://support.microsoft.com/zh-cn/office/xmatch-函数-d966da31-7a6b-4a13-a1c6-5a33ed6a0312)![Office 365 按钮](https://support.content.office.net/zh-cn/media/8f5fa894-48e1-47bc-a16b-6d4e8b42aba9.png) | 返回数组或单元格区域中的某一项的相对位置。                   |



## [数学和三角函数](javascript:)

| **函数**                                                     | **说明**                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [ABS 函数](https://support.microsoft.com/zh-cn/office/abs-函数-3420200f-5628-4e8c-99da-c99d7c87713c) | 返回数字的绝对值                                             |
| [ACOS 函数](https://support.microsoft.com/zh-cn/office/acos-函数-cb73173f-d089-4582-afa1-76e5524b5d5b) | 返回数字的反余弦值                                           |
| [ACOSH 函数](https://support.microsoft.com/zh-cn/office/acosh-函数-e3992cc1-103f-4e72-9f04-624b9ef5ebfe) | 返回数字的反双曲余弦值                                       |
| [ACOT 函数](https://support.microsoft.com/zh-cn/office/acot-函数-dc7e5008-fe6b-402e-bdd6-2eea8383d905) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回一个数的反余切值                                         |
| [ACOTH 函数](https://support.microsoft.com/zh-cn/office/acoth-函数-cc49480f-f684-4171-9fc5-73e4e852300f) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回一个数的双曲反余切值                                     |
| [AGGREGATE 函数](https://support.microsoft.com/zh-cn/office/aggregate-函数-43b9278e-6aa7-4f17-92b6-e19993fa26df) | 返回列表或数据库中的聚合                                     |
| [ARABIC 函数](https://support.microsoft.com/zh-cn/office/arabic-函数-9a8da418-c17b-4ef9-a657-9370a30a674f) | 将罗马数字转换为阿拉伯数字                                   |
| [ASIN 函数](https://support.microsoft.com/zh-cn/office/asin-函数-81fb95e5-6d6f-48c4-bc45-58f955c6d347) | 返回数字的反正弦值                                           |
| [ASINH 函数](https://support.microsoft.com/zh-cn/office/asinh-函数-4e00475a-067a-43cf-926a-765b0249717c) | 返回数字的反双曲正弦值                                       |
| [ATAN 函数](https://support.microsoft.com/zh-cn/office/atan-函数-50746fa8-630a-406b-81d0-4a2aed395543) | 返回数字的反正切值                                           |
| [ATAN2 函数](https://support.microsoft.com/zh-cn/office/atan2-函数-c04592ab-b9e3-4908-b428-c96b3a565033) | 返回 X 和 Y 坐标的反正切值                                   |
| [ATANH 函数](https://support.microsoft.com/zh-cn/office/atanh-函数-3cd65768-0de7-4f1d-b312-d01c8c930d90) | 返回数字的反双曲正切值                                       |
| [BASE 函数](https://support.microsoft.com/zh-cn/office/base-函数-2ef61411-aee9-4f29-a811-1c42456c6342) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 将一个数转换为具有给定基数的文本表示                         |
| [CEILING 函数](https://support.microsoft.com/zh-cn/office/ceiling-函数-0a5cd7c8-0720-4f0a-bd2c-c943e510899f) | 将数字舍入为最接近的整数或最接近的指定基数的倍数             |
| [CEILING.MATH 函数](https://support.microsoft.com/zh-cn/office/ceiling-math-函数-80f95d2f-b499-4eee-9f16-f795a8e306c8) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 将数字向上舍入为最接近的整数或最接近的指定基数的倍数         |
| [CEILING.PRECISE 函数](https://support.microsoft.com/zh-cn/office/ceiling-precise-函数-f366a774-527a-4c92-ba49-af0a196e66cb) | 将数字舍入为最接近的整数或最接近的指定基数的倍数。 无论该数字的符号如何，该数字都向上舍入。 |
| [COMBIN 函数](https://support.microsoft.com/zh-cn/office/combin-函数-12a3f276-0a21-423a-8de6-06990aaf638a) | 返回给定数目对象的组合数                                     |
| [COMBINA 函数](https://support.microsoft.com/zh-cn/office/combina-函数-efb49eaa-4f4c-4cd2-8179-0ddfcf9d035d) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回给定数目对象具有重复项的组合数                           |
| [COS 函数](https://support.microsoft.com/zh-cn/office/cos-函数-0fb808a5-95d6-4553-8148-22aebdce5f05) | 返回数字的余弦值                                             |
| [COSH 函数](https://support.microsoft.com/zh-cn/office/cosh-函数-e460d426-c471-43e8-9540-a57ff3b70555) | 返回数字的双曲余弦值                                         |
| [COT 函数](https://support.microsoft.com/zh-cn/office/cot-函数-c446f34d-6fe4-40dc-84f8-cf59e5f5e31a) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回角度的余弦值                                             |
| [COTH 函数](https://support.microsoft.com/zh-cn/office/coth-函数-2e0b4cb6-0ba0-403e-aed4-deaa71b49df5) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回数字的双曲余切值                                         |
| [CSC 函数](https://support.microsoft.com/zh-cn/office/csc-函数-07379361-219a-4398-8675-07ddc4f135c1) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回角度的余割值                                             |
| [CSCH 函数](https://support.microsoft.com/zh-cn/office/csch-函数-f58f2c22-eb75-4dd6-84f4-a503527f8eeb) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回角度的双曲余割值                                         |
| [DECIMAL 函数](https://support.microsoft.com/zh-cn/office/decimal-函数-ee554665-6176-46ef-82de-0a283658da2e) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 将给定基数内的数的文本表示转换为十进制数                     |
| [DEGREES 函数](https://support.microsoft.com/zh-cn/office/degrees-函数-4d6ec4db-e694-4b94-ace0-1cc3f61f9ba1) | 将弧度转换为度                                               |
| [EVEN 函数](https://support.microsoft.com/zh-cn/office/even-函数-197b5f06-c795-4c1e-8696-3c3b8a646cf9) | 将数字向上舍入到最接近的偶数                                 |
| [EXP 函数](https://support.microsoft.com/zh-cn/office/exp-函数-c578f034-2c45-4c37-bc8c-329660a63abe) | 返回 *e* 的 n 次方                                           |
| [FACT 函数](https://support.microsoft.com/zh-cn/office/fact-函数-ca8588c2-15f2-41c0-8e8c-c11bd471a4f3) | 返回数字的阶乘                                               |
| [FACTDOUBLE 函数](https://support.microsoft.com/zh-cn/office/factdouble-函数-e67697ac-d214-48eb-b7b7-cce2589ecac8) | 返回数字的双倍阶乘                                           |
| [FLOOR 函数](https://support.microsoft.com/zh-cn/office/floor-函数-14bb497c-24f2-4e04-b327-b0b4de5a8886) | 向绝对值减小的方向舍入数字                                   |
| [FLOOR.MATH 函数](https://support.microsoft.com/zh-cn/office/floor-math-函数-c302b599-fbdb-4177-ba19-2c2b1249a2f5) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 将数字向下舍入为最接近的整数或最接近的指定基数的倍数         |
| [FLOOR.PRECISE 函数](https://support.microsoft.com/zh-cn/office/floor-precise-函数-f769b468-1452-4617-8dc3-02f842a0702e) | 将数字向下舍入为最接近的整数或最接近的指定基数的倍数。 无论该数字的符号如何，该数字都向下舍入。 |
| [GCD 函数](https://support.microsoft.com/zh-cn/office/gcd-函数-d5107a51-69e3-461f-8e4c-ddfc21b5073a) | 返回最大公约数                                               |
| [INT 函数](https://support.microsoft.com/zh-cn/office/int-函数-a6c4af9e-356d-4369-ab6a-cb1fd9d343ef) | 将数字向下舍入到最接近的整数                                 |
| [ISO.CEILING 函数](https://support.microsoft.com/zh-cn/office/iso-ceiling-函数-e587bb73-6cc2-4113-b664-ff5b09859a83) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回一个数字，该数字向上舍入为最接近的整数或最接近的有效位的倍数 |
| [LCM 函数](https://support.microsoft.com/zh-cn/office/lcm-函数-7152b67a-8bb5-4075-ae5c-06ede5563c94) | 返回最小公倍数                                               |
| [LN 函数](https://support.microsoft.com/zh-cn/office/ln-函数-81fe1ed7-dac9-4acd-ba1d-07a142c6118f) | 返回数字的自然对数                                           |
| [LOG 函数](https://support.microsoft.com/zh-cn/office/log-函数-4e82f196-1ca9-4747-8fb0-6c4a3abb3280) | 返回数字的以指定底为底的对数                                 |
| [LOG10 函数](https://support.microsoft.com/zh-cn/office/log10-函数-c75b881b-49dd-44fb-b6f4-37e3486a0211) | 返回数字的以 10 为底的对数                                   |
| [MDETERM 函数](https://support.microsoft.com/zh-cn/office/mdeterm-函数-e7bfa857-3834-422b-b871-0ffd03717020) | 返回数组的矩阵行列式的值                                     |
| [MINVERSE 函数](https://support.microsoft.com/zh-cn/office/minverse-函数-11f55086-adde-4c9f-8eb9-59da2d72efc6) | 返回数组的逆矩阵                                             |
| [MMULT 函数](https://support.microsoft.com/zh-cn/office/mmult-函数-40593ed7-a3cd-4b6b-b9a3-e4ad3c7245eb) | 返回两个数组的矩阵乘积                                       |
| [MOD 函数](https://support.microsoft.com/zh-cn/office/mod-函数-9b6cd169-b6ee-406a-a97b-edf2a9dc24f3) | 返回除法的余数                                               |
| [MROUND 函数](https://support.microsoft.com/zh-cn/office/mround-函数-c299c3b0-15a5-426d-aa4b-d2d5b3baf427) | 返回一个舍入到所需倍数的数字                                 |
| [MULTINOMIAL 函数](https://support.microsoft.com/zh-cn/office/multinomial-函数-6fa6373c-6533-41a2-a45e-a56db1db1bf6) | 返回一组数字的多项式                                         |
| [MUNIT 函数](https://support.microsoft.com/zh-cn/office/munit-函数-c9fe916a-dc26-4105-997d-ba22799853a3) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回单位矩阵或指定维度                                       |
| [ODD 函数](https://support.microsoft.com/zh-cn/office/odd-函数-deae64eb-e08a-4c88-8b40-6d0b42575c98) | 将数字向上舍入为最接近的奇数                                 |
| [PI 函数](https://support.microsoft.com/zh-cn/office/pi-函数-264199d0-a3ba-46b8-975a-c4a04608989b) | 返回 pi 的值                                                 |
| [POWER 函数](https://support.microsoft.com/zh-cn/office/power-函数-d3f2908b-56f4-4c3f-895a-07fb519c362a) | 返回数的乘幂                                                 |
| [PRODUCT 函数](https://support.microsoft.com/zh-cn/office/product-函数-8e6b5b24-90ee-4650-aeec-80982a0512ce) | 将其参数相乘                                                 |
| [QUOTIENT 函数](https://support.microsoft.com/zh-cn/office/quotient-函数-9f7bf099-2a18-4282-8fa4-65290cc99dee) | 返回除法的整数部分                                           |
| [RADIANS 函数](https://support.microsoft.com/zh-cn/office/radians-函数-ac409508-3d48-45f5-ac02-1497c92de5bf) | 将度转换为弧度                                               |
| [RAND 函数](https://support.microsoft.com/zh-cn/office/rand-函数-4cbfa695-8869-4788-8d90-021ea9f5be73) | 返回 0 和 1 之间的一个随机数                                 |
| [RANDARRAY 函数](https://support.microsoft.com/zh-cn/office/randarray-函数-21261e55-3bec-4885-86a6-8b0a47fd4d33)![Office 365 按钮](https://support.content.office.net/zh-cn/media/8f5fa894-48e1-47bc-a16b-6d4e8b42aba9.png) | 返回0和1之间的随机数字数组。 但是，你可以指定要填充的行数和列数、最小值和最大值，以及是否返回整数或小数值。 |
| [RANDBETWEEN 函数](https://support.microsoft.com/zh-cn/office/randbetween-函数-4cc7f0d1-87dc-4eb7-987f-a469ab381685) | 返回位于两个指定数之间的一个随机数                           |
| [ROMAN 函数](https://support.microsoft.com/zh-cn/office/roman-函数-d6b0b99e-de46-4704-a518-b45a0f8b56f5) | 将阿拉伯数字转换为文本式罗马数字                             |
| [ROUND 函数](https://support.microsoft.com/zh-cn/office/round-函数-c018c5d8-40fb-4053-90b1-b3e7f61a213c) | 将数字按指定位数舍入                                         |
| [ROUNDDOWN 函数](https://support.microsoft.com/zh-cn/office/rounddown-函数-2ec94c73-241f-4b01-8c6f-17e6d7968f53) | 向绝对值减小的方向舍入数字                                   |
| [ROUNDUP 函数](https://support.microsoft.com/zh-cn/office/roundup-函数-f8bc9b23-e795-47db-8703-db171d0c42a7) | 向绝对值增大的方向舍入数字                                   |
| [SEC 函数](https://support.microsoft.com/zh-cn/office/sec-函数-ff224717-9c87-4170-9b58-d069ced6d5f7) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回角度的正割值                                             |
| [SECH 函数](https://support.microsoft.com/zh-cn/office/sech-函数-e05a789f-5ff7-4d7f-984a-5edb9b09556f) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回角度的双曲正切值                                         |
| [SERIESSUM 函数](https://support.microsoft.com/zh-cn/office/seriessum-函数-a3ab25b5-1093-4f5b-b084-96c49087f637) | 返回基于公式的幂级数的和                                     |
| [SEQUENCE 函数](https://support.microsoft.com/zh-cn/office/sequence-函数-57467a98-57e0-4817-9f14-2eb78519ca90)![Office 365 按钮](https://support.content.office.net/zh-cn/media/8f5fa894-48e1-47bc-a16b-6d4e8b42aba9.png) | 生成数组中的序列号列表，例如1、2、3、4                       |
| [SIGN 函数](https://support.microsoft.com/zh-cn/office/sign-函数-109c932d-fcdc-4023-91f1-2dd0e916a1d8) | 返回数字的符号                                               |
| [SIN 函数](https://support.microsoft.com/zh-cn/office/sin-函数-cf0e3432-8b9e-483c-bc55-a76651c95602) | 返回给定角度的正弦值                                         |
| [SINH 函数](https://support.microsoft.com/zh-cn/office/sinh-函数-1e4e8b9f-2b65-43fc-ab8a-0a37f4081fa7) | 返回数字的双曲正弦值                                         |
| [SQRT 函数](https://support.microsoft.com/zh-cn/office/sqrt-函数-654975c2-05c4-4831-9a24-2c65e4040fdf) | 返回正平方根                                                 |
| [SQRTPI 函数](https://support.microsoft.com/zh-cn/office/sqrtpi-函数-1fb4e63f-9b51-46d6-ad68-b3e7a8b519b4) | 返回某数与 pi 的乘积的平方根                                 |
| [SUBTOTAL 函数](https://support.microsoft.com/zh-cn/office/subtotal-函数-7b027003-f060-4ade-9040-e478765b9939) | 返回列表或数据库中的分类汇总                                 |
| [SUM 函数](https://support.microsoft.com/zh-cn/office/sum-函数-043e1c7d-7726-4e80-8f32-07b23e057f89) | 求参数的和                                                   |
| [SUMIF 函数](https://support.microsoft.com/zh-cn/office/sumif-函数-169b8c99-c05c-4483-a712-1697a653039b) | 按给定条件对指定单元格求和                                   |
| [SUMIFS 函数](https://support.microsoft.com/zh-cn/office/sumifs-函数-c9e748f5-7ea7-455d-9406-611cebce642b) ![2019](https://support.content.office.net/zh-cn/media/69779dc0-cc5c-46f2-9ba8-f64b98107de4.png) | 在区域中添加满足多个条件的单元格                             |
| [SUMPRODUCT 函数](https://support.microsoft.com/zh-cn/office/sumproduct-函数-16753e75-9f68-4874-94ac-4d2145a2fd2e) | 返回对应的数组元素的乘积和                                   |
| [SUMSQ 函数](https://support.microsoft.com/zh-cn/office/sumsq-函数-e3313c02-51cc-4963-aae6-31442d9ec307) | 返回参数的平方和                                             |
| [SUMX2MY2 函数](https://support.microsoft.com/zh-cn/office/sumx2my2-函数-9e599cc5-5399-48e9-a5e0-e37812dfa3e9) | 返回两数组中对应值平方差之和                                 |
| [SUMX2PY2 函数](https://support.microsoft.com/zh-cn/office/sumx2py2-函数-826b60b4-0aa2-4e5e-81d2-be704d3d786f) | 返回两数组中对应值的平方和之和                               |
| [SUMXMY2 函数](https://support.microsoft.com/zh-cn/office/sumxmy2-函数-9d144ac1-4d79-43de-b524-e2ecee23b299) | 返回两个数组中对应值差的平方和                               |
| [TAN 函数](https://support.microsoft.com/zh-cn/office/tan-函数-08851a40-179f-4052-b789-d7f699447401) | 返回数字的正切值                                             |
| [TANH 函数](https://support.microsoft.com/zh-cn/office/tanh-函数-017222f0-a0c3-4f69-9787-b3202295dc6c) | 返回数字的双曲正切值                                         |
| [TRUNC 函数](https://support.microsoft.com/zh-cn/office/trunc-函数-8b86a64c-3127-43db-ba14-aa5ceb292721) | 将数字截尾取整                                               |



## [统计函数](javascript:)

| **函数**                                                     | **说明**                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [AVEDEV 函数](https://support.microsoft.com/zh-cn/office/avedev-函数-58fe8d65-2a84-4dc7-8052-f3f87b5c6639) | 返回数据点与它们的平均值的绝对偏差平均值                     |
| [AVERAGE 函数](https://support.microsoft.com/zh-cn/office/average-函数-047bac88-d466-426c-a32b-8f33eb960cf6) | 返回其参数的平均值                                           |
| [AVERAGEA 函数](https://support.microsoft.com/zh-cn/office/averagea-函数-f5f84098-d453-4f4c-bbba-3d2c66356091) | 返回其参数的平均值，包括数字、文本和逻辑值                   |
| [AVERAGEIF 函数](https://support.microsoft.com/zh-cn/office/averageif-函数-faec8e2e-0dec-4308-af69-f5576d8ac642) | 返回区域中满足给定条件的所有单元格的平均值（算术平均值）     |
| [AVERAGEIFS 函数](https://support.microsoft.com/zh-cn/office/averageifs-函数-48910c45-1fc0-4389-a028-f7c5c3001690) ![2019](https://support.content.office.net/zh-cn/media/69779dc0-cc5c-46f2-9ba8-f64b98107de4.png) | 返回满足多个条件的所有单元格的平均值（算术平均值）           |
| [BETA.DIST 函数](https://support.microsoft.com/zh-cn/office/beta-dist-函数-11188c9c-780a-42c7-ba43-9ecb5a878d31) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回 beta 累积分布函数                                       |
| [BETA.INV 函数](https://support.microsoft.com/zh-cn/office/beta-inv-函数-e84cb8aa-8df0-4cf6-9892-83a341d252eb) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回指定 beta 分布的累积分布函数的反函数                     |
| [BINOM.DIST 函数](https://support.microsoft.com/zh-cn/office/binom-dist-函数-c5ae37b6-f39c-4be2-94c2-509a1480770c) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回一元二项式分布的概率                                     |
| [BINOM.DIST.RANGE 函数](https://support.microsoft.com/zh-cn/office/binom-dist-range-函数-17331329-74c7-4053-bb4c-6653a7421595) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 使用二项式分布返回试验结果的概率                             |
| [BINOM.INV 函数](https://support.microsoft.com/zh-cn/office/binom-inv-函数-80a0370c-ada6-49b4-83e7-05a91ba77ac9) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回使累积二项式分布小于或等于临界值的最小值                 |
| [CHISQ.DIST 函数](https://support.microsoft.com/zh-cn/office/chisq-dist-函数-8486b05e-5c05-4942-a9ea-f6b341518732) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回累积 beta 概率密度函数                                   |
| [CHISQ.DIST.RT 函数](https://support.microsoft.com/zh-cn/office/chisq-dist-rt-函数-dc4832e8-ed2b-49ae-8d7c-b28d5804c0f2) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回 χ2 分布的单尾概率                                       |
| [CHISQ.INV 函数](https://support.microsoft.com/zh-cn/office/chisq-inv-函数-400db556-62b3-472d-80b3-254723e7092f) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回累积 beta 概率密度函数                                   |
| [CHISQ.INV.RT 函数](https://support.microsoft.com/zh-cn/office/chisq-inv-rt-函数-435b5ed8-98d5-4da6-823f-293e2cbc94fe) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回 χ2 分布的单尾概率的反函数                               |
| [CHISQ.TEST 函数](https://support.microsoft.com/zh-cn/office/chisq-test-函数-2e8a7861-b14a-4985-aa93-fb88de3f260f) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回独立性检验值                                             |
| [CONFIDENCE.NORM 函数](https://support.microsoft.com/zh-cn/office/confidence-norm-函数-7cec58a6-85bb-488d-91c3-63828d4fbfd4) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回总体平均值的置信区间                                     |
| [CONFIDENCE.T 函数](https://support.microsoft.com/zh-cn/office/confidence-t-函数-e8eca395-6c3a-4ba9-9003-79ccc61d3c53) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回总体平均值的置信区间（使用学生 t-分布）                  |
| [CORREL 函数](https://support.microsoft.com/zh-cn/office/correl-函数-995dcef7-0c0a-4bed-a3fb-239d7b68ca92) | 返回两个数据集之间的相关系数                                 |
| [COUNT 函数](https://support.microsoft.com/zh-cn/office/count-函数-a59cd7fc-b623-4d93-87a4-d23bf411294c) | 计算参数列表中数字的个数                                     |
| [COUNTA 函数](https://support.microsoft.com/zh-cn/office/counta-函数-7dc98875-d5c1-46f1-9a82-53f3219e2509) | 计算参数列表中值的个数                                       |
| [COUNTBLANK 函数](https://support.microsoft.com/zh-cn/office/countblank-函数-6a92d772-675c-4bee-b346-24af6bd3ac22) | 计算区域内空白单元格的数量                                   |
| [COUNTIF 函数](https://support.microsoft.com/zh-cn/office/countif-函数-e0de10c6-f885-4e71-abb4-1f464816df34) | 计算区域内符合给定条件的单元格的数量                         |
| [COUNTIFS 函数](https://support.microsoft.com/zh-cn/office/countifs-函数-dda3dc6e-f74e-4aee-88bc-aa8c2a866842) ![2019](https://support.content.office.net/zh-cn/media/69779dc0-cc5c-46f2-9ba8-f64b98107de4.png) | 计算区域内符合多个条件的单元格的数量                         |
| [COVARIANCE.P 函数](https://support.microsoft.com/zh-cn/office/covariance-p-函数-6f0e1e6d-956d-4e4b-9943-cfef0bf9edfc) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回协方差（成对偏差乘积的平均值）                           |
| [COVARIANCE.S 函数](https://support.microsoft.com/zh-cn/office/covariance-s-函数-0a539b74-7371-42aa-a18f-1f5320314977) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回样本协方差，即两个数据集中每对数据点的偏差乘积的平均值   |
| [DEVSQ 函数](https://support.microsoft.com/zh-cn/office/devsq-函数-8b739616-8376-4df5-8bd0-cfe0a6caf444) | 返回偏差的平方和                                             |
| [EXPON.DIST 函数](https://support.microsoft.com/zh-cn/office/expon-dist-函数-4c12ae24-e563-4155-bf3e-8b78b6ae140e) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回指数分布                                                 |
| [F.DIST 函数](https://support.microsoft.com/zh-cn/office/f-dist-函数-a887efdc-7c8e-46cb-a74a-f884cd29b25d) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回 F 概率分布                                              |
| [F.DIST.RT 函数](https://support.microsoft.com/zh-cn/office/f-dist-rt-函数-d74cbb00-6017-4ac9-b7d7-6049badc0520) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回 F 概率分布                                              |
| [F.INV 函数](https://support.microsoft.com/zh-cn/office/f-inv-函数-0dda0cf9-4ea0-42fd-8c3c-417a1ff30dbe) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回 F 概率分布的反函数                                      |
| [F.INV.RT 函数](https://support.microsoft.com/zh-cn/office/f-inv-rt-函数-d371aa8f-b0b1-40ef-9cc2-496f0693ac00) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回 F 概率分布的反函数                                      |
| [F.TEST 函数](https://support.microsoft.com/zh-cn/office/f-test-函数-100a59e7-4108-46f8-8443-78ffacb6c0a7) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回 F 检验的结果                                            |
| [FISHER 函数](https://support.microsoft.com/zh-cn/office/fisher-函数-d656523c-5076-4f95-b87b-7741bf236c69) | 返回 Fisher 变换值                                           |
| [FISHERINV 函数](https://support.microsoft.com/zh-cn/office/fisherinv-函数-62504b39-415a-4284-a285-19c8e82f86bb) | 返回 Fisher 变换的反函数                                     |
| [FORECAST 函数](https://support.microsoft.com/zh-cn/office/预测和预测。线性函数-50ca49c9-7b40-4892-94e4-7ad38bbeda99) | 返回线性趋势值注意：在 Excel 2016 中，此函数将替换为 "[预测"。线性](https://support.microsoft.com/zh-cn/office/预测函数（参考）-897a2fe9-6595-4680-a0b0-93e0308d5f6e#_forecast.linear)作为新[预测函数](https://support.microsoft.com/zh-cn/office/预测函数（参考）-897a2fe9-6595-4680-a0b0-93e0308d5f6e)的一部分，但它仍可用于与早期版本兼容。 |
| [FORECAST.ETS 函数](https://support.microsoft.com/zh-cn/office/预测函数（参考）-897a2fe9-6595-4680-a0b0-93e0308d5f6e#_forecast.ets) ![Excel 2016](https://support.content.office.net/zh-cn/media/d41ff42e-0755-4d86-93c8-9729cfadb181.png) | 通过使用指数平滑 (ETS) 算法的 AAA 版本，返回基于现有（历史）值的未来值 |
| [FORECAST.ETS.CONFINT 函数](https://support.microsoft.com/zh-cn/office/预测函数（参考）-897a2fe9-6595-4680-a0b0-93e0308d5f6e#_forecast.ets.confint) ![Excel 2016](https://support.content.office.net/zh-cn/media/d41ff42e-0755-4d86-93c8-9729cfadb181.png) | 返回指定目标日期预测值的置信区间                             |
| [FORECAST.ETS.SEASONALITY 函数](https://support.microsoft.com/zh-cn/office/预测函数（参考）-897a2fe9-6595-4680-a0b0-93e0308d5f6e#_forecast.ets.seasonality) ![Excel 2016](https://support.content.office.net/zh-cn/media/d41ff42e-0755-4d86-93c8-9729cfadb181.png) | 返回 Excel 针对指定时间系列检测到的重复模式的长度            |
| [FORECAST.ETS.STAT 函数](https://support.microsoft.com/zh-cn/office/预测函数（参考）-897a2fe9-6595-4680-a0b0-93e0308d5f6e#_forecast.ets.stat) ![Excel 2016](https://support.content.office.net/zh-cn/media/d41ff42e-0755-4d86-93c8-9729cfadb181.png) | 返回作为时间序列预测的结果的统计值。                         |
| [FORECAST.LINEAR 函数](https://support.microsoft.com/zh-cn/office/预测函数（参考）-897a2fe9-6595-4680-a0b0-93e0308d5f6e#_forecast.linear) ![Excel 2016](https://support.content.office.net/zh-cn/media/d41ff42e-0755-4d86-93c8-9729cfadb181.png) | 返回基于现有值的未来值                                       |
| [FREQUENCY 函数](https://support.microsoft.com/zh-cn/office/frequency-函数-44e3be2b-eca0-42cd-a3f7-fd9ea898fdb9) | 以垂直数组的形式返回频率分布                                 |
| [GAMMA 函数](https://support.microsoft.com/zh-cn/office/gamma-函数-ce1702b1-cf55-471d-8307-f83be0fc5297) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回 γ 函数值                                                |
| [GAMMA.DIST 函数](https://support.microsoft.com/zh-cn/office/gamma-dist-函数-9b6f1538-d11c-4d5f-8966-21f6a2201def) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回 γ 分布                                                  |
| [GAMMA.INV 函数](https://support.microsoft.com/zh-cn/office/gamma-inv-函数-74991443-c2b0-4be5-aaab-1aa4d71fbb18) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回 γ 累积分布函数的反函数                                  |
| [GAMMALN 函数](https://support.microsoft.com/zh-cn/office/gammaln-函数-b838c48b-c65f-484f-9e1d-141c55470eb9) | 返回 γ 函数的自然对数，Γ(x)                                  |
| [GAMMALN.PRECISE 函数](https://support.microsoft.com/zh-cn/office/gammaln-precise-函数-5cdfe601-4e1e-4189-9d74-241ef1caa599) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回 γ 函数的自然对数，Γ(x)                                  |
| [GAUSS 函数](https://support.microsoft.com/zh-cn/office/gauss-函数-069f1b4e-7dee-4d6a-a71f-4b69044a6b33) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回小于标准正态累积分布 0.5 的值                            |
| [GEOMEAN 函数](https://support.microsoft.com/zh-cn/office/geomean-函数-db1ac48d-25a5-40a0-ab83-0b38980e40d5) | 返回几何平均值                                               |
| [GROWTH 函数](https://support.microsoft.com/zh-cn/office/growth-函数-541a91dc-3d5e-437d-b156-21324e68b80d) | 返回指数趋势值                                               |
| [HARMEAN 函数](https://support.microsoft.com/zh-cn/office/harmean-函数-5efd9184-fab5-42f9-b1d3-57883a1d3bc6) | 返回调和平均值                                               |
| [HYPGEOM.DIST 函数](https://support.microsoft.com/zh-cn/office/hypgeom-dist-函数-6dbd547f-1d12-4b1f-8ae5-b0d9e3d22fbf) | 返回超几何分布                                               |
| [INTERCEPT 函数](https://support.microsoft.com/zh-cn/office/intercept-函数-2a9b74e2-9d47-4772-b663-3bca70bf63ef) | 返回线性回归线的截距                                         |
| [KURT 函数](https://support.microsoft.com/zh-cn/office/kurt-函数-bc3a265c-5da4-4dcb-b7fd-c237789095ab) | 返回数据集的峰值                                             |
| [LARGE 函数](https://support.microsoft.com/zh-cn/office/large-函数-3af0af19-1190-42bb-bb8b-01672ec00a64) | 返回数据集中第 k 个最大值                                    |
| [LINEST 函数](https://support.microsoft.com/zh-cn/office/linest-函数-84d7d0d9-6e50-4101-977a-fa7abf772b6d) | 返回线性趋势的参数                                           |
| [LOGEST 函数](https://support.microsoft.com/zh-cn/office/logest-函数-f27462d8-3657-4030-866b-a272c1d18b4b) | 返回指数趋势的参数                                           |
| [LOGNORM.DIST 函数](https://support.microsoft.com/zh-cn/office/lognorm-dist-函数-eb60d00b-48a9-4217-be2b-6074aee6b070) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回对数累积分布函数                                         |
| [LOGNORM.INV 函数](https://support.microsoft.com/zh-cn/office/lognorm-inv-函数-fe79751a-f1f2-4af8-a0a1-e151b2d4f600) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回对数累积分布的反函数                                     |
| [MAX 函数](https://support.microsoft.com/zh-cn/office/max-函数-e0012414-9ac8-4b34-9a47-73e662c08098) | 返回参数列表中的最大值                                       |
| [MAXA 函数](https://support.microsoft.com/zh-cn/office/maxa-函数-814bda1e-3840-4bff-9365-2f59ac2ee62d) | 返回参数列表中的最大值，包括数字、文本和逻辑值               |
| [MAXIFS 函数](https://support.microsoft.com/zh-cn/office/maxifs-函数-dfd611e6-da2c-488a-919b-9b6376b28883) ![2019](https://support.content.office.net/zh-cn/media/69779dc0-cc5c-46f2-9ba8-f64b98107de4.png) | 返回一组给定条件或标准指定的单元格之间的最大值               |
| [MEDIAN 函数](https://support.microsoft.com/zh-cn/office/median-函数-d0916313-4753-414c-8537-ce85bdd967d2) | 返回给定数值集合的中值                                       |
| [MIN 函数](https://support.microsoft.com/zh-cn/office/min-函数-61635d12-920f-4ce2-a70f-96f202dcc152) | 返回参数列表中的最小值                                       |
| [MINA 函数](https://support.microsoft.com/zh-cn/office/mina-函数-245a6f46-7ca5-4dc7-ab49-805341bc31d3) | 返回参数列表中的最小值，包括数字、文本和逻辑值               |
| [MINIFS 函数](https://support.microsoft.com/zh-cn/office/minifs-函数-6ca1ddaa-079b-4e74-80cc-72eef32e6599) ![2019](https://support.content.office.net/zh-cn/media/69779dc0-cc5c-46f2-9ba8-f64b98107de4.png) | 返回一组给定条件或标准指定的单元格之间的最小值。             |
| [MODE.MULT 函数](https://support.microsoft.com/zh-cn/office/mode-mult-函数-50fd9464-b2ba-4191-b57a-39446689ae8c) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回一组数据或数据区域中出现频率最高或重复出现的数值的垂直数组 |
| [MODE.SNGL 函数](https://support.microsoft.com/zh-cn/office/mode-sngl-函数-f1267c16-66c6-4386-959f-8fba5f8bb7f8) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回在数据集内出现次数最多的值                               |
| [NEGBINOM.DIST 函数](https://support.microsoft.com/zh-cn/office/negbinom-dist-函数-c8239f89-c2d0-45bd-b6af-172e570f8599) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回负二项式分布                                             |
| [NORM.DIST 函数](https://support.microsoft.com/zh-cn/office/norm-dist-函数-edb1cc14-a21c-4e53-839d-8082074c9f8d) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回正态累积分布                                             |
| [NORM.INV 函数](https://support.microsoft.com/zh-cn/office/norm-inv-函数-54b30935-fee7-493c-bedb-2278a9db7e13) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回正态累积分布的反函数                                     |
| [NORM.S.DIST 函数](https://support.microsoft.com/zh-cn/office/norm-s-dist-函数-1e787282-3832-4520-a9ae-bd2a8d99ba88) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回标准正态累积分布                                         |
| [NORM.S.INV 函数](https://support.microsoft.com/zh-cn/office/norm-s-inv-函数-d6d556b4-ab7f-49cd-b526-5a20918452b1) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回标准正态累积分布函数的反函数                             |
| [PEARSON 函数](https://support.microsoft.com/zh-cn/office/pearson-函数-0c3e30fc-e5af-49c4-808a-3ef66e034c18) | 返回 Pearson 乘积矩相关系数                                  |
| [PERCENTILE.EXC 函数](https://support.microsoft.com/zh-cn/office/percentile-exc-函数-bbaa7204-e9e1-4010-85bf-c31dc5dce4ba) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回某个区域中的数值的第 k 个百分点值，此处的 k 的范围为 0 到 1（不含 0 和 1） |
| [PERCENTILE.INC 函数](https://support.microsoft.com/zh-cn/office/percentile-inc-函数-680f9539-45eb-410b-9a5e-c1355e5fe2ed) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回区域中数值的第 k 个百分点的值                            |
| [PERCENTRANK.EXC 函数](https://support.microsoft.com/zh-cn/office/percentrank-exc-函数-d8afee96-b7e2-4a2f-8c01-8fcdedaa6314) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 将某个数值在数据集中的排位作为数据集的百分点值返回，此处的百分点值的范围为 0 到 1（不含 0 和 1） |
| [PERCENTRANK.INC 函数](https://support.microsoft.com/zh-cn/office/percentrank-inc-函数-149592c9-00c0-49ba-86c1-c1f45b80463a) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回数据集中值的百分比排位                                   |
| [PERMUT 函数](https://support.microsoft.com/zh-cn/office/permut-函数-3bd1cb9a-2880-41ab-a197-f246a7a602d3) | 返回给定数目对象的排列数                                     |
| [PERMUTATIONA 函数](https://support.microsoft.com/zh-cn/office/permutationa-函数-6c7d7fdc-d657-44e6-aa19-2857b25cae4e) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回可从总计对象中选择的给定数目对象（含重复）的排列数       |
| [PHI 函数](https://support.microsoft.com/zh-cn/office/phi-函数-23e49bc6-a8e8-402d-98d3-9ded87f6295c) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回标准正态分布的密度函数值                                 |
| [POISSON.DIST 函数](https://support.microsoft.com/zh-cn/office/poisson-dist-函数-8fe148ff-39a2-46cb-abf3-7772695d9636) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回泊松分布                                                 |
| [PROB 函数](https://support.microsoft.com/zh-cn/office/prob-函数-9ac30561-c81c-4259-8253-34f0a238fc49) | 返回区域中的数值落在指定区间内的概率                         |
| [QUARTILE.EXC 函数](https://support.microsoft.com/zh-cn/office/quartile-exc-函数-5a355b7a-840b-4a01-b0f1-f538c2864cad) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 基于百分点值返回数据集的四分位，此处的百分点值的范围为 0 到 1（不含 0 和 1） |
| [QUARTILE.INC 函数](https://support.microsoft.com/zh-cn/office/quartile-inc-函数-1bbacc80-5075-42f1-aed6-47d735c4819d) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回一组数据的四分位点                                       |
| [RANK.AVG 函数](https://support.microsoft.com/zh-cn/office/rank-avg-函数-bd406a6f-eb38-4d73-aa8e-6d1c3c72e83a) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回一列数字的数字排位                                       |
| [RANK.EQ 函数](https://support.microsoft.com/zh-cn/office/rank-eq-函数-284858ce-8ef6-450e-b662-26245be04a40) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回一列数字的数字排位                                       |
| [RSQ 函数](https://support.microsoft.com/zh-cn/office/rsq-函数-d7161715-250d-4a01-b80d-a8364f2be08f) | 返回 Pearson 乘积矩相关系数的平方                            |
| [SKEW 函数](https://support.microsoft.com/zh-cn/office/skew-函数-bdf49d86-b1ef-4804-a046-28eaea69c9fa) | 返回分布的不对称度                                           |
| [SKEW.P 函数](https://support.microsoft.com/zh-cn/office/skew-p-函数-76530a5c-99b9-48a1-8392-26632d542fcb) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回一个分布的不对称度：用来体现某一分布相对其平均值的不对称程度 |
| [SLOPE 函数](https://support.microsoft.com/zh-cn/office/slope-函数-11fb8f97-3117-4813-98aa-61d7e01276b9) | 返回线性回归线的斜率                                         |
| [SMALL 函数](https://support.microsoft.com/zh-cn/office/small-函数-17da8222-7c82-42b2-961b-14c45384df07) | 返回数据集中的第 k 个最小值                                  |
| [STANDARDIZE 函数](https://support.microsoft.com/zh-cn/office/standardize-函数-81d66554-2d54-40ec-ba83-6437108ee775) | 返回正态化数值                                               |
| [STDEV.P 函数](https://support.microsoft.com/zh-cn/office/stdev-p-函数-6e917c05-31a0-496f-ade7-4f4e7462f285) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 基于整个样本总体计算标准偏差                                 |
| [STDEV.S 函数](https://support.microsoft.com/zh-cn/office/stdev-s-函数-7d69cf97-0c1f-4acf-be27-f3e83904cc23) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 基于样本估算标准偏差                                         |
| [STDEVA 函数](https://support.microsoft.com/zh-cn/office/stdeva-函数-5ff38888-7ea5-48de-9a6d-11ed73b29e9d) | 基于样本（包括数字、文本和逻辑值）估算标准偏差               |
| [STDEVPA 函数](https://support.microsoft.com/zh-cn/office/stdevpa-函数-5578d4d6-455a-4308-9991-d405afe2c28c) | 基于样本总体（包括数字、文本和逻辑值）计算标准偏差           |
| [STEYX 函数](https://support.microsoft.com/zh-cn/office/steyx-函数-6ce74b2c-449d-4a6e-b9ac-f9cef5ba48ab) | 返回通过线性回归法预测每个 x 的 y 值时所产生的标准误差       |
| [T.DIST 函数](https://support.microsoft.com/zh-cn/office/t-dist-函数-4329459f-ae91-48c2-bba8-1ead1c6c21b2) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回学生 t-分布的百分点（概率）                              |
| [T.DIST.2T 函数](https://support.microsoft.com/zh-cn/office/t-dist-2t-函数-198e9340-e360-4230-bd21-f52f22ff5c28) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回学生 t-分布的百分点（概率）                              |
| [T.DIST.RT 函数](https://support.microsoft.com/zh-cn/office/t-dist-rt-函数-20a30020-86f9-4b35-af1f-7ef6ae683eda) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回学生 t-分布                                              |
| [T.INV 函数](https://support.microsoft.com/zh-cn/office/t-inv-函数-2908272b-4e61-4942-9df9-a25fec9b0e2e) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回作为概率和自由度函数的学生 t 分布的 t 值                 |
| [T.INV.2T 函数](https://support.microsoft.com/zh-cn/office/t-inv-2t-函数-ce72ea19-ec6c-4be7-bed2-b9baf2264f17) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回学生 t-分布的反函数                                      |
| [T.TEST 函数](https://support.microsoft.com/zh-cn/office/t-test-函数-d4e08ec3-c545-485f-962e-276f7cbed055) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回与学生 t-检验相关的概率                                  |
| [TREND 函数](https://support.microsoft.com/zh-cn/office/trend-函数-e2f135f0-8827-4096-9873-9a7cf7b51ef1) | 返回线性趋势值                                               |
| [TRIMMEAN 函数](https://support.microsoft.com/zh-cn/office/trimmean-函数-d90c9878-a119-4746-88fa-63d988f511d3) | 返回数据集的内部平均值                                       |
| [VAR.P 函数](https://support.microsoft.com/zh-cn/office/var-p-函数-73d1285c-108c-4843-ba5d-a51f90656f3a) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 计算基于样本总体的方差                                       |
| [VAR.S 函数](https://support.microsoft.com/zh-cn/office/var-s-函数-913633de-136b-449d-813e-65a00b2b990b) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 基于样本估算方差                                             |
| [VARA 函数](https://support.microsoft.com/zh-cn/office/vara-函数-3de77469-fa3a-47b4-85fd-81758a1e1d07) | 基于样本（包括数字、文本和逻辑值）估算方差                   |
| [VARPA 函数](https://support.microsoft.com/zh-cn/office/varpa-函数-59a62635-4e89-4fad-88ac-ce4dc0513b96) | 基于样本总体（包括数字、文本和逻辑值）计算标准偏差           |
| [WEIBULL.DIST 函数](https://support.microsoft.com/zh-cn/office/weibull-dist-函数-4e783c39-9325-49be-bbc9-a83ef82b45db) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回 Weibull 分布                                            |
| [Z.TEST 函数](https://support.microsoft.com/zh-cn/office/z-test-函数-d633d5a3-2031-4614-a016-92180ad82bee) ![Excel 2010](https://support.content.office.net/zh-cn/media/f1cec941-a9cf-4f10-8bc9-db8d4fa78f74.png) | 返回 z 检验的单尾概率值                                      |



## [文本函数](javascript:)

| **函数**                                                     | **说明**                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [ASC 函数](https://support.microsoft.com/zh-cn/office/asc-函数-0b6abf1c-c663-4004-a964-ebc00b723266) | 将字符串中的全角（双字节）英文字母或片假名更改为半角（单字节）字符 |
| [BAHTTEXT 函数](https://support.microsoft.com/zh-cn/office/bahttext-函数-5ba4d0b4-abd3-4325-8d22-7a92d59aab9c) | 使用 ß（泰铢）货币格式将数字转换为文本                       |
| [CHAR 函数](https://support.microsoft.com/zh-cn/office/char-函数-bbd249c8-b36e-4a91-8017-1c133f9b837a) | 返回由代码数字指定的字符                                     |
| [CLEAN 函数](https://support.microsoft.com/zh-cn/office/clean-函数-26f3d7c5-475f-4a9c-90e5-4b8ba987ba41) | 删除文本中所有非打印字符                                     |
| [CODE 函数](https://support.microsoft.com/zh-cn/office/code-函数-c32b692b-2ed0-4a04-bdd9-75640144b928) | 返回文本字符串中第一个字符的数字代码                         |
| [CONCAT 函数](https://support.microsoft.com/zh-cn/office/concat-函数-9b1a9a3f-94ff-41af-9736-694cbd6b4ca2) ![2019](https://support.content.office.net/zh-cn/media/69779dc0-cc5c-46f2-9ba8-f64b98107de4.png) | 将多个区域和/或字符串的文本组合起来，但不提供分隔符或 IgnoreEmpty 参数。 |
| [CONCATENATE 函数](https://support.microsoft.com/zh-cn/office/concatenate-函数-8f8ae884-2ca8-4f7a-b093-75d702bea31d) | 将几个文本项合并为一个文本项                                 |
| [DBCS 函数](https://support.microsoft.com/zh-cn/office/dbcs-函数-a4025e73-63d2-4958-9423-21a24794c9e5) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 将字符串中的半角（单字节）英文字母或片假名更改为全角（双字节）字符 |
| [DOLLAR 函数](https://support.microsoft.com/zh-cn/office/dollar-函数-a6cd05d9-9740-4ad3-a469-8109d18ff611) | 使用 ￥（人民币）货币格式将数字转换为文本                    |
| [EXACT 函数](https://support.microsoft.com/zh-cn/office/exact-函数-d3087698-fc15-4a15-9631-12575cf29926) | 检查两个文本值是否相同                                       |
| [FIND、FINDB 函数](https://support.microsoft.com/zh-cn/office/find、findb-函数-c7912941-af2a-4bdf-a553-d0d89b0a0628) | 在一个文本值中查找另一个文本值（区分大小写）                 |
| [FIXED 函数](https://support.microsoft.com/zh-cn/office/fixed-函数-ffd5723c-324c-45e9-8b96-e41be2a8274a) | 将数字格式设置为具有固定小数位数的文本                       |
| [LEFT、LEFTB 函数](https://support.microsoft.com/zh-cn/office/left、leftb-函数-9203d2d2-7960-479b-84c6-1ea52b99640c) | 返回文本值中最左边的字符                                     |
| [LEN、LENB 函数](https://support.microsoft.com/zh-cn/office/len、lenb-函数-29236f94-cedc-429d-affd-b5e33d2c67cb) | 返回文本字符串中的字符个数                                   |
| [LOWER 函数](https://support.microsoft.com/zh-cn/office/lower-函数-3f21df02-a80c-44b2-afaf-81358f9fdeb4) | 将文本转换为小写                                             |
| [MID、MIDB 函数](https://support.microsoft.com/zh-cn/office/mid、midb-函数-d5f9e25c-d7d6-472e-b568-4ecb12433028) | 从文本字符串中的指定位置起返回特定个数的字符                 |
| [NUMBERVALUE 函数](https://support.microsoft.com/zh-cn/office/numbervalue-函数-1b05c8cf-2bfa-4437-af70-596c7ea7d879) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 以与区域设置无关的方式将文本转换为数字                       |
| [PHONETIC 函数](https://support.microsoft.com/zh-cn/office/phonetic-函数-9a329dac-0c0f-42f8-9a55-639086988554) | 提取文本字符串中的拼音（汉字注音）字符                       |
| [PROPER 函数](https://support.microsoft.com/zh-cn/office/proper-函数-52a5a283-e8b2-49be-8506-b2887b889f94) | 将文本值的每个字的首字母大写                                 |
| [REPLACE、REPLACEB 函数](https://support.microsoft.com/zh-cn/office/replace、replaceb-函数-8d799074-2425-4a8a-84bc-82472868878a) | 替换文本中的字符                                             |
| [REPT 函数](https://support.microsoft.com/zh-cn/office/rept-函数-04c4d778-e712-43b4-9c15-d656582bb061) | 按给定次数重复文本                                           |
| [RIGHT、RIGHTB 函数](https://support.microsoft.com/zh-cn/office/right、rightb-函数-240267ee-9afa-4639-a02b-f19e1786cf2f) | 返回文本值中最右边的字符                                     |
| [SEARCH、SEARCHB 函数](https://support.microsoft.com/zh-cn/office/search、searchb-函数-9ab04538-0e55-4719-a72e-b6f54513b495) | 在一个文本值中查找另一个文本值（不区分大小写）               |
| [SUBSTITUTE 函数](https://support.microsoft.com/zh-cn/office/substitute-函数-6434944e-a904-4336-a9b0-1e58df3bc332) | 在文本字符串中用新文本替换旧文本                             |
| [T 函数](https://support.microsoft.com/zh-cn/office/t-函数-fb83aeec-45e7-4924-af95-53e073541228) | 将参数转换为文本                                             |
| [TEXT 函数](https://support.microsoft.com/zh-cn/office/text-函数-20d5ac4d-7b94-49fd-bb38-93d29371225c) | 设置数字格式并将其转换为文本                                 |
| [TEXTJOIN 函数](https://support.microsoft.com/zh-cn/office/textjoin-函数-357b449a-ec91-49d0-80c3-0e8fc845691c) ![2019](https://support.content.office.net/zh-cn/media/69779dc0-cc5c-46f2-9ba8-f64b98107de4.png) | 将多个区域和/或字符串的文本组合起来，并包括你在要组合的各文本值之间指定的分隔符。 如果分隔符是空的文本字符串，则此函数将有效连接这些区域。 |
| [TRIM 函数](https://support.microsoft.com/zh-cn/office/trim-函数-410388fa-c5df-49c6-b16c-9e5630b479f9) | 删除文本中的空格                                             |
| [UNICHAR 函数](https://support.microsoft.com/zh-cn/office/unichar-函数-ffeb64f5-f131-44c6-b332-5cd72f0659b8) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回给定数值引用的 Unicode 字符                              |
| [UNICODE 函数](https://support.microsoft.com/zh-cn/office/unicode-函数-adb74aaa-a2a5-4dde-aff6-966e4e81f16f) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回对应于文本的第一个字符的数字（代码点）                   |
| [UPPER 函数](https://support.microsoft.com/zh-cn/office/upper-函数-c11f29b3-d1a3-4537-8df6-04d0049963d6) | 将文本转换为大写形式                                         |
| [VALUE 函数](https://support.microsoft.com/zh-cn/office/value-函数-257d0108-07dc-437d-ae1c-bc2d3953d8c2) | 将文本参数转换为数字                                         |



## [与加载项一起安装的用户定义的函数](javascript:)

如果您安装的加载项包含函数，这些加载项或自动化函数将在**“插入函数”**对话框中的**“用户定义的”**类别中可用。

用户定义的函数（Udf）在 Excel 网页版 中不可用。

| **函数**                                                     | **说明**                                                     |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| [CALL 函数](https://support.microsoft.com/zh-cn/office/call-函数-32d58445-e646-4ffd-8d5e-b45077a5e995) | 调用动态链接库或代码源中的过程                               |
| [EUROCONVERT 函数](https://support.microsoft.com/zh-cn/office/euroconvert-函数-79c8fd67-c665-450c-bb6c-15fc92f8345c) | 用于将数字转换为欧元形式，将数字由欧元形式转换为欧元成员国货币形式，或利用欧元作为中间货币将数字由某一欧元成员国货币转化为另一欧元成员国货币形式（三角转换关系） |
| [REGISTER.ID 函数](https://support.microsoft.com/zh-cn/office/register-id-函数-f8f0af0f-fd66-4704-a0f2-87b27b175b50) | 返回已注册过的指定动态链接库 (DLL) 或代码源的注册号          |



## [Web 函数](javascript:)

Web 函数在 Excel 网页版 中不可用。

| **函数**                                                     | **说明**                                        |
| :----------------------------------------------------------- | :---------------------------------------------- |
| [ENCODEURL 函数](https://support.microsoft.com/zh-cn/office/encodeurl-函数-07c7fb90-7c60-4bff-8687-fac50fe33d0e) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回 URL 编码的字符串                           |
| [FILTERXML 函数](https://support.microsoft.com/zh-cn/office/filterxml-函数-4df72efc-11ec-4951-86f5-c1374812f5b7) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 通过使用指定的 XPath，返回 XML 内容中的特定数据 |
| [WEBSERVICE 函数](https://support.microsoft.com/zh-cn/office/webservice-函数-0546a35a-ecc6-4739-aed7-c0b7ce1562c4) ![ Excel 2013](https://support.content.office.net/zh-cn/media/8e14cf2e-885c-4c59-bf41-6f42d79e9fc8.png) | 返回 Web 服务中的数据。                         |

版本标记表示介绍函数的 Excel 版本。 这些函数在早期版本中不可用。

**重要:** 公式和某些 Excel 工作表函数的计算结果在采用 x86 或 x86-64 架构的 Windows PC 与采用 ARM 架构的 Windows RT PC 之间略有不同。 [进一步了解区别](https://support.microsoft.com/zh-cn/office/pc-和-windows-rt-计算机之间的计算区别-858c27e6-7843-4a8c-a5aa-d7b1cbd021d5)。

[返回页首](https://support.microsoft.com/zh-cn/office/excel-函数（按类别列出）-5f91f4e9-7b42-46d2-9bd1-63f26a86c0eb#top)

## 需要更多帮助吗？

可随时在 [Excel 技术社区](https://techcommunity.microsoft.com/t5/Excel/ct-p/Excel_Cat)中咨询专家，在[解答社区](https://go.microsoft.com/fwlink/?linkid=827514)获得支持，或在 [Excel User Voice](https://excel.uservoice.com/) 上建议新功能或功能改进。



## 另请参阅

[Excel 函数（按字母顺序）](https://support.microsoft.com/zh-cn/office/excel-函数（按字母顺序）-b3944572-255d-4efb-bb96-c6d90033e188)

[Excel 中的公式概述](https://support.microsoft.com/zh-cn/office/excel-中的公式概述-ecfdc708-9162-49e8-b993-c311f47ca173)

[如何避免损坏的公式](https://support.microsoft.com/zh-cn/office/如何避免损坏的公式-8309381d-33e8-42f6-b889-84ef6df1d586)

[检测公式中的错误](https://support.microsoft.com/zh-cn/office/检测公式中的错误-3a8acca5-1d61-4702-80e0-99a36a2822c1)

