<template>
  <div class="resume-container">
    <header class="resume-header">
      <h1>熊彦哲</h1>
      <p class="contact-info">
        📱 电话：151-8353-5583 &nbsp;|&nbsp; 
        ✉️ 邮箱：nickwoluff@163.com &nbsp;|&nbsp; 
        🐙 GitHub：<a href="https://github.com/NickWoluff" target="_blank">NickWoluff</a>
      </p>
      <div class="intent-box">
        <p><strong>🎓 求职意向：</strong> 前端开发实习生 / 后端开发实习生 / 安全研发实习生</p>
        <p><strong>⏳ 到岗时间：</strong> 2026年5月初，每周可实习 4-5 天，可实习 3 个月以上</p>
      </div>
    </header>

    <section class="resume-section">
      <h2>🎓 教育背景</h2>
      <div class="section-content">
        <div class="flex-between">
          <strong>成都信息工程大学 | 网络空间安全学院 - 网络工程 | 本科</strong>
          <span>2023.09 - 2027.06（预计毕业）</span>
        </div>
        <p><strong>核心课程：</strong>网络编程技术、网络协议分析、计算机网络、密码学、操作系统、Web前端开发技术、移动应用开发。</p>
        <p><strong>荣誉奖项：</strong>CET-6: 503分</p>
      </div>
    </section>

    <section class="resume-section">
      <h2>🛠️ 专业技能</h2>
      <ul class="skills-list">
        <li><strong>编程语言：</strong> 熟悉 Java，掌握面向对象编程思想；了解 C 语言与底层内存分配机制；熟练 Python 语法与程序开发。</li>
        <li><strong>后端/Web技术：</strong> 熟悉 Spring Boot 框架；熟悉 HTML/CSS/JavaScript 等前端基础开发技术。</li>
        <li><strong>网络与底层：</strong> 深入理解 TCP/IP 协议栈，熟悉 HTTP/HTTPS 工作原理；掌握 Socket 网络编程模型；熟练使用 Wireshark 进行流量抓包与协议分析。</li>
        <li><strong>系统与工具：</strong> 熟悉 Linux 常用命令与基本系统管理；掌握 Git 版本控制；熟悉 MySQL 数据库基本操作与 SQL 语句编写。</li>
        <li><strong>安全加成：</strong> 了解常见 Web 安全漏洞（如 SQL 注入、XSS、CSRF）的产生原理及代码层面的防御修复方案；了解基础密码学应用。</li>
        <li><strong>移动端与系统调试：</strong> 深入理解 Android 系统运行机制，具备丰富的底层定制与 Root 环境调试经验。熟练处理设备安全环境校验（如 PlayIntegrity 机制原理与应对），并能在解锁设备上独立排查系统级异常（如 KeyStore 报错调试）；具备处理复杂开发环境依赖与冲突的实战能力。</li>
      </ul>
    </section>

    <section class="resume-section">
      <h2>💻 开源贡献与项目经历</h2>
      
      <div class="project-item">
        <div class="flex-between">
          <strong>项目一：基于大语言模型（LLM）的 AstrBot 机器人插件生态开发</strong>
          <span>2025.12 - 至今</span>
        </div>
        <p class="project-role">核心开发者 / 开源贡献者</p>
        <p><strong>项目描述：</strong> 深度参与开源 LLM 聊天机器人框架 AstrBot 的生态建设，独立开发并上架核心增强插件，同时作为核心 Contributor 参与多个热门社区插件的迭代维护。</p>
        <p><strong>技术栈：</strong> Python / 异步编程 (Asyncio) / LLM API 接入 / Git 协作</p>
        <p><strong>核心工作：</strong></p>
        <ul>
          <li><strong>独立开发 smart_quote（智能引用消息） 插件：</strong> 设计并实现了智能引用上消息逻辑，实现了群聊与私聊分别独立控制消息应用功能。</li>
          <li><strong>开源协同与架构扩展：</strong> 参与 uni_nickname（统一昵称） 与 proactive_chat (主动消息) 插件的核心代码重构，熟练运用 Git 流程处理 Issue 与 Pull Request。</li>
        </ul>
      </div>

      <div class="project-item">
        <div class="flex-between">
          <strong>项目二：《逃离鸭科夫》游戏存档解析编辑器</strong>
          <span><a href="https://github.com/NickWoluff/DuckovSaveEditor" target="_blank">查看 GitHub</a></span>
        </div>
        <p class="project-role">个人独立项目</p>
        <p><strong>项目描述：</strong> 在官方支持且法律允许的前提下，针对特定结构化本地数据进行逆向解析与动态修改的独立工具，体现了扎实的数据结构处理能力。</p>
        <p><strong>技术栈：</strong> Python / JSON / 正则表达式 / 逆向</p>
        <p><strong>核心工作：</strong></p>
        <ul>
          <li>分析并逆向解析本地序列化游戏存档文件（如 JSON 格式），构建对应的数据模型。</li>
          <li>开发了数据反序列化、内存修改与重序列化写回的核心模块，确保修改后的数据结构完整且能被原程序合法识别，有效避免文件损坏。</li>
          <li><strong>用户友好界面：</strong> 基于 Tkinter 开发了简洁直观的图形化用户界面，使非专业开发者也能方便地进行数据解析与修改。</li>
        </ul>
      </div>

            <div class="project-item">
        <div class="flex-between">
          <strong>项目三：高校学科竞赛管理系统</strong>
          <span>2025.9 - 2026.1</span>
        </div>
        <p class="project-role">大二核心项目 项目组长 / 全栈开发</p>
        <p><strong>项目描述：</strong> 针对高校学科竞赛管理中信息分散、流程繁琐等痛点，主导设计并实现了一套基于 B/S 架构的综合管理平台，实现了从赛事发布、报名组队到证书审核的竞赛全生命周期数字化与自动化闭环。</p>
        <p><strong>技术栈：</strong> Java / Spring Boot / Vue / MySQL / 前后端分离架构</p>
        <p><strong>核心工作：</strong></p>
        <ul>
          <li><strong>系统架构设计与核心业务链开发：</strong> 统筹开发团队把控项目进度，采用 Spring Boot 作为后端引擎结合 Vue 前端框架，构建了高交互性的单页应用（SPA）。主导实现了学生端在规定时间内的自主报名、动态灵活组队，以及教师端赛项参数配置、队伍人员审核与证书统计报表导出等核心业务逻辑。</li>
          <li><strong>数据库规范化建模与结构设计：</strong> 负责系统底层数据存储方案的统筹设计，基于业务生命周期绘制 E-R 实体联系图。在 MySQL 中设计并落地了包含用户身份、竞赛元数据、动态团队关系、审核记录等在内的多张强关联数据表，通过合理的主外键约束有效保障了复杂业务流下数据的一致性与完整性。</li>
          <li><strong>权限管控与安全机制落地：</strong> 设计并实现了基于角色（学生/教师双重身份）的精细化访问控制与权限隔离体系，确保不同工作流边界清晰、越权访问受限。并在底层将用户登录凭证等核心敏感信息采用 BCrypt 算法进行单向加密存储，从架构逻辑与数据固化双重维度提升了系统的安全性与可靠性。</li>
        </ul>
      </div>

      <div class="project-item">
        <div class="flex-between">
          <strong>项目四：即时通讯应用与文件传输系统</strong>
          <span>2025.3 - 2025.6</span>
        </div>
        <p class="project-role">大二核心项目 独立开发</p>
        <p><strong>项目描述：</strong> 抛弃传统 HTTP 协议，基于自底向上的设计思路，从零使用 Java Sockets 底层 API 实现的 C/S 架构即时通讯与文件分发服务器。</p>
        <p><strong>技术栈：</strong> Java / Socket 网络编程 / 多线程并发 / 自定义协议</p>
        <p><strong>核心工作：</strong></p>
        <ul>
          <li><strong>网络协议设计：</strong> 为解决 TCP 粘包/半包问题，自定义了应用层通信报文协议（Header+Body），实现消息广播、群聊与私聊的精准路由。</li>
          <li><strong>多线程与并发控制：</strong> 服务端采用线程池技术接管客户端连接，保障多用户在线时的稳定消息接收、处理与分发。</li>
          <li><strong>可靠文件传输：</strong> 基于文件流分块读取与校验机制，实现了大文件的可靠传输与断点续传功能，并在服务端实现了基于角色的权限管控体系。</li>
        </ul>
      </div>

      <div class="project-item">
        <div class="flex-between">
          <strong>项目五：个人多功能 Web 站点与沉浸式前端阅读器</strong>
          <span>2023.09 - 至今</span>
        </div>
        <p class="project-role">个人独立项目</p>
        <p><strong>项目描述：</strong> 独立设计与开发集个人门户、实用工具箱与原创文学于一体的综合性 Web 站点，并独立实现站点的无服务器架构与全球化部署。</p>
        <p><strong>核心工作：</strong></p>
        <ul>
          <li><strong>全球化托管与网络优化：</strong> 脱离传统服务器限制，将项目无缝托管至 GitHub Pages；接入 Cloudflare 实现全球 CDN 加速与智能 DNS 解析，配置 HTTPS 保障全站访问速度与传输安全。</li>
          <li><strong>无服务器权限管控：</strong> 针对纯静态托管无后端的限制，巧妙利用 Web Storage (LocalStorage) 实现前端 Session 会话管理。为保护小说“前瞻”板块的白名单访问逻辑，运用基础密码学思想，从零编写了一套轻量级前端数据混淆算法（UTF-8 字节流转换 + 自定义替换密码机制），对硬编码的鉴权凭据进行加盐保护，展现了灵活的安全攻防实战思维。</li>
          <li><strong>沉浸式阅读器前端研发：</strong> 脱离传统静态页面，开发了一套高交互性的前端文本阅读器。创新设计了“基于阅读进度的动态色彩引擎”，通过监听滚动位置计算进度，使页面主题色随特定故事情节的推进平滑渐变，极大提升了用户的沉浸式阅读体验。</li>
        </ul>
      </div>
    </section>

    <section class="resume-section">
      <h2>📝 自我评价</h2>
      <ul class="skills-list">
        <li>具备网安与软件开发的交叉学科背景，既能胜任业务代码编写，又能从安全和底层网络角度优化程序。</li>
        <li>极客发烧友，热衷于 Android 底层修改与系统深度定制，活跃于前沿数码技术社区。</li>
        <li>动手能力极强，具备在非标准环境（如深度定制系统）下独立排查、定位并解决深层依赖 Bug 的技术韧性。</li>
      </ul>
    </section>
  </div>
</template>

<script setup lang="ts">
</script>
