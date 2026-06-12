# Ben & Nini Universe · 妮本 品牌网站

> **A cozy companion character universe for everyday life.**  
> 一个关于陪伴、成长与日常快乐的原创角色品牌。

---

## 📁 项目结构

```
brand_site/
├── index.html          品牌主站（8区块 · 资料库入口 · 滚动动画 · 浮动按钮）
├── bible.html          IP圣经 V2.0（品牌定位 · 世界观 · 角色红线 · 路线图）
├── products.html       产品目录（4级矩阵 · 15个SKU · 7个目标市场）
├── plush-guide.html    毛绒打板手册（尺寸 · 材质 · 工艺 · 质检要求）
├── content.html        内容素材库（语录/场景/社交文案/包装金句/话题标签）
├── tourism.html        文旅合作（6城市 · 4合作模式 · 限定产品方案）
├── guidelines.html     品牌视觉规范（10色板 · 角色锚点 · 使用禁区）
├── licensing.html      授权规范（授权层级 · 审批流程 · 质量验收 · 禁止条款）
├── crossborder.html    跨境销售规范（平台策略 · 合规要求 · 物流方案）
├── operations.html     品牌运营路线图（90天启动计划 · 周节奏 · KPI · 交付清单）
├── faq.html            常见问题（15问答 · 搜索 · 分类筛选）
├── factory.html        工厂询价表单（报价汇总 · 一键复制）
├── downloads.html      下载中心（打板文档索引 · 发送指南）
├── 404.html            品牌化404页面
├── sitemap.xml         SEO站点地图
├── robots.txt          爬虫规则
├── README.md           本文件
└── images/             品牌素材图片（4张PNG）
```

---

## 🚀 快速开始

### 本地预览

```bash
cd brand_site
python -m http.server 8080
```

浏览器打开 `http://localhost:8080`

### 部署到 GitHub Pages（免费）

```bash
# 1. 在 GitHub 创建仓库 bennini
# 2. 将 brand_site 文件夹内容推送到仓库
git init
git add .
git commit -m "Initial brand site"
git remote add origin https://github.com/你的用户名/bennini.git
git push -u origin main

# 3. 在仓库 Settings → Pages 启用 GitHub Pages
#    选择 main 分支，根目录 /
#    等待部署完成，访问 https://你的用户名.github.io/bennini
```

### 部署到 Vercel / Netlify

直接将 `brand_site` 文件夹拖入 Vercel/Netlify 控制台即可，无需任何配置。

---

## 🎨 技术栈

| 层级 | 技术 |
|------|------|
| 页面 | 纯 HTML5 + CSS3 + Vanilla JS |
| 样式 | CSS Custom Properties · Grid · Flexbox |
| 动画 | CSS Transitions · IntersectionObserver |
| 双语 | CSS `html[lang]` 切换 · 无框架依赖 |
| 响应式 | 3断点：>768px / ≤768px / ≤540px |
| SEO | Open Graph · sitemap.xml · robots.txt |
| 服务器 | Python http.server（本地）/ 任意静态托管（生产） |

---

## 🧭 当前站点能力

| 模块 | 入口 | 用途 |
|------|------|------|
| 品牌官网 | [index.html](index.html) | 对外展示品牌、角色、产品矩阵和合作入口 |
| IP圣经 | [bible.html](bible.html) | 统一世界观、角色设定、授权红线和长期路线 |
| 毛绒打板 | [plush-guide.html](plush-guide.html) | 给工厂对接尺寸、材质、工艺、质检和安全要求 |
| 产品矩阵 | [products.html](products.html) | 管理 SKU、尺寸体系、角色变体和目标市场 |
| 授权规范 | [licensing.html](licensing.html) | 对接品牌联名、产品授权和审批流程 |
| 跨境销售 | [crossborder.html](crossborder.html) | 规划 Amazon、TikTok Shop、独立站和各市场合规 |
| 运营路线 | [operations.html](operations.html) | 90天推进打样、内容、电商、文旅和授权动作 |
| 文旅合作 | [tourism.html](tourism.html) | 以东平为起点扩展城市限定和地方文化传播 |
| 下载中心 | [downloads.html](downloads.html) | 集中交付文档、素材、工厂话术和资料清单 |

---

## 🌐 品牌信息

| 项目 | 内容 |
|------|------|
| 品牌名 | Ben & Nini（中文：妮本） |
| 宣传名 | 小妮儿 & 本哥 |
| 核心价值 | 可靠 Reliable · 温柔 Gentle · 快乐 Joyful |
| 品牌定位 | 陪伴系原创角色 IP |
| 世界观 | 菜菜街 Caicai Street（无魔法 · 日常生活） |
| 目标用户 | 18-35岁女性为主 · 情侣 · 大学生 · 年轻职场人群 |
| 目标市场 | 🇨🇳中 🇺🇸美 🇪🇺欧盟 🇬🇧英 🇯🇵日 🇰🇷韩 🌏东南亚 |

### 三个角色

| 角色 | 中文名 | 核心价值 | 一句话 |
|------|--------|---------|--------|
| 🐶 Ben | 菜团 | 可靠 | "我来负责。" |
| 🐱 Nini | 菜饼 | 温柔 | "我理解你。" |
| 🥟 Caibao | 菜包 | 快乐 | "先试试看！" |

---

## 📊 统计与分析

生产环境建议接入：

```html
<!-- Google Analytics (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>

<!-- 百度统计 -->
<script>var _hmt=_hmt||[];(function(){var hm=document.createElement("script");hm.src="https://hm.baidu.com/hm.js?xxxxxxxxxx";var s=document.getElementsByTagName("script")[0];s.parentNode.insertBefore(hm,s)})();</script>
```

---

## 📋 产品开发路线

| 阶段 | 时间 | 内容 |
|------|------|------|
| 首批打样 | 2026 | Ben/Nini/Caibao M号标准公仔首样 |
| 文创周边 | 2026 Q4 | 表情包贴纸、亚克力挂件、钥匙扣 |
| 关系组合款 | 2027 | Ben+Nini 双人款、三角色全家福 |
| 文旅首站 | 2027 | 东平限定款上线 |
| 城市扩展 | 2028 | 泰山/青岛/杭州/成都等城市限定 |
| 盲盒系列 | 2028 | 菜菜街的一天 场景盲盒 |
| 品牌授权 | 2029+ | 咖啡店/书店/景区/动画/绘本授权 |

---

## ⚖️ 知识产权

Ben、Nini、Caibao 角色形象、名称、故事设定及所有品牌素材均为原创知识产权。未经书面授权，禁止复制、修改、传播或用于商业目的。

---

## 📧 联系

- 工厂合作：请填写 [工厂询价表单](factory.html)
- 文旅合作：查看 [文旅合作页](tourism.html)
- 品牌联名/授权/媒体：通过主页 [合作洽谈](index.html#contact) 联系

---

*Built with ❤️ on Caicai Street. © 2026 Ben & Nini Universe.*
