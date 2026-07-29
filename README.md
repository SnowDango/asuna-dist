# asuna-dist

JetBrains IDE 向けプラグイン **Asuna** の配布リポジトリです。

このリポジトリは、[JetBrains のカスタムプラグインリポジトリ](https://plugins.jetbrains.com/docs/intellij/custom-plugin-repository.html)として機能します。`updatePlugins.xml` が最新バージョンのメタデータを公開し、実体の zip は [Releases](https://github.com/snowdango/asuna-dist/releases) で配布されます。IDE にこのリポジトリを登録しておくと、Asuna のインストールおよび自動アップデートが行えます。

## インストール

1. JetBrains IDE を開き、**Settings/Preferences → Plugins** を開きます。
2. 右上の歯車アイコン（⚙）から **Manage Plugin Repositories...** を選択します。
3. `+` をクリックし、次の URL を追加します。

   ```
   https://raw.githubusercontent.com/snowdango/asuna-dist/main/updatePlugins.xml
   ```

4. **OK** で閉じ、**Marketplace**（または検索）から **Asuna** を探してインストールします。

登録後は、通常のプラグインと同様に IDE 上で更新通知を受け取れます。

## 動作環境

| 項目 | 内容 |
| --- | --- |
| プラグイン ID | `com.snowdango.asuna` |
| 対応ビルド | `since-build 242`（2024.2 以降の IntelliJ ベース IDE） |
| 最新バージョン | [`26.07.28`](https://github.com/snowdango/asuna-dist/releases/tag/v26.07.28) |

## 手動インストール

カスタムリポジトリを使わずに導入する場合は、以下の手順でインストールできます。

1. [Releases](https://github.com/snowdango/asuna-dist/releases) から最新の `asuna-<version>.zip` をダウンロードします。
2. **Settings/Preferences → Plugins** を開きます。
3. 歯車アイコン（⚙）から **Install Plugin from Disk...** を選択し、ダウンロードした zip を指定します。
4. IDE を再起動します。

## リポジトリ構成

| ファイル | 説明 |
| --- | --- |
| `updatePlugins.xml` | カスタムプラグインリポジトリのメタデータ（最新バージョン・ダウンロード URL・対応ビルド） |

## リンク

- Releases: https://github.com/snowdango/asuna-dist/releases
- 作者: [@snowdango](https://github.com/snowdango)
