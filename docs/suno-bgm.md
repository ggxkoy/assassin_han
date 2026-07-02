# 《刺客信条·传国玉玺》第一部 · 预告片 BGM（Suno）

> 为第一部预告片 CG 配乐（**这一版按更长、更有起伏的弧线设计，总长 ≈3 分 45 秒**）。定位：**汉风民乐 × 刺客信条式预告片配乐**（Jesper Kyd / Lorne Balfe 既视感）——古琴、箫/笛、二胡、琵琶、编钟，叠史诗管弦、低频铜管 braam、战鼓与人声吟唱。
> 这条弧的关键不在"一个高潮"，而在 **三段递进**：掷玺(第一高潮) → **彻底静默** → 王莽超时代之力(全片顶峰) → 刺杀刘秀(收尾小高潮)。

## 一、情绪与结构（按你的音乐弧线 · ≈3′45″）

| 时间 | 对应分镜 | 音乐 |
| --- | --- | --- |
| 0:00–1:20 | 序 Animus + 登基(明) + 盯梢(暗) | **压抑**：阴郁、克制、始终压着不爆。长气息的古琴/箫 + 低频脉动 + 幽远人声，沉郁不祥，铺满约一分钟的暗涌。 |
| 1:20–1:55 | 杜吴现身 · 飞檐走壁 · 战巡逻兵 | **转激烈**：杜吴一出场，战鼓炸开、急促琵琶/竹笛、狂飙拨弦，动作段全速推进。 |
| 1:55–2:20 | 战斗后 · 索玺铺垫 | **缓和——暴风雨前的宁静**：骤然抽到极简，一缕二胡/箫低鸣，危险的安静。 |
| 2:20–2:55 | 暖阁 · 太后之怒 | **逐渐上扬**：弦乐与编钟一层层叠加，不断逼向临界点。 |
| 2:55–3:05 | 王政君掷玺 · 崩玺 | **第一高潮**：全奏轰然炸顶，落在玉碎那一击。 |
| 3:05–3:10 | 画面一转 | **整个声音消失**——数秒死寂（只留极轻耳鸣/环境）。 |
| 3:10–3:35 | 王莽得玺 · 渐露不属于这个时代的力量 | **全片顶峰**：自静默中重新升起，合唱 + 管弦 + 电子轰鸣层层堆叠，推到最强、最不祥的顶点（力量觉醒）。 |
| 3:35–3:50 | 末了 · "刺杀刘秀"浮现 | **收尾小高潮**：顶峰回落后，一记凌厉的暗色重击 / 吟唱点睛，留悬念收束。 |

> 调式与速度：小调/五声偏暗（如 D 小调）。压抑段 ~66–74 BPM 沉缓；动作段提到 ~120–140 BPM（或双倍速织体）；"宁静"段几乎无拍；顶峰段用宽广的慢速大编制 + 电子轰鸣。全曲**不解决**，结在悬念上。
>
> ✅ 分镜已按此弧线重排：`assassins-creed-story.md` 第一部（SC00–SC11，全片 ≈3′50″）的时间码与本表逐段对齐——掷玺 2:55、死寂 3:05、王莽超时代之力顶峰 3:11–3:35、刺杀刘秀钩子 3:35–3:50。

## 二、Suno 风格提示词（Style）

**纯器乐版（开 Instrumental）：**
```
Dark epic cinematic trailer score, traditional Han-Chinese guqin, dizi & xiao flutes, erhu, pipa and bianzhong bronze bells, thunderous taiko war drums, ominous low brass braams, ghostly wordless choir, sub-bass hits; a long brooding suppressed opening, a fierce action surge, a calm-before-the-storm lull, a first explosive climax, then TOTAL SILENCE, then rising to an even bigger supernatural final climax, and a dark unresolved coda, Assassin's Creed announcement trailer style, instrumental, D minor
```

**带吟唱版（关 Instrumental，用「易水歌」做主题）：**
```
Dark epic cinematic trailer score with a haunting solo male chant in ancient Chinese, traditional guqin / dizi / erhu / pipa / bianzhong bells, taiko war drums, ominous brass and ghostly choir, building to an explosive climax then a hollow lament, Assassin's Creed trailer style, cinematic, 80 BPM, D minor
```

## 三、Suno 段落结构（填到歌词框，控制起伏）

> 纯器乐也能用这些标签控制结构；括号是给模型的情绪提示。按你的弧线排：

```
[Intro] (~80s of brooding, suppressed dread: long-breath guqin and xiao over a low pulse and distant ghostly voices, never bursting)
[Build] (Du Wu appears — the action ignites: thunderous taiko, frantic pipa and dizi, driving wuxia chase rhythm)
[Break] (after the fight, the calm before the storm: strip to almost nothing, a single lone erhu over silence, dangerous quiet)
[Pre-Chorus] (slowly climbing again: strings and bianzhong bells layering, tension pushing toward the edge)
[Chorus] (FIRST CLIMAX — full orchestra and choir hit as the seal is hurled and shatters)
[Break - silence] (a hard cut to TOTAL SILENCE, a few seconds of dead air, only faint ringing)
[Climax] (THE PEAK — rising out of the silence to the loudest, most ominous height: massive choir, orchestra and electronic roar, a supernatural power awakening)
[Outro] (a final sharp dark hit / chant on the "kill Liu Xiu" reveal, a smaller spike, unresolved, suspended)
```

> Suno 不一定能做出真正的"死寂"。`[Break - silence]` 先占位，最稳的做法是生成后在剪辑里手动剪出 2–4 秒静音，再接 `[Climax]`。

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
- **两处高潮 + 中间死寂是灵魂**：第一高潮(掷玺·约2:55) → 死寂(约3:05) → 全片顶峰(王莽超时代之力·约3:10)。死寂多半要靠剪辑手剪 2–4 秒，再让顶峰从静默里轰然升起，反差才够。
- **时长**：这版弧 ≈3′45″。Suno v4.5+ 单曲可达 ~8 分钟，足够；若用较短版本，可分两段生成（前半"压抑→掷玺高潮"，后半"静默→顶峰→刘秀小高潮"）再拼。
- **顶峰要比第一高潮更大**：王莽力量觉醒处才是全片最强点——`[Climax]` 里强调 "even bigger / loudest / supernatural power awakening"，避免被掷玺那下盖过。
- **两版都跑**：纯器乐版做满铺底，带吟唱版在序章 / 大牢钩子处叠人声点睛，二选一或混用。
- **想更"刺客信条"**：风格里可加 `Jesper Kyd vibe, ethnic vocal ostinato, hybrid orchestral`；想更"东方武侠"可加 `wuxia film score, guzheng tremolo`。
