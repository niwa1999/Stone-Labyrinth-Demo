# SIGIL ABYSS（シジル・アビス）
### Rogue-ish RPG

旧タイトル：石の迷宮 / Stone Labyrinth

疑似3Dの迷宮を探索する、Windows向けのRogue-ish RPGです。職業や生い立ち、性格を選び、自分の冒険者を作成して挑みます。

**[新タイトル版・体験版50Oをダウンロード / Download SIGIL ABYSS demo 50O](https://github.com/niwa1999/Stone-Labyrinth-Demo/releases/download/demo-50O-gazal-forward-20261022/SigilAbyss_Demo_50O_GazalForward_Windows_x64.zip)**

[50Oのリリース案内 / Release notes](https://github.com/niwa1999/Stone-Labyrinth-Demo/releases/tag/demo-50O-gazal-forward-20261022)

Releaseページの **Assets → SigilAbyss_Demo_50O_GazalForward_Windows_x64.zip** を選んでください。Source code (zip) はゲーム本体ではありません。

## 50O 2026年10月22日更新版

デモを再ビルドし、更新履歴を更新しました。収録範囲は従来の2シナリオです。ガザルの小型化・施設の前進利用はFULL版のみの変更で、体験版には含まれません。既存の体験版セーブを引き継げます。

## 50O ギルド依頼表示版（2026年10月22日）

- 冒険者ギルドの依頼に **◎・金色＝現在の依頼／◯・緑色＝達成・報告済み** を表示します。訓練・休息・噂話は従来どおりです。
- 3言語の凡例を追加。既存の体験版セーブを引き継げます。

## 50O 追加修正版（2026年10月21日）

- 死因画面の後、任意のキーで「死亡時の所持品」を確認できます。未鑑定だった品も内容を表示し、Enterで再挑戦の選択へ進みます。
- 階段進入時の範囲外アクセスを修正しました。
- Shift＋テンキーの補完を追加しました。実機での長時間の再発解消は確認中です。

## 50O 起動ファイル名更新（2026年10月21日）

- 起動ファイル名を **SigilAbyss_Demo.exe** へ変更しました。旧体験版のセーブを引き継げます。保存先・保存形式とゲーム内容は維持しています。

## 50O 改題版の更新（2026年10月21日）

- タイトルを **SIGIL ABYSS（シジル・アビス）** へ変更しました。タイトル画面・ウィンドウ名・同梱文書を更新しています。
- 版番号とセーブの保存先・形式は維持しています。公開するのは体験版だけです。

- **Ctrl＋Sで索敵（1ターン）**を実行できるようになりました。**Shift＋Sの隠密態勢はそのまま**使えます。ヘルプ・技能画面の案内も更新しました。
- 持ち物・装備・ステータスを **I：持ち物／W：装備／C：ステータス** で直接切り替えられるようになりました。Escで戻る必要はありません。
- 従来のEによる持ち物・装備の往復と、Escで閉じる操作も使えます。同じ画面のキーをもう一度押すと閉じます。
- 受け流し後の近接攻撃に命中補正が正しく反映されない問題を修正しました。
- 謝辞・日付入り更新履歴・DXライブラリのライセンスを同梱しています。

## 体験版について

- バンシー編・ヴァリアド編まで遊べます。
- 日本語・English・Português (Brasil) に対応しています。
- 開発中の体験版です。感想・不具合報告をお待ちしています。
- このリポジトリは体験版の配布・紹介用です。ゲームのソースコードは公開していません。

## 起動方法

1. 体験版ZIPをダウンロードします。
2. ZIPの中身をすべて、書き込み可能なフォルダーへ展開します。
3. SigilAbyss_Demo.exeを起動します。mediaフォルダーも同じ場所に置いてください。

64bit WindowsとDirect3D 11に対応した環境が必要です。メモリ・CPUの正式な必要動作環境は現在確認中です。

## 主な操作

| キー | 操作 |
|---|---|
| タイトルでEsc | 言語・画面サイズ・音の設定 |
| Enter | ゲーム中のコマンド窓 |
| F1 | 詳しい操作説明 |
| ↑／テンキー8 | 前進 |
| ←／→ | 向き変更 |
| Shift＋方向 | 戦闘移動 |
| Ctrl＋方向 | 攻撃 |
| Ctrl＋↑／テンキー8 | 正面の扉・宝箱・発見済みの罠を操作（敵がいる場合は攻撃） |
| テンキー5 | 待機 |
| E | 調べる・利用／持ち物・装備画面では切り替え |
| Ctrl＋S | 索敵（1ターン） |
| Shift＋S | 隠密態勢 |
| A | 魔法・スキル |
| I | 持ち物 |
| W | 装備 |
| C | ステータス |
| M | 全体マップ |

キーボードのショートカットとコマンド窓を併用できます。持ち物・装備・ステータスの各画面から、I／W／Cで直接切り替えられます。

## 保存

ゲームは自動保存します。保存先は %LOCALAPPDATA%\StoneDungeonDemo です。製作版のセーブとは別に管理されます。

## 感想・不具合報告

[Issues](https://github.com/niwa1999/Stone-Labyrinth-Demo/issues) に、起きた状況・操作・使用言語を書いてください。スクリーンショットやプレイログがあると調査しやすくなります。公開の報告には、本名など公開したくない情報を含めないでください。

## English

Rebuilt demo with an updated changelog. Two scenarios only; Gazal and its forward facility entry remain exclusive to the full game. Existing demo saves remain compatible.

Guild quests: ◎ in gold marks the current quest; ◯ in green marks completed and reported quests.

SIGIL ABYSS (formerly Stone Labyrinth) is a Windows dungeon RPG with a pseudo-3D view.

- Play the Banshee and Variad arcs in this development demo.
- Japanese, English and Portuguese (Brazil) are supported.
- [Download demo 50O](https://github.com/niwa1999/Stone-Labyrinth-Demo/releases/tag/demo-50O-gazal-forward-20261022), then choose **Assets → SigilAbyss_Demo_50O_GazalForward_Windows_x64.zip**.
- Extract the entire ZIP and run SigilAbyss_Demo.exe. Keep the media folder beside it.
- Requires 64-bit Windows with Direct3D 11 support.
- Press **Esc on the title screen** for language and display settings, **Enter during play** for commands, and **F1** for detailed help.
- Ctrl+S performs Search (one turn); Shift+S still starts Stealth.
- In 50O, switch directly between inventory (I), equipment (W), and status (C) without Esc. E also switches inventory/equipment. Accuracy after parrying has been fixed.
- Progress is saved automatically.
- Feedback and bug reports are welcome in Issues.

## Português (Brasil)

Demonstração recompilada com histórico atualizado. Somente dois cenários; Gazal e o acesso às instalações ao avançar são exclusivos da versão completa. Os arquivos salvos continuam compatíveis.

Missões da guilda: ◎ dourado indica a missão atual; ◯ verde indica missões concluídas e relatadas.

SIGIL ABYSS (anteriormente Stone Labyrinth) é um RPG de exploração de masmorras para Windows, com visão em pseudo-3D.

- Esta demonstração em desenvolvimento inclui os arcos da Banshee e de Variad.
- Idiomas: japonês, inglês e português (Brasil).
- [Baixe a demonstração 50O](https://github.com/niwa1999/Stone-Labyrinth-Demo/releases/tag/demo-50O-gazal-forward-20261022) e escolha **Assets → SigilAbyss_Demo_50O_GazalForward_Windows_x64.zip**.
- Extraia todo o ZIP e execute SigilAbyss_Demo.exe. Mantenha a pasta media ao lado do executável.
- É necessário Windows de 64 bits com suporte a Direct3D 11.
- Pressione **Esc na tela de título** para configurar idioma e tamanho da janela, **Enter durante o jogo** para os comandos e **F1** para a ajuda detalhada.
- Ctrl+S executa Buscar (1 turno); Shift+S continua ativando Furtividade.
- Na versão 50O, alterne diretamente entre inventário (I), equipamento (W) e estado (C), sem Esc. E também alterna inventário/equipamento. A precisão após aparar foi corrigida.
- O progresso é salvo automaticamente.
- Comentários e relatos de problemas são bem-vindos em Issues.

---
Third-party notices: ZIP内のlicensesフォルダーを参照してください。

