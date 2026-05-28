# 弹珠诗 · Marble Poems

> 在玻璃弹珠的折射里,把藏在暗页中的里尔克诗轻轻显形——五关,逐光而来。
> A poetry-reveal game built atop glass-marble refraction. Five Rilke poems, hidden in light.

**▶ Play live**: <https://xiaoercamera.xyz/弹珠馆/>

## 玩法 · How to play

1. 开局会有几个漂浮的几何形状,轻点任意一个 → 进入显影玩法。
2. 拖动弹珠扫过暗页 → 诗句被"显影";找到 5 颗光点,每颗点亮一段。
3. 5 颗集齐 → 整首诗亮起,显出诗名和作者(里尔克 · 1875–1926)。
4. 点「继续」翻下一首;走完五首进终幕。
5. 左上角切 CN/EN(诗内容会从「德+中」切到「德+英」)。

## 五关

1. 《时辰之书》· 我的生命在渐渐扩大的环中度过
2. 《图像之书》· 预感 (Vorgefühl)
3. 《时辰之书》· 时辰俯身,触动我
4. 《图像之书》· 秋日落叶 (Herbst)
5. 《时辰之书》· 熄灭我的眼睛 (Lösch mir die Augen aus)

所有德文原文均经 [Project Gutenberg](https://www.gutenberg.org/files/24288/24288-h/24288-h.htm) 公版核对。
英文为我自译(为避开仍在版权期的 Mitchell / Bly 等译本)。

## 致谢与许可证 · Credits & License

**核心折射引擎**:[chiuhans111/marbles](https://github.com/chiuhans111/marbles) by **Hans Chiu**([@chiu_hans](https://x.com/chiu_hans))——原生 WebGL 光线追踪 + SVG Filter 折射真实 DOM + 自研物理。

> ⚠️ Hans 的原仓库**未声明许可证**(License: NONE,默认保留全部权利)。本项目是在其引擎上的**深度个人改造**,未取得他的明确许可。**如果你是 Hans,希望本项目下线,请联系 xiaoerzhan@gmail.com,我会立刻撤下。**

**音频**:从 [sensory-ui](https://github.com/SatyamVyas04/sensory-ui)(MIT © Satyam Vyas)忠实移植了 `click` 合成 + `GLASS` 乐器,保留 MIT 署名。

**诗作**:Rainer Maria Rilke(1875–1926),原文公版。

**项目代码作者**:Jane (xiaoer) —— 关卡系统 / 显影机制 / 渐扩光圈 / 5 光点收集 / 中英双语 / 程序化环境音乐 / 毛玻璃质感 / 排版与交互均为本项目原创。

## 本地跑

```bash
git clone https://github.com/Jane-xiaoer/marble-poems-play.git
cd marble-poems-play
python3 -m http.server 8000
# 浏览器打开 http://localhost:8000/
```

单文件 HTML,零依赖。
