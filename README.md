# newapp

個人管理リポジトリ（Private）。勤怠管理PWAと業務システム群の正本。

## 構成
| パス | 内容 | 公開 |
|---|---|---|
| `docs/` | 勤怠管理PWA（GitHub Pages 配信元：main /docs） | Pages経由で公開 |
| `projects/order-management/` | 受注管理システム | 非公開 |
| `projects/shipping-inspection/` | 出荷検査照合システム | 非公開 |
| `projects/parts-management/` | 部品管理 | 非公開 |
| `projects/delay-notice/` | 遅れ連絡システム | 非公開 |
| `projects/kanban-materials/` | 副資材かんばん管理システム | 非公開 |
| `projects/minutes/` | 議事録システム | 非公開 |
| `projects/material-order/` | MaterialOrder システム | 非公開 |

## 関連リポジトリ
- `sijiirai-app`：指示品依頼アプリ
- `skgame`：オリジナルゲーム

## 運用ルール
- 正本はこのリポジトリ。claude.ai Projects 側は参照用
- `docs/` 以外に公開したいファイルを置かない（Pages 配信対象は `docs/` のみ）
- Collaborator 追加禁止（勤怠と業務が同居しているため）。共有が必要になったら `git subtree split --prefix=projects/<slug>` で別リポジトリへ切り出す
- APIキー・トークン・GASデプロイURL等の機密はコミットしない
