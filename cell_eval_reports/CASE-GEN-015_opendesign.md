# CASE-GEN-015 详细评分 - OpenDesign

状态：v0.2 新跑结果
分数：5/5

## 摘要

Strong self-attention explainer with readable process diagrams and matrix/heatmap visuals. Scored on the OpenDesign source artifact rather than repeatedly penalizing the report PPTX screenshot wrapper.

产出：`本地运行目录/test_runs/ppt_v02_multi_agent_20260703/agents/opendesign/CASE-GEN-015/opendesign_CASE-GEN-015.pptx`

截图：`本地运行目录/test_runs/ppt_v02_multi_agent_20260703/report/assets/evidence/opendesign_v02/CASE-GEN-015/CASE-GEN-015_opendesign_montage.png`

## 打分项结果

### G-014（事实依据）: 通过

PPT 是否准确解释 Transformer 自注意力公式、玩具维度、Q/K/V 角色、softmax 加权和 causal mask 约束？

通过。

### C-008（覆盖度）: 通过

PPT 是否覆盖 Q/K/V 投影、分数计算、softmax、加权 value、多头 split/concat、热力图解读和 causal mask？

通过。

### V-021（视觉）: 通过

自注意力 PPT 是否包含可读的 4×4 热力图或矩阵可视化，帮助解释 token 间注意力？

通过。

### V-022（视觉）: 通过

PPT 是否包含清晰的 split/project/score/softmax/weighted-sum/multi-head 流程图，适合产品工程师理解？

通过。

### E-014（可编辑性）: 通过

自注意力流程图和热力图/矩阵是否足够可编辑，可供后续教学或产品团队修改？

通过。
