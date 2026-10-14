# 帝国时代2决定版 · 文明攻略

### Age of Empires II: Definitive Edition — Civilization Guide

> 面向《帝国时代2：决定版》模组 **「文明联盟」(Civilization Alliance)** 的全文明数据整理，以及**各流派「最优研究顺序」**推荐。
> 62 个文明的全部特性逐条整理；11 个流派各自一张推荐表；所有结论都与游戏官方简体中文字串、官方 `CivTechTrees` JSON、`empires2_x2_p1.dat` 交叉验证。

---

## 一、这是什么

「文明联盟」模组里可以**自选一个文明**当底座，然后通过 **62 个科技按钮**逐一「结盟」其他文明——每个按钮代表该文明的全部特性（**含独特科技、不含独特单位**），**每个按钮只能研究一次**。

于是问题变成：**62 个按钮，一个文明只能拿一部分，怎么选最划算？**

本仓库回答的正是这个问题，并给出：

- 📋 **62 个文明的全量特性总表**（主要功能 / 独特科技 / 团队加成 / 独特单位）
- 🎯 **11 个流派的最优研究顺序**（开局 3 免费位 → 后续 2000 金顺序 → 全 62 文明总名次）
- 🏆 **每个流派的主选文明推荐**（该流派用哪个文明当底座最强）
- 🖼️ **62 张文明卡片原图**（一切数据的原始依据）

### 模组机制（所有推荐表都按这个前提编排）

| 项目 | 规则 |
|---|---|
| 开局免费位 | **只有 3 个**，必须一次定好 |
| 之后每个 | **2000 金 / 个**，越往后越贵 |
| 按钮限制 | **一个按钮只能研究一次**，不能重复买 |
| 正确流程 | **先定主选文明**（底座），再按缺口挑 3 个免费位，最后按 2000 金顺序补 |

> ⚠️ **最容易犯的错**：主选文明**已经自带**的加成，不要再用按钮买一遍——一个按钮只能研究一次，重复等于白花 2000 金。

---

## 二、内容清单

### 📊 总表（1 张）

| 文件 | 内容 | 页数 |
|---|---|---|
| `帝国时代2决定版 文明联盟 全文明特色.xlsx` | 62 文明 × 4 栏（文明定位 / 主要功能 / 独特科技 / 团队加成）+ 独特单位 | 2 |

### 🎯 流派推荐表（11 张）

| 文件 | 流派 | 核心问题 |
|---|---|---|
| `… 箭塔流最优研究顺序 …` | 箭塔 / 瞭望箭塔系 | 封建塔爆怎么开局 |
| `… 炮塔流最优研究顺序 …` | 炮塔（Bombard Tower） | 帝王期炮塔怎么成型 |
| `… 城堡流最优研究顺序 …` | 城堡 / 防御工事 | 城堡推、城堡防守 |
| `… 步兵流最优研究顺序 …` | 步兵 / 民兵系 | 步兵海、步兵强攻 |
| `… 弓兵流最优研究顺序 …` | 步弓手 / 掷矛手系 | 弓兵推、远程压制 |
| `… 骑射流最优研究顺序 …` | 骑射手 | 骑射骚扰、机动火力 |
| `… 骑兵流最优研究顺序 …` | 骑士 / 斥候 / 骆驼 / 象兵 | 骑兵冲阵 |
| `… 弩车流最优研究顺序 …` | 蝎式弩 / 攻城武器 | 弩车推建筑 |
| `… 巨型投石机流最优研究顺序 …` | 巨型投石机 | 拆城攻坚 |
| `… 发育经济流最优研究顺序 …` | 村民 / 经济 / 资源 | 纯发育、长局经济 |
| `… 海战流最优研究顺序 …` | 战船 / 码头 / 海军 | 水图海战 |

### 🖼️ 文明卡片原图（62 张）

`01 阿兹特克 By RemonBo.png` … `62 雅典 By RemonBo.png`

共 62 张，全部小写编号与文明序号一致。**这是所有表格数据的原始依据**，任何一条存疑时都应回到原图核对。

---

## 三、流派表的结构（每张 8 页）

| 页签 | 内容 |
|---|---|
| **开局3免费位** | 开局唯三的免费位该怎么点；每位给 1 个首选 + 2 个备选与替换条件 |
| **后续2000金顺序** | 第 4 名之后的完整顺序（顺位 / 文明 / 档位 / 关键机制 / 生效条件 / 为什么） |
| **甲类 · 本体强化** | 直接加强该流派**本体**的条目（火力 / 耐久 / 功能） |
| **乙类 · 费用与前置** | 降低费用、免费科技、以及关键前置 |
| **与该流派无关 · 可跳过** | 明确**不用买**的文明，并逐条写「差在哪」 |
| **主选文明推荐** | 该流派用哪个文明当底座最强（科技树完整度 + 原生加成 + 短板） |
| **全62文明总名次** | 1–62 名完整排序，前 10 名标红 |
| **说明** | 口径、决定性前提、门槛、模组专属机制、未验证项 |

**档位**：`S` 最优 → `A` → `B` → `C` → `D`（不建议）。

---

## 四、数据来源与可信度

| 来源 | 用途 |
|---|---|
| **62 张文明卡片原图** | 一切条目的**第一依据**（逐条人工核对） |
| 官方简中字串 `key-value-strings-utf8.txt` | 术语权威（如「瞭望箭塔系」≠「炮塔」的区分） |
| 官方 `CivTechTrees\*.json`（62 份） | 主选文明的**科技树完整度** |
| 官方 `empires2_x2_p1.dat` | 效果的**实现层**验证（unit class / 属性 ID） |
| 模组文本 `key-value-modded-strings-utf8.txt` | 模组专属机制（塔防 SSR、切换贸易产石等） |

### 已经过实现层验证的关键结论（举例）

- **「瞭望箭塔系」≠「炮塔」**：官方 `unitlines.json` 的 `watch-tower-line` 只含 `79/234/235`，**不含 236 炮塔**；官方在需要排除炮塔时明写 `Watch Tower-line`。
- **撒克逊人「塔和城堡基础箭矢 +100%」对炮塔生效**：dat 里该效果按 **unit class 52（塔类）通配**加值，而炮塔 236 的 `Class` 正是 `52`。但炮塔 `TotalProjectiles = 0`、靠引擎「有主弹药则保底射 1 发」，所以**官方原版 +1 属于空转，本模组放大成 +5 才真正变成多发炮弹**；且**撒克逊自己造不了炮塔**，需底座文明能造才吃得到。
- **火绳枪（Arquebus）对炮塔生效**：官方帮助文本直接写「提升了火药单位**和炮塔**对移动中目标的准确度」。

### 未验证项

各表「说明」页均单列**未验证项**，例如效果的加算/乘算叠加方式、部分科技的实际生效范围等。这些是按官方文字与 dat 语义推算的相对排序，**不是逐项实机实测**，请在游戏内确认。

---

## 五、使用方法

1. 克隆或直接下载本仓库：
   ```bash
   git clone https://github.com/198agk/aoe2de-civilization-guide.git
   ```
2. 用 **Excel / WPS / LibreOffice** 打开 `tables/` 下（本仓库为平铺）对应流派的 xlsx。
3. 先看「说明」页了解口径与未验证项。
4. 按「主选文明推荐」定底座 → 按「开局3免费位」点前 3 个 → 按「后续2000金顺序」往下补。
5. 存疑的条目，回 `01`–`62` 的卡片原图核对。

---

## 六、搜索关键词 / Search Keywords

> 本仓库所有内容均可用**中文检索**。下面列出你可能用来找它的说法，覆盖游戏名、模组名、文明名、流派名与常见问法。

**游戏名**
帝国时代2、帝国时代二、帝国2、帝国2决定版、帝国时代2决定版、帝国时代2：决定版、帝国时代 II、AoE2、AoE 2、Age of Empires 2、Age of Empires II、AoE2DE、AOE2DE、决定版、DE版、罗马复兴

**模组名**
文明联盟、文明联盟模组、Civilization Alliance、文明联盟攻略、文明联盟机制、文明联盟结盟、联盟模组、62 按钮、62个科技按钮、科技按钮、结盟、联盟科技点、文明联盟骡车

**数据内容**
全文明特色、文明特色、文明特性、全文明数据、文明加成、文明一览、文明对比、文明强度、独特科技、金冠科技、银冠科技、团队加成、组队加成、独特单位、文明卡片、文明卡、数据表、Excel 表格、对照表、总表、攻略表

**流派 / 打法**
最优研究顺序、研究顺序、开局顺序、开局三选、开局3免费位、首发选择、选择顺序、优先级、推荐顺序、2000金、买什么、怎么选、怎么点、加点顺序、流派、打法、套路、战术
箭塔流、塔爆、塔rush、塔攻、瞭望箭塔、箭塔推、防御塔
炮塔流、炮塔、Bombard Tower、火绳枪、Arquebus
城堡流、城堡推、城堡攻、防御工事、城楼、营垒
步兵流、步兵海、民兵系、剑士、长剑士、冠军剑士、长矛兵、戟兵
弓兵流、步弓手、弓兵推、弩手、强弩兵、掷矛手、标枪兵、长弓兵
骑射流、骑射手、马弓、帕提亚战术、扳指
骑兵流、骑士、圣骑士、游侠、斥候、轻骑兵、骆驼兵、象兵、冲车
弩车流、蝎式弩、弩炮、重型蝎式弩、攻城武器
巨型投石机流、巨型投石机、投石机、抛石机、牵引抛石机、拆城
发育流、经济流、发育经济流、种田、爆经济、村民、采果工、伐木工、采矿工、贸易、市场、农田
海战流、海战、海军、水图、战船、箭船、大型战舰、喷火船、爆破船、炮舰、德罗蒙、卡拉维尔、码头、渔船
主选文明、底座文明、本命文明、选哪个文明、哪个文明好

**常见问法**
帝国时代2文明联盟怎么玩、文明联盟按钮怎么选、文明联盟先选什么、文明联盟开局选什么、文明联盟哪个文明强、帝国2决定版全文明加成、帝国2文明特色表、帝国2流派怎么打、箭塔流怎么开局、炮塔流顺序、骑兵流怎么选、海战流选什么文明

**English**
Age of Empires 2, Age of Empires II, Definitive Edition, AoE2DE, civilization guide, civilization bonuses, civ list, unique tech, team bonus, unique unit, Civilization Alliance mod, tech buttons, alliance, build order, research order, optimal order, tier list, spreadsheet, walkthrough
tower rush, bombard tower, castle drop, infantry, archer, cavalry archer, cavalry, scorpion, trebuchet, economy boom, naval, best base civilization

---

## 七、全部 62 个文明 / All 62 Civilizations

**常规文明（01–56）**

阿兹特克 Aztecs、埃塞俄比亚 Ethiopians、柏柏尔 Berbers、拜占庭 Byzantines、保加利亚 Bulgarians、波兰 Poles、波斯 Persians、波希米亚 Bohemians、
勃艮第 Burgundians、不列颠 Britons、达罗毗荼 Dravidians、鞑靼 Tatars、丹麦人 Danes、法兰克 Franks、高丽 Koreans、高棉 Khmer、
哥特 Goths、格鲁吉亚 Georgians、凯尔特 Celts、库曼 Cumans、立陶宛 Lithuanians、罗马 Romans、马来 Malay、马里 Malians、
马普切 Mapuche、马扎尔 Magyars、玛雅 Mayans、蒙古 Mongols、孟加拉 Bengalis、缅甸 Burmese、穆伊斯卡 Muisca、女真 Jurchens、
葡萄牙 Portuguese、契丹 Khitans、瞿折罗 Gurjaras、日本 Japanese、撒克逊人 Saxons、萨拉森 Saracens、蜀 Shu、斯拉夫 Slavs、
条顿 Teutons、图皮 Tupi、土耳其 Turks、瓦兰吉人 Varangians、维京 Vikings、魏 Wei、吴 Wu、西班牙 Spanish、
西西里 Sicilians、匈奴 Huns、亚美尼亚 Armenians、意大利 Italians、印度斯坦 Hindustanis、印加 Incas、越南 Vietnamese、中国 Chinese

**古典模式文明（57–62，Chronicles）**

阿契美尼德 Achaemenids、马其顿人 Macedonians、普鲁人 Purus、色雷斯人 Thracians、斯巴达 Spartans、雅典 Athenians

> 每个文明在总表里都有：**文明定位 / 主要功能 / 独特科技 / 团队加成 / 独特单位**。

---

## English

**Age of Empires II: Definitive Edition — Civilization Guide** (for the *Civilization Alliance* mod)

The **Civilization Alliance** mod lets you pick one base civilization and then unlock other civilizations' bonuses through **62 tech buttons** — each button grants one civilization's full set of traits (**unique techs included, unique units excluded**), and **each button can only be researched once**.

This repository contains:

- **Full trait tables for all 62 civilizations** — civ role, main bonuses, unique techs, team bonus, and unique unit
- **Optimal research orders for 11 playstyles** — Tower, Bombard Tower, Castle, Infantry, Archer, Cavalry Archer, Cavalry, Scorpion, Trebuchet, Economy, and Naval
- **Best base-civilization recommendations** per playstyle (tech-tree completeness + native bonuses + weaknesses)
- **62 original civilization card images** — the primary source for every entry

Every playstyle workbook follows an 8-sheet layout: `3 free picks`, `2000-gold order`, `Class A — core upgrades`, `Class B — cost & prerequisites`, `Irrelevant civs (skip)`, `Best base civ`, `Full 62-civ ranking`, and `Notes`.

All data is cross-checked against the game's official Simplified Chinese strings, the official `CivTechTrees` JSON files, and `empires2_x2_p1.dat` at the implementation level (unit classes and attribute IDs). Unverified items are listed explicitly on each workbook's Notes sheet.

---

## 致谢与声明 / Credits & Disclaimer

- **整理 / 制作：RemonBo**（所有表格文件名均带 `By RemonBo`）
- 数据依据为**玩家制作**的 62 张文明卡片原图，并与游戏官方数据交叉验证。卡片与表格均为玩家整理内容。
- 本项目为**非官方玩家攻略**，与 Microsoft / Forgotten Empires / World's Edge 无关；《Age of Empires》为 Microsoft 的商标。
- 模组「文明联盟」版权归其作者所有。
- 内容整理仅供学习交流使用，欢迎转载但请注明出处。

**欢迎提交 Issue 反馈错误**——如果你在游戏内实测到与表格不符之处，请附上截图或复现步骤，我会更新表格。
