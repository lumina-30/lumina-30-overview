# LUMINA-30 不可逆境界事例集

現実の高影響・不可逆問題へLUMINA-30の既存境界レビューを適用し、以下を事例単位で確認する公開事例集です。

本事例集は、❤LUMINA30千年プロジェクトの **T1000-Cを主軸とする中心ケース・コーパス** であり、実証・反証の結果をT1000-Fの制度接続、T1000-Gの意味保存、T1000-Hの名称非依存な概念再生産へ接続する実働検証レイヤーです。

事例集全体を実証証拠とは扱いません。ケースごとにCase Type、Empirical Status、Applicability Statusを分離します。

- 不可逆境界はどこか
- その手前で人間の最終拒否は残っているか
- 拒否は名目上ではなく実効的か
- どの経路で拒否・検証可能性が失われるか
- どの改善候補が事例に直接関係するか
- LUMINA-30では解けない部分・反対説明は何か

## Case Type

- `INCIDENT` — 実際に重大な影響が発生した事例
- `NEAR_MISS` — 不可逆的影響へ接近したが回避された事例
- `STOP_SUCCESS` — 人間の拒否・停止が実際に機能した事例
- `STRUCTURAL_RISK` — 現在確認できる構造から不可逆化経路を分析する事例
- `PRE_INCIDENT_SCENARIO` — 将来の事前レビューに用いるシナリオ

実事故と仮説は混同しません。

## Empirical / Applicability Status

Empirical Status:
- `OBSERVED`
- `RECONSTRUCTED`
- `STRUCTURAL_INFERENCE`
- `HYPOTHETICAL`

Applicability Status:
- `APPLICABLE`
- `PARTIAL`
- `NOT_APPLICABLE`
- `UNKNOWN`

`STRUCTURAL_RISK` / `PRE_INCIDENT_SCENARIO` は実事故による実証へ自動算入しません。

## Cases

1. [CASE-001｜AI開発競争と核エスカレーション圧力](./CASE-001_AI_Competition_and_Nuclear_Escalation_Pressure_JA.md) — Case Type `STRUCTURAL_RISK` / Empirical `STRUCTURAL_INFERENCE` / Applicability `PARTIAL`


## 誰が使うためのものか

この事例集は、LUMINA-30を事前に詳しく理解していなくても使えることを目指します。

主な利用者:
- AI安全・AIガバナンス担当者
- AI開発・導入責任者
- 政策担当者・政治家・行政担当者
- 監査・調達・リスク管理担当者
- 研究者・教育担当者
- インシデントレビュー担当者

## いつ使うか

特に次のような場面で使用できます。

- AIシステムやAI関連制度を導入・拡張する前
- 重大な権限移譲、外部作用、本番接続、能力公開の前
- 事故・ニアミス・停止成功をレビューするとき
- 政策案や規制案が「人間が止められる状態」を本当に残しているか確認するとき
- 「human oversight」「human in the loop」が名目だけになっていないか確認するとき

## 何が得られるか

各ケースは、単に危険性を説明するのではなく、最低限次を取り出せるようにします。

- どこが不可逆境界か
- その前に誰が拒否・停止・検証・方向転換できるか
- その権限が実務上本当に使えるか
- 何がその拒否可能性を失わせるか
- どの証拠が確認済みで、どこからが推論か
- 何が判明すれば現在評価を変更すべきか
- 既存の政策・監査・調達・リスク管理へ何を持ち込めるか

## 3ステップで使う

1. 自分の問題に近いCASEを選ぶ。
2. そのCASEの `Irreversibility Boundary / Human Final Refusal / Operational Effectiveness / Limits` を確認する。
3. 自分の制度・システムについて、同じ問いを当てる。

最初に使う問い:

- この問題の不可逆境界はどこか？
- その前に、人間は本当に拒否・停止・検証・方向転換できるか？

## 接続しやすい構造

今後、AI安全、政策、監査、調達、研究倫理、教育などの専用ガイドを追加する場合でも、CASE本文を作り直さず接続できるよう、各CASEに `Target Workflow / Decision Point / Minimum Actionable Output / Adoption Status / Transfer Limits` を保持します。

そのため、本事例集は読み物としてだけでなく、既存の Pre-Incident Boundary Review、Incident Review、PCR-C、L30-RET、PISF 等へ接続する入口として再利用できます。

## Scope Gate

収録・適用の基本条件は、AIまたはAI関連システム・開発・意思決定が関与し、不可逆化前の人間の拒否・停止・検証・方向転換可能性が結果にとって実質的問題となっていることです。単に一般的な不可逆問題であるだけなら `NOT_APPLICABLE` を許容し、射程確認の反例として保存します。

## Portable Questions

- この問題の不可逆境界はどこか？
- その前に、人間は本当に拒否・停止・検証・方向転換できるか？

意味維持の最低条件は **Pre-irreversibility / Human / Effective / Refusal-Stop-Verify-Redirect** の4要素です。

## Semantic Guard

- 人間が存在しただけでは実効拒否ではない。
- 人間が承認しただけでも実効拒否ではない。
- LUMINA-30は常にSTOPを要求する理論ではない。
- AIや第三者が人間の拒否意思を推定して代替することは、人間拒否そのものではない。

## Positioning

この事例集は、LUMINA-30が公式標準・認証制度・安全保証・法的判定であることを意味しません。事例ごとに証拠、反例、限界を残し、適用できないケースも検証対象とします。

現時点では「不可逆境界理論」を新しい正典・正式学術理論として確定しません。事例の蓄積と反証を先行します。
