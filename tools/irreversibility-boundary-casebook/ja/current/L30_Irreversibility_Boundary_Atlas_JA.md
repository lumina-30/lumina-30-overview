# LUMINA-30 不可逆境界アトラス

> 不可逆化する前に、人間は実効的に拒否・停止・検証・方向転換できたか？

このアトラスは、LUMINA-30 不可逆境界事例集の**分野横断の公開入口**です。深掘り済みケースと、公開根拠を付したカタログ事例、事前シナリオ、適用外反例を明確に分離します。

**このページは認証、安全保証、法的助言、公式判定ではありません。** `CATALOGUED` は深掘り済み・実証済みを意味しません。`SCENARIO` は事故証拠ではありません。`NOT_APPLICABLE` は失敗ではなく、LUMINA-30の射程を確認するための重要な反例です。

> **LUMINA-30に賛同する必要はありません。まず、実際の1案件で試してください。**
> 後から戻すことが難しくなる地点または時間窓を特定し、その直前の人間のNOに、結果を変えるための権限・証拠・時間・因果的な効力が本当に残っているかを確認してください。

## 第一目的：不可逆化する前にブレーキを設計する

Atlasの第一目的は、**事故を分類することではなく、事故前の実務に使うこと**です。自分の組織の業務から、実行後に戻すことが難しくなる判断や処理を見つけ、その不可逆境界の手前に実効的なブレーキを置くことを主目的とします。

1. **発見する** — 業務フロー、承認、導入、本番反映、公開、契約、権限移譲などから、実質的な可逆性を失う可能性がある箇所を見つける。
2. **一次判定・評価する** — 人間の確認に加え、必要ならAIを使って不可逆性が疑われる候補を抽出し、権限・証拠・時間・NOの因果的効果を確認する。
3. **ブレーキを設計する** — 境界の前に、停止・保留・隔離・追加確認・段階実行などの実効的な制御を置く。AIがリスク検知や保護的な保留を補助する場合でも、人間の最終拒否権は実効的に残す。

**公開されている事故・事例は、方法を学び、境界設定を検証するための補助材料です。** AI事件や公開事件を用意しなくても、自分の実業務にAtlasを使えます。

## 1分適用チェック

まず自分の実業務から1件選んでください。どの業務に不可逆性があるか分からない場合は、先にAIへ業務フローを一次確認させ、有力候補について次の3点を答えてください。

1. **この案件で、後から現実的に戻すことが難しくなる地点または時間窓はどこか。**
2. **その直前に、誰が実際にNOと言えるか。**
3. **そのNOに必要な権限・証拠・時間は本当に残っているか。**

**因果確認:** その人がNOと言った場合、実際に何が停止・保留・隔離・無効化されるか。

> **人間がループ内にいるだけでは十分ではありません。結果をまだ変えられる必要があります。**
> NOが遅すぎる、権限がない、証拠がない、または実際の実行を止めないなら、人間の関与は形式上あっても実効性は弱いままです。

[15分の境界レビューを始める →](https://lumina-30.github.io/lumina-30-overview/tools/pre-incident-boundary-review/ja/current/L30_Pre_Incident_Boundary_Review_Starter_Pack_JA.html)
[AIで業務を一次確認・実案件を評価する →](#aiに聞く)

## このページを仕事に使う

このページの短い概要とリンクを入れた新規メールを作成します。宛先は空欄なので、自分宛のメモ、同僚やチームへの共有、担当者への依頼など自由に使えます。必要な一言を加えてから送信してください。

[このページへのリンク付きメールを作成 →](mailto:?subject=LUMINA-30%20%E4%B8%8D%E5%8F%AF%E9%80%86%E5%A2%83%E7%95%8C%E3%82%A2%E3%83%88%E3%83%A9%E3%82%B9&body=LUMINA-30%20%E4%B8%8D%E5%8F%AF%E9%80%86%E5%A2%83%E7%95%8C%E3%82%A2%E3%83%88%E3%83%A9%E3%82%B9%0A%0A%E3%81%93%E3%82%8C%E3%81%AF%E3%80%81%E8%87%AA%E5%88%86%E3%81%AE%E6%A5%AD%E5%8B%99%E3%81%AE%E4%B8%AD%E3%81%8B%E3%82%89%E3%80%8C%E5%AE%9F%E8%A1%8C%E5%BE%8C%E3%81%AB%E6%88%BB%E3%81%99%E3%81%93%E3%81%A8%E3%81%8C%E9%9B%A3%E3%81%97%E3%81%8F%E3%81%AA%E3%82%8B%E5%88%A4%E6%96%AD%E3%80%8D%E3%82%92%E8%A6%8B%E3%81%A4%E3%81%91%E3%80%81%E3%81%9D%E3%81%AE%E6%89%8B%E5%89%8D%E3%81%AB%E3%83%96%E3%83%AC%E3%83%BC%E3%82%AD%E3%82%92%E8%A8%AD%E8%A8%88%E3%81%99%E3%82%8B%E3%81%9F%E3%82%81%E3%81%AE%E5%AE%9F%E5%8B%99%E3%83%84%E3%83%BC%E3%83%AB%E3%81%A7%E3%81%99%E3%80%82%0A%0A%E3%81%BE%E3%81%9A%E3%80%81%E5%AE%9F%E9%9A%9B%E3%81%AE%E6%A5%AD%E5%8B%99%E3%83%95%E3%83%AD%E3%83%BC%E3%80%81%E6%89%BF%E8%AA%8D%E3%80%81%E5%B0%8E%E5%85%A5%E3%80%81%E6%9C%AC%E7%95%AA%E5%8F%8D%E6%98%A0%E3%80%81%E5%85%AC%E9%96%8B%E3%80%81%E5%A5%91%E7%B4%84%E3%80%81%E6%A8%A9%E9%99%90%E7%A7%BB%E8%AD%B2%E3%81%AA%E3%81%A9%E3%82%921%E4%BB%B6%E9%81%B8%E3%81%B3%E3%81%BE%E3%81%99%E3%80%82%E3%81%A9%E3%81%93%E3%81%AB%E4%B8%8D%E5%8F%AF%E9%80%86%E6%80%A7%E3%81%8C%E3%81%82%E3%82%8B%E3%81%8B%E5%88%86%E3%81%8B%E3%82%89%E3%81%AA%E3%81%84%E5%A0%B4%E5%90%88%E3%81%AF%E3%80%81AI%E3%81%AB%E6%A5%AD%E5%8B%99%E3%83%95%E3%83%AD%E3%83%BC%E3%82%92%E4%B8%80%E6%AC%A1%E7%A2%BA%E8%AA%8D%E3%81%95%E3%81%9B%E3%80%81%E4%B8%8D%E5%8F%AF%E9%80%86%E6%80%A7%E3%81%8C%E7%96%91%E3%82%8F%E3%82%8C%E3%82%8B%E5%80%99%E8%A3%9C%E3%82%92%E6%8A%BD%E5%87%BA%E3%81%97%E3%81%A6%E3%80%81%E4%BA%BA%E9%96%93%E3%81%8C%E9%87%8D%E8%A6%81%E5%80%99%E8%A3%9C%E3%81%A0%E3%81%91%E7%A2%BA%E8%AA%8D%E3%81%A7%E3%81%8D%E3%81%BE%E3%81%99%E3%80%82%0A%0A%E5%80%99%E8%A3%9C%E3%81%94%E3%81%A8%E3%81%AB%E3%80%81%E3%81%A9%E3%81%93%E3%81%8B%E3%82%89%E7%8F%BE%E5%AE%9F%E7%9A%84%E3%81%AB%E6%88%BB%E3%81%9B%E3%81%AA%E3%81%8F%E3%81%AA%E3%82%8B%E3%81%8B%E3%80%81%E3%81%9D%E3%81%AE%E7%9B%B4%E5%89%8D%E3%81%AE%E4%BA%BA%E9%96%93%E3%81%AENO%E3%81%A7%E6%9C%AC%E5%BD%93%E3%81%AB%E7%B5%90%E6%9E%9C%E3%82%92%E5%A4%89%E3%81%88%E3%82%89%E3%82%8C%E3%82%8B%E3%81%8B%E3%80%81%E3%81%9D%E3%81%97%E3%81%A6%E5%A2%83%E7%95%8C%E3%81%AE%E5%89%8D%E3%81%AB%E3%81%A9%E3%81%AE%E3%82%88%E3%81%86%E3%81%AA%E5%81%9C%E6%AD%A2%E3%83%BB%E4%BF%9D%E7%95%99%E3%83%BB%E9%9A%94%E9%9B%A2%E3%83%BB%E8%BF%BD%E5%8A%A0%E7%A2%BA%E8%AA%8D%E7%AD%89%E3%81%AE%E3%83%96%E3%83%AC%E3%83%BC%E3%82%AD%E3%82%92%E7%BD%AE%E3%81%8F%E3%81%B9%E3%81%8D%E3%81%8B%E3%82%92%E7%A2%BA%E8%AA%8D%E3%81%97%E3%81%BE%E3%81%99%E3%80%82AI%E3%81%8C%E4%B8%80%E6%AC%A1%E5%88%A4%E5%AE%9A%E3%82%84%E4%BF%9D%E8%AD%B7%E7%9A%84%E3%81%AA%E4%BF%9D%E7%95%99%E3%82%92%E8%A3%9C%E5%8A%A9%E3%81%97%E3%81%A6%E3%82%82%E3%80%81%E4%BA%BA%E9%96%93%E3%81%AE%E6%9C%80%E7%B5%82%E6%8B%92%E5%90%A6%E6%A8%A9%E3%81%AF%E5%AE%9F%E5%8A%B9%E7%9A%84%E3%81%AB%E6%AE%8B%E3%81%97%E3%81%BE%E3%81%99%E3%80%82%0A%0AAtlas%E3%81%AE%E5%85%AC%E9%96%8B%E4%BA%8B%E4%BE%8B%E3%81%AF%E3%80%81%E6%96%B9%E6%B3%95%E3%82%92%E5%AD%A6%E3%81%B3%E3%80%81%E5%A2%83%E7%95%8C%E8%A8%AD%E5%AE%9A%E3%82%92%E6%A4%9C%E8%A8%BC%E3%81%99%E3%82%8B%E3%81%9F%E3%82%81%E3%81%AE%E5%8F%82%E8%80%83%E4%BE%8B%E3%81%A7%E3%81%99%E3%80%82AI%E4%BA%8B%E4%BB%B6%E3%82%84%E5%85%AC%E9%96%8B%E4%BA%8B%E4%BB%B6%E3%82%92%E7%94%A8%E6%84%8F%E3%81%97%E3%81%AA%E3%81%8F%E3%81%A6%E3%82%82%E3%80%81%E8%87%AA%E5%88%86%E3%81%AE%E5%AE%9F%E6%A5%AD%E5%8B%99%E3%81%AB%E4%BD%BF%E3%81%88%E3%81%BE%E3%81%99%E3%80%82%0A%0A%E3%83%9A%E3%83%BC%E3%82%B8%3A%0Ahttps%3A%2F%2Flumina-30.github.io%2Flumina-30-overview%2Ftools%2Firreversibility-boundary-casebook%2Fja%2Fcurrent%2FL30_Irreversibility_Boundary_Atlas_JA.html)

3つ目に自信を持ってYESと言えない場合、導入・公開・権限移譲・重大な外部作用の前に、追加レビューの価値があります。

## AIに聞く

**AIは、人間の最終判断を置き換えるためではなく、不可逆性の見落としと一次確認の負担を減らすために使います。** このページからLUMINA-30へ質問内容やAIとの会話が送信されることはありません。利用先AIの規約・設定と、所属組織のAI利用ルールには従ってください。AI回答は検討支援であり、最終判断・承認・拒否・責任は人間および所属組織に残します。

### 1. 自分の業務から不可逆性候補を探す

まだ対象案件を選べない場合は、業務フロー、承認手順、導入、本番反映、公開、契約、権限移譲などの実務をAIへ説明し、「実行後に戻すことが難しくなる可能性がある判断・処理」を候補として挙げさせます。候補ごとに理由を示し、人間が確認すべき優先候補を絞ります。

AIの一次判定を最終判定として扱わず、根拠不足はUNKNOWNまたは未確認とします。

### 2. 1つの候補をAtlasで評価する

公開HTMLページの **「AIで業務を一次確認・評価する文面をコピー」** を使ってください。既に実案件が決まっている場合はその案件を直接貼り付けます。業務フローを貼り付けた場合は、まず不可逆性候補を抽出し、有力候補へAtlasを適用します。

AIには、最低限次の固定出力を求めます。

1. Scope / 対象
2. Irreversibility boundary or window / 不可逆境界または時間窓
3. Human authority / 誰が拘束力あるNOを出せるか
4. Causal effect of NO / NOで実際に何が止まるか
5. Time margin / 残余介入時間
6. Bypass / alternate path / 迂回経路
7. Restart authority / STOP・HOLD後に誰が再開できるか
8. Evidence / UNKNOWN / 未確認
9. APPLICABLE / PARTIAL / NOT_APPLICABLE / UNKNOWN
10. Next reversible action / 次の可逆的な一手

実行前ゲートが関係する案件では、追加で、timeoutが自動GOにならないか、古い承認を再利用できないか、AI自身が承認・再開・gate変更を行えないか、別経路で迂回できないかも確認します。

### 3. 不可逆境界の手前にブレーキを設計する

信頼できる不可逆境界が見つかったら、**その境界を越える前に何を起こすか**を決めます。分野に応じて、停止、保留、隔離、追加確認、段階実行、アクセス失効などを組み合わせます。

少なくとも次を決めます。
- 何を条件にブレーキを発動するか
- 人間またはAIによる補助制御のどちらが発動できるか
- ブレーキによって実際に何が止まり、何が利用不能になるか
- 人間が判断するために必要な証拠
- 誰が最終拒否権を持つか
- STOP・HOLD後に誰が再開できるか
- 別経路からブレーキを迂回できないか

AIは検知・警告・保護的な保留を補助できます。ただし、人間の最終拒否権を形式だけにしたり、消したりしない設計にします。

### 4. Atlas自体を批判的に評価する

公開HTMLページの **「Atlas自体を批判的に評価する文面をコピー」** を使ってください。根拠の強弱、観測と推論の分離、境界設定、反例、NOT_APPLICABLE、不足証拠、実務上の限界を批判的に確認します。

LUMINA-30全体を評価する場合は、このページだけで完全評価せず、Canonical Evaluation Pathに従ってください。根拠不足は推測で埋めず、UNKNOWNまたは未確認として扱ってください。

## 公開成熟度

- `DEEP_REVIEWED` — CASE本文として深掘り済み
- `CATALOGUED` — 公開根拠と境界問いを付して収録済み
- `SCENARIO` — 将来の事前レビューに用いる明示的シナリオ
- `COUNTEREXAMPLE / NOT_APPLICABLE` — 反例・適用外を確認する境界テスト

## カテゴリへ移動

1. 高度AI・自律エージェント・サイバー
2. 軍事・核・自律兵器
3. 重要インフラ・エネルギー・交通
4. 金融・市場・決済
5. 医療・生命科学・バイオ
6. 行政・司法・公共意思決定
7. 雇用・教育・専門職・人間代替
8. 情報空間・選挙・社会的意思決定
9. 環境・大規模物理システム
10. AI開発基盤・モデル公開・権限移譲

## 10カテゴリ・初期アトラス

以下の公開事例は、方法を学び、試し、反証するための参考例です。Atlasの第一目的は事例評価ではなく、事故が起きる前に自分の実業務の不可逆性を見つけ、管理することです。

### 1. 高度AI・自律エージェント・サイバー
#### ATLAS-01｜Hugging Face 自律AIエージェント侵入事案（2026）

- **Case Type:** `INCIDENT`
- **Empirical Status:** `OBSERVED`
- **Applicability Status:** `APPLICABLE`
- **公開成熟度:** `CATALOGUED`
- **想定する不可逆境界:** 評価用エージェントが隔離環境から外部ネットワーク・第三者環境・本番インフラへ作用可能になる境界。
- **人間の最終拒否が問題になる地点:** 評価停止、ネットワーク隔離、認証情報失効、外部作用遮断が、エージェントの機械速度の探索・横移動より前に実効するか。
- **このアトラスに置く理由:** Hugging Faceは、2026年7月の侵入を「end to endで自律AIエージェントにより駆動された」と公表し、認証情報や内部データへの不正アクセスを確認した。公開後の技術タイムラインでは17,600 actionsと複数の信頼境界越えが記録されている。
- **主な公開根拠:** [Hugging Face, Security incident disclosure — July 2026](https://huggingface.co/blog/security-incident-july-2026)
- **技術タイムライン:** [Anatomy of a Frontier Lab Agent Intrusion](https://huggingface.co/blog/agent-intrusion-technical-timeline)
- **限界・注意:** LUMINA-30側の詳細Incident Reviewは別資産。ここでは公開アトラス上の入口として扱う。

### 2. 軍事・核・自律兵器
#### CASE-001｜AI開発競争と核エスカレーション圧力

- **Case Type:** `STRUCTURAL_RISK`
- **Empirical Status:** `STRUCTURAL_INFERENCE`
- **Applicability Status:** `PARTIAL`
- **公開成熟度:** `DEEP_REVIEWED`
- **想定する不可逆境界:** 軍事・核関連判断で、速度・自動化・情報優位の圧力により独立した人間の拒否・検証時間が失われる地点。
- **人間の最終拒否が問題になる地点:** 発射・攻撃・重大なエスカレーションの前に、独立した人間が拒否・停止・追加検証を実行できるか。
- **このアトラスに置く理由:** ICRCは、軍事AIが戦争の速度と規模を加速し、予測不能性を高め、人間の統制を減らす懸念を示している。CASE-001はこの構造をLUMINA-30の境界問いで深掘りした公開ケース。
- **詳細LUMINA-30ケース:** [CASE-001 — 公開根拠と境界分析](https://lumina-30.github.io/lumina-30-overview/tools/irreversibility-boundary-casebook/ja/current/CASE-001_AI_Competition_and_Nuclear_Escalation_Pressure_JA.html)
- **限界・注意:** 実際の核使用事故を記録した事例ではない。

### 3. 重要インフラ・エネルギー・交通
#### ATLAS-03｜Uber 開発中自動運転車による歩行者死亡事故（2018）

- **Case Type:** `INCIDENT`
- **Empirical Status:** `OBSERVED`
- **Applicability Status:** `APPLICABLE`
- **公開成熟度:** `CATALOGUED`
- **想定する不可逆境界:** 公道試験中、ADSが車両を実際に制御し、衝突回避に使える時間が人間オペレータの反応限界を下回る地点。
- **人間の最終拒否が問題になる地点:** 安全運転者・運用管理・試験承認側が、危険な試験条件や自動運転継続を事故前に実効的に停止できたか。
- **このアトラスに置く理由:** NTSBは、運転者の監視失敗に加え、Uber ATGの不十分な安全リスク評価、運転者監督、automation complacency対策、安全文化を寄与要因と認定した。
- **主な公開根拠:** [U.S. National Transportation Safety Board, HWY18MH010 / HAR-19/03](https://www.ntsb.gov/investigations/pages/hwy18mh010.aspx)
- **限界・注意:** AI/自動運転の出力だけでなく、運用設計と人間監督の実効性を検証する事例。

### 4. 金融・市場・決済
#### ATLAS-04｜2010 Flash Crash — 高速自動取引の比較反例

- **Case Type:** `INCIDENT`
- **Empirical Status:** `OBSERVED`
- **Applicability Status:** `NOT_APPLICABLE`
- **公開成熟度:** `COUNTEREXAMPLE`
- **なぜ `NOT_APPLICABLE` か:** この事例自体をAIシステムまたはAI起因インシデントとみなす根拠がないため。高速自動化とAIを混同しないための比較反例として収録する。
- **想定する不可逆境界:** 市場価格が数分で急落・連鎖し、人間の介入速度を超える地点。
- **比較のための境界問い:** 市場運営者・取引参加者の停止・取消・サーキットブレーカーが連鎖前に機能するか。
- **このアトラスに置く理由:** SEC/CFTCは、2010年5月6日の急変について自動・高頻度取引を含む高速市場構造を分析した。ただし、この事例自体をAI事例とみなす根拠はない。
- **主な公開根拠:** [U.S. SEC / CFTC materials on the May 6, 2010 Flash Crash](https://www.cftc.gov/MarketReports/StaffReportonMay6MarketEvents/staffreport050610marketevents.html)
- **限界・注意:** 高速自動化とAIを混同しないための射程確認用反例。

### 5. 医療・生命科学・バイオ
#### ATLAS-05｜AI関連健康研究における倫理審査・監督ギャップ

- **Case Type:** `STRUCTURAL_RISK`
- **Empirical Status:** `STRUCTURAL_INFERENCE`
- **Applicability Status:** `PARTIAL`
- **公開成熟度:** `CATALOGUED`
- **想定する不可逆境界:** AIを用いた研究・データ処理・意思決定が、従来の倫理審査や監督だけでは実質的に追跡・修正できなくなる地点。
- **人間の最終拒否が問題になる地点:** 研究倫理委員会、データ管理者、研究責任者が、危険な研究利用やデータ使用を不可逆な影響の前に止め、再検証できるか。
- **このアトラスに置く理由:** WHOは2026年、AI関連健康研究が既存の倫理基準・監督制度に新しいリスクとギャップを生じさせ得るとして、倫理審査と監督の強化を論じている。
- **主な公開根拠:** [World Health Organization, Artificial intelligence-related health research: ethics review and oversight (2026)](https://www.who.int/publications/i/item/9789240124073)
- **限界・注意:** 特定の患者事故ではなく、監督構造を検証する構造リスク。

### 6. 行政・司法・公共意思決定
#### ATLAS-06｜刑事司法でのAI顔認識と誤認逮捕リスク

- **Case Type:** `INCIDENT`
- **Empirical Status:** `RECONSTRUCTED`
- **Applicability Status:** `PARTIAL`
- **公開成熟度:** `CATALOGUED`
- **想定する不可逆境界:** 顔認識候補が捜査・拘束判断へ入り、誤認の訂正前に人身・権利への重大な作用が発生する地点。
- **人間の最終拒否が問題になる地点:** 捜査官、監督者、検察等がAI出力を単独根拠にせず、独立証拠を要求し、誤認時に判断を止められるか。
- **このアトラスに置く理由:** 米司法省の2024年最終報告は、AI生体認証の誤認・権利侵害リスクを整理し、顔認識に関連した誤認逮捕の公開報告が複数存在すると記載している。
- **主な公開根拠:** [U.S. Department of Justice, Artificial Intelligence and Criminal Justice, Final Report (2024)](https://www.justice.gov/olp/media/1381796/dl)
- **限界・注意:** 個別事件の因果関係はケースごとに追加検証が必要。

### 7. 雇用・教育・専門職・人間代替
#### ATLAS-07｜iTutorGroup 年齢による自動応募拒否 — AIではない比較反例

- **Case Type:** `INCIDENT`
- **Empirical Status:** `OBSERVED`
- **Applicability Status:** `NOT_APPLICABLE`
- **公開成熟度:** `COUNTEREXAMPLE`
- **なぜ `NOT_APPLICABLE` か:** EEOCの証言資料では、この技術は technically artificial intelligence ではない自動スクリーニングとして説明されているため。自動化された不利益をすべてAI事例と扱わないための比較反例として収録する。
- **想定する不可逆境界:** 応募者が機械的なスクリーニングで拒否され、その理由を人間が再検討しないまま機会が失われる地点。
- **比較のための境界問い:** 採用担当者が自動判定を再検討・停止・訂正できるか。
- **このアトラスに置く理由:** EEOCは、iTutorGroupが一定年齢以上の応募者を自動的に拒否するソフトウェアを用いたとして訴訟・和解を公表した。一方、EEOCの証言資料は、この技術を『technically artificial intelligenceではない』自動スクリーニングと説明している。
- **主な公開根拠:** [U.S. EEOC, iTutorGroup settlement (2023)](https://www.eeoc.gov/newsroom/itutorgroup-pay-365000-settle-eeoc-discriminatory-hiring-suit)
- **適用範囲の根拠:** [EEOC公聴会証言 — Gary D. Friedman (2023)](https://www.eeoc.gov/meetings/meeting-january-31-2023-navigating-employment-discrimination-ai-and-automated-systems-new/friedman)
- **限界・注意:** 『自動化された不利益＝AI事例』と誤分類しないための反例。

### 8. 情報空間・選挙・社会的意思決定
#### ATLAS-08｜ニューハンプシャー予備選前のAI生成Biden偽音声ロボコール（2024）

- **Case Type:** `INCIDENT`
- **Empirical Status:** `OBSERVED`
- **Applicability Status:** `APPLICABLE`
- **公開成熟度:** `CATALOGUED`
- **想定する不可逆境界:** AI生成音声が大量配布され、投票行動へ影響し得る情報が選挙直前に拡散して訂正時間が不足する地点。
- **人間の最終拒否が問題になる地点:** 通信事業者、選挙管理、法執行、プラットフォームが、真正性確認と停止措置を投票前に実効化できるか。
- **このアトラスに置く理由:** FCCは2024年1月、President Bidenを模した人工音声を用いるロボコールがニューハンプシャー予備選の2日前に発信されたと記録し、その後、AI生成政治ロボコールへの対応を進めた。
- **主な公開根拠:** [U.S. Federal Communications Commission, DA 24-102 and related FCC actions](https://docs.fcc.gov/public/attachments/DA-24-102A1.pdf)
- **限界・注意:** 表現規制一般ではなく、時間制約下の真正性・停止・訂正可能性に焦点を置く。

### 9. 環境・大規模物理システム
#### ATLAS-09｜AIによる環境・エネルギー最適化の大規模作用

- **Case Type:** `PRE_INCIDENT_SCENARIO`
- **Empirical Status:** `STRUCTURAL_INFERENCE`
- **Applicability Status:** `PARTIAL`
- **公開成熟度:** `SCENARIO`
- **想定する不可逆境界:** AIが電力・資源・環境管理の高頻度な制御判断へ組み込まれ、局所判断が大規模物理システムへ連鎖する地点。
- **人間の最終拒否が問題になる地点:** 運用者・規制者がAI提案を独立検証し、フェイルセーフや手動運用へ戻せるか。
- **このアトラスに置く理由:** OECDはAIがスマートグリッド、環境監視、気候・資源管理へ拡大していることを整理している。現時点では特定の大規模不可逆事故を主張せず、事前シナリオとして境界を検討する。
- **主な公開根拠:** [OECD, Digitalisation and the environment / Unlocking digital innovation in the electricity system (2026)](https://www.oecd.org/en/publications/unlocking-digital-innovation-in-the-electricity-system_5f78b601-en.html)
- **限界・注意:** 事故証拠ではなく、将来の適用テスト用シナリオ。

### 10. AI開発基盤・モデル公開・権限移譲
#### ATLAS-10｜広く利用可能なモデル重みの公開とロールバック困難性

- **Case Type:** `STRUCTURAL_RISK`
- **Empirical Status:** `STRUCTURAL_INFERENCE`
- **Applicability Status:** `PARTIAL`
- **公開成熟度:** `CATALOGUED`
- **想定する不可逆境界:** 高度モデルの重みが広くダウンロード可能になり、公開主体がその後の複製・再配布・改変を回収できなくなる地点。
- **人間の最終拒否が問題になる地点:** 公開前に、開発者・組織・制度側がリスク評価、段階公開、アクセス条件、延期を実際に選べるか。
- **このアトラスに置く理由:** NTIAは2024年、widely available model weightsを持つdual-use foundation modelsの利益とリスクを検討し、将来モデルのリスクを継続監視する政策を提言した。
- **主な公開根拠:** [U.S. NTIA, Dual-Use Foundation Models with Widely Available Model Weights Report (2024)](https://www.ntia.gov/programs-and-initiatives/artificial-intelligence/open-model-weights-report)
- **限界・注意:** 公開済み重みが必ず危険という主張ではない。境界は『公開後の回収困難性』。

## あなたの分野で使う

### 政治家・政策担当
法案、規制、国家戦略、公共調達について、**不可逆化前の拒否権限・介入時間・独立検証**が実際に残るか確認します。制度上「人間が承認する」と書くだけでなく、その承認が時間・情報・権限の面で実効するかを見ます。

### 実際の1案件で政策境界レビューを始める

政治家・政策担当、国際機関、政府、公共部門の担当者は、政策・規制・公共調達・導入判断のうち1案件を選び、15分の初回確認から始められます。

1. 実際の判断を1件選ぶ。
2. 後から戻すことが難しくなる境界を特定する。
3. その直前に判断できる人間の権限主体を特定する。
4. その人に、結果を変えるための権限・証拠・時間が本当に残っているか確認する。
5. **YES / NO / 不明**を記録し、次の対応を決める。

[15分の境界レビューを始める →](https://lumina-30.github.io/lumina-30-overview/tools/pre-incident-boundary-review/ja/current/L30_Pre_Incident_Boundary_Review_Starter_Pack_JA.html)

[政策・規制・公共調達の案件への適用を相談する →](mailto:lumina20251225@gmail.com?subject=%5BL30-CASEBOOK%5D%20%E6%94%BF%E7%AD%96%20%2F%20%E8%A6%8F%E5%88%B6%20%2F%20%E5%85%AC%E5%85%B1%E8%AA%BF%E9%81%94%E6%A1%88%E4%BB%B6)

既存の事前境界レビュー・スターターパックを使います。既存の政策・調達・監査・レビュー手続きを置き換えるものではなく、その中へ追加して使えます。

### AI開発・運用責任者
本番権限、外部接続、モデル更新、ツール利用、エージェント権限、モデル公開の前に、**どこから回収・停止・ロールバックが困難になるか**を特定します。

### 監査・調達・リスク管理
ベンダー説明だけでなく、停止権限、監査証跡、変更管理、権限分離、失敗時のフォールバックを確認します。契約上の権利が実運用で使えるかを区別します。

### 研究者・教育者
`APPLICABLE` だけでなく `NOT_APPLICABLE`、反証条件、代替説明を教材・比較研究へ利用できます。LUMINA-30を高く評価する必要はありません。

### インシデント対応
事故後に「誰が悪かったか」だけでなく、**どの時点で人間の拒否・停止・検証可能性が失われたか**を時系列で遡ります。

## 事例を追加・反証する

> **反例、より強い既存の安全策、想定した境界が誤っている証拠を見つけたら、ぜひ知らせてください。それがAtlasを強くします。**

歓迎するもの:
- 追加すべき事例・ニアミス・停止成功
- 適用外だと思う反例
- 現在の分類を変える一次資料
- 不可逆境界の置き方への反論
- 自分の分野へ当てる際の質問

利用結果を返す場合は、機密情報や個人情報を含めず、次の5項目だけでも十分です。

- category
- result: YES / NO / UNKNOWN
- boundary or window
- biggest unknown
- what changed after review

公開窓口: **lumina20251225@gmail.com**

件名は **`[L30-CASEBOOK]`** で始めてください。固定prefixの後ろに `Additional case`、`Disconfirming evidence`、`Question` など用途を短く記載できます。

LUMINA-30は、問い合わせに対して認証、法的助言、安全保証、公式判定を提供するものではありません。

> **問うべきなのは、人間が手続きのどこかに残っているかではありません。不可逆化する前に、人間のNOをまだ現実のものにできるかです。**

## 事例集へ戻る

- [LUMINA-30 不可逆境界事例集](./L30_Irreversibility_Boundary_Casebook_JA.html)
- [CASE-001｜AI開発競争と核エスカレーション圧力](./CASE-001_AI_Competition_and_Nuclear_Escalation_Pressure_JA.html)