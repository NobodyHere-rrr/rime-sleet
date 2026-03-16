# 凍雨拼音

凍雨拼音, 一款基于霚凇拼音, 受洋蔥注音和萬象拼音啓發修改而來的自用拼音方案.

## 與霚凇拼音的不同

- 僅保留 26 鍵全拼與小鶴雙拼方案
- 新增詞庫
  - 維基百科 (felixonmars/fcitx5-pinyin-zhwiki)
  - 萌娘百科 (suiginko/moetype)
  - Minecraft (改自 Kimiblock/rime-minecraft-dict)
  - 詩詞 (amzxyz/rime_wanxiang)
  - 自定義詞庫
  - 東方 Project (自製, WIP)
  - Paradox (自製, WIP)
- 默認關閉自動調頻, 改爲使用自造詞庫
- 新增 萬象語灋模型 (amzxyz/RIME-LMDG) 與 華宇語灋模型 (默認使用華宇模型).
- 移除挂接方案
  - melt_eng (中英混輸方案, 妨礙鍵位修改與個人潔癖)
- 新增挂接方案
  - cangjie5 (反査) (oniondelta/Onion_Rime_Files) (字庫來源于 Fitzgerald-Porthmouth-Koenigsegg/Cangjie5_Integration)
  - easy_en (BlindingDark/rime-easy-en) (詞庫及英漢反査來源于 oniondelta/Onion_Rime_Files)
  - jaroomaji.kana (lazyfoxchan/rime-jaroomaji)

## 後續計劃

- 大字表 (目標是包含 Unicode 中所有有讀音的中日韓越統一表意文字. 缺少讀音的文字捨去)
- 爲新增詞庫添加合適詞頻
- 添加顏文字 (OpenCC)
- 爲 Dvorak 鍵盤佈局設計一箇雙拼方案
- LLM 候選詞
- 手動調頻

## 注意事項

- 英漢反査註釋較長, 可能會導致輸入灋崩潰. 配置文件內有解決方案.
- 本方案默認使用的 "繁軆中文" 不符合任何地區的規範, 但也提供臺灣正軆和日本新字軆的轉換.
