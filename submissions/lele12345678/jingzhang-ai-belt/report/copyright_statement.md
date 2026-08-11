# Copyright & Source Statement / 版权与来源声明

> 本声明覆盖投稿包中所有资产的版权、许可和来源信息。
> This statement covers copyright, licensing, and source information for all assets in the submission package.

## 1. 字体 / Fonts

| 字体 | 用途 | 许可 | 备注 |
|------|------|------|------|
| MiSans | 图片、PDF 中英文渲染 | Xiaomi 免费商用字体 | https://hyperos.mi.com/font-download |
| Helvetica | HTML 英文渲染 | 系统字体 | 标准 Web 字体 |

**许可声明**: MiSans 是小米提供的免费商用字体，允许商业使用。详见 https://hyperos.mi.com/font-download

## 2. 图标与图形 / Icons & Graphics

| 资产 | 来源 | 许可 | 备注 |
|------|------|------|------|
| assets/figures/*.png | AI 辅助生成 + 人工编辑 | CC BY 4.0 | 使用 Pillow (PIL) 生成，Noto Sans CJK SC 字体 |
| assets/figures/*.en.png | 英文版图件 | CC BY 4.0 | 与中文版同源 |

## 3. 地图与地理数据 / Maps & Geodata

| 资产 | 来源 | 许可 | 备注 |
|------|------|------|------|
| geometry/site_boundary.geojson | 从官方公告面积推导 | 临时数据 | ⚠ NOT official redline |
| geometry/key_areas.geojson | 从官方公告描述推导 | 临时数据 | ⚠ NOT official boundary |
| geometry/land_use.geojson | 设计建议 | 临时数据 | 设计方案，非控规 |
| geometry/green_space.geojson | 设计建议 | 临时数据 | 设计方案 |
| geometry/public_space.geojson | 设计建议 | 临时数据 | 设计方案 |
| geometry/buildings.geojson | 设计建议 | 临时数据 | 设计方案 |
| geometry/phasing.geojson | 设计建议 | 临时数据 | 分期方案 |

**重要声明**: 所有几何数据均为临时推导或设计建议，不构成官方红线或精确面积依据。待主办方提供正式几何数据后必须替换。

## 4. 数据来源 / Data Sources

| 来源 | 内容 | 许可 | 限制 |
|------|------|------|------|
| 官方公告 (2026-05-09) | 项目范围、面积、功能定位 | 公开信息 | 仅允许使用面积和任务描述，不允许推导官方 polygon |
| 任务书 (2026-05-18) | agent.1-6 要求、场景、画像 | 公开征集文件 | 按征集规则使用 |
| 全球案例研究 | AI 创新园区案例 | 公开信息 | 案例描述基于公开资料，来源已标注 |

## 5. 代码与工具 / Code & Tools

| 工具 | 用途 | 许可 |
|------|------|------|
| Python 3 | 脚本生成 | PSF License |
| Pillow (PIL) | 图片生成 | MIT License |
| fpdf2 | PDF 生成 | LGPL |
| Shapely | 几何计算 | BSD License |
| pyproj | 坐标变换 | MIT License |

## 6. AI 生成内容 / AI-Generated Content

| 内容类型 | 生成方式 | 人工编辑 |
|----------|----------|----------|
| proposal.md | Xiaomi MiMo v2.5 Pro 生成 + 人工编辑 | 是 |
| proposal.en.md | 从 proposal.md 翻译 + 人工校对 | 是 |
| HTML 文件 | 代码生成 | 是 |
| 图片 (PNG) | Pillow 代码生成（非 AI 图像模型） | 是 |
| PDF 文件 | fpdf2 代码生成 | 是 |
| GeoJSON | 代码生成 + 人工校验 | 是 |
| JSON 配置文件 | 代码生成 | 是 |

**声明**: 本方案中的文字内容由 AI 辅助生成，经人工编辑和校验。图片和 PDF 由代码程序化生成（非 AI 图像生成模型），使用开源字体和图形库。

## 7. 第三方材料 / Third-Party Materials

本投稿包中**不包含**任何第三方受版权保护的图片、照片、视频或音频材料。所有视觉内容均为程序化生成。

## 8. 许可条款 / License Terms

本投稿方案根据 **CC BY 4.0** (Creative Commons Attribution 4.0 International) 发布。

您可以：
- 共享 — 以任何媒介或格式复制及传播本材料
- 改编 — 混合、转换及基于本材料创作

条件：
- 署名 — 您必须给出适当的署名

## 9. 限制与免责 / Limitations & Disclaimers

1. 本方案为**开放共创建议**，不替代正式规划，不构成政府审定结论
2. 所有几何边界均为**临时数据**，不得作为官方红线或精确面积依据
3. 建筑高度、开发强度等控制值为**概念建议**，需正式规划审批
4. 全球案例描述基于公开信息，不保证信息的完整性和时效性
5. AI 生成内容已尽力确保准确性，但不保证无误

## 10. 资产权利核验状态 / Asset Rights Verification Status

| 资产类别 | 核验状态 | 备注 |
|----------|----------|------|
| 字体 | ✅ 已核验 | MiSans - 小米免费商用 |
| 图标/图形 | ✅ 已核验 | 程序化生成，CC BY 4.0 |
| 地图/地理 | ⚠️ 临时数据 | 待主办方正式数据替换 |
| 数据来源 | ✅ 已标注 | 来源已在正文和 source_registry 中标注 |
| 代码工具 | ✅ 已核验 | 全部为开源工具 |
| AI 生成 | ✅ 已声明 | 已注明生成方式和人工编辑 |
| 第三方材料 | ✅ 无 | 不包含第三方受保护材料 |

---

*Last updated: 2026-08-11*
*Submission: submissions/lele12345678/jingzhang-ai-belt*
