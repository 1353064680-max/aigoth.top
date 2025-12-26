# NeonTonight - Minecraft服务器网站
# 作者：Aigoth_
这是一个基于Bootstrap框架开发的多页面响应式网站，专为Minecraft服务器设计。网站包含首页、社区、登录、资源和服务器信息等多个页面，具有现代化的界面设计和良好的用户体验。

## 技术栈

### HTML技术
- **HTML5**: 使用最新的HTML5标准构建页面结构
- **响应式设计**: 采用响应式设计原则，适配手机、平板和桌面设备
- **语义化标签**: 使用标准的HTML5语义化标签构建页面结构
- **Meta标签优化**: 包含viewport等移动设备优化标签
- **多页面结构**: 包含index.html、about.html、community.html、login.html、resources.html、server-info.html等6个页面

### CSS技术
- **Bootstrap 3.3.7**: 使用流行的前端框架，包含完整的组件库
  - 网格系统（Grid System）
  - 响应式工具类
  - 预定义样式类
  - 组件样式（导航栏、按钮、表单等）
- **自定义CSS样式**:
  - 固定背景效果：`background-attachment: fixed`
  - 背景覆盖：`background-size: cover`
  - 半透明背景：`rgba()` 颜色值
  - 圆角设计：`border-radius`
  - 渐变效果：`linear-gradient()`
  - 阴影效果：`box-shadow`
  - 过渡动画：`transition`
  - 变换效果：`transform`
  - 内容区域样式定制
- **CSS3特性**:
  - 灵活的布局（Flexbox）
  - 渐变效果
  - 阴影效果
  - 动画效果
  - 响应式单位

### JavaScript/jQuery技术
- **jQuery 3.3.1**: 实现动态交互功能
- **Bootstrap JavaScript组件**:
  - 导航栏功能
  - 模态框
  - 轮播图
  - 下拉菜单
  - 工具提示
  - 标签页切换
- **响应式交互**: 适配不同设备的交互体验

### 设计规范
- **多页面网站**: 包含首页、关于、社区、登录、资源、服务器信息等多个页面
- **统一导航**: 所有页面通过统一导航栏连接
- **视觉设计**:
  - 固定背景图片，提升视觉体验
  - 内容区域使用半透明白色背景，确保文字可读性
  - 页脚使用半透明黑色背景，保持视觉统一
  - 圆角设计，提升现代感
  - 渐变覆盖层，增强文字对比度
- **布局规范**:
  - 导航栏固定在顶部，内容区域设置适当的顶部内边距
  - 主要内容块设置左右外边距，防止内容紧贴边缘
  - 横幅类组件设置适当的内边距和外边距，应用统一圆角
  - 使用Bootstrap的网格系统实现响应式布局

### 页面功能特性
- **首页 (index.html)**: 包含服务器特色介绍、轮播图展示、功能模块等
- **关于 (about.html)**: 包含团队成员介绍、服务器历史时间线等
- **社区 (community.html)**: 包含社区帖子展示、活动信息等
- **登录 (login.html)**: 提供用户登录功能的表单页面
- **资源 (resources.html)**: 提供Minecraft相关资源链接，包括通用链接和启动器下载
- **服务器信息 (server-info.html)**: 显示服务器IP地址、规则、特色功能等

### 其他技术特点
- **跨设备兼容**: 确保在不同设备和浏览器上的兼容性
- **链接优化**: 实现无错误的超链接，确保页面间可互相跳转
- **性能优化**: 合理使用CSS和JS资源，优化页面加载速度
- **可维护性**: 清晰的目录结构和文件命名规范
- **字体优化**: 使用"Microsoft YaHei"等中文字体，提升中文显示效果

## 文件结构

```
bootstrap-3.3.7-dist/
├── css/
│   ├── bootstrap.css
│   ├── bootstrap.min.css
│   ├── bootstrap-theme.css
│   └── bootstrap-theme.min.css
├── js/
│   ├── bootstrap.js
│   ├── jquery.js
│   └── npm.js
├── view/
│   ├── about.html
│   ├── community.html
│   ├── index.html
│   ├── login.html
│   ├── resources.html
│   └── server-info.html
├── image/
│   ├── background-about.png
│   ├── background-community.png
│   ├── background-index.png
│   ├── background-login.png
│   ├── background-resources.png
│   └── background-info.png
└── README.md
```

## 部署方式

项目可部署在GitHub Pages、阿里云OSS等静态网站托管服务上，支持自定义域名访问。

## 开发规范

- 遵循Bootstrap开发规范
- 使用响应式设计原则
- 注重用户体验和界面美观
- 代码结构清晰，便于维护和扩展