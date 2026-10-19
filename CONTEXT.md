# MinDoc

在线文档管理系统。一个 Book 由若干 Document 组成，读者在阅读页通过 Catalog 在 Document 之间跳转。

## Language

### 内容结构

**Book（项目）**：
一组 Document 的集合，有独立的成员、权限和分享配置。界面文案常称「项目」。
_Avoid_: 文档集, 知识库, wiki

**Document（文档）**：
Book 内的一篇正文，是 Catalog 中的一项。
_Avoid_: 页面, page, 文章

**Catalog（目录）**：
阅读页左侧抽屉中按 Book 结构组织的 Document 树，用于在 Document 之间导航。
_Avoid_: 大纲, TOC, 菜单, 侧边栏

**Outline（页内大纲）**：
由当前 Document 的标题层级生成的导航列表，只在宽屏显示，与 Catalog 是两回事。
_Avoid_: 目录, 小目录, 右侧目录

### 阅读页移动端

**Drawer（抽屉）**：
窄屏下由页头图标或书名唤出、由同一图标、目录 tab、遮罩或选中 Catalog Item 收起的覆盖层，承载 Catalog 与搜索。
_Avoid_: 侧边栏, 侧栏, sidebar, 菜单

**Catalog Item（目录项）**：
Catalog 中的一个节点，可能是可打开的 Document，也可能是仅用于分组的空节点。
_Avoid_: 条目, 节点, 链接
