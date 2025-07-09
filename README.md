# 凍雨拼音

凍雨拼音, 一款基于霚凇拼音, 受洋蔥注音啓發修改而來的自用拼音方案.

## 與霚凇拼音的不同

- 僅保留 26 鍵全拼方案
- 新增詞庫
  - 維基百科 (felixonmars/fcitx5-pinyin-zhwiki)
  - 萌娘百科 (outloudvi/mw2fcitx)
  - Minecraft (改自 Kimiblock/rime-minecraft-dict)
  - 詩詞 (amzxyz/RIME-LMDG)
  - 東方 Project (自製, WIP)
  - 鋼鐵雄心 4 (自製, WIP)
  - Linux (自製, WIP)
- 使用 萬象語灋模型 (amzxyz/RIME-LMDG)
- 移除挂接方案
  - melt_eng (中英混輸方案, 妨礙鍵位修改與個人潔癖)
- 新增挂接方案
  - cangjie5 (反査) (按 uu 調出) (oniondelta/Onion_Rime_Files) (字庫來源于 Fitzgerald-Porthmouth-Koenigsegg/Cangjie5_Integration)
  - easy_en (按 i 調出) (BlindingDark/rime-easy-en) (詞庫及英漢反査來源于 oniondelta/Onion_Rime_Files)
  - rime-japanese (按 I 調出) (gkovacs/rime-japanese)
- 修改 custom_phrase (妨礙鍵位修改)

## 後續計劃

- 大字表 (目標是包含 Unicode 中所有有讀音的中日韓越統一表意文字. 缺少讀音的文字捨去)
- 爲新增詞庫添加合適詞頻

## 注意事項

- 英漢反査註釋較長, 可能會導致輸入灋崩潰. 配置文件內有解決方案.
- 拼音反査需自行根據 mirtlecn/rime-radical-pinyin#反查带声调注音 下載安裝.
