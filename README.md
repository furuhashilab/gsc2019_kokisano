# 2019年古橋研究室ゼミ論文

「自家用車×ドローン」

青山学院大学　地球社会共生学部　1A117081 佐野公紀

## 資料一覧
-  [ゼミ論中間発表資料](https://docs.google.com/presentation/d/1sK6hci77wB66VWDzsLREO3fmZuH6N_5laPwgrq21Mu4/edit#slide=id.p)

-  [ゼミ論テンプレート](https://docs.google.com/document/d/1hT6A7MQRmD3jp-NkzAT2dIeWN-2X0_WGo1aTpzgv2CQ/edit)

-  [ゼミ論報告書](https://medium.com/furuhashilab/ドローンによる人命救助の加速案-5c61bf5faf5e)

-  [参考文献テンプレート](https://docs.google.com/spreadsheets/d/1g0eQedyXYkM6U7-wQ9Sk8WuwJ6fTcOxlsa2oQIvfT6o/edit?usp=sharing)

-  [ゼミ論最終発表資料](https://docs.google.com/presentation/d/1DdGM_dXuUQODMRYJt2wPjhBJuJjZrWy2z_LjX31izCY/edit#slide=id) 


-----------
# ゼミ論本文
## はじめに
　近年、「ドローン」という言葉を日常生活の中でも頻繁に耳にすることがとても多くなってきた。しかし果たしてそれは本当の意味で人々の生活に溶け込んだと言えるのであろうか。実際問題、多くの人の中では一体ドローンがどのような状況で使われるか、あるいはそれがどのようなメリットをもたらすかという部分までは理解していないのではないだろうか。
　本研究では、我々に馴染みのある自動車という物とドローンという最先端的機械を組み合わせることにより、現在よりもリアリティな道路事情（渋滞など）をより素早く運転者に知らせ、それを回避するための行動を取らせることを目的としている。しかし、それを一から全て行うとするならば膨大な時間と労力を注ぐことにならざるを得なかったため、現実的に考えて今回はこのドローンをどのようにして自動車に搭載するか、またそのドローンとの操作方法についての調査をメインに行なった。




## 研究方法
今回、下の3つの方法にて研究を進めた。
1. ドローンの大きさの研究
→車に取り付けることができる最適なサイズを決定するため。
2. ドローンの取り付け方法
→「車」本来のデザイン、または空力性能を損なわないための取り付け方法を考案することが目的
3. 搭載ドローンの操作方法の考案
→どのような操作方法が一番メリットを与えるかを考える


## 研究結果
（ここでの番号は、上の研究方法の番号の結果を表すものである。例：Result1→Methods1の結果）
1. 私のドローンの大きさに関するスペックと、それを車に取り付け（仮）した画像がこちら
　
 ![IMG_5521 2](https://user-images.githubusercontent.com/52966947/73157030-19290180-4123-11ea-91b3-1c31930c584a.jpg)

 - 縦の長さ→410mm 
 - 高さ→90mm 
 - 横の長さ→410mm
この大きさだと車に対してかなり大きいことがわかる。しかし、ドローンという物の特性上ある程度のサイズ感は考慮しなければならない。
　比較対象として研究室所有のドローンのparrot manbo flyのサイズでの調査も行った。
　
 ![IMG_1667 3](https://user-images.githubusercontent.com/52966947/73156976-e67f0900-4122-11ea-802f-9f4066cded46.JPG)

　parrot flyの大きさに関するスペック
 - 縦の長さ→180mm
 - 高さ→不明（だが、前者の半分以上小さいことは目視で確認できるため推定45mm以下）
 - 横の長さ→180mm

明らかにこちらのサイズの方が搭載には適していると言えるのではないだろうか。前者の場合、かなり広いスペースを要することになるが、こちらのようなサイズ感の場合、インテリアのスペースをそこまで損なうことがないため、実用化するならばこのサイズに近いドローンを採用することが望ましい。

2. 車の外に取り付けることを想定するとこのようになる。

![IMG_5518](https://user-images.githubusercontent.com/52966947/73157054-33fb7600-4123-11ea-85e3-c6e9ba9af46d.JPG)

見るからに取ってつけた感が否めなく、デザインの概念を壊してしまっていることがよくわかる。これでは車の空力性能をも損なってしまう。
最近、自動車メーカーのダイハツがこのような車をコンセプトカーとしてモーターショウに出展した。このように、車よりメインを「ドローン」にすることでこのような車、あるいはそのデザインは良いのかもしれないが、本研究が対象としているのは一般人であり、「自家用車」である。これを踏まえるとこのコンセプトカー的車両のデザインを採用しようとはならない。

![modal_img_tsumutsumu04_s](https://user-images.githubusercontent.com/52966947/73157221-c0a63400-4123-11ea-82ba-cb151f0dfda5.jpg)

そこで、私が提案する搭載方法は「覆面パトカーの赤色灯の格納方法」の流用です。現在主流となっている赤色灯の格納方法はこの通りである。

![masked-patrol-car-find](https://user-images.githubusercontent.com/52966947/73157334-02cf7580-4124-11ea-94dc-b3be9a58af4a.jpg)

このように必要な時のみ車外に出し、必要ない時はルーフに格納するというものである。こうすることで、外観デザインとドローンの機能の両者を融合できる唯一の方法である推測する。

3. 搭載ドローンの操作方法についてだが、渋滞時にドローンを操作するというのは極めて無謀なものであり、危険である。つまり、人間の操作なしに飛ぶドローンを搭載する必要がある。自動操縦のドローンとして最近注目されているskydio 2 dockのようなドローンを車両に搭載することでこの問題はパスできる。
 

## 論点
今回の研究をすすめるにあたって外してはならない要素は車のデザインとドローンの搭載を高いレベルで両立することである。たとえの一つとして出てきた覆面パトカーは、デザインと赤色灯という目的媒体の搭載を高いレベルで両立している。自家用車でドローンを搭載するということを考えると、ドローンのサイズが大きすぎるとかえってデザイン要素の欠落を齎す。反対に、小さすぎると道路状況を撮影するためのカメラが付いていないため、ドローンのサイズの塩梅が実用化させる上で非常に鍵となる点ということを忘れてはならない。

##  結論・課題
今回の研究で明らかになったことは、以下の通りである
 - 自家用車にドローンを搭載することを考慮した際、重要なことはそのサイズであり大きすぎず、小さすぎないドローンサイズに決定することが有効的である。
 - 車のデザインとドローンの搭載ということを両立させる際、使う時のみ表に出し、使わない時はルーフ部分に収納することでそれを達成できる。
 - 「車の運転=ドローンを操作できる」という基本的なことを見落としてはならない。そのため自動操縦が可能なドローンの搭載することで、それが運転者に渋滞情報などを伝達しそれの回避行動を取ることにつながる

## 参考文献
- https://dronetribune.jp/articles/16641/
- https://japanese.engadget.com/2019/10/17/skydio-24/
- http://home.kingsoft.jp/news/app/radiolife/25586.html
## 謝辞
本研究を進めるにあたり青山学院大学・地球社会共生学部教授の古橋大地氏をはじめ多くの方々より多大な助言を賜りました。厚く感謝を申し上げます。

