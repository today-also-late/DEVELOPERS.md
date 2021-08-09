# DEVELOPERS.md
## Commit Message Guidelines
- feat: 新しい機能
- fix: バグの修正
- docs: ドキュメントのみの変更
- style: 空白、フォーマット、セミコロン追加など
- refactor: 仕様に影響がないコード改善(リファクタ)
- perf: パフォーマンス向上関連
- test: テスト関連
- chore: ビルド、補助ツール、ライブラリ関連
- ※コミットログにはwhyを書く

## branch-rules
- 新しい機能のブランチの場合 feat-(issue_number) 例 (feat-1-create-userpage)
- バグの修正 fix-(issue_number)
- ドキュメントのみの変更 docs-(issue_number)
- 空白、フォーマット、セミコロン追加など style-(issue_number)
- 仕様に影響がないコード改善(リファクタ)refactor-(issue_number)
- パフォーマンス向上関連 perf-(issue_number)
- テスト関連 test-(issue_number)
- ビルド、補助ツール、ライブラリ関連 chore-(issue_number)

## TailwindCSS
- cheetsheet (https://nerdcave.com/tailwind-cheat-sheet)

## Atomic Design-rules
- Organisms以上の単位のコンポーネントは「機能としての役割」は持たず「レイアウトとしての役割」を持つ (単一責任の原則)
- 「子コンポーネントは親コンポーネントの"レイアウトのスタイル"を知ってはならない」,「親コンポーネントは子コンポーネントの"見た目のスタイル"を知ってはならない」(スタイルクローズドの原則)
- 
