# sol-checkin-liff — どれが本番か

| フォルダ / ファイル | 状態 | 中身 |
|---|---|---|
| `checkin/` | **【本番】** | チェックイン v4（2026-10-12〜）。LIFF `2008938862-AlepUDEH`（チェックイン）・`2008938862-M5N6CXP3`（現地払い）の向き先 |
| `sol-pay/` | **【本番・SoL Pay】** | SoL Pay。触らない |
| `checkin-trial/` | 【試運転】 | 更新を試すための画面（会員は使わない）。LIFF `2008938862-2Zm9aPCI`・`2008938862-bBbSTyiI` |
| `index.html` | 【保管】 | 旧チェックイン（〜2026-10-12）。切り戻し用に残しているだけ。直さない |
| `cash_checkin/` | 【保管】 | 旧現地払い（〜2026-10-12）。切り戻し用に残しているだけ。直さない |

切り戻し：LINE Developers で上の2つの本番 LIFF のエンドポイントURLを、旧の `index.html` / `cash_checkin/` に戻す。
