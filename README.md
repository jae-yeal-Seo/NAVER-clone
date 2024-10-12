勉強したこと
1. ページを横と縦に分けて考える.
2. text-alignはブロック要素の中にあるインライン要素のみalginできる。
最初から、ブロック要素は横幅を全部占めているのでalignするのができない。
3. flexは子要素がインラインかブロック化と関係なくalignできる。
4. タグのAREAを確認する時はbackground-colorを使おう。
5. 横幅は親タグで指定して、縦幅は子タグのheightで決まる。
6. display:blockのタグがブロックタグだ。
7. ↓子タグの中でインラインタグだけ適用される。
        #wrap {
            text-align: center;
        }
8. インラインタグ(display:inline)はwidth, heightがなく中身だけのwidth, heightを占める。
width, heightは持ちながらインラインタグのように扱いたかったらdisplay:inline-blockを使おう。
inline(text-align:centerとか適用されられる)-block(width, height持てる)