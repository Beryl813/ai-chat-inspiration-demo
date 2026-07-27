# HelloTalk AI助聊优化 Demo

这是一个纯静态 demo，可以直接打开预览，也可以上传到 GitHub Pages。

- 中文聊天场景：`index.html`，GitHub Pages 根链接默认打开这一版
- 英文聊天场景：`index-en.html`
- 中文备用入口：`index-zh.html`

## 本地预览

直接双击对应文件，或在浏览器打开：

```text
index.html
index-en.html
index-zh.html
```

## GitHub Pages 上传

1. 新建一个 public repository。
2. 上传本文件夹内的全部文件：
   - `index.html`
   - `index-en.html`
   - `index-zh.html`
   - `README.md`
   - `.nojekyll`
3. 进入 repository 的 `Settings`。
4. 打开 `Pages`。
5. Source 选择 `Deploy from a branch`。
6. Branch 选择 `main`，目录选择 `/root`。
7. 保存后等待 Actions / Pages 部署完成。

部署完成后的链接通常是：

```text
https://beryl813.github.io/仓库名/
```

## Demo 覆盖的核心交互

- 保留快捷入口文案：点我获取聊天灵感。
- 点击后只填入输入框，不直接发送。
- 生成后出现：查看更多。
- 点击查看更多展开现有底部工具区，并默认选中 AI助聊。
- 保留 AI助聊 / 常用语 / 聊天话题 三个 tab。
- 保留剩余次数与右上角换一换入口。
- 只有换一换消耗次数。
- 点击每条建议右侧紫色箭头只填入或合并到输入框。
- 用户点击发送后，按普通文本消息发送，不展示 AI 标识。
- 英文聊天内容生成英文建议，中文聊天内容生成中文建议。
