Leveling System

このプロジェクトは、自己研鑽のためのデイリークエスト・トラッカーです。

🚀 特徴

ダイナミックなランクシステム: レベルに応じてプレイヤーランク（EからSまで）が変動します。

ハイブリッド・クエスト:

フィジカル: 腕立て伏せ、腹筋、スクワット。ランクが上がるごとにノルマ回数が増加し、負荷が高まります。

スキル（創作）: イラスト制作、プログラミング。ランクに関わらず一定のタスク量を維持し、継続をサポートします。

ステータス管理: 完了したタスクに応じて「STRENGTH（筋力）」「AGILITY（敏捷）」「INTELLIGENCE（知能）」のステータスが上昇します。

永続化: ブラウザの localStorage を使用して、レベルやステータスを自動保存します。

レスポンシブデザイン: Tailwind CSSを使用し、PC・スマートフォンの両方でスタイリッシュに表示されます。

🛠️ 技術スタック

HTML5 / CSS3 (Tailwind CSS)

JavaScript (Vanilla JS)

Google Fonts (Orbitron / Noto Sans JP)

📖 使いかた

https://lukaglyph.github.io/LEVELING_SYSTEM/
をブラウザで開きます。

画面上の名前（デフォルト: user）をクリックして、プレイヤー名を変更します。

デイリークエストを完了したら、各項目をクリックして経験値（XP）とステータスを獲得します。

経験値が一定に達するとレベルアップし、より高いランクを目指すことができます。

翌日になるとクエスト状況が自動的にリセットされます（レベルや累計ステータスは保持されます）。

🔧 カスタマイズ

index.html 内の questDefinitions 配列を編集することで、独自のクエストや上昇するステータスを自由に変更できます。

const questDefinitions = [
    { id: 'custom-id', name: '新しいクエスト', baseCount: 10, unit: '回', stat: 'str', isVariable: true }
];


📜 ライセンス

MIT License
