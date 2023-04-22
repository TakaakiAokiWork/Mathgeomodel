---
title: "数理地理モデリング研究会"
---
# 数理地理モデリングへの試み

人文社会科学系において，デジタルデータの蓄積に伴い, 「人文学的課題 × データ × 数理モデル」によるアプローチが注目されつつあります.
まず地理情報システム (GIS) の発展から,地形・気候・水資源・植生などのデータが整備されており,さらには古気候学データや歴史デジタルアーカイブが整備されつています．
また歴史人口学では,出産,結婚,死亡といった人口と家族形態に関するデータがデジタル化処理されて蓄積・整備され,数理モデルによる分析・説明も報告されています.
考古学においても,地形情報と数理モデルに基づき,人の移住や交易路の形成を議論する手法が提案されています.

このような状況を踏まえ,人文科学と数理科学との交流場所として「数理地理モデリング研究会」を企画しました．
京都大学数理解析研究所の共同研究プロジェクトなどの支援をいただき，考古学・歴史学・地理学・経済学などの関連分野の研究者を招き,研究発表と討論を行っています．

# セミナー情報
{% if site.posts.size > 0 %}
<ul class="post-list">
  {% for post in site.posts %}
  <li>
    <div>
      {% assign date_format = site.minima.date_format | default: "%Y/%m/%d" %}
      {{ post.date | date: date_format }}
      {% if post.enddate %}
      &ndash; {{ post.enddate }}
      {% endif %}
      <br>
        <a class="post-link" href="{{ post.url | relative_url }}">
          {{ post.title | escape }}
        </a>
      {% if site.show_excerpts %}
      {{ post.excerpt }}
      {% endif %}
    </div>
  </li>
  {% endfor %}
</ul>
{% endif %}


# 運営
この研究会は以下のメンバーで運営しています．
- 青木 高明 (滋賀大学) [web](https://takaakiaokiwork.github.io/)
- 村山 聡 (香川大学) [web](http://rfweb.ed.kagawa-u.ac.jp/project/wiki/muras/wiki.cgi)
- 山田道夫(京都大学数理解析研究所) [web](http://www.kurims.kyoto-u.ac.jp/~yamada/index.html)
- 藤原直哉 (東北大学大学院情報科学研究科) [web](https://www.is.tohoku.ac.jp/jp/laboratory/list_dept/c10.html)

# 共催
地球ディベロプメントサイエンス国際コンソーシアム / International Consortium for Earth and Development Sciences (ICEDS)

# 連絡先

〒522-8522　滋賀県彦根市馬場1-1-1<BR>
滋賀大学データサイエンス学部<BR>
青木 高明<BR>
<span class="glyphicon glyphicon-envelope"></span>takaaki-aoki<span class="no-spam">nospamword</span>@biwako.shiga-u.ac.jp

