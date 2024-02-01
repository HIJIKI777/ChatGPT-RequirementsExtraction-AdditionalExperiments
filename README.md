# ChatGPT-RequirementsExtraction-AdditionalExperiments

これは，「ChatGPT に質問させることによる要求抽出能力の調査」にて行った追加実験における

* ChatGPTとのやりとり
* 要求獲得数
* 要求獲得率

を記したものである．

各pdfに記した内容は，以下の通りである．

## new1st-talking-result.pdf
追加実験1回目のやりとり，要求獲得数，要求獲得率を記録したもの．

## new2nd-talking-result.pdf
追加実験2回目のやりとり，要求獲得数，要求獲得率を記録したもの．

## new3rd-talking-result.pdf
追加実験3回目のやりとり，要求獲得数，要求獲得率を記録したもの．


## やりとりの記載方式の説明

###  〇回目(▲問目～□問目）
###  質問群：・・・．
###  回答：・・・．
###  獲得した要求項目：xxx，yyy，zzz

* 〇回目は，，初めに出力した質問群を1回目とし，そこから何回目に出力した文章かを表す．
* ▲問目～□問目は，質問群の一番初めの質問を▲問目，質問群の一番後の質問を□問目として表したものである．□問目が 100 問目となった時点で実験を終了する．
* 質問群には，ChatGPTから提示された質問群の文章を示す．
* 回答には，実際に回答した回答文を示す．
* 獲得した要求項目には，回答によって獲得した要求項目がどれかを示す．3桁の数字は，あらかじめ用意した仕様書内にある要求項目RExxx のうちのxxxに該当する3桁の数字を表す．また，要求項目を1つも満たしていない質問については，「なし」と記載する．

また，質問に関係のない文章は省略した．

例
* 「了解しました。以下の質問を通じて、要求仕様書作成に必要な情報を引き出していきましょう。」
* 「了解しました。以下のような要件を含んだ在庫管理システムの機能が必要ですね。・・・上記の要件を満たすために、さらに以下の点について教えていただけますか？」            など        
