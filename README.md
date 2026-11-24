<div align="center">

# 🚀 NOVA ERP

**零服务器、零 SQL、零 Node.js、零数据库维护——用 GitHub API 驱动的全能型浏览器 ERP 系统！**

<br />

[![Version](https://img.shields.io/badge/Version-v3.1.40.3-2563EB?style=for-the-badge)](#版本与技术信息)
[![Architecture](https://img.shields.io/badge/Stack-HTML%20%7C%20JS%20%7C%20JSON-F59E0B?style=for-the-badge)](#版本与技术信息)
[![Backend](https://img.shields.io/badge/Storage-GitHub%20API-10B981?style=for-the-badge)](#版本与技术信息)
[![Language](https://img.shields.io/badge/UI%20Language-English%20Only-6366F1?style=for-the-badge)](#版本与技术信息)

<br />

<p>
  无论是<strong>大型企业、中小企业、零售门店</strong>，还是<strong>餐饮与临时业务场景</strong>，<br />
  <strong>NOVA ERP</strong> 都为你整合了日常运营所需的整套核心模块。<br />
  无需复杂部署环境，打开即用，把数据与配置牢牢握在自己手里。
</p>

</div>

---

## ✨ 核心亮点

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ 真正免后端搭建</h3>
      <p>无需自建服务器、数据库或 Node.js 运行环境，依托 <strong>GitHub API</strong> 实现数据存储与同步，告别繁琐配置与高昂服务器成本。</p>
    </td>
    <td width="50%" valign="top">
      <h3>🏪 多行业全场景覆盖</h3>
      <p>兼顾常规商业管理、销售业绩追踪、餐饮桌台状态（红/绿状态直观区分）以及临时/快闪业务需求。</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🪶 轻量纯前端架构</h3>
      <p>基于 <strong>HTML、JavaScript 与 JSON</strong> 构建，结构清晰、部署快捷、易于扩展，浏览器端即可流畅运行。</p>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ 完整操作留痕</h3>
      <p>从员工打卡、费用报销、薪资记录到全系统操作日志，关键业务节点清晰可查，权责分明。</p>
    </td>
  </tr>
</table>

---

## 📦 版本与技术信息

| 项目 | 说明 |
| :--- | :--- |
| **最新版本** | `v3.1.40.3` **`[NEW]`** |
| **界面语言** | 目前仅支持英文（English） |
| **系统架构** | HTML + JavaScript + JSON |
| **核心数据引擎** | GitHub API（免传统 SQL 数据库与独立后端服务） |

---

## 🧩 完整功能清单（共 30 项模块）

| 序号 | 功能模块 | 序号 | 功能模块 | 序号 | 功能模块 |
| :---: | :--- | :---: | :--- | :---: | :--- |
| **01** | 基础登录与数据克隆 (`Login & Data Clone`) | **11** | 效期追踪 (`Expiry Tracker`) | **21** | 薪资记录 (`Payroll`) |
| **02** | 基础首页仪表盘 (`Dashboard / Home`) | **12** | 库存盘点 (`Stock Check`) | **22** | 费用报销 (`Claims`) |
| **03** | 系统安装引导界面 (`Setup / Install`) | **13** | 订单管理 (`Orders`) | **23** | 考勤时间线 (`Timeline`) |
| **04** | POS 收银系统 (`POS`) | **14** | 采购开单 (`Purchase`) | **24** | 会员管理 (`Members`) |
| **05** | 桌台管理 (`Table`) | **15** | 调拨与配送 (`Delivery`) | **25** | 促销员管理 (`Promoter`) |
| **06** | 销售绩效 (`Sales Performance`) | **16** | 换货管理 (`Exchange`) | **26** | 收银柜台管理 (`Station Intel`) |
| **07** | 销售记录 (`Sales Records`) | **17** | 退货管理 (`Returns`) | **27** | 工作笔记 (`Notes`) |
| **08** | 收据查看与重印 (`Receipt Viewer`) | **18** | 云端网盘存储 (`Drive Storage`) | **28** | 系统操作日志 (`Logs`) |
| **09** | 佣金报表 (`Commission Report`) | **19** | 员工与账号管理 (`Staff`) | **29** | 公司与分公司管理 (`Company`) |
| **10** | 商品与 SKU 管理 (`Products / SKU`) | **20** | 员工手册 (`Staff Manual`) | **30** | 基础系统设置 (`Settings`) |

---

## 📖 功能详细介绍

<details open>
<summary><strong>💳 一、前台收银与门店运营（POS / Table / Station Intel / Receipt Viewer）</strong></summary>
<br />

1. **POS（收银台）**：支持多种收款与结算方式，涵盖**现金、QR、银行卡、电子钱包（Wallet）、分期付款**以及**记账（赊账/挂账）**。
2. **Table（桌台状态）**：专为餐饮场景打造，直观区分桌台状态——🟢 **绿色代表空座**，🔴 **红色代表已下单或有人使用**。
3. **Station Intel（收银柜台）**：可创建多个收银台/站点，并在 POS 界面中切换对应柜台进行收银。
4. **Receipt Viewer（收据查看器）**：支持随时查询并**重新打印收据**给顾客。

</details>

<details open>
<summary><strong>📈 二、销售、客户与推广管理（Sales / Members / Promoter）</strong></summary>
<br />

5. **Sales Performance（销售绩效）**：面向销售团队，展示员工**销售目标**与**当前实际销售额**对比。
6. **Sales Records（销售记录）**：集中查看所有历史销售明细，方便核对与追踪。
7. **Commission Report（佣金报表）**：面向销售业务，清晰查看每位员工对应的**佣金（Commission）**数据。
8. **Members（会员系统）**：为顾客建立会员档案，支持**预约登记、会员积分**与**会员等级**管理。
9. **Promoter（促销员管理）**：适用于涉及驻场或跨店推广的企业，管理外部促销人员来访推广，或安排内部员工前往合作企业/门店推广。

</details>

<details open>
<summary><strong>📦 三、商品、库存与供应链（Products / Expiry / Stock / Supply Chain）</strong></summary>
<br />

10. **Products（商品/SKU 管理）**：适用于零售、餐饮等所有售卖型业务，内置 `More` 扩展选项，提供更丰富的商品管理能力。
11. **Expiry Tracker（效期追踪）**：自动帮你盯紧临期商品，提前标注**即将过期的产品**，降低损耗风险。
12. **Stock Check（库存盘点）**：快速对比盘点结果，找出**多出**或**少于仓库账面**的货品（需手动执行盘点操作）。
13. **Orders（订单管理）**：支持企业内部进货下单，也可协助处理顾客订单（需手动操作）。
14. **Purchase（采购开单）**：帮助企业快速创建采购单据（需手动操作）。
15. **Delivery（配送/调货）**：将货物配送至旗下关联企业或合作企业。
16. **Exchange（换货）**：当采购货物出现瑕疵或损坏时，支持向原供货方发起换货处理。
17. **Returns（退货）**：当进货过多时，支持向供货来源办理多余商品退回。

</details>

<details open>
<summary><strong>👥 四、团队、人事与行政（Staff / Manual / Payroll / Claims / Timeline）</strong></summary>
<br />

18. **Staff（员工管理）**：新增员工时快速建档，并为员工创建专属登录账号。
19. **Staff Manual（员工手册）**：仅限管理人员发布说明/须知，员工阅读后勾选确认，即表示已完成阅读。
20. **Payroll（薪资记录）**：主打记录员工工资发放与薪资明细。
21. **Claims（费用报销）**：员工垫付采购或产生可报销费用后提交索赔，可为其开立报销记录。
22. **Timeline（考勤时间线）**：覆盖全企业员工打卡记录，清晰呈现每天的**上班时间到下班时间**。

</details>

<details open>
<summary><strong>🗂️ 五、文档、日志、公司与系统配置（Drive / Notes / Logs / Company / 基础模块）</strong></summary>
<br />

23. **Drive Storage（网盘存储）**：支持上传资料、**在线编辑与在线创建文件**，也可随时下载到本地设备。
24. **Notes（工作笔记）**：员工可在其中创建、编辑或删除个人/工作日志与便签。
25. **Logs（系统日志）**：记录全系统关键变动——无论是谁进行了**修改、编辑还是删除**，都会留下操作记录。
26. **Company（公司管理）**：仅限管理人员创建，支持维护主公司以及旗下**分公司**信息。
27. **基础登录与数据克隆 / 首页仪表盘 / 安装引导界面 / Settings（基础设置）**：提供完整的账号登录与数据克隆能力、初始安装引导、系统首页入口以及基础参数配置。

</details>

---

## 🛠️ 快速上手

```text
1. 下载或克隆本仓库源码（v3.1.40.3）
        │
        ▼
2. 打开「安装系统界面」配置 GitHub API 参数
        │
        ▼
3. 登录系统，创建公司与员工账号，开始运营！
