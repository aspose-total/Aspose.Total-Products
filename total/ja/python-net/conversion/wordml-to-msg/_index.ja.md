---
title: Python で WORDML を MSG に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で WORDML を MSG に保存します。

family: total
platformtag: Python
feature: conversion
informat: WORDML
outformat: MSG
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して WORDML を MSG に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで WORDML から MSG への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に WORDML から MSG への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に WORDML ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、MSG 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で WORDML を MSG に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース WORDML ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、WORDML ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にWORDMLが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- WORDML から MSG への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでWORDMLをMSGに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

WordML から MSG への変換は、ドキュメントコンテンツからメールメッセージファイルを作成し、デスクトップメールのワークフロー、アーカイブプロセス、コミュニケーションのパッケージ化で使用されます。構造化されたドキュメント情報を個別のメッセージレコードとして保持する必要がある場合に有益です。

Python API は、ドキュメントテキストをメッセージコンポーネントにマッピングし、メール対応環境向けに出力生成を自動化することで、WordML から MSG への変換をサポートします。

{{% blocks/products/pf/agp/feature-section-col title="主な使用ケース" %}}

* **メッセージファイル作成**
  WordML コンテンツを MSG ファイルに変換し、個別のメールレコードの取り扱いに使用します。

* **デスクトップメール互換性**
  デスクトップ環境でメッセージファイルのやり取りに依存するワークフローをサポートします。

* **コミュニケーションのアーカイブ**
  ドキュメントベースのコンテンツを個別のメール形式アーティファクトとして保持します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **大量 MSG 生成**
  複数の WordML ドキュメントからメッセージファイルの作成を自動化します。

* **アーカイブ準備**
  構造化されたドキュメントを MSG レコードに変換し、保存および取得のワークフローに利用します。

* **運用コンテンツのパッケージ化**
  ドキュメント由来のコミュニケーションをメッセージシステムへプログラム的に配信することをサポートします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}