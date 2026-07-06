# CASE-GEN-002 详细评分 - OpenAgents（ppt master glm5.2）

状态：v0.2 新跑结果
分数：5/8

## 摘要

OpenAgents 的 Apple 发布 PPT 视觉完成度不错，文本和形状也可以在 PowerPoint 里编辑。主要扣分点是：有些产品参数和能力描述在 Apple PDF 中找不到依据；规格/功能对比也不是原生可编辑表格，部分数值无法回到来源核对。

产出：`本地运行目录/test_runs/ppt_v02_multi_agent_20260703/agents/openagents/CASE-GEN-002/openagents_CASE-GEN-002.pptx`

截图：`本地运行目录/test_runs/ppt_v02_multi_agent_20260703/report/assets/evidence/rendered_outputs/openagents/CASE-GEN-002/CASE-GEN-002_openagents_montage.png`

## 打分项结果

### G-004（事实依据）: 未通过

PPT 是否正确把 Apple iPhone 16 Pro 和 iPhone 16 Pro Max 作为发布主题，并且只使用来源支持的产品事实？

未通过。主题本身正确，但 PPT 里出现了 Apple PDF/事实表中找不到依据的参数，例如 35 万亿次运算/秒、电池小时数和充电细节。

### G-005（事实依据）: 未通过

Apple Intelligence、A18 Pro、Camera Control、专业相机、电池、钛金属和环保相关表述是否遵守来源约束，且没有夸大可用性或能力？

未通过。主要功能都提到了，但部分表述放宽了来源限制：Apple Intelligence 的隐私/可用性说法不够严谨，电池和充电细节缺少依据，环保部分也把 Apple 的 2030 目标说成了具体产品生命周期结论。

### C-002（覆盖度）: 通过

产品发布 PPT 是否覆盖 Apple 发布要求的定位、Apple Intelligence、A18 Pro、相机、显示屏、价格/上市、环保、受众和竞争框架？

通过。

### N-002（叙事）: 通过

PPT 是否讲出高级产品发布故事，把受众、功能层级和购买/定位逻辑连接起来？

通过。

### V-002（视觉）: 通过

产品发布 PPT 是否使用高级、产品相关的视觉层级和媒体/素材，适合 Apple 发布会场景？

通过。

### V-003（视觉）: 通过

产品发布 PPT 是否跨页面保持字体、间距、颜色和规格/功能布局的一致与可读？

通过。

### CH-003（图表）: 未通过

产品发布 PPT 是否包含结构化、来源支持的功能对比或规格表，且没有编造竞品规格？

未通过。PPT 里有规格展示，但不是 PowerPoint 原生可编辑表格/图表；性能、电池和规格面板里的部分数值也无法回溯到给定来源。

### E-002（可编辑性）: 通过

产品发布文本、功能表/对比、主要形状和媒体位置是否在 PPTX 中可编辑？

通过。
