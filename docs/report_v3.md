# Argon v3：言外之意维度与加分题


## S1：30 秒讲清楚：为什么天空是蓝的，傍晚又变成橙红？

| 运行 | overall 排名 | subtext 排名 | craft 排名 | overall 胜率 | subtext 胜率 | craft 胜率 |
|---|---|---|---|---|---|---|
| cc-hf-S1 | 1 | 1 | 2 | 94% | 94% | 81% |
| cc5-bare-S1 | 2 | 4 | 1 | 81% | 69% | 88% |
| codex-hf-S1 | 3 | 2 | 3 | 81% | 84% | 75% |
| cc-bare-S1 | 4 | 5 | 5 | 62% | 44% | 56% |
| codex-bare-S1 | 5 | 6 | 4 | 50% | 28% | 69% |
| dsh-hf-S1 | 6 | 3 | 6 | 44% | 75% | 38% |
| dsh-bare-S1 | 7 | 7 | 7 | 25% | 28% | 31% |
| sol-bare-S1 | 8 | 8 | 8 | 12% | 25% | 12% |
| dshp-bare-S1 | 9 | 9 | 9 | 0% | 3% | 0% |

subtext 换左右后一致：29/36

| 加分题 | 回答 yes 的运行（两次都 yes / 只有一次 yes） | 两次回答一致率 | 对照亮点报告：正例识别 | 反例误判 |
|---|---|---|---|---|
| B6 是否有两个以上表示同一机制的量在同一时段内一起变… | cc-bare-S1、cc-hf-S1、cc5-bare-S1、dsh-hf-S1、sol-bare-S1 / codex-hf-S1 | 8/9 | 8/8 | 1/2 |
| B8 示意图到实景的转场，是否由示意图里的某个元素直接… | cc-hf-S1 / 无 | 9/9 | 2/4 | 0/2 |
| B9 结尾是否回到开场画面，并在上面加入回答开场问题的… | cc-bare-S1、cc-hf-S1、cc5-bare-S1、codex-bare-S1、codex-hf-S1、dsh-hf-S1 / 无 | 9/9 | 2/2 | 2/2 |

## B2：给附带的这首歌（song.m4a）做一个贴合歌曲内容的 MV。机器上装了 whisper，可以用来听歌词。

| 运行 | overall 排名 | subtext 排名 | craft 排名 | overall 胜率 | subtext 胜率 | craft 胜率 |
|---|---|---|---|---|---|---|
| codex-bare-B2 | 1 | 2 | 1 | 100% | 84% | 100% |
| cc-bare-B2 | 2 | 5 | 2 | 81% | 50% | 81% |
| dsh-hf-B2 | 3 | 4 | 3 | 75% | 72% | 75% |
| codex-hf-B2 | 4 | 3 | 4 | 69% | 72% | 69% |
| cc-hf-B2 | 5 | 1 | 6 | 50% | 97% | 34% |
| dsh-bare-B2 | 6 | 6 | 5 | 38% | 38% | 47% |
| cc5-bare-B2 | 7 | 7 | 7 | 19% | 19% | 31% |
| sol-bare-B2 | 8 | 8 | 8 | 19% | 19% | 12% |
| dshp-bare-B2 | 9 | 9 | 9 | 0% | 0% | 0% |

subtext 换左右后一致：32/36

| 加分题 | 回答 yes 的运行（两次都 yes / 只有一次 yes） | 两次回答一致率 | 对照亮点报告：正例识别 | 反例误判 |
|---|---|---|---|---|
| B1 是否至少有一个镜头表达了题面或歌词没有直接写出的… | cc-bare-B2、cc-hf-B2、cc5-bare-B2、codex-bare-B2、codex-hf-B2、dsh-bare-B2、dsh-hf-B2、sol-bare-B2 / 无 | 9/9 | 4/4 | 2/2 |
| B5 情绪转折处，人物是否做了一个具体动作（伸手、回头… | cc-bare-B2、cc-hf-B2、cc5-bare-B2、codex-bare-B2、codex-hf-B2 / 无 | 9/9 | 2/2 | 2/2 |

## C1：讲一个 45 秒、三幕的无台词小故事：一只纸飞机想飞出窗外。

| 运行 | overall 排名 | subtext 排名 | craft 排名 | overall 胜率 | subtext 胜率 | craft 胜率 |
|---|---|---|---|---|---|---|
| codex-hf-C1 | 1 | 4 | 2 | 88% | 72% | 88% |
| cc-bare-C1 | 2 | 3 | 3 | 75% | 78% | 69% |
| codex-bare-C1 | 3 | 5 | 1 | 75% | 44% | 88% |
| dsh-bare-C1 | 4 | 2 | 5 | 69% | 84% | 56% |
| cc5-bare-C1 | 5 | 6 | 4 | 56% | 38% | 69% |
| cc-hf-C1 | 6 | 1 | 6 | 50% | 91% | 44% |
| dsh-hf-C1 | 7 | 7 | 7 | 25% | 31% | 25% |
| sol-bare-C1 | 8 | 8 | 8 | 12% | 12% | 12% |
| dshp-bare-C1 | 9 | 9 | 9 | 0% | 0% | 0% |

subtext 换左右后一致：32/36

| 加分题 | 回答 yes 的运行（两次都 yes / 只有一次 yes） | 两次回答一致率 | 对照亮点报告：正例识别 | 反例误判 |
|---|---|---|---|---|
| B1 是否至少有一个镜头表达了题面或歌词没有直接写出的… | cc-bare-C1、cc-hf-C1、cc5-bare-C1、codex-bare-C1、codex-hf-C1、dsh-bare-C1、dsh-hf-C1 / 无 | 9/9 | 无标注 | 无标注 |
| B2 片中前三分之一是否出现了一个元素，在结尾被兑现？… | cc-bare-C1、cc-hf-C1、cc5-bare-C1、codex-bare-C1、codex-hf-C1、dsh-bare-C1、dsh-hf-C1、sol-bare-C1 / 无 | 9/9 | 2/2 | 14/16 |
| B3 主角是否付出了可见的代价（损伤、时间流逝、失败后… | cc-bare-C1、cc-hf-C1、cc5-bare-C1、codex-bare-C1、codex-hf-C1、dsh-bare-C1、dsh-hf-C1、dshp-bare-C1、sol-bare-C1 / 无 | 9/9 | 2/2 | 2/2 |
| B4 外部障碍消失后，主角是否还要克服一个内心障碍（犹… | cc-bare-C1、cc-hf-C1 / cc5-bare-C1、codex-bare-C1 | 7/9 | 2/2 | 0/2 |
| B5 情绪转折处，人物是否做了一个具体动作（伸手、回头… | cc-bare-C1、cc-hf-C1、cc5-bare-C1、codex-bare-C1、codex-hf-C1、dsh-bare-C1 / 无 | 9/9 | 无标注 | 无标注 |

## M1：不用一个字，在 30 秒内让人看懂勾股定理为什么成立。

| 运行 | overall 排名 | subtext 排名 | craft 排名 | overall 胜率 | subtext 胜率 | craft 胜率 |
|---|---|---|---|---|---|---|
| cc-hf-M1 | 1 | 1 | 1 | 94% | 100% | 97% |
| cc-bare-M1 | 2 | 2 | 2 | 88% | 78% | 88% |
| codex-bare-M1 | 3 | 4 | 3 | 81% | 72% | 72% |
| dsh-hf-M1 | 4 | 5 | 4 | 56% | 31% | 69% |
| cc5-bare-M1 | 5 | 6 | 5 | 50% | 28% | 44% |
| dshp-bare-M1 | 6 | 3 | 6 | 44% | 75% | 44% |
| sol-bare-M1 | 7 | 7 | 8 | 19% | 25% | 12% |
| dsh-bare-M1 | 8 | 9 | 7 | 12% | 19% | 19% |
| codex-hf-M1 | 9 | 8 | 9 | 6% | 22% | 6% |

subtext 换左右后一致：30/36

| 加分题 | 回答 yes 的运行（两次都 yes / 只有一次 yes） | 两次回答一致率 | 对照亮点报告：正例识别 | 反例误判 |
|---|---|---|---|---|
| B7 是否演示了结论在条件变化时仍然成立（换参数、换形… | cc-hf-M1 / 无 | 9/9 | 2/2 | 0/16 |