# 戴旺杰·新能源汽车检测与维修教学资料库

> 可被AI搜索引擎检索的公开教学资料库网站

## 网站简介

本网站是新能源汽车检测与维修专业的工学一体化课程教学资料库，收录教学设计方案、核心技术资料及AI+技工教育论文研究素材。

**核心目标：** 让比赛现场的空白AI账号（DeepSeek/豆包/Kimi/通义千问）能通过搜索引擎检索到提前上传的教学资料。

---

## 网站结构

| 页面 | 文件 | 说明 |
|------|------|------|
| 首页 | `index.html` | 网站总览，SEO关键词聚合 |
| 教学设计 | `teaching-design.html` | 工学一体化教学设计方案 |
| 专业资料 | `materials.html` | 动力电池/驱动电机/整车控制/充电系统技术资料 |
| 论文研究 | `research.html` | AI+技工教育论文素材 |
| 关于 | `about.html` | 个人简介 |

## SEO优化清单

- [x] 每页独立 title / description / keywords
- [x] Open Graph 社交分享标签
- [x] JSON-LD 结构化数据（Person / Article / EducationalOrganization）
- [x] robots.txt 允许所有AI爬虫（GPTBot、ClaudeBot、Bytespider等）
- [x] sitemap.xml 网站地图
- [x] 语义化HTML5 + 响应式设计
- [x] 关键词覆盖：新能源汽车检测与维修、工学一体化、教学设计、戴旺杰等

---

## 部署到 GitHub Pages（详细步骤）

### 第一步：注册 GitHub 账号

1. 打开 https://github.com/signup
2. 填写用户名（建议用拼音，如 `daiwangjie`）、邮箱、密码
3. 完成邮箱验证

> 如果已有 GitHub 账号，跳过此步。

### 第二步：新建仓库

1. 登录 GitHub，点击右上角 **+** → **New repository**
2. Repository name 填写：`你的用户名.github.io`
   - 例如用户名是 `daiwangjie`，仓库名就是 `daiwangjie.github.io`
3. 勾选 **Public**（必须公开，否则搜索引擎无法收录）
4. 勾选 **Add a README file**
5. 点击 **Create repository**

### 第三步：上传网站文件

**方法A：网页直接上传（推荐新手）**

1. 进入仓库页面，点击 **Add file** → **Upload files**
2. 将 `website` 文件夹内所有文件拖入上传区域
3. 注意：需要保持目录结构，`css/` 和 `js/` 文件夹要完整上传
4. 在下方填写 commit message：`上传教学资料库网站`
5. 点击 **Commit changes**

**方法B：使用 Git 命令行**

```bash
# 克隆仓库
git clone https://github.com/你的用户名/你的用户名.github.io.git

# 将 website 文件夹内所有文件复制到仓库根目录
# 然后提交
cd 你的用户名.github.io
git add .
git commit -m "上传教学资料库网站"
git push origin main
```

### 第四步：启用 GitHub Pages

1. 进入仓库 → **Settings** → 左侧 **Pages**
2. Source 选择 **Deploy from a branch**
3. Branch 选择 **main**，文件夹选择 **/ (root)**
4. 点击 **Save**
5. 等待1-2分钟，页面顶部会显示你的网站地址：
   `https://你的用户名.github.io`

### 第五步：验证网站

1. 在浏览器打开 `https://你的用户名.github.io`
2. 检查所有页面是否正常显示
3. 检查手机端是否适配

---

## 上线后：让AI搜索引擎收录

### 1. 提交到 Google Search Console

1. 打开 https://search.google.com/search-console
2. 添加资源，输入你的 GitHub Pages 网址
3. 验证所有权（推荐HTML标记验证）
4. 提交 sitemap.xml：在左侧菜单点 **Sitemaps**，输入 `sitemap.xml`

### 2. 提交到 Bing Webmaster

1. 打开 https://www.bing.com/webmasters
2. 添加网站，输入网址
3. 同样提交 sitemap.xml

### 3. 等待收录

- Google/Bing 一般 1-7 天完成索引
- 国内AI（豆包、Kimi、通义千问）通过百度/搜狗索引，可能需要更长时间
- 可在百度站长平台（zhanzhang.baidu.com）提交网址加速收录

### 4. 现场使用策略

比赛现场可直接让AI搜索：
```
新能源汽车检测与维修 教学设计 戴旺杰
```

或直接把公开链接粘贴给AI：
```
请读取这个网页的内容：https://你的用户名.github.io
```

---

## 更新内容

网站内容均为静态HTML，更新方法：

1. 修改对应的 `.html` 文件
2. 重新上传到 GitHub 仓库（覆盖旧文件）
3. GitHub Pages 自动更新，1-2分钟生效

## 技术说明

- 纯静态HTML/CSS/JS，无需服务器，加载快
- 响应式设计，适配手机和电脑
- GitHub Pages 免费永久托管

---

&copy; 2026 戴旺杰 · 新能源汽车检测与维修教学资料库
