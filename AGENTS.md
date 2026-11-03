# xylara-study — Agent Instructions

> 本仓库存放 **《AI 学习最终版方法论（摩擦优先回路）》** 及其 **参考文献审计清单**。
> 供 Agent / 人工复核、维护、扩展时参考。

---

## 仓库结构

```text
xylara-study/
├── docs/
│   ├── methodology.md       # 方法论本体（AI 学习最终版方法论）
│   └── audit-references.md  # 参考文献审计清单（17 条核心文献 + 6 项证据空白）
├── LICENSE                  # MIT License
└── .git/
```

---

## 核心文档说明

### methodology.md
- **内容**：AI 学习最终版方法论（摩擦优先回路），包含全景回路、10 个节点操作细则、单轮运行建议、废弃观点记录
- **核心原则**：AI 负责制造可检验的摩擦，不替你完成认知工作；外部结构只问责交付，不替代你的判断
- **置信等级**：A（元分析/RCT 直接支持）到 D（证据空白，合理假设）

### audit-references.md
- **内容**：17 条核心文献完整引用，**全部含经验证的 DOI + 多平台入口链接**
- **结构**：按方法论节点分组（先测效应、自我解释、手绘结构、AI审计、AI依赖、瓶颈前置、实施意图、Deadline、主动拖延、自我宽恕、FSRS）
- **证据空白表**：6 项 D/C 级条目，已诚实标注
- **补充说明**：未重新检索条目追溯指引、链接可用性说明、审计使用说明

---

## 已验证的关键 DOI（2025-11-03 通过 keenable search 核对）

| # | 文献 | DOI | 状态 |
|---|------|-----|------|
| 1 | Kliegl et al. (2024) | 10.1037/mac0000085 | ✅ |
| 2 | Hausman & Rhodes (2018) | 10.1037/xap0000160 | ✅ |
| 3 | Bisra et al. (2018) | 10.1007/s10648-018-9434-2 | ✅ |
| 4 | Chi et al. (1989) | 10.1207/s15516709cog1302_1 | ✅ |
| 5 | Leutner & Biele (2025) | 10.1007/s10648-025-10026-0 | ✅ |
| 6 | Schroeder et al. (2018) | 10.1007/s10648-017-9403-9 | ✅ |
| **7** | **Liu et al. (AIED 2026)** | **10.1007/978-3-032-29760-0_37** | **✅ 已修正** |
| **8** | **Tian & Zhang (2025, Acta Psychol)** | **10.1016/j.actpsy.2025.105725** | **✅ 已修正（期刊修正）** |
| 9 | Fan et al. (2024, BJET) | arXiv:2412.09315 | ✅ |
| 10 | 元认知懒惰条件性 | 共享 #9 文献群 | ✅ |
| 11 | Habbert & Schroeder (2020) | 10.1016/j.jesp.2020.104032 | ✅ |
| **12** | **Sheeran et al. (2025, Eur Rev Soc Psychol)** | **10.1080/10463283.2024.2334563** | **✅ 已修正** |
| 13 | Gollwitzer & Sheeran (2006) | 10.1016/S0065-2601(06)38002-1 | ✅ |
| 14 | Capelle et al. (2023) | 10.3389/fpsyg.2023.1224533 | ✅ |
| 15 | Chu & Choi (2005) | 10.3200/SOCP.145.3.245-264 | ✅ |
| 16 | Wohl et al. (2010) | 10.1016/j.paid.2010.01.029 | ✅ |
| 17 | open-spaced-repetition/srs-benchmark | GitHub: open-spaced-repetition/srs-benchmark | ✅ |

---

## 常用操作指南

### 审计/核对文献
1. 打开 `docs/audit-references.md`
2. 按 DOI 链接跳转原文核对效应量、样本量、边界条件
3. 重点核对标注 "优先核对" 的 8 条带效应量文献（#2, #3, #5, #6, #12, #13, #15, #17）

### 更新方法论
1. 修改 `docs/methodology.md`
2. 同步更新 `docs/audit-references.md` 对应节点的引用与置信等级
3. 新增文献时按现有格式添加：完整引用 + DOI + 多平台链接 + 支撑论点 + 边界 + 置信

### 文件命名规范
- 全小写 kebab-case：`methodology.md`、`audit-references.md`
- 文档集中于 `docs/` 目录
- 根目录仅保留 `LICENSE`、`.git`

---

## 远程仓库

- **Origin**: `git@github.com:ADX15xs/xylara-study.git`
- **默认分支**: `main`

---

## 变更记录

- **2025-11-03**: 整理仓库文档、补全审计来源、修正 3 个 DOI（#7, #8, #12）、文件重命名并移入 docs/、生成 AGENTS.md
