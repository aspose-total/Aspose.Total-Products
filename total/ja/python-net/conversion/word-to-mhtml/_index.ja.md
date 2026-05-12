---
title: Python で WORD を MHTML に変換する
description: Microsoft Word を使用せずに Python アプリケーションで WORD から mhtml Web アーカイブ形式および HtmlFixed ファイルに変換 

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して WORD を MHTML に変換する" h2="Microsoft Word<sup>&reg;</sup> をインストールせずに、Python アプリケーションで WORD から MHTML、HtmlFixed、および HTML への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

WORD から MHTML (Web アーカイブ形式) への変換機能または HtmlFixed を追加しようとしている Python 開発者は、アプリケーション内の絶対配置要素を使用してドキュメントを HTML 形式で保存したいと考えています。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。これは、さまざまな形式を扱うさまざまな API の完全なパッケージです。 

[Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API を使用して、WORD から MHTML への変換機能を追加します。 WORD ファイルが単純な場合、コードは 2 行だけです。 WORD ファイルをロードし、MHTML または HTML_FIXED としての SaveFormat 列挙と共に、適切なファイル パスを使用して保存メソッドを呼び出します。 ただし、ドキュメント モデルを元のモデルに近いものに復元する必要がある場合は、結果のドキュメント内に往復情報と呼ばれる追加情報を保存する必要があります。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="方法 Python で WORD を MHTML に変換する" %}}
- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース WORD ファイルをロードする
- [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/) のインスタンスを作成します。
- export_roundtrip_information を True に設定します。
- [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) を MHTML として指定します。
- パラメータとして出力ファイルのパスと SaveFormat を指定して `save` メソッドを呼び出します。 したがって、WORD ファイルは指定されたパスで MHTML に変換されます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- WORD から MHTML または HtmlFixed 形式への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/)) から直接参照する
- または、次の pip コマンド ```pip install aspose.words``` を使用します。
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、[INSTALL](https://docs.aspose.com/words/python-net/installation/) の手順に従ってください。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでWORDをMHTMLに保存 - シンプル" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python での WORD から MHTML への変換" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API を使用した Word から MHTML への変換は、ワードプロセッシング文書をテキスト、スタイル、埋め込みリソースを自己完結型パッケージに保持した単一ファイルの Web アーカイブ形式に変換します。これは、プレゼンテーションの一貫性を保ちつつ、ブラウザフレンドリーな形式で文書コンテンツを共有する際に有用です。

自動化されたワークフローにおいて、MHTML 変換は、受信者が元の作成環境に依存することなく、ポータブルな公開、アーカイブ生成、Web 互換のコンテンツ配信をサポートします。

{{% blocks/products/pf/agp/feature-section-col title="主な使用ケース" %}}

* **単一ファイル Web アーカイブ**
  文書コンテンツと関連リソースを 1 つのブラウザで読み取れるファイルに保存します。

* **一貫したビジュアル共有**
  システム間でコンテンツを配布する際に、レイアウトとフォーマットの維持に役立ちます。

* **ポータブル文書公開**
  Word で作成されたコンテンツを Web 互換環境で公開しやすくします。

* **オフラインレビューサポート**
  別個のアセットなしで、完全な文書コンテンツをローカルで閲覧可能にします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **自動化された Web アーカイブ作成**
  定期的な Word ファイルを配布、保存、またはレビュー用に MHTML に変換します。

* **コンテンツ公開パイプライン**
  文書から Web へのワークフローで、MHTML 出力を中間資産として使用します。

* **自己完結型配信自動化**
  テキストとリソースを一緒にパッケージ化し、システム間で信頼できる交換を実現します。

* **アーカイブ一貫性ワークフロー**
  大規模にビジネス文書のブラウザフレンドリーな保存バージョンを生成します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}