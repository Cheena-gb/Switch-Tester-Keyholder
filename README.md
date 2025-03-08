# Keyswich Tester Keyholder
[ENGLISH VER](README-EN.md)  
スイッチテスター・キーホルダー(3u/5u)
![](images/5utester.jpg)

## 遊び方
本品はスイッチテスターにもなる、キーホルダーです。  
サンドイッチケース構造を採用しているため、同じサンドイッチケース構造を持つ自作キーボードキットと似た音や感触になっています。  
カラビナやナスカンなどのパーツを取り付けて、お気に入りのスイッチに世界を見せてあげましょう。  

| 対応表 | Cherry MX版 | ロープロファイル版 |
| ----- | ----- | ----- |
| Cherry MX | 〇 | × |
| Tecsee LP | 〇 | × |
| Outemu LP | × | × |
| Kailh Choc | × | 〇 |
| Gateron LP | × | 〇 |
| Gateron LP 3.0 | × | × |

Cherry MX…Cherry MXまたはその互換スイッチ
Tecsee Low Profile…Cherry MXとの混載が可能な、スイッチプレートより上のみがロープロファイルのもの  
Outemu Low Profile…Cherry MXとの混載が**不可能**な、スイッチプレートから基板までの距離を変える必要があるもの  
Kailh Choc…Kailh Choc V1またはV2互換スイッチ  
Gateron Low Profile…Gateron KS-27またはKS-33互換スイッチ
Gateron Low Profile 3.0…NuPhy Nos75対応スイッチ


## 注意事項
本品は同人ハードウェアであり、ハンドメイドアクセサリーです。  
細かい傷やはんだ面の不均一、フラックスによる汚れは、組み立てた後に大きく目立たない限りは問題ないものとして扱っています。  
  
電子部品は使用していないため、水に濡れても破損することはありませんが、ねじやスペーサー、はんだ面は錆びてしまうことがあるため、もし濡らしてしまった場合はスイッチを外してしっかりと乾かすようにしてください。  
なお、キーキャップを使用することは、外れてしまう可能性が高いため、推奨していません。  
どうしても使用したいという場合は、安く入手性の良いものを使用する程度にとどめておきましょう。
  
分解や改造は自身の責任において行ってください。  
分解を行ったかどうかの判別が難しいため、ネジのゆるみや金具の破損に起因する損害に対しての補償を行うことはできません。  
使用前にはパーツのゆるみや破損、脱落、錆がないことを確認の上、強い力で引っ張るなどといったことを行わないようにお願いします。  
  
本品に使用しているスペーサー、ネジはRoHS対応品ですが、基板製造時に使用するはんだや、スイッチソケットの固定に使用するはんだ、アクセサリー金具の部分に関してはRoHS対応の保証はできかねます。  
2025年春のロットからエッジ部の塗装があるものとないものが混在しているほか、ソケットのメーカーが変更されています。  
機能について変化はないのでご安心ください。塗装は油性ペンで塗れば大丈夫です。

# Build Guide
## 必要な部品 - MX版
※販路やイベントにより同梱品が異なります。組み立て済みのこともあります。
- 基板とプレート  
  星と文字の描かれているものがバックパネル、スイッチソケットの表示があるものが基板、四角い穴があるものがスイッチプレートです。
  3u版の場合、バックパネルは星が外側に来るように、スイッチプレートははんだ面が平らで綺麗な方が外側に来るようにします。
- スペーサー・ネジ  
  必要なものはすべてM2サイズです。  
  「3.組み立てる」を参照し、ネジとスペーサーを選定してください。  
  同梱の場合は同梱品を使用してください。
- 対応するキーソケット  
  3個または5個
## 必要な部品 - ロープロファイル版
- 基板とプレート  
  MX版との差異は厚みのみです(MX版=1.6mm、ロープロファイル版=1.2mm)。
- スペーサー・ネジ  
  「3.組み立てる」を参照し、ネジとスペーサーを選定してください。  
  同梱の場合は同梱品を使用してください。
- 対応するキーソケット  
  3個または5個

  ## 必要な工具
- はんだ作業用品
- ドライバー
- やすり  
  ※必要ないかもしれません
- 油性ペンやマーカー

## 組み立て方
### 1.基板を手入れする
  基板の端には割った跡があります。ガサガサになっている場合はヤスリで磨きます。  
  端を油性ペンで塗ると綺麗に見えます。
### 2.キーソケットをはんだづけする
  部品を実装する基板に、基板の表示に合わせてキーソケットをはめ、はんだ付けします。  
  ロープロファイル版の場合、Gateronソケットを実装するとChoc用の固定ピンが通る場所がなくなります。ソケットを実装しない場所を残すとか、固定ピンを切断するなどして調整してください。
### 3.組み立てる
  使用するネジの長さと種類により組み立て方が変わります。
 - MX版
    - (推奨・高価)7mmと3mmのネジを使用する場合  
    この場合、バックパネルの、星のある面から7mmのネジを通します。  
    マスキングテープでネジを仮止めし、ネジが上向くようにしたら、2mmのスペーサーを入れ、基板を重ねて3.5mmのネジ付きスペーサーで固定します。  
    この状態でスイッチプレートを重ね、3mmのネジで固定します。  
    - (推奨・安価)12mmのネジとナットを使用する場合  
    スイッチプレートの表からネジを通したら、3.5mmスペーサー、基板、2mmスペーサー、バックパネルの順に重ねます。  
    最後にナットでしっかり固定します。
    - (非推奨)6mmと3mmのネジを使用する場合  
    バックパネルの、星のある面から6mmのネジを通したら、スペーサーを入れずに基板を重ね、3.5mmのネジ付きスペーサーで固定します。  
    このままスイッチプレートを重ね、3mmのネジで固定します。
  - ロープロファイル版  
    スイッチプレートの表から8mmネジを通します。3種ナット(M2、厚みが1.2mmのもの)で固定し、さらに基板、2mmスペーサー、バックパネル、の順に重ねます。  
    最後に3種ナットで固定します。
  
  これで、スイッチテスターは完成です。好みのスイッチを装着し、三角形の穴には好みのキーチェーンやパラコードなどを通してネックレスやキーホルダーにしましょう。  
  ※強く引っ張ると基板の破損の原因になるためご注意ください  

## 組み立て済み販売のバラし方
組み立て済みの状態で販売している際、部品の在庫状況によって使用するパーツや組み立て手順が変わってくる場合があります。  
基本的には以下の説明の通りですが、もし異なる場合はスイッチプレートのネジからバラしてください。  
なお、ネジに使用している緩み止め剤は取り外し可能タイプですが、場合により非常に硬く固着してしまう場合があります。  
衝撃を与える、加熱するなどの手段で解除できる場合がありますが、不安な場合はサポートを行いますので、連絡してください。  

### 裏側がナット止めの場合
裏からナットで固定されている場合、長いネジを1本通すことで固定しています。  
ネジを回してナットを外すと、ネジを抜いた時にすべてのスペーサーが落ちるため、注意してください。  
組み立て時は、スイッチプレートにネジをさしてから硬い板を載せてひっくり返したり、マスキングテープで仮止めすることでネジを裏側から上向きに露出させます。  
この状態で、元の順番にパーツを重ね、最後に全てのナットを仮止めしたら、ドライバーとソケットレンチ等を使用してしっかり固定してください。
