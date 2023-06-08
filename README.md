# suncha3-dic
駿台予備学校お茶の水校3号館に出講している講師の名前を変換するためのIME辞書。
# 使用方法
## MS-IME,Google日本語入力
`dic.txt`をダウンロードして、それを辞書としてインポートすればよい。
## その他の入力システム
`gboard.zip`はGboard用  
`macosx.plist`はMacOSX用(所持していないため動作未確認)  
`skk-jisyo.suncha3.utf8`はSKK用である。
## ファイルの生成
```
(convertフォルダ内で)
go get
go build convert_dic.go
(バイナリを親ディレクトリに持って行って)
./convert_dic
```
# 権利について
/convert 以下のソースコードはほとんど未改変であるから、(これが再頒布なのかわからないが)元の著作権表示でMITライセンスのままとしておく。

それ以外に関しては、(この程度の辞書に権利が生じるとは思えないが)一応CC0で全権利を放棄しておく。
# 謝辞
辞書作成にはお茶飲みwiki( https://pchira.wicurio.com/ )を参照した。寄稿者に感謝する。  
その他の入力システム向けのファイル作成用のプログラム(/convert 以下)は[ maruamyu/imas-ime-dic ](https://github.com/maruamyu/imas-ime-dic)よりお借りし、一部改変した。MIT Licenseという寛容なライセンスで公開していただいたことを感謝する。  
良質な授業を提供してくださった駿台予備学校の各講師にも感謝する。
