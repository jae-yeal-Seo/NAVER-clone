勉強したこと
1. ★ページを横と縦に分けて考える.

2. text-alignはブロック要素の中にあるインライン要素のみalignできる。
最初から、ブロック要素は横幅を全部占めているのでalignするのができない。

3. flexは子要素がインラインかブロック化と関係なくalignできる。

4. ★タグのAREAを確認する時はbackground-colorを使おう。

5. ★横幅は親タグで指定して、縦幅は子タグのheightで決まる。

6. display:blockのタグがブロックタグだ。

7. ↓子タグの中でインラインタグだけ適用される。
        #wrap {
            text-align: center;
        }

8. ★インラインタグ(display:inline)はwidth, heightがない。
width, heightは持ちながらインラインタグのように扱いたかったらdisplay:inline-blockを使おう。
inline(text-align:centerとか適用されられる)-block(width, height持てる)

9. ブラウザに基本的に適用されているスタイルがある。
10. ★開発ツールで先に属性の値を入れた後正しく作動したらvscodeのCSSに適用する。
11. width, height, paddingで切られたイメージはpadding領域まで含めて表示される。\
(background-imageはタグのコンテンツではない)
12. paddingは自分とコンテンツとの余白だ。コンテンツとして子タグがある場合は子タグと親タグの余白になる。
13. background-sizeについてよく整理されているぺーじ：https://devjhs.tistory.com/611

14. background-position: (写真が移動する)
x軸の値を増やしたら、写真が右の方に移動する。
y軸の値を増やしたら、写真が下の方に移動する。

15. position: absolute は、基本的に一番近い先祖要素の中で position が relative、absolute、fixed、または sticky に設定されている要素を基準に位置が決まります。