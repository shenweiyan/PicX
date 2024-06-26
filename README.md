# PicX

**[PicX](https://github.com/XPoet/picx)** 是一款基于 GitHub API 开发的图床工具，提供图片上传托管、生成图片链接和常用图片工具箱服务。

本仓库为 **[PicX v2](https://github.com/XPoet/picx/tree/v2)** 自部署版本，以满足个人 GitHub 图床自定义的仓库和分支使用需求。

---

## 亮点 | Highlights

- 在线使用、无需下载、无需安装。
- 操作简单、文档完善、持续维护。
- 代码开源、数据安全、完全免费。

## 如何使用 | How to use

通过 [GitHub OAuth 授权](https://picx-docs.xpoet.cn/docs/usage-guide/config.html#github-oauth-%E6%8E%88%E6%9D%83%E7%99%BB%E5%BD%95) 或 [填写 GitHub Token](https://picx-docs.xpoet.cn/docs/usage-guide/config.html#%E5%A1%AB%E5%86%99-github-token-%E7%99%BB%E5%BD%95) 登录到 [PicX](https://picx.xpoet.cn)，完成 [图床配置](https://picx-docs.xpoet.cn/docs/usage-guide/config.html#%E5%9B%BE%E5%BA%8A%E9%85%8D%E7%BD%AE) 后即可使用。

**在线使用入口：https://picx.weiyan.cc**

## 文档 | Documents

**官方文档 https://picx-docs.xpoet.cn**

通过阅读 **[快速开始](https://picx-docs.xpoet.cn/docs/usage-guide/get-start.html)** 教程，可帮助你迅速上手 PicX。 

## 功能 | Features

- [x] 支持 **[拖拽](https://picx-docs.xpoet.cn/docs/usage-guide/upload.html#%E6%8B%96%E6%8B%BD%E5%9B%BE%E7%89%87)**、**[复制粘贴](https://picx-docs.xpoet.cn/docs/usage-guide/upload.html#%E5%A4%8D%E5%88%B6%E7%B2%98%E8%B4%B4)**、**[选择文件](https://picx-docs.xpoet.cn/docs/usage-guide/upload.html#%E9%80%89%E6%8B%A9%E6%96%87%E4%BB%B6)** 等方式进行选择图片
- [x] 支持上传时对图片 **[重命名](https://picx-docs.xpoet.cn/docs/usage-guide/upload.html#%E9%87%8D%E5%91%BD%E5%90%8D)**、**[哈希化](https://picx-docs.xpoet.cn/docs/usage-guide/upload.html#%E5%93%88%E5%B8%8C%E5%8C%96)**（确保图片名唯一）和 **[设置命名前缀](https://picx-docs.xpoet.cn/docs/usage-guide/upload.html#%E5%89%8D%E7%BC%80%E5%91%BD%E5%90%8D)**
- [x] 支持 **批量上传图片**、**[批量删除图片](https://picx-docs.xpoet.cn/usage-guide/management.html#%E5%88%A0%E9%99%A4-%E6%89%B9%E9%87%8F%E5%88%A0%E9%99%A4)** 和 **[批量复制图片链接](https://picx-docs.xpoet.cn/docs/usage-guide/management.html#%E6%89%B9%E9%87%8F%E5%A4%8D%E5%88%B6%E5%A4%9A%E5%BC%A0%E5%9B%BE%E7%89%87%E9%93%BE%E6%8E%A5)**
- [x] 支持图床 **多级目录** 管理 （创建多级目录 / 查看多级目录下图片）
- [x] 支持 **[一键复制](https://picx-docs.xpoet.cn/docs/usage-guide/upload.html#%E5%A4%8D%E5%88%B6%E5%9B%BE%E7%89%87%E9%93%BE%E6%8E%A5)** 图片链接和 **[自由转换 Markdown / HTML / BBCode 格式](https://picx-docs.xpoet.cn/docs/usage-guide/settings.html#%E5%9B%BE%E7%89%87%E9%93%BE%E6%8E%A5%E6%A0%BC%E5%BC%8F%E8%AE%BE%E7%BD%AE)**
- [x] 内置 **[多种图片链接规则](https://picx-docs.xpoet.cn/docs/usage-guide/settings.html#%E5%9B%BE%E7%89%87%E9%93%BE%E6%8E%A5%E8%A7%84%E5%88%99%E9%85%8D%E7%BD%AE)**（GitHub、GitHub Pages、jsDelivr、Statically 等）
- [x] 支持 **[自定义配置图片链接规则](https://picx-docs.xpoet.cn/docs/usage-guide/settings.html#%E9%85%8D%E7%BD%AE%E8%87%AA%E5%AE%9A%E4%B9%89%E5%9B%BE%E7%89%87%E9%93%BE%E6%8E%A5%E8%A7%84%E5%88%99)**
- [x] 支持 **[图片压缩](https://picx-docs.xpoet.cn/docs/usage-guide/settings.html#%E5%9B%BE%E7%89%87%E5%8E%8B%E7%BC%A9%E8%AE%BE%E7%BD%AE)** (内置高效压缩算法，可配置在上传前自动压缩)
- [x] 支持配置 **[图片水印](https://picx-docs.xpoet.cn/docs/usage-guide/settings.html#%E5%9B%BE%E7%89%87%E6%B0%B4%E5%8D%B0%E8%AE%BE%E7%BD%AE)**
- [x] 支持 **PWA**
- [x] 支持 **[暗夜模式](https://picx-docs.xpoet.cn/docs/usage-guide/settings.html#%E4%B8%BB%E9%A2%98%E8%AE%BE%E7%BD%AE)** (自动切换 / 自由切换)
- [x] i18n（中文简体、中文繁体、英文）
- [x] 工具箱（[图片压缩](https://picx-docs.xpoet.cn/docs/usage-guide/toolbox.html#%E5%9B%BE%E7%89%87%E5%8E%8B%E7%BC%A9)、[图片转 Base64](https://picx-docs.xpoet.cn/docs/usage-guide/toolbox.html#%E5%9B%BE%E7%89%87%E8%BD%AC-base64)、[图片水印](https://picx-docs.xpoet.cn/docs/usage-guide/toolbox.html#%E5%9B%BE%E7%89%87%E6%B0%B4%E5%8D%B0)）

## 许可 | License

**[AGPL-3.0](https://github.com/XPoet/picx/blob/master/LICENSE)** 
