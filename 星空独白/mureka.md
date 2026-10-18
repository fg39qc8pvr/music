# 《星空独白》Mureka 生成指南

和 Suno 的区别：Mureka 官方建议用**按顺序描述的自然语言提示词**（曲风 → 氛围 → 速度 → 人声 → 乐器 → 段落对比 → 混音质感），而不是堆一串标签。所以表演指令（念白、鼓停、放慢）都写在风格提示词里，歌词里只保留最基础的结构标签，避免这些标签被当成歌词唱出来。

来源：[Mureka 官方博客：How to write AI music prompts](https://www.mureka.ai/blog_en/how-to-write-ai-music-prompts.html)

## 1. 风格提示词（英文版，推荐）

```
Emotional Mandarin Chinese storytelling rap, dark and cinematic, about Van Gogh's lonely life. 90 BPM, minor key. Deep raspy male vocal with a tight, punchy rap flow. Dark melancholic piano, swelling orchestral strings, hard boom bap drums. Opens with a short spoken-word line over soft piano, verses build tension, chorus explodes with a big melodic hook. In the second verse the drums drop out near the end, leaving only piano. The outro brings the drums back, then ends with a quiet spoken line over piano. Warm, wide cinematic mix, very short intro, no long instrumental sections.
```

## 2. 风格提示词（中文版，备用）

```
情绪化的中文叙事说唱，暗黑、电影感，讲述梵高孤独的一生。90 BPM，小调。低沉沙哑的男声，咬字紧凑有力。暗色忧郁钢琴、逐渐推高的管弦乐、硬朗的 boom bap 鼓。开头是一句钢琴伴奏下的念白，主歌逐步推高张力，副歌爆发，旋律感强、记忆点强。第二段主歌结尾鼓点停掉，只留钢琴。尾段鼓重新进来，最后在钢琴声中以一句轻声念白结束。混音温暖宽阔，前奏很短，不要长间奏。
```

字数超出限制时，用这个短版：

```
Emotional Mandarin storytelling rap, dark cinematic, 90 BPM, deep raspy male vocal, tight flow, sad piano, orchestral strings, boom bap drums, explosive melodic chorus, spoken intro and outro, short intro
```

## 3. 歌名

```
星空独白
```

## 4. 歌词（整段复制）

```
[Intro]
亲爱的提奥 今晚的星星 比白天还亮

[Verse]
画架一扛 往南走
追着太阳 黄满手
盼高更来 当盟友
一间屋里 俩猛兽
剃刀一抖 血往下流
全镇签名 堵门口
九百张画 没人收
只有提奥 不松手

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
我把疯 画成了天
九零年 奥维尔麦田
枪声很轻 像句晚安
提奥 只多撑了半年
两块墓碑 并肩

[Outro]
一百年后 锤子一响
八千万 全场鼓掌
印上帆布包 手机屏
九块九包邮 还要好评
全世界 晚到了一百年
只有你 一直看得见
亲爱的提奥 今晚的星星 还是很亮
```

## 5. 使用技巧

- **用参考音频**：Mureka 支持上传参考曲，找一首你喜欢的中文叙事说唱上传，曲风和人声质感会更接近你想要的
- **念白被唱出来了**：把歌词里开头和结尾的两句念白删掉再生成，念白用自己的声音或 AI 配音后期拼接
- **字唱错**：把多音字或生僻字换成同音字，例如“漩”改成“旋”
- **控制成本**：先生成 2～3 版，挑出最接近的一版，再用局部修改功能重做有问题的段落
