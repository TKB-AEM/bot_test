# OEbot [@open\_esys](https://twitter.com/open_esys)   

## 召喚の呪文   
　例：OE_bot、OpenEsysBot、おーいーぼっと、など   

## 入退室に関する機能
- **入退室報告**   
学生証を登録すれば部屋にあるPaSoRiにかざすだけでTwitter上での入室の報告ができます。   
もう一度かざせば退室となりますが、退室に限り「退室」を含むリプを本人のアカウントでOE_botに送ると、同じ処理ができます。   
また、退室時にそれまでの滞在時間が合計滞在時間に加算され訪問回数も１回増えますが、全ユーザの状態を不在にリセットする朝６時までに退室をしないと滞在時間も訪問回数も加算されません。   
   
- **ダレカオルカ**   
「だれかおるか？」、「誰かいますか」、「おるかｗ」などとリプを送ると3L502にいる人がわかります。   
   
- **これまでの記録**   
「記録」を含むリプを送ると、これまでの訪問回数及び合計滞在時間がわかります。   
   
## その他の機能
- **esysPinger**   
「きしつ」「機室」を含むリプを送ると、3L504で何台PCが稼働中であるかわかります。   
   
- **L棟パンガチャ**   
「L棟パンガチャ」とリプを送ると、L棟２階ラウンジにあるパンの中からランダムでオススメを返します。   
   
- **ｷｪｪｪｪｪｪｱｧｧｧｧｧｧOE_botｶﾞｼｬｧﾍﾞｯﾀｧｧｧｧｧｧｧ!!!**   
「〜って言って」「say 〜」とリプを送ると3L502の本体がしゃべります。(OpenJTalk)   
記号とか特殊文字はしゃべりません。   
例：ほげって言って、say ほげ   
   
- **抵抗値エンコーダ**   
「～Ω」(Ωは必須、オームでも可)のようにリプを送ると4本帯のカラーコードを返します。   
また、誤差を指定することもできます。（誤差を指定する場合±必須）   
例：100Ω、2.2kオーム、1MΩ±5％   
   
- **カラーコードデコーダ**   
上記のものと逆で、「茶黒赤」のようにリプを送るとその抵抗値を返します。   
また、同様に「赤黄赤金」のように誤差を指定することもできます。（誤差を指定しないと±20％で返します。）   
例：赤赤赤、黄黒赤銀
   
## 謝辞
- [ktansai](https://github.com/ktansai)さんの[esysPinger](https://github.com/ktansai/esysPinger)を使用させていただきました。ありがとうございます。   
- bunkai_freeさんにL棟パンガチャを提供していただきました。カレーパンです。   
