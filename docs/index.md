# 数理地理モデリング研究会

# セミナー情報
{% if site.posts.size > 0 %}
<ul class="post-list">
  {% for post in site.posts %}
  <li>
    <div>
      {% assign date_format = site.minima.date_format | default: "%Y/%m/%d" %}
      {{ post.date | date: date_format }}
      
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

