---
title: Python で PDF を MHTML に変換する
description: Microsoft Word を使用せずに Python アプリケーションで PDF から mhtml Web アーカイブ形式および HtmlFixed ファイルに変換 

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して PDF を MHTML に変換する" h2="Microsoft Word<sup>&reg;</sup> をインストールせずに、Python アプリケーションで PDF から MHTML、HtmlFixed、および HTML への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

PDF から MHTML (Web アーカイブ形式) への変換機能または HtmlFixed を追加しようとしている Python 開発者は、アプリケーション内の絶対配置要素を使用してドキュメントを HTML 形式で保存したいと考えています。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。これは、さまざまな形式を扱うさまざまな API の完全なパッケージです。 

[Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API を使用して、PDF から MHTML への変換機能を追加します。 PDF ファイルが単純な場合、コードは 2 行だけです。 PDF ファイルをロードし、MHTML または HTML_FIXED としての SaveFormat 列挙と共に、適切なファイル パスを使用して保存メソッドを呼び出します。 ただし、ドキュメント モデルを元のモデルに近いものに復元する必要がある場合は、結果のドキュメント内に往復情報と呼ばれる追加情報を保存する必要があります。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="方法 Python で PDF を MHTML に変換する" %}}
- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース PDF ファイルをロードする
- [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/) のインスタンスを作成します。
- export_roundtrip_information を True に設定します。
- [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) を MHTML として指定します。
- パラメータとして出力ファイルのパスと SaveFormat を指定して `save` メソッドを呼び出します。 したがって、PDF ファイルは指定されたパスで MHTML に変換されます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- PDF から MHTML または HtmlFixed 形式への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/)) から直接参照する
- または、次の pip コマンド ```pip install aspose.words``` を使用します。
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、[INSTALL](https://docs.aspose.com/words/python-net/installation/) の手順に従ってください。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでPDFをMHTMLに保存 - シンプル" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-mhtml-simple.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python での PDF から MHTML への変換" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "pdf-to-mhtml-conversion-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

PDF を Python API で MHTML に変換することで、マークアップと埋め込みリソースを単一ファイルに結合したウェブアーカイブ形式に文書コンテンツを変換できます。これにより、PDF の情報をブラウザ互換環境で保存、表示、配布しやすくなります。

自動化により、静的文書からスケーラブルにポータブルなウェブ対応ファイルを生成できるようになり、この変換の価値が向上します。コンテンツの公開、アーカイブ、自己完結型ウェブ文書出力を必要とするシステムとの統合をサポートします。

{{% blocks/products/pf/agp/feature-section-col title="主な使用例" %}}

* **ウェブアーカイブ作成**  
  PDF ファイルを MHTML に変換し、ブラウザベースの保存と閲覧を可能にします。

* **ポータブル文書の公開**  
  自己完結型のウェブフレンドリーな形式で文書コンテンツを共有します。

* **コンテンツの保存**  
  ウェブワークフローに適したアーカイブで視覚情報とテキスト情報を保持します。

* **システム相互運用性**  
  文書交換がブラウザ互換標準に合わせる必要がある場合に MHTML 出力を使用します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **自動化ウェブ変換パイプライン**  
  Python スクリプトは、デジタル出版システム向けに PDF を MHTML ファイルに変換できます。

* **アーカイブ配布ワークフロー**  
  変換された出力は、ウェブアーカイブコンテンツを管理するリポジトリに配信できます。

* **バッチ文書公開**  
  大量の PDF を手動介入なしでポータブルなウェブファイルに変換できます。

* **動的コンテンツエクスポート**  
  システムは、共有やレビューのために要求に応じて文書の MHTML バージョンを生成できます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}