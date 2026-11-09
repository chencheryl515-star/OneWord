# 一句 · 用读书代替刷手机

信息流里的每条帖子，都是从一本书的某一章里摘出的最抓人的一段。点进去就从这一章的开头读起。

## 部署到 GitHub Pages

1. 登录 github.com，右上角「+」→「New repository」，名字填 `yiju`，选 **Public**，点「Create repository」。
2. 在新仓库页面点「uploading an existing file」，把这个文件夹里的**所有文件**（不是文件夹本身）拖进去，点「Commit changes」。
3. 进仓库的「Settings」→ 左侧「Pages」→「Branch」选 `main`、目录选 `/ (root)`，点「Save」。
4. 等一两分钟，刷新这个页面，顶部会出现网址：`https://你的用户名.github.io/yiju/`。

## 装到手机上

- iPhone：用 Safari 打开上面的网址 →「分享」→「添加到主屏幕」。
- 安卓：用 Chrome 打开 → 右上角菜单 →「添加到主屏幕 / 安装应用」。

之后从桌面图标打开，再导入书（iPhone 上桌面图标和 Safari 的数据是分开的）。

## 接上 DeepSeek

1. 打开 platform.deepseek.com，注册后在「API keys」里新建一个 key，充几块钱就够用很久。
2. 在 App 的「书架」页底部「AI 挑句设置」里填上 key，点「测试连接」。
3. 已经导入的书点「重新挑句」。

key 只存在你的手机上，不会上传到 GitHub。

## 以后更新

改完代码后，把改动的文件重新上传覆盖，并把 `sw.js` 第一行的 `yiju-v1` 改成 `yiju-v2`（每次 +1），手机上重新打开两次就会更新。
