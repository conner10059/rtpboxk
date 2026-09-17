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

gitlab.com/JDJTY/txiqmhb/-/blob/main/2026%E5%88%86%E6%9E%90%E7%AC%AC%E4%B8%80%EF%BC%9A%E7%99%BB1%E7%99%BB2%E7%99%BB3%E7%9A%87%E5%86%A0%E5%8C%BA%E5%88%AB-%E7%AC%94%E8%AE%B0%E6%9C%AC%E8%AF%84%E6%B5%8B%E8%AE%BA%E5%9D%9B.md?/Bfd
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2357268d8d06c617a9c3d751ca3a1c73c1e97a7a?/7b5
<br>
gitlab.com/EHWGW/fxleljy/-/blob/main/2026%E7%AC%AC%E4%B8%80%E8%81%8C%E5%9C%BA%E7%83%AD%E8%AE%AE%EF%BC%9A%E7%9A%87%E5%86%A0%E7%99%BB3%E7%99%BB2%E7%99%BB1-%E4%B8%8B%E9%A5%AD%E8%8F%9C%E8%AE%BA%E5%9D%9B.md
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2022638c5bbc5cc8056bddc0ce5616d78b82fb87
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2022638c5bbc5cc8056bddc0ce5616d78b82fb87?/vm=0TR
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2022638c5bbc5cc8056bddc0ce5616d78b82fb87?/wQu
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5f25d957055c880a733c6059cc725d50b5cc0457
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5f25d957055c880a733c6059cc725d50b5cc0457?/Nu=Vi9
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5f25d957055c880a733c6059cc725d50b5cc0457?/hB9
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7c4eb5241a29963c0d6ade64394e5466a90a9b14
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7c4eb5241a29963c0d6ade64394e5466a90a9b14?/2x=Hys
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7c4eb5241a29963c0d6ade64394e5466a90a9b14?/0Uy
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7e18fb47b277743f41aaa05c9e5c4abf8eb72053
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7e18fb47b277743f41aaa05c9e5c4abf8eb72053?/4E=csP
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7e18fb47b277743f41aaa05c9e5c4abf8eb72053?/lFj
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/13311048442e74f2c9c79776224a537116ec6498
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/13311048442e74f2c9c79776224a537116ec6498?/nv=BiJ
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/13311048442e74f2c9c79776224a537116ec6498?/Y2W
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/600bd1246c4c8be3213a684ab84ae757bc13fea9
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/600bd1246c4c8be3213a684ab84ae757bc13fea9?/7H=bmc
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/600bd1246c4c8be3213a684ab84ae757bc13fea9?/LpJ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e8ec3f36465da46f389f63d0344528147c23b551
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e8ec3f36465da46f389f63d0344528147c23b551?/A4=O2p
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/e8ec3f36465da46f389f63d0344528147c23b551?/e8c
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7056f7234fb436f0a5ed2ad7c211208b340f2614
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7056f7234fb436f0a5ed2ad7c211208b340f2614?/is=jwu
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/7056f7234fb436f0a5ed2ad7c211208b340f2614?/PtN
<br>
gitlab.com/EHWGW/fxleljy/-/commit/411697824e71ba3bcc2632ba308bd852fa734f5f
<br>
gitlab.com/EHWGW/fxleljy/-/commit/411697824e71ba3bcc2632ba308bd852fa734f5f?/g3=JrR
<br>
gitlab.com/EHWGW/fxleljy/-/commit/411697824e71ba3bcc2632ba308bd852fa734f5f?/Ae8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/09602804608635eb2752c99e64a2f7c04a0c90bf
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/09602804608635eb2752c99e64a2f7c04a0c90bf?/bY=ztD
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/09602804608635eb2752c99e64a2f7c04a0c90bf?/VzT
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/2a8ad4e4072be4a00ac0fef4e677b9953d1e53ad
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/2a8ad4e4072be4a00ac0fef4e677b9953d1e53ad?/6r=rOz
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/2a8ad4e4072be4a00ac0fef4e677b9953d1e53ad?/EiC
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f19a954b88f477f05396b1050417ad9b6c9cc688
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f19a954b88f477f05396b1050417ad9b6c9cc688?/Lz=nQh
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f19a954b88f477f05396b1050417ad9b6c9cc688?/3X1
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/546dd9c26bc3fac2df5b6d2769f74537932eff50
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/546dd9c26bc3fac2df5b6d2769f74537932eff50?/Id=nes
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/546dd9c26bc3fac2df5b6d2769f74537932eff50?/oIm
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8c84d5ec777a32903f00e83766e7b85c48d18c14
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8c84d5ec777a32903f00e83766e7b85c48d18c14?/YP=da1
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8c84d5ec777a32903f00e83766e7b85c48d18c14?/Z3X
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/03bba9523c93ef4c52d152f12e6aed9da2d99bb3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/03bba9523c93ef4c52d152f12e6aed9da2d99bb3?/nX=Y5C
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/03bba9523c93ef4c52d152f12e6aed9da2d99bb3?/sMq
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/39f1e390facbce792769032565628e7cfda47e86
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/39f1e390facbce792769032565628e7cfda47e86?/R5=P3N
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/39f1e390facbce792769032565628e7cfda47e86?/f9d
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/17d1a9a327d997feb93e988fd33fc5e9d10ab697
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/17d1a9a327d997feb93e988fd33fc5e9d10ab697?/JT=KXV
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/17d1a9a327d997feb93e988fd33fc5e9d10ab697?/0Uy
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9b408cc46f5a76b5825e0b5cc135a438aa2be3f4
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9b408cc46f5a76b5825e0b5cc135a438aa2be3f4?/xY=iZm
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9b408cc46f5a76b5825e0b5cc135a438aa2be3f4?/lFj
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f9f2732d97dcaf76f02fa3c69221803d302ff82c
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f9f2732d97dcaf76f02fa3c69221803d302ff82c?/oS=GtA
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/f9f2732d97dcaf76f02fa3c69221803d302ff82c?/W0U
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/25b9017a296e39c4fdf62435418d73df6142cd9b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/25b9017a296e39c4fdf62435418d73df6142cd9b?/V6=G7r
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/25b9017a296e39c4fdf62435418d73df6142cd9b?/nHl
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/16bc19e95bb9b9a204642396831510ecdec7ea87
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/16bc19e95bb9b9a204642396831510ecdec7ea87?/Yt=3u7
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/16bc19e95bb9b9a204642396831510ecdec7ea87?/6a4
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1b8c41f84ace7828edf1dace7e2e5a7973702f3d
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1b8c41f84ace7828edf1dace7e2e5a7973702f3d?/SP=Jdn
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1b8c41f84ace7828edf1dace7e2e5a7973702f3d?/tNr
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4d36a51e7e254f1380a75af4eff6de3bfa588ab4
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4d36a51e7e254f1380a75af4eff6de3bfa588ab4?/Zr=R8V
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4d36a51e7e254f1380a75af4eff6de3bfa588ab4?/Ae8
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8e6a32e24f5ee2ee3af044a278d31632c63bc95e
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8e6a32e24f5ee2ee3af044a278d31632c63bc95e?/nX=1Vy
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8e6a32e24f5ee2ee3af044a278d31632c63bc95e?/xRv
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/d37fd395b853a49627ad9758284a52741c3998e9
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/d37fd395b853a49627ad9758284a52741c3998e9?/U8=v3n
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/d37fd395b853a49627ad9758284a52741c3998e9?/CgA
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/774a5f4e04b14d09004d8c5d098f3da3fa5addb5
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/774a5f4e04b14d09004d8c5d098f3da3fa5addb5?/89=gn0
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/774a5f4e04b14d09004d8c5d098f3da3fa5addb5?/zTx
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d0544e703b6d34cf388e2b21fd0f0b19d7b77b60
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d0544e703b6d34cf388e2b21fd0f0b19d7b77b60?/Ll=9tu
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d0544e703b6d34cf388e2b21fd0f0b19d7b77b60?/mGk
<br>
gitlab.com/EHWGW/fxleljy/-/commit/b0abece5ce008f11157ccbf7dcf6d71fad20dfd2
<br>
gitlab.com/EHWGW/fxleljy/-/commit/b0abece5ce008f11157ccbf7dcf6d71fad20dfd2?/ZQ=hlP
<br>
gitlab.com/EHWGW/fxleljy/-/commit/b0abece5ce008f11157ccbf7dcf6d71fad20dfd2?/X1V
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1305580f2ee7c4db93993d1c08fce84b2a774eea
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1305580f2ee7c4db93993d1c08fce84b2a774eea?/MG=4BS
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1305580f2ee7c4db93993d1c08fce84b2a774eea?/KoI
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9c5a556a9a6bc0ad450dec6e80babd9953596aa0
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9c5a556a9a6bc0ad450dec6e80babd9953596aa0?/P3=qyC
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9c5a556a9a6bc0ad450dec6e80babd9953596aa0?/b5Z
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b4037434d7c6d2f59dbb21d130470847ff5a7183
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b4037434d7c6d2f59dbb21d130470847ff5a7183?/Tt=kUy
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b4037434d7c6d2f59dbb21d130470847ff5a7183?/uOs
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/8787e53174cbb6516f42c03d6274a25900198982
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/8787e53174cbb6516f42c03d6274a25900198982?/nk=B5P
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/8787e53174cbb6516f42c03d6274a25900198982?/Bf9
<br>
gitlab.com/EHWGW/fxleljy/-/commit/92efa6a0355a9f64bed70f808ceeb253058e649d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/92efa6a0355a9f64bed70f808ceeb253058e649d?/Cq=Aob
<br>
gitlab.com/EHWGW/fxleljy/-/commit/92efa6a0355a9f64bed70f808ceeb253058e649d?/QuO
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/cae46e3d49bec82638a030c3b22c6e7f99455f35
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/cae46e3d49bec82638a030c3b22c6e7f99455f35?/j6=NR5
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/cae46e3d49bec82638a030c3b22c6e7f99455f35?/hBf
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/bae58150d890e6d12645083cdb98899904f01f0f
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/bae58150d890e6d12645083cdb98899904f01f0f?/kN=eip
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/bae58150d890e6d12645083cdb98899904f01f0f?/UyS
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ca6289f615741f6137ae0c19bedce16b0ed3ad8d
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ca6289f615741f6137ae0c19bedce16b0ed3ad8d?/pk=4lf
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ca6289f615741f6137ae0c19bedce16b0ed3ad8d?/nHl
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d22f210b161058fb8486c0b4d1fcccb87f6c2203
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d22f210b161058fb8486c0b4d1fcccb87f6c2203?/im=Pgk
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d22f210b161058fb8486c0b4d1fcccb87f6c2203?/2W0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/dd035f1c067ce2b0f0d78ba22f128f606aec7645
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/dd035f1c067ce2b0f0d78ba22f128f606aec7645?/4C=wTX
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/dd035f1c067ce2b0f0d78ba22f128f606aec7645?/pJn
<br>
gitlab.com/EHWGW/fxleljy/-/commit/aa63835a7592154ffec3b09a133ff79d1053b62a
<br>
gitlab.com/EHWGW/fxleljy/-/commit/aa63835a7592154ffec3b09a133ff79d1053b62a?/74=yIS
<br>
gitlab.com/EHWGW/fxleljy/-/commit/aa63835a7592154ffec3b09a133ff79d1053b62a?/Y2W
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3e0139d03529db7f6bbb3367166d058a7df0f17f
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3e0139d03529db7f6bbb3367166d058a7df0f17f?/Nk=Y8q
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/3e0139d03529db7f6bbb3367166d058a7df0f17f?/LpJ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/dfa96b1bffa9050482e0f178cd398e4c9b2cfb63
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/dfa96b1bffa9050482e0f178cd398e4c9b2cfb63?/B2=Gjh
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/dfa96b1bffa9050482e0f178cd398e4c9b2cfb63?/CgA
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1a3975faccabe94660fda954d38a6c2f5958b263
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1a3975faccabe94660fda954d38a6c2f5958b263?/Sq=6eE
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1a3975faccabe94660fda954d38a6c2f5958b263?/xRv
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9d5405fbd8fc7e95ac1b3129896348aa45f37e89
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9d5405fbd8fc7e95ac1b3129896348aa45f37e89?/bP=zga
<br>
gitlab.com/EHWGW/fxleljy/-/commit/9d5405fbd8fc7e95ac1b3129896348aa45f37e89?/iCg
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1985884587f4c8f875d0ffb67402626f0b6d55cd
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1985884587f4c8f875d0ffb67402626f0b6d55cd?/J3=XYZ
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/1985884587f4c8f875d0ffb67402626f0b6d55cd?/RvP
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4a06f5d9bacb135c5cb7cff099fd40d93ad0441c
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4a06f5d9bacb135c5cb7cff099fd40d93ad0441c?/4p=pMx
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4a06f5d9bacb135c5cb7cff099fd40d93ad0441c?/CgA
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0e838e3c2befb1ac7e734704c98159a63489ffd8
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0e838e3c2befb1ac7e734704c98159a63489ffd8?/96=3xI
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0e838e3c2befb1ac7e734704c98159a63489ffd8?/X1V
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/9cf72622f4ae6d4fe754d1bcb12b498083e47dd2
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/9cf72622f4ae6d4fe754d1bcb12b498083e47dd2?/ur=ICW
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/9cf72622f4ae6d4fe754d1bcb12b498083e47dd2?/oIm
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6abbcb51b99348cfea800e97326fc83782ac50fa
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6abbcb51b99348cfea800e97326fc83782ac50fa?/r2=sa0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6abbcb51b99348cfea800e97326fc83782ac50fa?/Z3X
<br>
gitlab.com/EHWGW/fxleljy/-/commit/eec64857733ecc56051a3e4d1e82dc1b592231a5
<br>
gitlab.com/EHWGW/fxleljy/-/commit/eec64857733ecc56051a3e4d1e82dc1b592231a5?/sm=Zhy
<br>
gitlab.com/EHWGW/fxleljy/-/commit/eec64857733ecc56051a3e4d1e82dc1b592231a5?/aKo
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/ff558b22758b1640d5b9b8c511229c01abc42095
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/ff558b22758b1640d5b9b8c511229c01abc42095?/Aa=yEl
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/ff558b22758b1640d5b9b8c511229c01abc42095?/7b5
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/cf99fc709fcdf305b3115b381009d3fa7994b5bf
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/cf99fc709fcdf305b3115b381009d3fa7994b5bf?/Y2=XY5
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/cf99fc709fcdf305b3115b381009d3fa7994b5bf?/uOs
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2144c9a9c5f0e7932be19c2a71534946cdd041b9
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2144c9a9c5f0e7932be19c2a71534946cdd041b9?/JG=hbv
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/2144c9a9c5f0e7932be19c2a71534946cdd041b9?/DhB
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7ec09204ec3ef996e9aa9c01aa969fde9d60507c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7ec09204ec3ef996e9aa9c01aa969fde9d60507c?/ZX=yL6
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/7ec09204ec3ef996e9aa9c01aa969fde9d60507c?/SwQ
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4c785e12cfc1a06da57beb4958a629967d7170a7
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4c785e12cfc1a06da57beb4958a629967d7170a7?/4l=f0h
<br>
gitlab.com/EHWGW/fxleljy/-/commit/4c785e12cfc1a06da57beb4958a629967d7170a7?/FjD
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f2aa92d48cff06b0d741d553475a4f41fc6660ce
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f2aa92d48cff06b0d741d553475a4f41fc6660ce?/N4=ylt
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f2aa92d48cff06b0d741d553475a4f41fc6660ce?/2W0
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/cbce986bd1cd02a6a6853c4b9e94a9babe480834
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/cbce986bd1cd02a6a6853c4b9e94a9babe480834?/cm=AQx
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/cbce986bd1cd02a6a6853c4b9e94a9babe480834?/JnH
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/22c607b452f05365bceecfe8f214583b68b937f3
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/22c607b452f05365bceecfe8f214583b68b937f3?/kh=82M
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/22c607b452f05365bceecfe8f214583b68b937f3?/e8c
<br>
gitlab.com/EHWGW/fxleljy/-/commit/cbe81a6b7cc70ff003d1f31f457d60d52db5f1d5
<br>
gitlab.com/EHWGW/fxleljy/-/commit/cbe81a6b7cc70ff003d1f31f457d60d52db5f1d5?/BM=CuK
<br>
gitlab.com/EHWGW/fxleljy/-/commit/cbe81a6b7cc70ff003d1f31f457d60d52db5f1d5?/tNr
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/3e13bac748103dd0fc2c29a6b93e033591deeec1
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/3e13bac748103dd0fc2c29a6b93e033591deeec1?/Fg=auY
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/3e13bac748103dd0fc2c29a6b93e033591deeec1?/gAe
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/88a86489b03f0119103e5ab15958ef4168e43fb2
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/88a86489b03f0119103e5ab15958ef4168e43fb2?/HU=Ssj
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/88a86489b03f0119103e5ab15958ef4168e43fb2?/vPt
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f367074c1a5546e570012526c7c0482d740c7d14
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f367074c1a5546e570012526c7c0482d740c7d14?/nD=4HF
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/f367074c1a5546e570012526c7c0482d740c7d14?/kEi
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/dd1712b82d7cd4ba94fa6e48c8085a50193889f4
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/dd1712b82d7cd4ba94fa6e48c8085a50193889f4?/3U=LYz
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/dd1712b82d7cd4ba94fa6e48c8085a50193889f4?/X1V
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fab6753cffebbde94e7f3632965a27e2c494c2ae
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fab6753cffebbde94e7f3632965a27e2c494c2ae?/E1=9Pw
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fab6753cffebbde94e7f3632965a27e2c494c2ae?/ImG
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fe30b28e244c15e0359f402594fb0471e3ccdc6c
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fe30b28e244c15e0359f402594fb0471e3ccdc6c?/TH=uBF
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fe30b28e244c15e0359f402594fb0471e3ccdc6c?/X1V
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e8b307d18829d78081837d2f8288d74d7973283c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e8b307d18829d78081837d2f8288d74d7973283c?/oi=3kd
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e8b307d18829d78081837d2f8288d74d7973283c?/mGk
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ca061ee62a523d7360bff6dbfcff5fe57649c1d7
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ca061ee62a523d7360bff6dbfcff5fe57649c1d7?/s0=kHL
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ca061ee62a523d7360bff6dbfcff5fe57649c1d7?/d7b
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b951e6304bc97c7ced6108a68fc195007ef9c1c2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b951e6304bc97c7ced6108a68fc195007ef9c1c2?/AK=fMG
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b951e6304bc97c7ced6108a68fc195007ef9c1c2?/OsM
<br>
gitlab.com/EHWGW/fxleljy/-/commit/84032ba8d8c8a8dcad2266389ad2ca33c4a01496
<br>
gitlab.com/EHWGW/fxleljy/-/commit/84032ba8d8c8a8dcad2266389ad2ca33c4a01496?/jD=hA8
<br>
gitlab.com/EHWGW/fxleljy/-/commit/84032ba8d8c8a8dcad2266389ad2ca33c4a01496?/d7b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/71f1e8efe877a1f2938262592e19d410b287d999
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/71f1e8efe877a1f2938262592e19d410b287d999?/uL=BPq
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/71f1e8efe877a1f2938262592e19d410b287d999?/OsM
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0b34a541a959e847b5c370587bf832f1adf31d05
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0b34a541a959e847b5c370587bf832f1adf31d05?/93=O5y
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0b34a541a959e847b5c370587bf832f1adf31d05?/7b5
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b7bd6048515cbee43c0652ec6885b0453c8fd585
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b7bd6048515cbee43c0652ec6885b0453c8fd585?/IT=KXV
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/b7bd6048515cbee43c0652ec6885b0453c8fd585?/0Uy
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/83d5a3cdd6e40086bff1f5c1c39e55d8e9690e5c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/83d5a3cdd6e40086bff1f5c1c39e55d8e9690e5c?/hy=6Mt
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/83d5a3cdd6e40086bff1f5c1c39e55d8e9690e5c?/FjD
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8a2d7f0b18b2878f58f032438bb8422030deb00d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8a2d7f0b18b2878f58f032438bb8422030deb00d?/cZ=0uE
<br>
gitlab.com/EHWGW/fxleljy/-/commit/8a2d7f0b18b2878f58f032438bb8422030deb00d?/W0U
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/2ff34464f8b1ff8df55347e5980211ec7758ca9c
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/2ff34464f8b1ff8df55347e5980211ec7758ca9c?/Jh=1C3
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/2ff34464f8b1ff8df55347e5980211ec7758ca9c?/FjD
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0d5a757af712c57dc0fc4a1e92aca52e2403eb50
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0d5a757af712c57dc0fc4a1e92aca52e2403eb50?/0k=EiB
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0d5a757af712c57dc0fc4a1e92aca52e2403eb50?/Ae8
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7969f578737bbdf511d599edc6d3aa89341969cc
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7969f578737bbdf511d599edc6d3aa89341969cc?/8i=wNG
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/7969f578737bbdf511d599edc6d3aa89341969cc?/PNr
<br>
gitlab.com/EHWGW/fxleljy/-/commit/20c22ad1155196431ff39ae25d9262c1a307e30d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/20c22ad1155196431ff39ae25d9262c1a307e30d?/kE=FFm
<br>
gitlab.com/EHWGW/fxleljy/-/commit/20c22ad1155196431ff39ae25d9262c1a307e30d?/8c6
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/305323e71da40c2d477cb5891fb38e9b9ff47c9c
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/305323e71da40c2d477cb5891fb38e9b9ff47c9c?/8j=wtn
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/305323e71da40c2d477cb5891fb38e9b9ff47c9c?/NrL
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fad0d739dadc7619ad68763930f335e2964063f6
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fad0d739dadc7619ad68763930f335e2964063f6?/PW=kDA
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fad0d739dadc7619ad68763930f335e2964063f6?/gAe
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/91a5241d4255c5bce70f9242727b78b0689b444b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/91a5241d4255c5bce70f9242727b78b0689b444b?/fG=wKa
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/91a5241d4255c5bce70f9242727b78b0689b444b?/TRv
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1b7f66cab2dcf520332dc3c770ae0e0d77d50b8f
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1b7f66cab2dcf520332dc3c770ae0e0d77d50b8f?/4H=E9z
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1b7f66cab2dcf520332dc3c770ae0e0d77d50b8f?/iCg
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4b7c26e6f3802f806377ede1ecafb799ac9d8287
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4b7c26e6f3802f806377ede1ecafb799ac9d8287?/88=fFQ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/4b7c26e6f3802f806377ede1ecafb799ac9d8287?/zxR
<br>
gitlab.com/EHWGW/fxleljy/-/commit/63198aff641586221cb2ea5be108a2445ff6eea9
<br>
gitlab.com/EHWGW/fxleljy/-/commit/63198aff641586221cb2ea5be108a2445ff6eea9?/Mq=Knk
<br>
gitlab.com/EHWGW/fxleljy/-/commit/63198aff641586221cb2ea5be108a2445ff6eea9?/GkE
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/edea8d7021545696b0408d0ba9fbe853d29c78eb
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/edea8d7021545696b0408d0ba9fbe853d29c78eb?/Wu=Aip
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/edea8d7021545696b0408d0ba9fbe853d29c78eb?/1zT
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fdeb39192832904d73942da1d3f83c37c602f116
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fdeb39192832904d73942da1d3f83c37c602f116?/Z9=NKE
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fdeb39192832904d73942da1d3f83c37c602f116?/KoI
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b38334165a0b6969dab8f45e05cab15c1bd5d7cf
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b38334165a0b6969dab8f45e05cab15c1bd5d7cf?/sz=kHL
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b38334165a0b6969dab8f45e05cab15c1bd5d7cf?/d7b
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/37714630f11b1224337dcf205d0e15214ce3fbe3
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/37714630f11b1224337dcf205d0e15214ce3fbe3?/OI=5j0
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/37714630f11b1224337dcf205d0e15214ce3fbe3?/MqK
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/36da28771d488f48cd013024191a506d59b35d99
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/36da28771d488f48cd013024191a506d59b35d99?/NQ=YoM
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/36da28771d488f48cd013024191a506d59b35d99?/Bf9
<br>
gitlab.com/EHWGW/fxleljy/-/commit/26d6390b4d9a64b14353a65ca7cf9e25410155d8
<br>
gitlab.com/EHWGW/fxleljy/-/commit/26d6390b4d9a64b14353a65ca7cf9e25410155d8?/L8=jQK
<br>
gitlab.com/EHWGW/fxleljy/-/commit/26d6390b4d9a64b14353a65ca7cf9e25410155d8?/QuO
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8312c1d0a3c7b1cb200b81b0bc9a0530d03071d8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8312c1d0a3c7b1cb200b81b0bc9a0530d03071d8?/fz=dQY
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8312c1d0a3c7b1cb200b81b0bc9a0530d03071d8?/DhB
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/027c012d2a8b83e403215abaaca21ad2675297ca
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/027c012d2a8b83e403215abaaca21ad2675297ca?/FM=7ei
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/027c012d2a8b83e403215abaaca21ad2675297ca?/0Uy
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/466034e6eec437878b08783c17d7839928ca7e77
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/466034e6eec437878b08783c17d7839928ca7e77?/ao=F9T
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/466034e6eec437878b08783c17d7839928ca7e77?/lFj
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/91039dadd78c29cbf235bf82696755ae0e549294
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/91039dadd78c29cbf235bf82696755ae0e549294?/HO=9gk
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/91039dadd78c29cbf235bf82696755ae0e549294?/2W0
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0497fa5c5fc65d343a8740c98e71a450c61a057f
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0497fa5c5fc65d343a8740c98e71a450c61a057f?/j4=leS
<br>
gitlab.com/EHWGW/fxleljy/-/commit/0497fa5c5fc65d343a8740c98e71a450c61a057f?/HlF
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/14bbfdade95c1ceb5fff6048bd70dfc4b87b634f
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/14bbfdade95c1ceb5fff6048bd70dfc4b87b634f?/6X=O8c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/14bbfdade95c1ceb5fff6048bd70dfc4b87b634f?/Y2W
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/42c7ce11b3d0a8f9c37465eaed78622116cb35a3
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/42c7ce11b3d0a8f9c37465eaed78622116cb35a3?/37=HcJ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/42c7ce11b3d0a8f9c37465eaed78622116cb35a3?/rLp
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d63cf5c056f33a52ee30ddddde057e6b03c98a7d
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d63cf5c056f33a52ee30ddddde057e6b03c98a7d?/Bc=VJQ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d63cf5c056f33a52ee30ddddde057e6b03c98a7d?/c6a
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2c1e12ffa79e5f68db629bfec1730f419bbaf645
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2c1e12ffa79e5f68db629bfec1730f419bbaf645?/Lf=qgu
<br>
gitlab.com/EHWGW/fxleljy/-/commit/2c1e12ffa79e5f68db629bfec1730f419bbaf645?/tNr
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b99c935ae3fb3a02b0f102f274f6d793edbf0b26
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/b99c935ae3fb3a02b0f102f274f6d793edbf0b26?/E8=vXn
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

> 外链数量: 350 | 生成时间:2026年09月18日03时47分11秒
