# 《星空独白》Suno 生成指南（短版）

## 1. Style of Music（风格）

```
Chinese rap, tight punchy flow, 90 BPM, dark piano, orchestral strings, hard boom bap drums, raspy male vocal, emotional, cinematic, short intro
```

## 2. Exclude Styles（排除风格）

```
female vocals, autotune, EDM, pop, happy, upbeat, long instrumental
```

## 3. Title（标题）

```
星空独白 Starry Monologue
```

## 4. Lyrics（整段复制粘贴）

方括号 `[...]` 是结构标签，不会被唱出来；歌词里不放圆括号。

```
[Intro]
[Spoken Word]
亲爱的提奥 今晚的星星 比白天还亮

[Verse]
画架一扛 往南走
太阳一烫 黄满手
盼高更来 当盟友
一间屋里 俩猛兽
剃刀一抖 血往下流
割下左耳 塞她手
九百张画 没人收
一直画 画不到白头

[Chorus]
星空在烫 孤独在涨
蓝是忧伤 黄是倔强
活着 没人捧场
死后 万人鼓掌
星星不疯 怎么发光
我是一颗星 烧在他乡

[Verse]
铁窗把天 剪成片
夜里星空 在窗前
柏树是火 星是漩
月亮是橙 挂天边
九零年 奥维尔麦田
枪声很轻 像句晚安
一百年后 锤子一响
八千万 买我一张

[Outro]
星星不疯 怎么发光
我是一颗星 烧在他乡

[Spoken Word]
亲爱的提奥 今晚的星星 还是很亮

[End]
```

## 5. 控制时长

Suno 没有精确设置时长的选项，歌曲长度主要由歌词多少决定。这版歌词约 24 行加两句念白，按 90 BPM 算大约 70～80 秒。

- 生成出来如果超过 90 秒，通常是前奏或间奏被拉长了。可以在 Suno 编辑器里用 **Crop / Trim** 剪掉多余的部分，或者剪映导入后再剪
- 风格框里的 `short intro` 和排除风格里的 `long instrumental` 是用来压缩前奏、间奏的
- 每次生成都会消耗额度，建议先抽 3～4 版，挑出最好的一版再局部修

## 6. 其他技巧

- 某一句咬字不清，用 **Replace Section** 只重做那一段
- 念白念得不自然，就删掉念白再生成，念白用自己的声音后期拼接
- 多音字或生僻字唱错时换成同音字，例如“漩”写成“旋”
