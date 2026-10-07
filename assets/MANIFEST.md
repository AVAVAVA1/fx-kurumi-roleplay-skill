# `assets/` — 表情包清单与来源

本目录的 8 张图片来自《FX战士久留美》（FX戦士くるみちゃん）原作漫画分镜的**中文译版**，由本项目使用者提供，并按情绪语义重命名，供角色扮演时按情景调用。

> ⚠ **版权**：图片著作权属于原作者 **でむにゃん**（原作）／**炭酸だいすき**（作画）／**KADOKAWA**。本目录**不适用**本仓库的 MIT 许可证，详见根目录 `NOTICE.md`。

---

## 命名映射

原文件名为图源站点（百度贴吧）的随机串，已按语义重命名。映射关系留存于此，便于核对与替换。

| 现文件名 | 原文件名 | 图上文字 | 含义 |
|---|---|---|---|
| `01-manic-allin.jpg` | `-9lddQkdt-4vi7K26T1kShs-ja.jpg` | 現在買入 一定爆賺！ | 梭哈的瞬间——兴奋到失智，不是自信 |
| `02-profit-gone-panic.jpg` | `-9lddQkdt-63g8ZgT3cShs-l1.jpg` | 盈利 哪裡去了？ | 浮盈蒸发，呆滞多于痛苦 |
| `03-will-it-rise-or-fall.jpg` | `-9lddQkdt-7m9oZbT1kSfs-dk.jpg` | 家人们 会涨还是会跌啊？ | 完全没主见，把判断权交给别人 |
| `04-i-figured-it-out.jpg` | `-9lddQkdt-cat4K2pT3cSqo-el.jpg` | 我已經完全看懂走勢了！接下來是上漲！ | 过度自信的顶点（赌徒的自我催眠） |
| `05-dead-man-walking.jpg` | `-9lddQkdt-j8l2ZgT3cSuz-pk.jpg` | 我已經是個要死的人了 你能出去嗎？ | 谷底。面无表情的自我放弃 |
| `06-stocks-easy.jpg` | `-9lddQkdt-ka21ZtT3cSk0-du.jpg.medium.jpg` | 股票 簡單啊 | 轻蔑，Dunning-Kruger 的具象化 |
| `07-not-enough-money.jpg` | `-9lddQkdt-ukyZ1bT3cSsg-k8.jpg.medium.jpg` | 這點不上不下的金額 我才不要 | 嫌钱少，胃口被撑大 |
| `08-honest-work-is-boring.png` | `老实赚钱很枯燥吧？.png` | 老實賺錢很枯燥吧？ | 拉人入坑的"恶魔的低语"（黑色锯齿气泡） |

## 技术信息

| 文件 | 尺寸 | 说明 |
|---|---|---|
| `01-manic-allin.jpg` | 640×694 | 仰角大特写＋爆炸状集中线 |
| `02-profit-gone-panic.jpg` | 640×757 | 黑色漩涡背景 |
| `03-will-it-rise-or-fall.jpg` | 568×488 | 台词气泡在左侧 |
| `04-i-figured-it-out.jpg` | 960×525 | 横构图，带贴吧水印 |
| `05-dead-man-walking.jpg` | 1115×920 | 分辨率最高，**唯一含黑暗内容的图** |
| `06-stocks-easy.jpg` | 640×442 | 脸部凑到最近 |
| `07-not-enough-money.jpg` | 640×455 | 满屏钞票被挥手扫开 |
| `08-honest-work-is-boring.png` | 672×457 | 唯一 PNG，黑底台词气泡 |

合计约 **1.0 MB**。

## 使用限制

见 `../references/stickers.md` 第四节。要点：
- 一条消息最多一张图
- `05-dead-man-walking.jpg` 每场对话最多一次，且不得与自伤描写相邻
- 图是语气的一部分，不是装饰

## 替换为自己的图

若你希望换成自己收集的表情包：
1. 保持文件名不变（8 个名字即接口），skill 无需改动
2. 或改文件名后同步更新 `../references/stickers.md` 的投放规则表
3. 建议同样用 `NN-语义短名.ext` 的格式，数字前缀保证排序稳定

## 来源与致谢

图片来源：百度贴吧「FX战士久留美吧」流传的表情包图源（原文件名形如 `-9lddQkdt-xxxx.jpg`，为贴吧图床命名规则）。
作品与角色版权：**でむにゃん・炭酸だいすき／KADOKAWA**。
本目录仅用于个人同人性质的对话练习，**不作任何商业用途**。
