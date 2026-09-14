# 藍宥欣 Yu-Shin Lan

高中生。寫 C++ 與 Python，主要做遊戲 AI、強化學習，以及一個情緒健康陪伴應用。

比起把東西做出來，我更在意能不能說清楚它哪裡不成立。所以每個 repo 都會記錄失敗的實驗、放棄的構想，以及與比賽版本之間的落差。

## 專案

| 專案 | 一句話 | 我的角色 | 語言 |
|---|---|---|---|
| [rummikub-ai-agent](https://github.com/acacapcs-star/rummikub-ai-agent) | 拉密遊戲引擎與 AI Agent，含「大風吹」全域重組演算法。對 baseline 千場測試 82% 勝率 | 個人（資芽大作業二之延伸） | C++ |
| [cognitive-coach](https://github.com/acacapcs-star/cognitive-coach) | 領域無關的認知教練引擎：決定什麼時候該提示、提示多深、什麼時候閉嘴 | 個人，成大實驗室討論中 | C++ |
| [lii](https://github.com/acacapcs-star/lii) | 分級式 AI 情緒健康應用。核心設計：風險越高，系統說得越少 | v1 四人團隊 → v2 起獨立迭代 | Dart / Flutter |
| [ytp-arena-agent](https://github.com/acacapcs-star/ytp-arena-agent) | 2026 YTP 競技場自主 agent。場景偵測 → 候選過濾 → beam search → MPC 控制 | 隊長，策略程式碼由我撰寫 | Python |
| [TankMan-RL-Agent](https://github.com/acacapcs-star/TankMan-RL-Agent) | 用 PPO 訓練坦克決策系統，拆成瞄準／追擊／補給三個子任務 | 三人團隊，我負責 RL 模組 | Python |
| [math-cpp-portfolio](https://github.com/acacapcs-star/math-cpp-portfolio) | 數理解題紀錄：預處理、BFS 連通性、三維枚舉、離散化誤差控制 | 個人 | C++ |

## 一條貫穿的線

五個專案做的其實是同一件事：區分「我以為的」和「實際上的」。

- **拉密**：原本規劃遞迴窮舉找最佳解，為了讓安全回滾鎖每一步可控，改成迭代貪心。`solveRummikub` 保留介面但未實作——這個決定被明確記錄，而不是悄悄消失
- **坦克**：25 項單元測試全部針對獎勵函數。方向判斷寫錯不會報錯，訓練照跑、loss 照降，agent 卻永遠學不會瞄準
- **YTP**：場景偵測是對固定地圖調參，換地圖就退化。這個 trade-off 是刻意的，也寫在 README 裡
- **lii**：web 版首次載入慢，附 7 天、n=66 的實測數據，而不是含糊帶過

## 競賽

| 年 | 賽事 | 成績 | 角色 |
|---|---|---|---|
| 2026 | YTP 少年圖靈計畫 AI Agent 對戰賽（全國） | 初賽 23/99 → 複賽 2/35 → 決賽 | 隊長，策略程式碼由我撰寫 |
| 2026 | 第 23 屆育秀盃創意獎 高中職 AI 應用類組（全國 714 件） | **苗豐強科技創新獎**（不分類，714 件取 3）＋ 類組佳作 | 四人團隊，負責技術問答、簡報與決賽答辯 |
| 2025 | FunAI Winter Camp 坦克大作戰（39 組，清大／成大／陽明交大／臺科大主辦） | **第一名** | 三人團隊，負責 RL 模組 |
| 2026 | 資訊之芽 C++ 語法班 二階大作業 | 49.8 / 50，該屆全台語法班最高分 | 個人 |
| 2026 | IOAI 國際人工智慧奧林匹亞 台灣選拔 | 通過書審，進入複選筆試 | 個人 |
| 2025 | PUPC 私立大學程式競賽 高中職新星組 | 銀獎 | 個人 |
| 2025 | 台灣半導體 IC 營（Synopsys × 交大校友總會） | 第二名；邏輯實作傑出獎、溝通與闡述表現獎 | 負責 logic gate 電路優化；四子棋抽象化為具體應用 |
| 2026 | IONC 清大資奧研習營 結業小組挑戰賽 | 18/29 | 隊長 |
| 2026 | 國際達文西發明展 | 金牌（lii v2） | 獨立開發 |

## 研究與培訓

| 年 | 項目 | 內容 |
|---|---|---|
| 2026– | 成大資工 蘇文鈺教授實驗室 | 參與開放討論；就認知教練型 AI 的架構抽象化與驗證方法請益（持續中） |
| 2026 | 中國醫藥大學 × 清大 MISLAB 齒顎矯正 AI 研究 | 臉部／側臉解剖標記點偵測、鼻唇角與 E-line 自動量測、相似病例檢索、醫療影像前處理與去識別化 |
| 2026 | TAICA 課程助教研習營（機器導航與探索 · 模仿式學習） | ROS、SLAM、物件辨識、模仿式學習機器人取放；第二階段限額 30 人，唯一高中生 |
| 2026 | IONC 清大資奧研習營 | 複雜度、資料結構、DP、圖論、數論組合、賽局；書審正取 |

## 表達

把事情說清楚是這份履歷的主軸，不只在程式碼裡：

- 全國國文閱讀心得 特優
- 外交小尖兵 優勝
- TOEIC 940+（C1）
- 半導體 IC 營 溝通與闡述表現獎；育秀盃決賽答辯

## 解題紀錄

NTUCPC 76 AC · TIOJ 64 AC · CSES Introductory 6 + Stick Game、Counting Divisors · AtCoder Boot Camp Easy 27/100、Medium 40/100

練習規則只有一條：不查 AI。要能說清楚哪些是自己想出來的，前提是真的有一段時間完全靠自己想。

## 技術

`C++` 遊戲引擎、演算法、競程 · `Python` 強化學習、agent 策略 · `Dart/Flutter` 跨平台應用 · `ROS` SLAM、導航、模仿式學習 · CMake · Docker · Git · Stable Baselines3 · Gymnasium

## 關於 AI 協助

每個 repo 的 README 都揭露 AI 協助的範圍，並明確區分哪些部分完全由我設計與撰寫。我對每一行提交的程式碼負責，如需 code review 可隨時安排。
