---
layout: indexpage
---
<div class="container">
        {% comment %}<div class="card">
                <div class="card-body">
                        現在生徒さんを募集しております。ぜひご連絡ください。
                </div>
        </div>{% endcomment %}
        <div class="row">
                <div class="style-content col-md-6">
                        <h2>いつからでも始められます。</h2>
                        <p>「ヴァイオリンを習う」こと、「ヴァイオリンを弾く」ことは、プロ志望の人たちに限られているものではありません。</p>
                        <p>ヴァイオリンを弾くことは人生にとって素晴らしい出会いや、精神の豊かさをもたらす効果が期待できます。</p><p>ヴァイオリンは3歳児頃から始められ、単に「ヴァイオリンが弾けるようになる」だけではなく「習うこと」を通して色々な点で人間形成に役立ってくるのです。</p>
                        <p>お子様とご一緒に牧野ヴァイオリン教室に見学にいらしてみてはいかがでしょうか。</p>
                </div>
                <div class="style-content col-md-6">
                        <h2>今後の主なイベント</h2>
                        <p>月曜日〜土曜日のレッスンや、全生徒が月1回集まる合奏レッスン、年1回の発表会、ハロウィンやクリスマスなどのイベントへのご見学に気軽にお越しください。</p>
                        <p>今後のイベントは以下の通りです。</p>
                        <p>見学ご希望の方はこちらよりお問い合わせください。</p>
                        {% for event in site.data.kengakuevents %}
                        <p><span class="style-datebadge">{{ event.date }}</span>{{ event.name }}</p>
                        {% endfor %}
                </div>
        </div>
</div>
