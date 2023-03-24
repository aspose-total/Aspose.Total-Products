---
title: Python で DOCM を MHTML に変換する
description: Microsoft Word を使用せずに Python アプリケーションで DOCM から mhtml Web アーカイブ形式および HtmlFixed ファイルに変換 

family: total
platformtag: Python
feature: conversion
informat: DOCM
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して DOCM を MHTML に変換する" h2="Microsoft Word<sup>&reg;</sup> をインストールせずに、Python アプリケーションで DOCM から MHTML、HtmlFixed、および HTML への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

DOCM から MHTML (Web アーカイブ形式) への変換機能または HtmlFixed を追加しようとしている Python 開発者は、アプリケーション内の絶対配置要素を使用してドキュメントを HTML 形式で保存したいと考えています。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。これは、さまざまな形式を扱うさまざまな API の完全なパッケージです。 

[Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API を使用して、DOCM から MHTML への変換機能を追加します。 DOCM ファイルが単純な場合、コードは 2 行だけです。 DOCM ファイルをロードし、MHTML または HTML_FIXED としての SaveFormat 列挙と共に、適切なファイル パスを使用して保存メソッドを呼び出します。 ただし、ドキュメント モデルを元のモデルに近いものに復元する必要がある場合は、結果のドキュメント内に往復情報と呼ばれる追加情報を保存する必要があります。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="方法 Python で DOCM を MHTML に変換する" %}}
- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース DOCM ファイルをロードする
- [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/) のインスタンスを作成します。
- export_roundtrip_information を True に設定します。
- [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) を MHTML として指定します。
- パラメータとして出力ファイルのパスと SaveFormat を指定して `save` メソッドを呼び出します。 したがって、DOCM ファイルは指定されたパスで MHTML に変換されます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- DOCM から MHTML または HtmlFixed 形式への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/)) から直接参照する
- または、次の pip コマンド ```pip install aspose.words``` を使用します。
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、[INSTALL](https://docs.aspose.com/words/python-net/installation/) の手順に従ってください。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでDOCMをMHTMLに保存 - シンプル" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python での DOCM から MHTML への変換" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}