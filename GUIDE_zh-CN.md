# 更低成本的 Diagram Design API 流程图方案

## 输入

[Original prompts and parameters](cases/briefs.json)

## 生成与输出

本地可编辑 HTML/SVG API 流程图 + 独立 ToAPIs PNG 示意图实测；PNG 是模型输出，HTML/SVG 由代码制作，未验证 Agent 宿主。

逐案例执行；生成后保存原 PNG 与 SHA256。参考案例依赖首张图；先生成或复用首张图，再执行参考编辑。不要删除 private-state 后重跑同一任务。

## 可编辑图与模型 PNG

直接打开 diagrams 中的 HTML 或 SVG，修改节点、箭头与文本。三张 API PNG 仅是对照示意图，文字与结构以真实输出为准；不要用 PNG 替代必须准确、可编辑的技术图。本地 HTML/SVG 制作无新增 API 调用费用；上方花费只属于三次独立 PNG 生成。

## 参数与截图

[Exact request evidence](evidence/runs.json) · [Original outputs](assets/)

README 中的双语封面由原图与脱敏请求信息制作，不是上游软件 UI 截图。
