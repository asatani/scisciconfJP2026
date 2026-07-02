---
title: プログラム
layout: single
permalink: /program/
author_profile: false
classes: wide
---

<style>
.prog-note { color:#666; font-size:0.9em; margin-bottom:24px; }

/* 日別バナー */
.day-banner {
  background: linear-gradient(135deg, #4CAF50 0%, #2e7d32 100%);
  color:#fff; padding:18px 24px; border-radius:10px; margin:36px 0 24px;
  box-shadow:0 3px 8px rgba(0,0,0,0.12);
}
.day-banner .day-num { font-size:0.85em; letter-spacing:2px; opacity:0.9; display:block; }
.day-banner .day-date { font-size:1.5em; font-weight:bold; }

/* タイムライン */
.prog-item {
  display:flex; gap:16px; padding:14px 0; border-bottom:1px solid #eee;
  align-items:flex-start;
}
.prog-time {
  flex:0 0 118px; font-weight:bold; color:#2c3e50; font-size:0.92em;
  padding-top:2px; white-space:nowrap;
}
.prog-body { flex:1 1 auto; min-width:0; }
.prog-title { font-weight:bold; color:#222; font-size:1.05em; }
.prog-sub { color:#555; font-size:0.9em; margin-top:4px; }

/* 種別バッジ */
.badge {
  display:inline-block; font-size:0.72em; font-weight:bold; color:#fff;
  padding:2px 9px; border-radius:12px; margin-right:8px; vertical-align:middle;
}
.badge-invited { background:#5c6bc0; }
.badge-lt      { background:#fb8c00; }
.badge-general { background:#26a69a; }
.badge-info    { background:#90a4ae; }

/* 招待講演カード */
.talk-card {
  border-left:4px solid #5c6bc0; background:#f7f8fc;
  padding:16px 18px; border-radius:0 8px 8px 0; margin-top:10px;
}
.talk-card .speaker { font-weight:bold; color:#3949ab; }
.talk-card .talk-title { font-weight:bold; margin:8px 0 4px; color:#222; }
.talk-card .talk-abstract { font-size:0.9em; color:#444; line-height:1.7; }
.talk-card .lbl { font-size:0.78em; color:#5c6bc0; font-weight:bold; display:block; margin-top:10px; }

/* テーブル */
.prog-table-wrap { overflow-x:auto; margin-top:12px; -webkit-overflow-scrolling:touch; }
table.prog-table { width:100%; border-collapse:collapse; font-size:0.85em; min-width:640px; }
table.prog-table th {
  background:#37474f; color:#fff; padding:8px 10px; text-align:left; font-weight:bold;
  white-space:nowrap;
}
table.prog-table td { padding:8px 10px; border-bottom:1px solid #eee; vertical-align:top; }
table.prog-table tr:nth-child(even) td { background:#fafafa; }
table.prog-table .id-cell { font-weight:bold; color:#fb8c00; white-space:nowrap; }
table.prog-table .idg-cell { font-weight:bold; color:#26a69a; white-space:nowrap; }

/* チュートリアル箇条書き */
.tut-box { background:#f1f8f1; border-radius:8px; padding:14px 18px; margin-top:10px; }
.tut-box ol { margin:6px 0 6px 1.1em; }
.tut-box li { margin:4px 0; font-size:0.92em; }
.tut-note { font-size:0.85em; color:#666; margin-top:8px; }

@media (max-width:600px){
  .prog-item{ flex-direction:column; gap:4px; }
  .prog-time{ flex-basis:auto; color:#4CAF50; }
}
</style>

<p class="prog-note">※本プログラムでは、発表者・共同研究者の敬称を省略しております。<br>
最新の情報は変更される場合があります。</p>

<!-- ============ 1日目 ============ -->
<div class="day-banner">
  <span class="day-num">DAY 1</span>
  <span class="day-date">7月4日（土）</span>
</div>

<div class="prog-item">
  <div class="prog-time">14:00</div>
  <div class="prog-body"><div class="prog-title">受付開始</div></div>
</div>

<div class="prog-item">
  <div class="prog-time">14:30</div>
  <div class="prog-body"><div class="prog-title">開会挨拶</div></div>
</div>

<div class="prog-item">
  <div class="prog-time">14:30–16:30</div>
  <div class="prog-body">
    <div class="prog-title">チュートリアル</div>
    <div class="prog-sub">講師：浅谷 公威（東京大学）</div>
    <div class="tut-box">
      <ol>
        <li>SciSci分野の簡単な紹介</li>
        <li>OpenAlexデータへのアクセスと基礎統計量を計算する</li>
        <li>研究者の貢献や研究環境を数値化して研究者の将来を予測する</li>
        <li>学術分野をネットワーク解析で俯瞰する</li>
        <li>ジェンダー別にパフォーマンスと共著構造の差異を理解する</li>
        <li>CD-index [Funk &amp; Owen-Smith, <em>Manage. Sci.</em>, 2017; Wu et al., <em>Nature</em>, 2019] を実装して論文の革新性を評価する</li>
      </ol>
      <p class="tut-note">※ PC（Mac/Windows/Linux等）をご持参いただくことを推奨します。ブラウザからGoogle Colabへアクセスして手元で分析コードを動かせます。コードは6月末までに公開予定です。</p>
    </div>
  </div>
</div>

<div class="prog-item">
  <div class="prog-time">16:30</div>
  <div class="prog-body">
    <div class="prog-title">1日目閉会挨拶</div>
    <div class="prog-sub">SciSci研究会からのお知らせ1・運営記念撮影</div>
  </div>
</div>

<div class="prog-item">
  <div class="prog-time">18:00</div>
  <div class="prog-body">
    <div class="prog-title">🍻 懇親会</div>
    <div class="prog-sub">神戸大学レストランさくら（参加登録者に連絡済）</div>
  </div>
</div>

<!-- ============ 2日目 ============ -->
<div class="day-banner">
  <span class="day-num">DAY 2</span>
  <span class="day-date">7月5日（日）</span>
</div>

<div class="prog-item">
  <div class="prog-time">08:30</div>
  <div class="prog-body"><div class="prog-title">受付開始</div></div>
</div>

<div class="prog-item">
  <div class="prog-time">08:55</div>
  <div class="prog-body"><div class="prog-title">開場</div></div>
</div>

<div class="prog-item">
  <div class="prog-time">08:55–09:00</div>
  <div class="prog-body"><div class="prog-title">開会・趣旨説明</div></div>
</div>

<div class="prog-item">
  <div class="prog-time">09:00–09:45</div>
  <div class="prog-body">
    <div class="prog-title"><span class="badge badge-invited">招待講演①</span></div>
    <div class="talk-card">
      <div class="speaker">久壽米木 圭吾 氏（Cornell University）</div>
      <div class="talk-title">Scientific production in the era of large language models</div>
      <span class="lbl">要旨</span>
      <div class="talk-abstract">本講演では、3つの主要なプレプリントサーバーに2018年1月から2024年6月までに投稿された約210万件の論文を分析し、大規模言語モデル（LLM）の利用が、論文産出の増加、非英語話者の参入障壁の低下、参照される先行研究の多様化と関連していることを示します。その一方で、文章の複雑さといった従来の科学的質のシグナルが、もはや研究の価値を測る指標としては信頼できなくなりつつある点についても議論します。</div>
    </div>
  </div>
</div>

<div class="prog-item">
  <div class="prog-time">09:45–10:45</div>
  <div class="prog-body">
    <div class="prog-title"><span class="badge badge-lt">LT セッション1</span>評価・キャリア・政策</div>
    <div class="prog-sub">※ ライトニングトークは各発表5分</div>
    <div class="prog-table-wrap">
      <table class="prog-table">
        <thead><tr><th>ID</th><th>タイトル</th><th>発表者</th><th>所属</th><th>共同研究者（所属）</th></tr></thead>
        <tbody>
          <tr><td class="id-cell">LT01</td><td>主成分分析と独立成分分析による科学評価指標の次元削減と構造分析</td><td>中村 洋暢</td><td>JAIST</td><td>持橋 大地（統計数理研究所）、太田 由宇（JAIST）、小泉 周（JAIST）、中分 遥（JAIST）</td></tr>
          <tr><td class="id-cell">LT02</td><td>大学研究の独自性指標の構築：文書埋め込みと不均衡最適輸送を用いて</td><td>太田 由宇</td><td>JAIST</td><td>小泉 周（JAIST）、荻 多加之（JAIST・福島大学）、中分 遥（JAIST）、持橋 大地（統計数理研究所）</td></tr>
          <tr><td class="id-cell">LT03</td><td>ポスター賞は「見せ方」も評価しているか？</td><td>伊藤 和浩</td><td>東京大学</td><td>市川 慧（東京科学大）、宮部 裕貴（東京大学）</td></tr>
          <tr><td class="id-cell">LT04</td><td>2000年代以降の日本の大学における分野別教員ポスト・求人の変化</td><td>高橋 祐貴</td><td>東京大学</td><td></td></tr>
          <tr><td class="id-cell">LT05</td><td>研究者のピボットとキャリア成功 — 分野間距離の観点から</td><td>柴谷 佳弥</td><td>東京大学</td><td>浅谷 公威（東京大学）</td></tr>
          <tr><td class="id-cell">LT06</td><td>研究費獲得情報の統合分析基盤構築の試行と研究支援実務への応用</td><td>渡邉 吉康</td><td>京都大学</td><td></td></tr>
          <tr><td class="id-cell">LT07</td><td>研究者は自身の研究の意義をどのように記述するのか</td><td>宮部 裕貴</td><td>東京大学</td><td></td></tr>
          <tr><td class="id-cell">LT08</td><td>モード論から見る地域連携研究のマネージメント課題</td><td>奥本 素子</td><td>北大</td><td></td></tr>
          <tr><td class="id-cell">LT09</td><td>COVID-19関連プレプリントにおける宣伝的表現と社会的関心の関係性</td><td>大木 有</td><td>立正大学</td><td>イム ドンウ（関西大学）、田中 幹人（早稲田大学）</td></tr>
          <tr><td class="id-cell">LT10</td><td>オープンサイエンスとAI for Scienceで進む構成学的メタサイエンスとSynthetic Metascience</td><td>林 和弘</td><td>NISTEP</td><td></td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div>

<div class="prog-item">
  <div class="prog-time">10:45–11:00</div>
  <div class="prog-body"><div class="prog-title">休憩</div></div>
</div>

<div class="prog-item">
  <div class="prog-time">11:00–12:00</div>
  <div class="prog-body">
    <div class="prog-title"><span class="badge badge-lt">LT セッション2</span>AI・ツール・ネットワーク・人文</div>
    <div class="prog-sub">※ ライトニングトークは各発表5分</div>
    <div class="prog-table-wrap">
      <table class="prog-table">
        <thead><tr><th>ID</th><th>タイトル</th><th>発表者</th><th>所属</th><th>共同研究者（所属）</th></tr></thead>
        <tbody>
          <tr><td class="id-cell">LT11</td><td>意味的ワードクラウドのURA現場活用：実務家による事例報告</td><td>荻 多加之</td><td>JAIST／福島大</td><td>藤村 具紀（JAIST）、小泉 周（JAIST）</td></tr>
          <tr><td class="id-cell">LT12</td><td>OpenAlexとLLMを用いた論文特徴の分解と可視化</td><td>大滝 啓介</td><td>豊田中央研究所</td><td>牧野 寛也（豊田中央研究所）、大西 健史（豊田中央研究所）、堺 浩之（豊田中央研究所）</td></tr>
          <tr><td class="id-cell">LT13</td><td>未解決問題の判別・生成能力を測る LLM 評価ベンチマーク</td><td>牧野 寛也</td><td>豊田中央研究所</td><td>大西 健史（豊田中央研究所）、大滝 啓介（豊田中央研究所）、堺 浩之（豊田中央研究所）</td></tr>
          <tr><td class="id-cell">LT14</td><td>タイポミスに注目したネイティブの論文執筆におけるAI使用の指摘</td><td>小島 昂太</td><td>東京大学</td><td>山田 大貴、西山 慶</td></tr>
          <tr><td class="id-cell">LT15</td><td>潜在的知財を発掘するための論文・特許引用分析</td><td>FEI WANG</td><td>総研大／NII</td><td>水野 貴之（NII）</td></tr>
          <tr><td class="id-cell">LT16</td><td>科学哲学の科学への寄与（PinS）は再生産可能なのか</td><td>佐藤 公亮</td><td>北海道大学</td><td></td></tr>
          <tr><td class="id-cell">LT17</td><td>年表・ナレッジグラフ・人文研究を連動させる科学史可視化の構想</td><td>髙橋 廉</td><td>COTEN</td><td></td></tr>
          <tr><td class="id-cell">LT18</td><td>ソーシャルメディア上の学術情報流通とコミュニティに関する探索的分析</td><td>左野 寛之</td><td></td><td>吉田 光男（筑波大学）</td></tr>
          <tr><td class="id-cell">LT19</td><td>arXiv e-printの投稿実態分析に向けた可視化手法の構築</td><td>天賀 広</td><td>和歌山大学</td><td>風間 一洋（和歌山大学）、吉川 次郎（和歌山大学）、大波 純一（理化学研究所）、佐藤 翔（同志社大学）、吉田 光男（筑波大学）</td></tr>
          <tr><td class="id-cell">LT20</td><td>オープンサイエンスと研究DXを支えるNII RDCと研究データエコシステムの構築（仮）</td><td>佐藤 知生</td><td>NII</td><td></td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div>

<div class="prog-item">
  <div class="prog-time">12:00–13:15</div>
  <div class="prog-body"><div class="prog-title">昼休み</div></div>
</div>

<div class="prog-item">
  <div class="prog-time">13:15–14:00</div>
  <div class="prog-body">
    <div class="prog-title"><span class="badge badge-invited">招待講演②</span></div>
    <div class="talk-card">
      <div class="speaker">小泉 周 氏（北陸先端科学技術大学院大学（JAIST）理事・副学長／教授）</div>
      <div class="talk-title">定量指標は科学技術政策をゆがめるのか？——「厚み」指標から大学ランキング・若手研究者育成評価まで</div>
      <span class="lbl">要旨</span>
      <div class="talk-abstract">科学技術政策において、論文数、被引用数、大学ランキング、外部資金獲得額などの定量指標は、研究力や政策効果を把握するための重要な手がかりとして用いられてきた。小泉は、2015年の科学研究費補助金（特別研究促進費）において「大学の研究力評価」に関する「厚み」指標を提言して以来、定量指標の適用範囲と限界について議論してきた。一方で、定量指標は研究現場をゆがめる、研究の質や多様性を捉えられない、といった批判も根強い。本講演では、定量指標そのものの是非ではなく、「何を知るために、どの指標を用いるのか」という目的と指標の対応関係に着目する。「研究大学強化促進事業」、THE世界大学ランキングや「世界で活躍できる研究者育成事業」などにおける講演者の経験事例を通じて、定量指標が有効に機能する条件と、政策目的とのミスマッチが生む問題を検討する。あわせて、政策側には、指標を単なる管理・配分の道具としてではなく、現場との対話を促し、政策目的の妥当性を問い直すための補助線として扱う姿勢が求められることを論じる。定性評価と定量評価を対立的に捉えるのではなく、両者を組み合わせ、科学技術政策におけるよりよい意思決定のあり方を考えたい。</div>
    </div>
  </div>
</div>

<div class="prog-item">
  <div class="prog-time">14:00–14:10</div>
  <div class="prog-body"><div class="prog-title">休憩</div></div>
</div>

<div class="prog-item">
  <div class="prog-time">14:10–16:00</div>
  <div class="prog-body">
    <div class="prog-title"><span class="badge badge-general">一般講演 セッションA</span></div>
    <div class="prog-sub">発表15分・質疑5分</div>
    <div class="prog-table-wrap">
      <table class="prog-table">
        <thead><tr><th>ID</th><th>時間</th><th>発表者</th><th>所属</th><th>タイトル</th><th>共同研究者（所属）</th></tr></thead>
        <tbody>
          <tr><td class="idg-cell">A01</td><td>14:10–14:30</td><td>浅谷 公威</td><td>東大</td><td>IGOsの政策文書が引用する科学論文の少数の研究者への集中</td><td>岩田 由理恵、友清 雄太、Basil Mahfouz、鎗目 雅、坂田 一郎</td></tr>
          <tr><td class="idg-cell">A02</td><td>14:30–14:50</td><td>宮部 裕貴</td><td>NISTEP／東大</td><td>知識はどのように波及するのか？ — ノーベル受賞論文に対する引用を事例として —</td><td>川崎 正貴（筑波大学／NISTEP）、原 泰史（神戸大学／NISTEP）、赤池 伸一（NISTEP）</td></tr>
          <tr><td class="idg-cell">A03</td><td>14:50–15:10</td><td>池田 周平</td><td>筑波大</td><td>特許共起ネットワークを通じたプラットフォーム技術の固有性の定量化</td><td>吉田 光男（筑波大学）</td></tr>
          <tr><td class="idg-cell">A04</td><td>15:20–15:40</td><td>横山 重俊</td><td>NII</td><td>meta-AI と AI Agent 群による AI for Math の試作：Chebyshev bias研究を題材に</td><td>青木 美穂（島根大学）</td></tr>
          <tr><td class="idg-cell">A05</td><td>15:40–16:00</td><td>小作 貴司</td><td>東大</td><td>論文・特許の共通概念空間構築によるScience–Technology Linkageの可視化</td><td>浅谷 公威、西本 恵太、坂田 一郎</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div>

<div class="prog-item">
  <div class="prog-time">16:00–16:45</div>
  <div class="prog-body">
    <div class="prog-title"><span class="badge badge-invited">招待講演③</span></div>
    <div class="talk-card">
      <div class="speaker">近藤 潤 氏（文部科学省 科学技術・学術政策局 研究開発戦略課長）</div>
      <div class="talk-title">行政官から見た「Science of Science」</div>
      <span class="lbl">要旨</span>
      <div class="talk-abstract">「科学」は観測可能か、そして介入の影響は予測可能か。STI政策の検討の前提として、科学や研究活動を取り巻く状況をどのように認識するか、政策課題の設定が最重要である。第８期STI基本計画に向けて、当研究会の多様な参加者との対話を楽しみにしています。</div>
    </div>
  </div>
</div>

<div class="prog-item">
  <div class="prog-time">16:45–17:00</div>
  <div class="prog-body"><div class="prog-title">休憩</div></div>
</div>

<div class="prog-item">
  <div class="prog-time">17:00–18:20</div>
  <div class="prog-body">
    <div class="prog-title"><span class="badge badge-general">一般講演 セッションB</span></div>
    <div class="prog-sub">発表15分・質疑5分</div>
    <div class="prog-table-wrap">
      <table class="prog-table">
        <thead><tr><th>ID</th><th>時間</th><th>発表者</th><th>所属</th><th>タイトル</th><th>共同研究者（所属）</th></tr></thead>
        <tbody>
          <tr><td class="idg-cell">B01</td><td>17:00–17:20</td><td>佐原 恭平</td><td>COTEN</td><td>間主観性と引用</td><td>河島 泰斗（COTEN）</td></tr>
          <tr><td class="idg-cell">B02</td><td>17:20–17:40</td><td>松野 大河</td><td>京大</td><td>サーベイ・実験と計算機科学の組み合わせによる新たなScience of Scienceの可能性</td><td></td></tr>
          <tr><td class="idg-cell">B03</td><td>17:40–18:00</td><td>今井 泰佑</td><td>阪大</td><td>A Framework for Reproducible Experiments in the Lab</td><td>今井 倫子（大阪大学）、下平 勇太（信州大学）</td></tr>
          <tr><td class="idg-cell">B04</td><td>18:00–18:20</td><td>林 斐子</td><td>筑波大</td><td>科研費データを用いた研究生産性の男女差に関する予備調査</td><td>吉田 光男（筑波大学）</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div>

<div class="prog-item">
  <div class="prog-time">18:20–18:35</div>
  <div class="prog-body">
    <div class="prog-title">SciSci研究会からのお知らせ2・閉会挨拶</div>
  </div>
</div>

<p style="margin-top:32px; font-size:0.85em; color:#888; text-align:center;">
  念のため、旧プログラム（Google ドキュメント版）も残しています →
  <a href="https://docs.google.com/document/d/1swVCdtPq6k2FxvjSOWRu_694QkcQW4MOk3A_5UHU_KA/edit?usp=sharing" target="_blank" rel="noopener" style="color:#888; text-decoration:underline;">こちら</a>
</p>
