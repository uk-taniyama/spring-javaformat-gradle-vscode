# spring-javaformat-gradle-vscode

## What is this?

VSCodeでgradleによるSpringの書式で使うためのサンプルです。
以下のようなことができます。

* VSCodeで推奨拡張機能を追加できます。
* VSCodeでEclipseのフォーマッタを使えます。
* VSCodeでCheckstyleによるスタイルの検証ができます。
* Gradleのformatタスクでフォーマットができます。
* GradleのcheckでCheckstyleによるスタイルの検証ができます。
* GradleのsetupでVSCode用にspring-javaformat-checkstyleのjarをローカルにコピーします。

### How to use

このリポジトリをgit cloneして、gradlew setupを実行してください。

もしくは、build.gradleの履歴を見て、フォーマッタとCheckstyleの定義等を参考にして既存のプロジェクトに組み込んでください。

## Appendix

* config/checkstyle/checkstyle.xml：Checkstyleの設定。
* config/checkstyle/checkstyle-suppressionx.xml：Checkstyleの除外条件。
* config/formatter/eclipse-code-formatter.xml：Eclipse用のフォーマッタの設定。
* .vscode/extensions.json：VSCodeの推奨拡張機能。
* .vscode/settings.json：VSCodeの設定。Checkstyleのパス解決等。
