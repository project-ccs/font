# 漢字硏究計劃開源字型
Open-source fonts from the Project on Chinese Character Studies

## 字型簡介
因漢字字形之硏究所需，目前沒有符合硏究需求的字型可用，故啟動本計劃，製作符合需求之字型。目前的字型成品有：

- **Study Ming JP（学参明朝体 日本 印刷）**：<br>主要依《常用漢字表》（東京：文化庁，2010年），以及《常用漢字表の字体・字形に関する指針（報告）》（東京：文化庁，2016年）中的明朝體字形，檢校、修改當中常用字的漢字字形。
- **Study Ming JA（学参明朝体 日本 教科書）**：<br>主要依《常用漢字表の字体・字形に関する指針（報告）》（東京：文化庁，2016年）中的教科書體字形﹐並參考表中的手書文字例子字形，以及モトヤ、モリサワ、イワタ等字型廠商的学参明朝体，檢校、修改當中常用字的漢字字形。
- **Study Ming HK（學參明體 香港）**：<br>主要依《常用字字形表》（香港：香港特別行政區政府敎育局課程發展處中國語文敎育組，2012年）及《香港小學學習字詞表》（香港：香港特別行政區政府敎育局課程發展處中國語文敎育組，2007年），並參考《常用字字形表（二零零年修訂本）》（香港：香港敎育學院，2000年）和《香港電腦漢字參考字形》（香港：香港特別行政區政府政府資訊科技總監辦公室、公務員事務局法定語文事務部，2017年），檢校、修改當中常用字的漢字字形。
- **Study Ming TW（學參明體 臺灣）**：<br>主要依《國字標準字體宋體母稿〈敎育部字序〉》（臺北：敎育部國語推行委員會，1998年），並參考《國字標準字體楷書母稿〈敎育部字序〉》（臺北：敎育部國語推行委員會，1998年）、《常用國字標準字體表》（臺北：敎育部，1982年），檢校、修改當中常用字的漢字字形。
- **Study Ming CN（学参明体 中国）**：<br>主要依《通用規範漢字表》（北京：敎育部、國家語言文字工作委員會，2013年），檢校、修改當中常用字的漢字字形。

爲方便不同語系的作業系統使用，避免在其他語系的作業系統或軟件中失效，這些字型的實際名字都只有英文名。所有字型的字高、行高皆與一點字坊的[新一細明體](https://github.com/ichitenfont/I.Ming)統一，除了可以與之搭配使用，亦能與視窗作業系統預設的「細明體」搭配，不會出現行高改變之問題。

## 下載
請移玉步到[Releases頁面](https://github.com/project-ccs/font/releases)下載。

## 概覽
![各字型的字形比較表](img/比較表s.png)  

## 注意事項
本計劃的主旨爲滿足漢字字形硏究所需。字型的修改，未必能顧及設計美感，也欠缺時間仔細修繕。而且因人手和時間所限，我們難以展望後續能作大量修改。若有意幫忙修繕，使這些字型更好，歡迎在[Issues頁面](https://github.com/project-ccs/font/issues)留言。

## 衍生來源與授權
這裏的字型，乃基於[IPAex明朝](https://moji.or.jp/ipafont)、[IPAmj明朝](https://moji.or.jp/mojikiban/font/)、[一點明體、一點明體異體](https://github.com/ichitenfont/I.Ming)以及[霞鶩新緻宋](https://github.com/lxgw/LxgwNeoZhiSong)等開源字型編輯、修改而成。因此與上述字型一樣，採用[IPA開放字型授權協議 1.0版](LICENSE.md)作爲開源授權條款。使用時請遵從此授權協議之規定。

但凡有任何人使用、複製、修改、分發這些字型，或對這些字型進行任何符合「IPA開放字型授權協議 1.0版」規定的行爲，使用、下載或行使合約規定權利之接受方，亦視爲同意遵守「IPA開放字型授權協議 1.0版」的一切規定。

## 版本選擇及技術困難
本計劃初開展時，我們曾考慮基於[思源字型](https://source.typekit.com/source-han-serif/)或其衍生字型來編輯、修改。然而，我們發現思源字型使用較高階的字圖曲線和技術，以我們使用的字型編輯軟件打開，會有進多操作困難。有些版本（主要是筆畫未合併、聲稱可自動計算粗細度的版本）根本幾乎無法編輯。有些版本雖然打得開，但許多編輯作業也變得不可能，字型檔的生成也極度緩慢。即使幾經辛苦把檔案生成出來，在MS Word、MS Execl等軟件中應用時，也常常碰到奇怪問題，儲存作或列印作pdf檔案也會失敗。我們最終得放棄，白白耗費了時間與精力，從頭以IPA系列的字型，把我們的編輯工作重新再來。

有編修字型需求的人，不一定是高階技術愛好者或狂熱者。我們硏究漢字字型，專長在漢字文字學方面，卻發現市面上的字型都不合需求，不得不自行修改。即使我們無法掌握高階技術，我們不認爲我們的需求應遭忽視。謹此呼籲有關方面，能降低技術門檻，使相關技術能普及和方便應用。

## 鳴謝
- 日本・林隆男（Takao Hayashi）：[TB明朝（TB Mincho）](https://www.typebank.co.jp/fontfamily/tbmincho/)
- 日本・情報処理推進機構（IPA）：[IPAex明朝（IPAex Mincho）](https://moji.or.jp/ipafont)
- 日本・情報処理推進機構（IPA）：[IPAmj明朝（IPAmj Mincho）](https://moji.or.jp/mojikiban/font/)
- 一點字坊（Ichitenfont）：[一點明體（I.Ming）](https://github.com/ichitenfont/I.Ming)
- 一點字坊（Ichitenfont）：[一點明體異體（I.Ming Var）](https://github.com/ichitenfont/I.Ming)
- 一點字坊（Ichitenfont）：[新一細明體（PMingI.U）](https://github.com/ichitenfont/I.Ming)
- 一點字坊（Ichitenfont）：[新一細明體異體（PMingI.UVar）](https://github.com/ichitenfont/I.Ming)
- 落霞孤鶩（LXGW）：[霞鶩新緻宋（LXGW Neo ZhiSong）](https://github.com/lxgw/LxgwNeoZhiSong)
