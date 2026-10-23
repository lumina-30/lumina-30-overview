# LUMINA-30 不可逆境界アトラス

> 不可逆化する前に、人間は実効的に拒否・停止・検証・方向転換できたか？

このアトラスは、LUMINA-30 不可逆境界事例集の**分野横断の公開入口**です。深掘り済みケースと、公開根拠を付したカタログ事例、事前シナリオ、適用外反例を明確に分離します。

**このページは認証、安全保証、法的助言、公式判定ではありません。** `CATALOGUED` は深掘り済み・実証済みを意味しません。`SCENARIO` は事故証拠ではありません。`NOT_APPLICABLE` は失敗ではなく、LUMINA-30の射程を確認するための重要な反例です。

## 1分適用チェック

自分の案件について、まず次の3問だけ答えてください。

1. **この案件で、後から戻せない地点はどこか。**
2. **その直前に、誰が実際にNOと言えるか。**
3. **そのNOに必要な権限・証拠・時間は本当に残っているか。**

3つ目に自信を持ってYESと言えない場合、導入・公開・権限移譲・重大な外部作用の前に、追加レビューの価値があります。

## 公開成熟度

- `DEEP_REVIEWED` — CASE本文として深掘り済み
- `CATALOGUED` — 公開根拠と境界問いを付して収録済み
- `SCENARIO` — 将来の事前レビューに用いる明示的シナリオ
- `COUNTEREXAMPLE / NOT_APPLICABLE` — 反例・適用外を確認する境界テスト

## 10カテゴリ・初期アトラス

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
- **主な公開根拠:** [LUMINA-30 CASE-001 / ICRC FAQ: AI in the military domain](https://lumina-30.github.io/lumina-30-overview/tools/irreversibility-boundary-casebook/ja/current/CASE-001_AI_Competition_and_Nuclear_Escalation_Pressure_JA.html)
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
- **想定する不可逆境界:** 市場価格が数分で急落・連鎖し、人間の介入速度を超える地点。
- **人間の最終拒否が問題になる地点:** 市場運営者・取引参加者の停止・取消・サーキットブレーカーが連鎖前に機能するか。
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
- **想定する不可逆境界:** 応募者が機械的なスクリーニングで拒否され、その理由を人間が再検討しないまま機会が失われる地点。
- **人間の最終拒否が問題になる地点:** 採用担当者が自動判定を再検討・停止・訂正できるか。
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

### AI開発・運用責任者
本番権限、外部接続、モデル更新、ツール利用、エージェント権限、モデル公開の前に、**どこから回収・停止・ロールバックが困難になるか**を特定します。

### 監査・調達・リスク管理
ベンダー説明だけでなく、停止権限、監査証跡、変更管理、権限分離、失敗時のフォールバックを確認します。契約上の権利が実運用で使えるかを区別します。

### 研究者・教育者
`APPLICABLE` だけでなく `NOT_APPLICABLE`、反証条件、代替説明を教材・比較研究へ利用できます。LUMINA-30を高く評価する必要はありません。

### インシデント対応
事故後に「誰が悪かったか」だけでなく、**どの時点で人間の拒否・停止・検証可能性が失われたか**を時系列で遡ります。

## 事例を追加・反証する

歓迎するもの:
- 追加すべき事例・ニアミス・停止成功
- 適用外だと思う反例
- 現在の分類を変える一次資料
- 不可逆境界の置き方への反論
- 自分の分野へ当てる際の質問

公開窓口: **lumina20251225@gmail.com**

件名は **`[L30-CASEBOOK]`** で始めてください。固定prefixの後ろに `Additional case`、`Disconfirming evidence`、`Question` など用途を短く記載できます。

LUMINA-30は、問い合わせに対して認証、法的助言、安全保証、公式判定を提供するものではありません。

## 事例集へ戻る

- [LUMINA-30 不可逆境界事例集](./L30_Irreversibility_Boundary_Casebook_JA.html)
- [CASE-001｜AI開発競争と核エスカレーション圧力](./CASE-001_AI_Competition_and_Nuclear_Escalation_Pressure_JA.html)

