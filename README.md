<div align="center">

### McCain

**把「很酷」翻译成模型能执行的话。**

</div>

---

## 我在做什么

做的东西基本是同一件事的不同切面：**把模糊的诉求，变成可以判断对错的具体指标。**

- 「这张图能不能发小红书」不是审美问题，是宽度差 56px 的问题。
- 「这个效果是怎么做出来的」不是灵感问题，是光线、镜头、色温的问题。
- 「今天额度用得顺不顺」不该翻四页数据，该是一条灯带的长度。

所以这些项目大多长这样：零依赖、只解决一件事、结论确定、不联网也能跑。

---

## 主推

### [publish-size-check](https://github.com/Stephen-pc/publish-size-check)

**AI 出图默认 1024×1024，小红书方版要 1080×1080——差 56px，而平台只说「图片不符合要求」。**

扔一张图进去，它告诉你差在哪一项、以及是不是真的救不回来。

还能抓出「dpi 字段达标但实际印不出来」那一类：一张 800×600 @300dpi 的图，dpi 元数据完全合格，但按 300dpi 印出来只有 68mm 宽，够不到期刊单栏的 88mm。多数工具只比 dpi 数值，会直接放行。

10 个平台 / 20 个槽位，纯标准库零依赖，原件只读。

```bash
git clone https://github.com/Stephen-pc/publish-size-check.git
cd publish-size-check && python demo.py    # 五种典型场景，跑完自动清理
```

`Python` · MIT

---

## 点开就能用

### [Prompt Forge · 提示词锻造炉](https://github.com/Stephen-pc/prompt-forge) · [**在线试用 →**](https://stephen-pc.github.io/prompt-forge/)

看到别人的 AI 作品想做同款，却拿不到提示词？**按维度拆，别按整体猜。**

把「很酷」「高级感」这类对人是信息、对模型是噪声的词，换成光线、材质、镜头、焦段、色温这些能被画出来的物理事实。覆盖图像 / 视频 / 文案 / 网页代码 / 音乐五个品类。

`JavaScript` · MIT

---

## 其他

- [dsh-usage-display](https://github.com/Stephen-pc/dsh-usage-display) — 把 DeepSeek Harness 的用量折成 JSON，让灯带、墨水屏、手表都能读
- [ncm-radar](https://github.com/Stephen-pc/ncm-radar) — 网易云评论区情绪雷达：抓评论、算情绪、出时间线
- [repovision](https://github.com/Stephen-pc/repovision) — 在终端里看 git 仓库的分析工具
- [ci-pipeline](https://github.com/Stephen-pc/ci-pipeline) — 给 GitHub Actions / GitLab CI 生成流水线配置的 skill
- [video-extractor](https://github.com/Stephen-pc/video-extractor) — 浏览器视频源提取插件，支持 MP4 / M3U8 / TS 的预览与下载

---

## 常用

`Python` `JavaScript` `Shell` `DeepSeek Harness` `CodeBuddy` `GitHub Actions`

---

<div align="center">
<sub>工具应该少解释，多给结论。</sub>
</div>
