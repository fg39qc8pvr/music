# 《星空独白》Suno 生成指南

## 1. Style of Music（风格）

推荐版（短，适合所有版本）：

```
Chinese rap, tight punchy flow, 90 BPM, dark piano, orchestral strings, hard boom bap drums, raspy male vocal, emotional, cinematic
```

加长版（新版 Suno 风格框字数够时用）：

```
Mandarin Chinese hip hop, storytelling rap, tight punchy flow, 90 BPM, minor key, dark melancholic piano, swelling orchestral strings, hard boom bap drums, deep raspy male vocal, emotional chorus with melodic hook, spoken word intro and outro, cinematic, dramatic dynamics
```

## 2. Exclude Styles（排除风格，如有此选项）

```
female vocals, autotune, EDM, pop, happy, upbeat
```

## 3. Title（标题）

```
星空独白 Starry Monologue
```

## 4. Lyrics（直接整段复制粘贴）

说明：
- 方括号 `[...]` 是给 Suno 的结构标签，不会被唱出来
- 圆括号 `(...)` 会被当作喊词或和声
- 年份写成汉字，避免 Suno 用英文读数字

```
[Intro]
[Spoken Word]
[Soft piano]
亲爱的提奥
今晚的星星 比白天还亮

[Verse 1]
(一八八八！)
画架一扛 往南走
太阳一烫 黄满手
兜里没钱 只剩酒
苦艾一口 就上头
盼高更来 当盟友
一间屋里 俩猛兽
他骂我疯 我骂他丑
平安夜 他摔门撒手
剃刀一抖 血往下流
割下左耳 塞她手
全镇签名 堵在门口
说这疯子 赶出镇口
九百张画 没人收
骨气嚼碎 咽进喉
画商摆手 我不回头
一直画 画不到白头

[Chorus]
星空在烫 孤独在涨
蓝是忧伤 黄是倔强
活着 没人捧场
死后 万人鼓掌
你说我疯 你说我狂
星星不疯 怎么发光
烧到最亮 才被仰望
我是一颗星 烧在他乡

[Verse 2]
(一八八九！)
自己走进 疗养院
铁窗把天 剪成片
白天只能 看墙面
夜里星空 在窗前

[Double Time]
柏树是火 星是漩
月亮是橙 挂天边
医生说 你要安眠
我说 灵感正在点燃

[Build]
九零年 奥维尔麦田
乌鸦压着 半边天

[Beat drops out]
[Spoken Word]
枪声很轻 像句晚安
提奥 只多撑了半年
墓碑并肩
藤蔓缠了 一百年

[Chorus]
星空在烫 孤独在涨
蓝是忧伤 黄是倔强
活着 没人捧场
死后 万人鼓掌
你说我疯 你说我狂
星星不疯 怎么发光
烧到最亮 才被仰望
我是一颗星 烧在他乡

[Bridge]
[Slow, soft piano]
六百封信 你细品
我装坚强 装自信
你给颜料 给体温
全世界不信
只有你信
我就你 一个知音

[Outro]
[Drums kick back in]
一百年后 排队看星
闪光灯 刺我眼睛
拍卖锤响 全场安静
八千万 买我一命
印上帆布包 手机屏
九块九包邮 还要好评
可你隔着玻璃 看清
那不是风景
是一个人 拼了命
想被看见的 心

[Spoken Word]
[Piano only]
亲爱的提奥 今晚的星星 还是很亮

[End]
```

## 5. 生成技巧

- **多抽几次**：同一份提示词生成 5～10 版，重点挑副歌最抓耳的一版
- **念白单独录**：如果 Suno 念得不自然，就把 Intro 和结尾念白删掉再生成，念白用自己的声音或 AI 配音（低沉、沙哑）后期拼接
- **太长唱不完**：先只放 Intro → Verse 1 → Chorus 生成，满意后用 Extend 功能接着生成后半段
- **局部重唱**：哪一句咬字不清，用 Suno 的 Replace Section 只重做那一段
- **字咬错**：多音字或生僻字唱错时，可以换成同音字，例如把“漩”写成“旋”
