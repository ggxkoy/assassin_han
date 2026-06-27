# 《刺客信条·传国玉玺》第一部 · 预告片 BGM（Suno）

> 为第一部 ≈2 分 25 秒的预告片 CG 配乐。定位：**汉风民乐 × 刺客信条式预告片配乐**（Jesper Kyd / Lorne Balfe 既视感）——古琴、箫/笛、二胡、琵琶、编钟，叠史诗管弦、低频铜管 braam、战鼓与人声吟唱，随分镜起伏。

## 一、情绪与结构（对齐分镜时间轴）

| 时间 | 对应分镜 | 音乐 |
| --- | --- | --- |
| 0:00–0:18 | 段·序 Animus 开场 | 电子微光中浮出一缕**古琴/箫**，神秘空灵；实体化瞬间一记低频 **braam**，古今交汇。 |
| 0:18–0:55 | 段一/二 登基(明) + 盯梢(暗) | 心跳般的低鼓进入，**二胡**哀婉主题缓缓铺开；明线掺**编钟/雅乐**的庄严，暗线用压低的弦乐悬疑。 |
| 0:55–1:25 | 段三 + 飞檐走壁 | 节奏收紧，**战鼓(太鼓感)**、急促**琵琶/竹笛**与拨弦，轻功追逐的律动，层层推进。 |
| 1:25–1:45 | 段四 崩玺·高潮 | 全奏冲到受贺顶点——玉玺落地的「咔」=**爆点后骤然抽空**：一记满堂重击 + 超低频，随即近乎静默，只留一记余音不散的钟/磬。 |
| 1:45–2:10 | 段五 碎玉/科技 | 余烬般的空寂，一支孤独的**箫/二胡**哀鸣，阴冷、不安。 |
| 2:10–2:25 | 大牢·悬赏钩子 | 低沉的暗涌渐强，落一记沉鼓，**悬而不决**地收尾，把张力留给第二部（"刘秀"之名）。 |

> 调式与速度：小调/五声偏暗（如 D 小调），基础 ~78–84 BPM，动作段用双倍速织体提速；全曲**不解决**，结在悬念上。

## 二、Suno 风格提示词（Style）

**纯器乐版（开 Instrumental）：**
```
Dark epic cinematic trailer score, traditional Han-Chinese guqin, dizi & xiao flutes, erhu, pipa and bianzhong bronze bells, thunderous taiko war drums, ominous low brass braams, ghostly wordless choir, sub-bass hits, building tension to an explosive climax then a hollow ominous aftermath, Assassin's Creed announcement trailer style, instrumental, 80 BPM, D minor
```

**带吟唱版（关 Instrumental，用「易水歌」做主题）：**
```
Dark epic cinematic trailer score with a haunting solo male chant in ancient Chinese, traditional guqin / dizi / erhu / pipa / bianzhong bells, taiko war drums, ominous brass and ghostly choir, building to an explosive climax then a hollow lament, Assassin's Creed trailer style, cinematic, 80 BPM, D minor
```

## 三、Suno 段落结构（填到歌词框，控制起伏）

> 纯器乐也能用这些标签控制结构；括号是给模型的情绪提示。

```
[Intro] (eerie digital shimmer, lone guqin emerging, a single low braam)
[Build] (heartbeat taiko, mournful erhu theme, ceremonial bianzhong bells rising)
[Pre-Chorus] (fast pipa and dizi, accelerating taiko chase rhythm, tension climbing)
[Drop] (full orchestral + choir hit at the peak, then sudden near-silence, one ringing bell as the seal shatters)
[Break] (hollow, a lone xiao flute lament over sub-bass drone)
[Outro] (dark ominous swell, a final deep war drum, unresolved, fade)
```

## 四、可选吟唱词 ——《易水歌》（荆轲，贴合史记刺客）

> 用作幽冷的吟唱主题（低沉男声或空灵女声皆可），呼应杜吴的"决死一击"。带吟唱版把它放进 `[Verse]`：

```
[Verse] (whispered, haunting, ancient Chinese chant)
风萧萧兮易水寒
壮士一去兮不复还
（拼音备用：feng xiao xiao xi yi shui han / zhuang shi yi qu xi bu fu huan）
```

## 五、操作贴士

- **风格框别堆太满**：Suno 风格框偏好精炼，上面的 Style 一段直接贴即可；细节交给段落标签。
- **要"崩玺骤静"那一下**：在 `[Drop]` 里强调 "then sudden near-silence / one ringing bell"，多生成几版挑那一下做得最干净的。
- **时长**：Suno 单曲常 2–4 分钟，够覆盖 2'25"；可生成后在剪辑里把高潮点对齐崩玺（约 1:35）。
- **两版都跑**：纯器乐版做满铺底，带吟唱版在序章 / 大牢钩子处叠人声点睛，二选一或混用。
- **想更"刺客信条"**：风格里可加 `Jesper Kyd vibe, ethnic vocal ostinato, hybrid orchestral`；想更"东方武侠"可加 `wuxia film score, guzheng tremolo`。
