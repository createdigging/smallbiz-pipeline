# Small-Business Idea Pipeline

> **EN**: Eight standard startup frameworks (JTBD, Mom Test, Lean, Hooked, Sean Ellis 40%, AARRR, April Dunford, Van Westendorp) stitched into one gate-based flow — a checklist that kills a weak idea *before* you build it, cheaply. Written in Japanese below.

8 つの標準フレームワークを**原典に忠実なまま** 1 本のゲート付きパイプラインに組んだもの。「思いつき → 作りたい → 作った → なぜか売れない」の典型死を、各ゲートの関所で防ぐ。特定の個人・事業に最適化していない汎用版。どの事業ドメイン(アプリ / Web / コンテンツ / サービス / 物販)にも使える。

> 使い方: 事業アイデアを G0 から順に通す。**各ゲートで「証拠がなければ止める」を強制する**のが本体。AI アシスタントに判断させるなら「各ゲートで証拠がなければ先に進めるな」というルールとして渡すと効く。

## パイプライン全景

```
S1 発見     JTBD              — 人は製品でなく「進歩」を雇う
S2 検証     Mom Test          — 意見でなく過去の行動とコミットメントを取る
S3 構築     Lean Startup      — MVP は製品でなく検証された学習
S4 習慣化   Hooked            — Trigger → Action → Variable Reward → Investment
S5 PMF 測定 Sean Ellis 40%    — 「使えなくなったらとても残念」40% + retention 曲線
S6 成長     AARRR             — Acquisition → Activation → Retention → Referral → Revenue
S7 位置取り April Dunford     — 5+1 components(競合代替から市場カテゴリまで)
S8 価格     Van Westendorp    — WTP を 4 問で測る
```

順序はライフサイクル。ただし S7(位置取り)と S8(価格)は S3 の前に仮決めし、S5 通過後に本決めするのが実務(位置取りなしに MVP のコピーが書けず、価格なしに unit economics が組めないため)。

## S1. 発見 — Jobs to be Done(Christensen / Moesta / Ulwick)

人は機能を買わない。**生活の中の progress(進歩)を製品に「雇わせる」**。

- 分析単位は顧客属性でなく **job**(「状況 × 動機 × 望む結果」)
- スイッチを決めるのは **Forces of Progress の 4 力**:
  - **Push** — 現状への不満(離れたい力)
  - **Pull** — 新解決への魅力(引かれる力)
  - **Anxiety** — 乗り換えの不安(殺す力)
  - **Habit** — 現状の惰性(殺す力)
- Push + Pull が Anxiety + Habit を上回った時だけスイッチが起きる。機能追加は Pull しか触らない — **Anxiety を下げる(返金保証・移行支援)方が効くことが多い**
- 計器: **Switch interview**(直近で乗り換えた人に「なぜ"その日"だったか」を時系列再構成)。インタビューを使わない場合は競合レビューの 1★/5★ 分析・解約理由データ・検索クエリで push/pull を推定(精度は落ちる)

## S2. 検証 — The Mom Test(Rob Fitzpatrick)

「母親でさえ嘘をつけない聞き方」の 3 ルール:

1. 自分のアイデアの話をするな — **相手の生活**の話をしろ
2. 仮定・将来を聞くな — **過去の具体**を聞け(「最後にそれが起きた時、何をした?」)
3. 喋るな、聞け

- 捨てるべき悪データ 3 種: **お世辞 / 仮定の与太(「あったら使うと思う」)/ 要望リスト**
- 会話の締めは必ず**コミットメント要求**(金・時間・紹介)。断る具体的チャンスを与えるまでは見込み客ではない
- 本質は「インタビュー術」ではなく「**意見を信じるな、行動を信じろ**」。インタビューを使わない場合も原理は同じで、コミットメントを行動データで取る: **プレオーダー / LP のメール登録 / 有料 waitlist / 実際の課金**。「登録した・払った」だけが Yes で、いいね・DL・感想は全部お世辞側
- ただし行動データは **what しか言わない**。why(なぜ離脱したか・何と比較したか)はどこかで人間に聞かないと永久に埋まらない — これは省略の代償として自覚しておく

## S3. 構築 — Lean Startup(Eric Ries)

- **Build → Measure → Learn** ループを最速で回す。作っているのは製品ではなく**検証された学習(validated learning)**
- MVP = 「学習を最速で得られる最小の実験」。恥ずかしくない MVP は出すのが遅い
- **Innovation accounting**: 虚栄の指標(累計 DL・累計登録)でなく、行動を変えられる指標(コホート別の転換・継続)で測る
- 各ループの終わりに **pivot or persevere** を明示的に判定する(ズルズル続けるのが最悪)

## S4. 習慣化 — Hooked(Nir Eyal)

継続 = 収益の本体。4 段ループ:

1. **Trigger** — 外的(通知)から始め、内的(感情・文脈)に育てる
2. **Action** — 実行の摩擦を極小に(Fogg: 動機 × 能力 × トリガー)
3. **Variable Reward** — 報酬は**変動**させる。3 種: Tribe(社会的承認)/ Hunt(探索・獲得)/ Self(達成・熟達)
4. **Investment** — ユーザーに時間・データ・カスタマイズ・社会資本を注がせ、**やめると失うもの**を作る(ストック価値が次のトリガーを強化する)

設計チェック: 「このプロダクトの内的トリガーは何の感情か」「報酬のどれが変動しているか」「ユーザーが 30 日で蓄積するものは何か」に即答できなければ習慣設計が無い。

## S5. PMF 測定 — Sean Ellis テスト + retention 曲線

- **設問 1 つ**: 「このプロダクトが使えなくなったらどう感じますか?」— とても残念 / やや残念 / 残念でない
- **「とても残念」が 40% 超え**が PMF の分水嶺。ただし対象は**直近 2 週間で 2 回以上使ったユーザーに限定**(全員に聞くと薄まる)
- **Superhuman PMF Engine**(Rahul Vohra): 40% 未達でも捨てない — ①「とても残念」と答えた層のペルソナで**セグメントを絞り直す**(製品を変えずに数字が上がる)②「やや残念」層が引っかかる障害だけ潰す ③「とても残念」層が愛する核を伸ばす、のループ
- **retention 曲線が最強の計器**: コホートの継続率を日次でプロット。**下がり続ける = 穴の空いたバケツ(PMF なし)。どこかで平らになる = その高さが retained core = 本当に欲しがっている層の実寸**。サーベイを打てない規模でも曲線は嘘をつかない
- 実装: サーベイはアプリ内 1 問(モーダル 1 タップ)で足りる。インタビュー不要

## S6. 成長 — AARRR / Pirate Metrics(Dave McClure)

ファネル 5 段。**どこが詰まっているかを特定してから、その 1 段だけ直す**:

| 段 | 問い | 代表指標 |
|---|---|---|
| Acquisition | どこから来るか | チャネル別流入 |
| Activation | 最初の価値体験に到達したか | オンボ完了率・aha moment 到達率 |
| Retention | 戻ってくるか | D1/D7/D30、曲線の平坦化 |
| Referral | 人を連れてくるか | 招待送信率・k 係数 |
| Revenue | 払うか | 転換率・ARPU・LTV |

- **North Star Metric を 1 つ**決める(提供価値に直結する行動指標)。AARRR はその診断系であってダッシュボード装飾ではない
- 順序の罠: Acquisition に金を注ぐ前に Retention を直す(穴の空いたバケツに水を注がない)
- **配信チャネルは構築前に 1 つ確定させる**。「作ってから考える」が最頻死因

## S7. 位置取り — April Dunford(Obviously Awesome)

5+1 コンポーネントを**この順で**流す(順序が本体):

1. **Competitive alternatives** — 自分がいなければ客は何をするか(「Excel で我慢」「何もしない」も競合)
2. **Unique attributes** — 代替に無くて自分にある能力
3. **Value + proof** — その能力が生む顧客価値と、その証拠
4. **Target market** — その価値を最も強く感じるセグメント
5. **Market category** — 価値が自明になる「棚」を選ぶ(棚を変えると同じ製品の意味が変わる)
6. **(+1)Relevant trends** — 今この話が重要になる追い風

出力はストア説明文・LP・スクショ 1 枚目・paywall コピーの全てに反映する。位置取りが決まっていない文言は書けないはず — 書けてしまうなら位置取りが空。

## S8. 価格 — Van Westendorp PSM

WTP(支払意思額)を 4 問で測る:

1. 高すぎて検討外になるのはいくらから?
2. 安すぎて品質を疑うのはいくらから?
3. 高いが検討の余地があるのはいくら?
4. お買い得だと感じるのはいくら?

4 曲線の交点から受容価格帯(RAI/OPP)を得る。

- サーベイを打てない場合の代替: **価格 A/B(paywall 実験)**で実測する。意思より行動の方が信用できるという意味では、むしろ本命
- サブスクの実務ベンチ(RevenueCat / Adapty): Day1 paywall 表示率 80% 以上を狙う / trial は 5-9 日が主流・trial→課金の中央値 ≈ 45% / **hard paywall の課金転換は freemium の数倍**(価値を見た人だけが来る構造)/ 「いつ課金されるか」を明示するタイムライン型 paywall は開始・転換とも改善
- 価格は一度置いて終わりでなく、価値・パッケージ・paywall・プロモを回し続ける(Subscription Value Loop)

## ゲート付き統合フロー

```
G0 発見       job と 4 力を 1 枚に書く(S1)
    │ progress が言語化できない → 進まない
G1 需要の証拠 コミットメントを取る(S2: プレオーダー/LP登録/課金 — 意見は数えない)
    │ 証拠ゼロ → 殺す(構築前なら無料)
G2 配信確定   チャネルを 1 つ決めてから着工(S6)
    │ 決まらない → 着工しない
G3 構築       MVP = 最小の学習実験。位置取り(S7)と価格(S8)は仮決めして同梱
G4 初期ユーザー 手で集める(スケールしないことをする)
G5 ★PMF★    40% テスト(S5、絞ったセグメントで)+ retention 曲線の平坦化
    │ 曲線が下がり続ける → pivot or kill(S3 の判定を明示的に)
G6 成長       AARRR で詰まりを特定 → 位置取り・価格を本決めして最適化(S6-S8)
G7 拡大       効いたチャネル・セグメントに追加投資
```

## 出典

- Paul Graham — [Do Things that Don't Scale](https://www.paulgraham.com/ds.html)
- Bob Moesta / Christensen — [JTBD & Forces of Progress](https://jobstobedone.org/)
- Rob Fitzpatrick — [The Mom Test](https://www.momtestbook.com/)
- Eric Ries — The Lean Startup
- Nir Eyal — [Hooked Model](https://www.nirandfar.com/how-to-manufacture-desire/)
- Sean Ellis / Rahul Vohra — [Superhuman PMF Engine](https://review.firstround.com/how-superhuman-built-an-engine-to-find-product-market-fit/)
- Dave McClure — [AARRR Pirate Metrics](https://www.productcompass.pm/p/aarrr-pirate-metrics)
- April Dunford — Obviously Awesome
- Van Westendorp PSM / [RevenueCat paywall guide](https://www.revenuecat.com/blog/growth/guide-to-mobile-paywalls-subscription-apps/) / [Adapty trial conversion](https://adapty.io/blog/trial-conversion-rates-for-in-app-subscriptions/)

## License

各フレームワークの原典は各著者に帰属。本ドキュメント(統合・記述)は MIT License。
