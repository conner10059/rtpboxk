<h1> Mobile Article Aggregator Platform (MAP)</h1><br><br><hr><br>

Mobile Article Aggregator Platform 是一个面向移动端内容聚合与分发场景的开源技术资源导航站。该项目定位于为开发者、技术研究人员以及内容运营团队提供结构化的移动端文章链接索引与快速检索能力，解决移动端技术文章分散、检索效率低下、域名迁移频繁导致链接失效等实际问题。

项目本身不存储任何文章内容，仅作为外链元数据的索引层与展示层，通过静态化的资源列表与分类标签体系，帮助用户在海量移动端技术文档中快速定位目标资源。目标用户包括移动端开发工程师、全栈技术学习者、技术博客维护者以及企业内部知识库管理人员。

<h2>功能概览</h2><br>

<p><h3>海量链接索引管理</h3>：支持对超过 250 条移动端技术文章链接进行集中存储与分类展示，覆盖多种技术子领域。</p>

<p><h3>静态化资源列表呈现</h3>：所有链接以纯 Markdown 形式维护于项目仓库中，无需数据库依赖，便于版本控制与协作编辑。</p>

<p><h3>分类标签体系</h3>：根据文章主题、技术栈或访问热度对链接进行逻辑分组，降低用户筛选成本。</p>

<p><h3>快速检索入口</h3>：提供基于文章 ID 或路径关键字的本地搜索功能，提升链接定位速度。</p>

<p><h3>链接状态检测工具</h3>：集成可选的定时检测脚本，自动标记可能失效或响应异常的链接，保障资源列表的有效性。</p>

<p><h3>移动端适配展示</h3>：前端模板针对手机和平板设备进行优化，确保在移动浏览器上获得良好的阅读与导航体验。</p>

<p><h3>开源协作扩展机制</h3>：支持社区用户通过提交 Issue 或 Pull Request 的方式新增、更新或删除链接条目，保持资源列表的时效性。</p>

<p><h3>轻量化部署能力</h3>：项目整体基于静态文件生成，可托管于任何支持 HTTP 服务的平台，包括 GitHub Pages、Cloudflare Pages 或自建 Nginx 服务器。</p>

<h2>应用场景</h2><br>

技术团队内部知识库建设：企业内部的技术团队可将本项目作为基础框架，整理团队内部积累的移动端技术文章链接，形成统一的知识索引入口，减少重复的文档查找工作。

个人技术博客的友情链接扩展：独立技术博客作者可利用本项目的资源列表作为博客侧边栏的补充，为读者提供更多外部阅读资源，同时降低博客维护外链的复杂度。

技术社区的内容聚合展示：技术社区运营方可基于本项目快速搭建文章推荐专区，将社区内的高质量技术帖按分类进行外链汇总，提升社区内容的曝光率与复用率。

技术培训课程的参考资料索引：培训机构或技术讲师可将本项目作为课程参考资料库，将课程中涉及的外部延伸阅读链接统一整理到项目列表中，方便学员课后查阅。

开源项目文档的关联资源导航：开源项目维护者可在项目文档中引用本项目的资源列表，为使用者提供相关的技术背景阅读材料，丰富项目的辅助信息生态。

<h2>快速开始</h2><br>

以下步骤将帮助您在本地环境快速部署并运行本项目的静态站点。

# 1. 克隆项目仓库到本地
git clone https://github.com/example/mobile-article-aggregator.git
cd mobile-article-aggregator

# 2. 安装项目依赖（基于 Node.js 环境）
npm install

# 3. 运行本地开发服务器，默认监听端口 3000
npm run dev

执行上述命令后，在浏览器中访问 `http://localhost:3000` 即可查看资源列表页面。如需构建生产环境静态文件，请执行 `npm run build`，生成的静态资源位于 `dist` 目录下。

<h2>安装要求</h2><br>

| 依赖项 | 必需版本 | 说明 |
|--------|----------|------|
| Node.js | 18.0 及以上 | 项目构建工具与开发服务器运行环境 |
| npm | 8.0 及以上 | Node.js 包管理器，用于安装项目依赖 |
| Git | 2.30 及以上 | 用于克隆仓库与版本管理 |
| 现代浏览器 | Chrome 90+ / Firefox 88+ | 前端页面访问与调试支持 |
| HTTP 服务器 | 任意静态文件服务 | 生产环境托管构建后的静态文件，如 Nginx、Caddy 或 Apache |
| 可选：Shell 环境 | Bash 4.0+ | 运行链接状态检测脚本（位于 scripts/ 目录） |

<h2>文档导航</h2><br>

| 层面 | 目录 | 回答的问题 |
|------|------|------------|
| 用户入门 | docs/getting-started.md | 如何使用本项目的资源列表？如何通过分类标签快速找到所需文章？ |
| 维护者指南 | docs/maintenance.md | 如何新增、修改或删除链接条目？链接格式校验规则是什么？ |
| 开发贡献 | docs/contributing.md | 如何搭建开发环境？代码风格规范与提交信息格式要求有哪些？ |
| 部署运维 | docs/deployment.md | 如何将站点部署到生产服务器？如何配置自定义域名与 HTTPS？ |

<h2>资源列表</h2><br>

<h3>移动端技术文章链接汇总</h3><br>

以下列表收录了本批次（第 8/24 批，共300 个资源链接）的全部移动端文章外链。所有链接均按照用户提供的原始格式原样呈现，未做任何协议、域名或路径的改动。

gitlab.com/EHWGW/fxleljy/-/commit/b5382b782488e07cdf8eb65746c5da88e9d34126?/rLp
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e63781dfd5595937a5aaf6bd55c25fd742b45977
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e63781dfd5595937a5aaf6bd55c25fd742b45977?/oP=5Tk
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e63781dfd5595937a5aaf6bd55c25fd742b45977?/6a4
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f5a1acbbf2fe918872b78daf7e521a425bd6908c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f5a1acbbf2fe918872b78daf7e521a425bd6908c?/Dq=elV
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f5a1acbbf2fe918872b78daf7e521a425bd6908c?/PtN
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b887cc4cbdfd7d761d72aa72707cf42873f831ed
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b887cc4cbdfd7d761d72aa72707cf42873f831ed?/YI=mFj
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b887cc4cbdfd7d761d72aa72707cf42873f831ed?/iCg
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0f3b445996c3c6dab8067f7702202bd08329ded2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0f3b445996c3c6dab8067f7702202bd08329ded2?/YW=TNh
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0f3b445996c3c6dab8067f7702202bd08329ded2?/RvP
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8ca1cf58d2dc4ce869654ae45766d5c34b1414b8
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8ca1cf58d2dc4ce869654ae45766d5c34b1414b8?/D4=Hli
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8ca1cf58d2dc4ce869654ae45766d5c34b1414b8?/EiC
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e5843c86f91196ac2b6206aadac244abc40b2121
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e5843c86f91196ac2b6206aadac244abc40b2121?/ei=Mdg
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e5843c86f91196ac2b6206aadac244abc40b2121?/TxR
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/78f9bd5a8a4ddc90069f070fa97903d8386e44f4
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/78f9bd5a8a4ddc90069f070fa97903d8386e44f4?/EY=j6q
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/78f9bd5a8a4ddc90069f070fa97903d8386e44f4?/GkE
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/2da24b60f266c039e56779250dfaf4f4817cb4e9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/2da24b60f266c039e56779250dfaf4f4817cb4e9?/Bf=9dd
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/2da24b60f266c039e56779250dfaf4f4817cb4e9?/3XV
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e0327359d1f2a987bbbc24ee52a687af01763738
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e0327359d1f2a987bbbc24ee52a687af01763738?/8J=9NK
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e0327359d1f2a987bbbc24ee52a687af01763738?/qKo
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c33825038be967c07cbb793bf97faf1f60df945b
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c33825038be967c07cbb793bf97faf1f60df945b?/CA=71L
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c33825038be967c07cbb793bf97faf1f60df945b?/b5Z
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e7c30db3c1ad95ab8655ca4dfeb816ee985aa769
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e7c30db3c1ad95ab8655ca4dfeb816ee985aa769?/DR=rlZ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e7c30db3c1ad95ab8655ca4dfeb816ee985aa769?/OsM
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b74608d44023d735ba163716a2d7ee5b8fd4d749
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b74608d44023d735ba163716a2d7ee5b8fd4d749?/VF=FGn
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b74608d44023d735ba163716a2d7ee5b8fd4d749?/9d7
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/70a3a9eaec45226061429d15027a34097822d062
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/70a3a9eaec45226061429d15027a34097822d062?/Uv=mW0
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/70a3a9eaec45226061429d15027a34097822d062?/wQu
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5846507c792e76ec95630a2c4adf5f83984027ad
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5846507c792e76ec95630a2c4adf5f83984027ad?/vV=fWk
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5846507c792e76ec95630a2c4adf5f83984027ad?/jDh
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ceee719e6f1916ad0d90ecf15439a36bbf9c7a81
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ceee719e6f1916ad0d90ecf15439a36bbf9c7a81?/QH=UvI
<br>
gitlab.com/EHWGW/fxleljy/-/commit/ceee719e6f1916ad0d90ecf15439a36bbf9c7a81?/ySw
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/eeca3c3adba5b51fe9dc6e7c7094c795c104c357
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/eeca3c3adba5b51fe9dc6e7c7094c795c104c357?/IF=90h
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/eeca3c3adba5b51fe9dc6e7c7094c795c104c357?/DhB
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6dcbd55e3694ffaca225d43e6edd1e9b94ad9d69
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6dcbd55e3694ffaca225d43e6edd1e9b94ad9d69?/sc=667
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6dcbd55e3694ffaca225d43e6edd1e9b94ad9d69?/0Uy
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/733a417a639c566c9a9c4382b4124157ed4f6fa4
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/733a417a639c566c9a9c4382b4124157ed4f6fa4?/OM=JDX
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/733a417a639c566c9a9c4382b4124157ed4f6fa4?/nHl
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/86fff90e3a0fa4828bfbf80eccc6da62ad3a520b
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/86fff90e3a0fa4828bfbf80eccc6da62ad3a520b?/mM=WNb
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/86fff90e3a0fa4828bfbf80eccc6da62ad3a520b?/a4Y
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6fb0cd4377db92b6c2126d97b9496de9e882de7d
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6fb0cd4377db92b6c2126d97b9496de9e882de7d?/4B=wSW
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6fb0cd4377db92b6c2126d97b9496de9e882de7d?/pJn
<br>
gitlab.com/EHWGW/fxleljy/-/commit/44226a83bda9e1ec33f533408271144c37c53ba2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/44226a83bda9e1ec33f533408271144c37c53ba2?/QA=ABi
<br>
gitlab.com/EHWGW/fxleljy/-/commit/44226a83bda9e1ec33f533408271144c37c53ba2?/4Y1
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7f6b21f3507e7a90c29842c3804f1fbbc33019bc
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7f6b21f3507e7a90c29842c3804f1fbbc33019bc?/wQ=NoB
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7f6b21f3507e7a90c29842c3804f1fbbc33019bc?/rLo
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fe511aee1b43bc5c9ecbc79b93f6e19e3211b272
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fe511aee1b43bc5c9ecbc79b93f6e19e3211b272?/S9=XKv
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fe511aee1b43bc5c9ecbc79b93f6e19e3211b272?/e8c
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0a8530b175138e89f22f75b05fabb71e3b6f3274
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0a8530b175138e89f22f75b05fabb71e3b6f3274?/WU=vo8
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0a8530b175138e89f22f75b05fabb71e3b6f3274?/RvP
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/ff14cc0d48754e039b38a9305e98d183a491bcc7
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/ff14cc0d48754e039b38a9305e98d183a491bcc7?/Ay=90k
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/ff14cc0d48754e039b38a9305e98d183a491bcc7?/g9d
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/3db24107da4110e1c90bec804eb7801f9dd51b30
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/3db24107da4110e1c90bec804eb7801f9dd51b30?/fm=0xO
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/3db24107da4110e1c90bec804eb7801f9dd51b30?/wQu
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f70394e478609f97d2bca4bc2e7c59386db599e3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f70394e478609f97d2bca4bc2e7c59386db599e3?/18=sMq
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/f70394e478609f97d2bca4bc2e7c59386db599e3?/GkD
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fdabfc86f5113054ca7618a83bf4a98eb2a7d102
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fdabfc86f5113054ca7618a83bf4a98eb2a7d102?/A8=ZSm
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fdabfc86f5113054ca7618a83bf4a98eb2a7d102?/5Z3
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/dffa4f09e1f93876401648eda6ccfa71d826480b
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/dffa4f09e1f93876401648eda6ccfa71d826480b?/Zg=Qx1
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/dffa4f09e1f93876401648eda6ccfa71d826480b?/oHl
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/12bd16000aa78a6bc770513eddea78fd0c0df1c5
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/12bd16000aa78a6bc770513eddea78fd0c0df1c5?/ov=fCG
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/12bd16000aa78a6bc770513eddea78fd0c0df1c5?/Y2W
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e8c7822043d5e3934a0c8b200f77c1a0d64ee33f
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e8c7822043d5e3934a0c8b200f77c1a0d64ee33f?/j3=hyZ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e8c7822043d5e3934a0c8b200f77c1a0d64ee33f?/HlF
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1bfc8336e559751f3683bb5cdb8d604a5863e593
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1bfc8336e559751f3683bb5cdb8d604a5863e593?/cT=DhB
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1bfc8336e559751f3683bb5cdb8d604a5863e593?/6a4
<br>
gitlab.com/EHWGW/fxleljy/-/commit/cffdd216c111da03356af92f724ab1fc541f810a
<br>
gitlab.com/EHWGW/fxleljy/-/commit/cffdd216c111da03356af92f724ab1fc541f810a?/wG=RI2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/cffdd216c111da03356af92f724ab1fc541f810a?/ySv
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/37e9cc71a584b503519688e86e090dfda0b814fa
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/37e9cc71a584b503519688e86e090dfda0b814fa?/Ec=PWk
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/37e9cc71a584b503519688e86e090dfda0b814fa?/jCg
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0c36146536afff72baaba176bcabe3b522a9afa7
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0c36146536afff72baaba176bcabe3b522a9afa7?/dA=kRL
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0c36146536afff72baaba176bcabe3b522a9afa7?/TxR
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fe75250782971d680821f813c0dd13e9f3759c35
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fe75250782971d680821f813c0dd13e9f3759c35?/2g=U8P
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fe75250782971d680821f813c0dd13e9f3759c35?/kEi
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/92308b86f7e4f24277f7bd91b1d38bda888bdfe2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/92308b86f7e4f24277f7bd91b1d38bda888bdfe2?/4V=scc
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/92308b86f7e4f24277f7bd91b1d38bda888bdfe2?/1Vz
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/084f17d91548d8757883ae96467854d0fc8c46e3
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/084f17d91548d8757883ae96467854d0fc8c46e3?/Bf=9d7
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/084f17d91548d8757883ae96467854d0fc8c46e3?/X1V
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2ad361ca7f53ed2a605b9d9511da64309c46ab37
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2ad361ca7f53ed2a605b9d9511da64309c46ab37?/lp=wDk
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2ad361ca7f53ed2a605b9d9511da64309c46ab37?/Z3X
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/85a019c02b3817da46776231690fe40a3a4c4c03
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/85a019c02b3817da46776231690fe40a3a4c4c03?/OL=FZj
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/85a019c02b3817da46776231690fe40a3a4c4c03?/oIm
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/13d67d033e660686f4c52e5eb53511a582056b4f
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/13d67d033e660686f4c52e5eb53511a582056b4f?/kk=lpw
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/13d67d033e660686f4c52e5eb53511a582056b4f?/b5Z
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e1c7a2835ebdd2bdd1e2591522fe256c521c3807
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e1c7a2835ebdd2bdd1e2591522fe256c521c3807?/sj=SwQ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e1c7a2835ebdd2bdd1e2591522fe256c521c3807?/MqK
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e1d811c9e74773c7bdaaca5a0193a1f078eff526
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e1d811c9e74773c7bdaaca5a0193a1f078eff526?/x4=oLP
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e1d811c9e74773c7bdaaca5a0193a1f078eff526?/hBf
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c452a8dcae6a552eaa4026bef07604e0ce8b292c
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c452a8dcae6a552eaa4026bef07604e0ce8b292c?/FP=GUR
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/c452a8dcae6a552eaa4026bef07604e0ce8b292c?/wQu
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ee99673bbb2a0b430af6c700aca2c4550097b592
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ee99673bbb2a0b430af6c700aca2c4550097b592?/CW=h4o
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ee99673bbb2a0b430af6c700aca2c4550097b592?/DhB
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/2e3661f92fb5ca540f3dade25256d47aa55f8922
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/2e3661f92fb5ca540f3dade25256d47aa55f8922?/AE=r8C
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/2e3661f92fb5ca540f3dade25256d47aa55f8922?/UyS
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cb6d3f795f676182d63fd4aeaafc4a2d627c0701
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cb6d3f795f676182d63fd4aeaafc4a2d627c0701?/ro=i2C
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/cb6d3f795f676182d63fd4aeaafc4a2d627c0701?/HlF
<br>
gitlab.com/EHWGW/fxleljy/-/commit/f12137ff0fa14f6ef7c89e61559d95d9a8a72ede
<br>
gitlab.com/EHWGW/fxleljy/-/commit/f12137ff0fa14f6ef7c89e61559d95d9a8a72ede?/YS=mQD
<br>
gitlab.com/EHWGW/fxleljy/-/commit/f12137ff0fa14f6ef7c89e61559d95d9a8a72ede?/2W0
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2f78ff972a58167f62db66c8596c0066c5a8bf08
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2f78ff972a58167f62db66c8596c0066c5a8bf08?/eO=Ovz
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2f78ff972a58167f62db66c8596c0066c5a8bf08?/HlF
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ec15be252aad177c9fdd469e65fe1130dda2d450
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ec15be252aad177c9fdd469e65fe1130dda2d450?/ym=Pgk
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ec15be252aad177c9fdd469e65fe1130dda2d450?/2W0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a6d201ad99ee1cc935d5068c4663b2fd12948532
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a6d201ad99ee1cc935d5068c4663b2fd12948532?/qG=7rL
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a6d201ad99ee1cc935d5068c4663b2fd12948532?/HlF
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/2d5b8a7bbfbe2be78208e4b04a5dd4507c4f798e
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/2d5b8a7bbfbe2be78208e4b04a5dd4507c4f798e?/da=Upz
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/2d5b8a7bbfbe2be78208e4b04a5dd4507c4f798e?/4Y2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/cfec329bcfbb999bdb45ac7c334da5f15011a1fa
<br>
gitlab.com/EHWGW/fxleljy/-/commit/cfec329bcfbb999bdb45ac7c334da5f15011a1fa?/Oo=ftN
<br>
gitlab.com/EHWGW/fxleljy/-/commit/cfec329bcfbb999bdb45ac7c334da5f15011a1fa?/LpJ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b2c5f1d771c934c1e5f891abc1364560d243f626
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b2c5f1d771c934c1e5f891abc1364560d243f626?/3u=85W
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b2c5f1d771c934c1e5f891abc1364560d243f626?/4Y2
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/40f50b7af108c2633ef1ecace9698f565a6a9e9a
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/40f50b7af108c2633ef1ecace9698f565a6a9e9a?/jw=NHb
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/40f50b7af108c2633ef1ecace9698f565a6a9e9a?/tNr
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8d254da42a645a0d9ac430a84ed6b8f5ea4c71ee
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8d254da42a645a0d9ac430a84ed6b8f5ea4c71ee?/4s=zGn
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8d254da42a645a0d9ac430a84ed6b8f5ea4c71ee?/c6a
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0cdb0f7bfba86226d49d2f732bf82f199dd815ec
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0cdb0f7bfba86226d49d2f732bf82f199dd815ec?/Ak=ulV
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0cdb0f7bfba86226d49d2f732bf82f199dd815ec?/RvP
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2788ffe65633163be0f14e95d82c020749ca84b3
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2788ffe65633163be0f14e95d82c020749ca84b3?/sM=qKo
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2788ffe65633163be0f14e95d82c020749ca84b3?/EiC
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3572ae47fa76f37f9377842b2f0b18af48a4d095
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3572ae47fa76f37f9377842b2f0b18af48a4d095?/UL=ZWx
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3572ae47fa76f37f9377842b2f0b18af48a4d095?/VzT
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d7638ffd8fa1776a7a93303457a33da5486c092e
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d7638ffd8fa1776a7a93303457a33da5486c092e?/ah=Ry2
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d7638ffd8fa1776a7a93303457a33da5486c092e?/KIm
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/97a9b82916d2569b68401906e16c5a6be9acf94f
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/97a9b82916d2569b68401906e16c5a6be9acf94f?/FJ=xHv
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/97a9b82916d2569b68401906e16c5a6be9acf94f?/3X1
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e22dcbc2c58db617bf1393f32e0f167a350d9fe5
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e22dcbc2c58db617bf1393f32e0f167a350d9fe5?/pg=uOs
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/e22dcbc2c58db617bf1393f32e0f167a350d9fe5?/qoI
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7c1a1e0a426ecf5fe197f33a9bf1442da2817985
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7c1a1e0a426ecf5fe197f33a9bf1442da2817985?/NU=Elp
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7c1a1e0a426ecf5fe197f33a9bf1442da2817985?/7b5
<br>
gitlab.com/EHWGW/fxleljy/-/commit/5253c2e64e9f040bb4d716baa5dda4616a5a8840
<br>
gitlab.com/EHWGW/fxleljy/-/commit/5253c2e64e9f040bb4d716baa5dda4616a5a8840?/Lf=MG3
<br>
gitlab.com/EHWGW/fxleljy/-/commit/5253c2e64e9f040bb4d716baa5dda4616a5a8840?/sqK
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/77a3cb489acb5e9ea7d2c3f5a94363dada987ac5
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/77a3cb489acb5e9ea7d2c3f5a94363dada987ac5?/li=93N
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/77a3cb489acb5e9ea7d2c3f5a94363dada987ac5?/f9d
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6dfa4dc0bfc398e4eb14826e2e01bce6d1d383cb
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6dfa4dc0bfc398e4eb14826e2e01bce6d1d383cb?/dk=ySP
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6dfa4dc0bfc398e4eb14826e2e01bce6d1d383cb?/usM
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8ab238bcc2572b0fe7b91a4647063d54170f7b4c
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8ab238bcc2572b0fe7b91a4647063d54170f7b4c?/AU=BYq
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8ab238bcc2572b0fe7b91a4647063d54170f7b4c?/Bf9
<br>
gitlab.com/EHWGW/fxleljy/-/commit/eaecb2127215906ad3dc4ca2dfe53614879b3ebc
<br>
gitlab.com/EHWGW/fxleljy/-/commit/eaecb2127215906ad3dc4ca2dfe53614879b3ebc?/ip=Z6A
<br>
gitlab.com/EHWGW/fxleljy/-/commit/eaecb2127215906ad3dc4ca2dfe53614879b3ebc?/SwQ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b0066a7a7db34b876c3d853a8e81d3361275242c
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b0066a7a7db34b876c3d853a8e81d3361275242c?/R4=LPW
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b0066a7a7db34b876c3d853a8e81d3361275242c?/Bf9
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/3b32ead6d0253fa72c1593c6104b4e1d0dde7185
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/3b32ead6d0253fa72c1593c6104b4e1d0dde7185?/DK=YVw
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/3b32ead6d0253fa72c1593c6104b4e1d0dde7185?/UyS
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d87449610bbd765cbfd63b24dbd4f0e7401e7b02
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d87449610bbd765cbfd63b24dbd4f0e7401e7b02?/iZ=nkA
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d87449610bbd765cbfd63b24dbd4f0e7401e7b02?/jDh
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/98ef6fad969970b4f90890f5ad0e9d5c63e6ada7
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/98ef6fad969970b4f90890f5ad0e9d5c63e6ada7?/85=2wH
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/98ef6fad969970b4f90890f5ad0e9d5c63e6ada7?/W0U
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0c4b6896fe618a470705bb0ede27b9d074fcf18c
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0c4b6896fe618a470705bb0ede27b9d074fcf18c?/MG=aHB
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0c4b6896fe618a470705bb0ede27b9d074fcf18c?/JnH
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/014cd0bafbe64bd60c1a296d415e1c320ce000c2
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/014cd0bafbe64bd60c1a296d415e1c320ce000c2?/N4=yIw
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/014cd0bafbe64bd60c1a296d415e1c320ce000c2?/4Y2
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6455fd814125734c7ce4a4f023224bd3164ff9e1
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6455fd814125734c7ce4a4f023224bd3164ff9e1?/k2=cJg
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6455fd814125734c7ce4a4f023224bd3164ff9e1?/LpJ
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/3636e1e5b09ab28a21264c864fe0ce495f8658c5
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/3636e1e5b09ab28a21264c864fe0ce495f8658c5?/TA=4sz
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/3636e1e5b09ab28a21264c864fe0ce495f8658c5?/e8c
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/1c0be08fcdf116df9f989c30236e7c5f4a507df3
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/1c0be08fcdf116df9f989c30236e7c5f4a507df3?/PJ=dHb
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/1c0be08fcdf116df9f989c30236e7c5f4a507df3?/tNr
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/9c15a1786c25afdb43d6e1d6bec50d6ce1f060c2
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/9c15a1786c25afdb43d6e1d6bec50d6ce1f060c2?/v3=nKO
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/9c15a1786c25afdb43d6e1d6bec50d6ce1f060c2?/gAe
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e09bbb5ae531a485c59fc1605dd5898d4d4a5036
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e09bbb5ae531a485c59fc1605dd5898d4d4a5036?/sC=tna
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e09bbb5ae531a485c59fc1605dd5898d4d4a5036?/PtN
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/3031a33a88b85c10e6a688001db965043c453e84
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/3031a33a88b85c10e6a688001db965043c453e84?/E8=w3K
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/3031a33a88b85c10e6a688001db965043c453e84?/CgA
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/8e343b1f24e767e79b1ee515c353a4e2fe53f5d4
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/8e343b1f24e767e79b1ee515c353a4e2fe53f5d4?/2T=NAH
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/8e343b1f24e767e79b1ee515c353a4e2fe53f5d4?/TxR
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f51857fdce779674ded929d834649fb6606ca3c3
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f51857fdce779674ded929d834649fb6606ca3c3?/C0=duV
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f51857fdce779674ded929d834649fb6606ca3c3?/kEi
<br>
gitlab.com/EHWGW/fxleljy/-/commit/244760640c6b5da83390f22a30be20ea31edd240
<br>
gitlab.com/EHWGW/fxleljy/-/commit/244760640c6b5da83390f22a30be20ea31edd240?/q0=r42
<br>
gitlab.com/EHWGW/fxleljy/-/commit/244760640c6b5da83390f22a30be20ea31edd240?/X1V
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2500953b6f0fd852bb7aecb23c130353d8079224
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2500953b6f0fd852bb7aecb23c130353d8079224?/D1=bIC
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2500953b6f0fd852bb7aecb23c130353d8079224?/ImG
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/99b170a7b0dda72bcd10edf9449ddb3647b6c3b9
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/99b170a7b0dda72bcd10edf9449ddb3647b6c3b9?/Qb=Vq0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/99b170a7b0dda72bcd10edf9449ddb3647b6c3b9?/Z3X
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b64ce0526f6748c81d8177049d3ed466c6e6d34b
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b64ce0526f6748c81d8177049d3ed466c6e6d34b?/F3=dKE
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b64ce0526f6748c81d8177049d3ed466c6e6d34b?/MqK
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/a95dadff189f40e809db6340418977676fb2930e
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/a95dadff189f40e809db6340418977676fb2930e?/Hs=2td
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/a95dadff189f40e809db6340418977676fb2930e?/Z3X
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4060161348e3644c074741b7171f14a07bdb85ec
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4060161348e3644c074741b7171f14a07bdb85ec?/UR=OId
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4060161348e3644c074741b7171f14a07bdb85ec?/sMq
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1f4cfa628f02f2dc1c95605337ded5d3bdf4e030
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1f4cfa628f02f2dc1c95605337ded5d3bdf4e030?/Te=Ug6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1f4cfa628f02f2dc1c95605337ded5d3bdf4e030?/f9d
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/537e6454d31bbc68c6fa9a6a0fdd9a066ff586e7
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/537e6454d31bbc68c6fa9a6a0fdd9a066ff586e7?/dB=lTt
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/537e6454d31bbc68c6fa9a6a0fdd9a066ff586e7?/SwQ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/19b1aecacba013062865bfc96c59ebec7756844a
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/19b1aecacba013062865bfc96c59ebec7756844a?/7r=MMN
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/19b1aecacba013062865bfc96c59ebec7756844a?/jDh
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/8c84d301b3a3d63766a8c134bf0377bd981572db
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/8c84d301b3a3d63766a8c134bf0377bd981572db?/c6=a31
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/8c84d301b3a3d63766a8c134bf0377bd981572db?/W0U
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3e733d9aa0be5319bd4ed30c6bcdc0910af83c56
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3e733d9aa0be5319bd4ed30c6bcdc0910af83c56?/07=Lom
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3e733d9aa0be5319bd4ed30c6bcdc0910af83c56?/lFj
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/53858483cd540cace7620b2a1be431c25cf65c60
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/53858483cd540cace7620b2a1be431c25cf65c60?/nv=fCG
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/53858483cd540cace7620b2a1be431c25cf65c60?/Y2W
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c1d34a4a45a1cbb34ddd2f9ac0b987369dc13b81
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c1d34a4a45a1cbb34ddd2f9ac0b987369dc13b81?/bl=5G6
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c1d34a4a45a1cbb34ddd2f9ac0b987369dc13b81?/JnH
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9688d12d30f071a28df86e5ddf73bfff6d97d6d6
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9688d12d30f071a28df86e5ddf73bfff6d97d6d6?/eY=MzG
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9688d12d30f071a28df86e5ddf73bfff6d97d6d6?/c6a
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/8275bc1ab190d3e688cfaea06d1a29237dd19925
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/8275bc1ab190d3e688cfaea06d1a29237dd19925?/vp=ck1
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/8275bc1ab190d3e688cfaea06d1a29237dd19925?/tNr
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0e973829b84b0f34386bd6c6629a64c26fa6fc5d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0e973829b84b0f34386bd6c6629a64c26fa6fc5d?/t0=EBc
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0e973829b84b0f34386bd6c6629a64c26fa6fc5d?/Ae8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0e11205a4d1b47ddbde7c9ff1eabccd7359ccee5
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0e11205a4d1b47ddbde7c9ff1eabccd7359ccee5?/wJ=45c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0e11205a4d1b47ddbde7c9ff1eabccd7359ccee5?/RvP
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/9474bdc4ef79a2948b990a108913496a79f97a36
<br>

<h2>项目结构</h2><br>

项目目录采用模块化分层设计，便于维护与扩展。各子目录职责清晰，核心资源列表与前端展示逻辑分离。


mobile-article-aggregator/
├── public/                          # 静态资源目录，无需构建直接复制
│   ├── favicon.ico                  # 站点图标文件
│   └── robots.txt                   # 搜索引擎爬虫规则，屏蔽非生产环境路径
├── src/                             # 源代码主目录
│   ├── assets/                      # 前端资源文件（图片、字体、全局样式）
│   │   ├── images/                  # 项目用到的矢量图与位图素材
│   │   └── styles/                  # 全局基础样式与 CSS 变量定义
│   ├── components/                  # 可复用的 UI 组件
│   │   ├── LinkList.vue             # 链接列表核心渲染组件，支持分页与过滤
│   │   ├── SearchBar.vue            # 关键字搜索输入组件
│   │   └── CategoryFilter.vue       # 分类标签筛选组件
│   ├── data/                        # 数据层，存放静态链接资源列表
│   │   ├── links.json               # 主链接索引文件，包含全部 250 条记录
│   │   └── categories.json          # 分类映射表，定义标签与链接 ID 的对应关系
│   ├── layouts/                     # 页面布局模板
│   │   ├── default.vue              # 默认两栏布局（侧边栏 + 主内容区）
│   │   └── full-width.vue           # 全宽布局，用于搜索与统计页面
│   ├── pages/                       # 路由页面入口
│   │   ├── index.vue                # 首页，展示全部资源列表与分类概览
│   │   ├── about.vue                # 项目介绍与使用说明页面
│   │   └── stats.vue                # 链接统计信息页面（总数、分类分布）
│   ├── utils/                       # 工具函数库
│   │   ├── validator.js             # 链接格式校验与规范化工具
│   │   └── filter.js                # 数组过滤与排序辅助函数
│   └── main.js                      # 应用入口文件，初始化 Vue 实例与插件
├── scripts/                         # 运维与辅助脚本
│   ├── check-links.sh               # 批量检测链接可用性的 Bash 脚本
│   └── generate-sitemap.js          # 生成站点地图 XML 文件的 Node 脚本
├── tests/                           # 单元测试与集成测试
│   ├── unit/                        # 组件与函数的单元测试用例
│   └── e2e/                         # 端到端测试脚本（基于 Playwright）
├── .gitignore                       # Git 版本忽略规则文件
├── package.json                     # Node.js 项目依赖与脚本定义
├── README.md                        # 项目说明文档（本文件）
├── LICENSE                          # MIT 许可证全文
└── vite.config.js                   # Vite 构建工具配置文件


<h2> 贡献指南</h2><br>

我们欢迎社区开发者以多种形式参与本项目的维护与改进。所有贡献需遵守项目行为准则，并按照以下流程操作。

第一步：查阅现有 Issue 与 Pull Request。在提交新贡献之前，请先浏览 GitHub 上的现有议题，确认无人正在处理相同问题或功能请求，避免重复劳动。

第二步：Fork 项目并创建功能分支。将本仓库 Fork 至个人账号下，然后基于 `main` 分支创建一个新的分支，分支命名建议采用 `feature/功能描述` 或 `fix/问题简述` 的格式。

第三步：完成代码或文档修改。请遵循项目既定的代码风格（ESLint 配置）与提交信息规范（使用 Conventional Commits 格式）。若涉及链接列表的增删，请同步更新 `src/data/links.json` 中的对应条目。

第四步：编写或更新测试用例。对于新增的功能或修复的缺陷，请在 `tests/` 目录下补充相应的单元测试或端到端测试，确保代码覆盖率不下降。

第五步：提交 Pull Request。推送本地分支到远程仓库后，向本项目的 `main` 分支发起 Pull Request，并在描述中清晰说明修改内容、动机以及相关 Issue 编号。项目维护者会在三个工作日内进行审阅。

<h2>常见问题</h2><br>

问：如何快速判断某条链接是否仍然有效？

答：项目根目录下的 `scripts/check

> 外链数量: 350 | 生成时间:2026年09月18日03时47分28秒
