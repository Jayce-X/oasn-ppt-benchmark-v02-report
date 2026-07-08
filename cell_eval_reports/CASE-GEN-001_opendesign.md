# CASE-GEN-001 详细评分 - OpenDesign

状态：v0.2 新跑结果
分数：9/10

## 摘要

OpenDesign generated the strongest visual 10-slide HTML/SVG deck for Case 1. Its source artifact contains structured SVG/table content, so the chart/table requirement is counted; it still loses the final PPTX editability point because the report adapter rasterized slides.

产出：`/Users/weixiang/Desktop/clawlink2/test_runs/ppt_case1_multi_agent_20260702_215551/agents/opendesign/opendesign_CASE-GEN-001.pptx`

截图：`/Users/weixiang/Desktop/clawlink2/test_runs/ppt_case1_multi_agent_20260702_215551/report/screenshots/opendesign/montage.png`

## 打分项结果

### G1（事实依据）: 通过

PPT 是否始终把 Fancy's Foods / Whipped Dream 识别为调味奶油顶料业务，并基于来源商业计划书把输出定位为投资人或合作伙伴路演？

正确识别 Fancy's Foods 投资人路演主题。

### G2（事实依据）: 通过

产品口味、包装形式、保质期/验证主张和餐厅背景是否可追溯到 Fancy's Foods PDF，且没有未经支持的牵引力或渠道主张？

覆盖产品、包装形式、验证、扩张、分销、制造、财务和风险。

### G3（事实依据）: 通过

市场扩张、分销、制造、财务和风险表述是否限制在 PDF 支持的事实和数字内，包括使用到的一年正现金流和 10.88% 股本回报率？

来源约束较稳健，并明确避免编造融资金额。

### C1（覆盖度）: 通过

10 页投资人 PPT 是否实质覆盖全部 10 个指定简报部分？

正好 10 页，且顺序符合题目要求。

### N1（叙事）: 通过

页标题和内容是否形成连贯的投资人路演叙事，而不是来源摘要顺序或泛泛章节标签？

标题有明确观点，投资人叙事框架较强。

### V1（视觉）: 通过

商业计划 PPT 是否保持投资人级别的视觉层级、可读密度、一致设计系统，并且没有明显空白、溢出、裁切或重叠问题？

在当前产物中，视觉层级和信息密度表现最好。

### CH1（图表）: 通过

商业计划 PPT 是否至少有 3 页包含基于来源数字的可编辑图表或表格，而不是截图或装饰性占位？

通过。

### CH2（图表）: 通过

财务和数字图表/表格的值是否有来源支持或可直接推导，并带有有意义标签、单位和投资人相关结论？

可见数字都有标签，并且有来源支持。

### E1（可编辑性）: 未通过

输出是否是真正可编辑的 PPTX，标题、正文、图表/表格和主要形状是独立可编辑对象，而不是扁平化页面图片？

最终 PPTX 是截图适配产物，不是真正可编辑的 PPTX。

### EF1（效率）: 通过

智能体是否在生成预算内产出完整有效 PPTX，且无需评测端修复或反复重跑？

OpenDesign 新运行成功，并转换为有效的 10 页 PPTX。
